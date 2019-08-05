---
description: >-
  Subiz Platform sẽ gửi dữ liệu sự kiện xẩy ra thông qua webhook. Qua đó bạn có
  thể tích hợp Subiz với các bên khác như CRM; SMS ...
---

# Webhook

Subiz Platform gửi các sự kiện đến webhook của bạn để thông báo cho ứng dụng của bạn khi có những sự kiện tương tác xảy ra, bao gồm cả khách hàng gửi tin nhắn hay thông tin khách hàng được cập nhật. Các sự kiện được gửi đi bởi Subiz Platform sẽ dưới dạng POST.

Webhook trong Subiz Platform là một hành động của automation. Ví dụ: Khi khách hàng nhập điền số điện thoại, webhook sẽ gửi dữ liệu khách hàng đó về ứng dụng của bạn.

Để tạo Automation, bạn xem tài liệu tại đây. Dứoi đây chúng tôi sẽ hướng dẫn bạn thực hiện các bước để thiết lập webhook trong automation.

### Khai báo URL webhook

Bạn cần có một URL để nhận dữ liệu của Subiz. Nhập nó vào form, copy lại _mã xác thực_ \(verification key\) hoặc đặt mã mới cho nó bằng cách edit lại gia trị trên form.

### Xác thực webhook

Subiz cần xác thực bạn thực sự là chủ của Webhook này. Khi click vào nút "Xác thực webhook" thì Subiz sẽ gửi một Request GET với các Params:

| Tên  | Loại | Mô  |
| :--- | :--- | :--- |
| subiz\_challenge |  | Boolean \(true\) |
| subiz\_verify | string |  |
| subiz\_timestamp |  |  |

Bạn cần nhận các params trên, và trả về mã hóa SHA256 của subiz\_verify. Mã hóa này được tính bằng HMAC và với "key" là _mã xác thực_ \(verification key\) được nói ở bước trước.

```text
GET /hook?subiz_verify=true&subiz_challenge=23FA0DD5&subiz_timestamp=1234567 HTTP/1.1
Host: example.com
```

Ví dụ xác thực webhook được viết bằng PHP

```php
<?
$verification_key = '347533333339';

function verifyURL($verification_key) {
  parse_str($_SERVER['QUERY_STRING'], $query);
  if (!isset($query['subiz_verify'])) return;
  $request_timestamp = $query['subiz_challenge'];
  $challenge = $query['subiz_challenge'];
  return hash_hmac('sha256', $request_timestamp.$challenge, $verification_key);
}
echo verifyURL($verification_key);
?> 
```

Sau khi thiết lập xong, bạn quay về màn hình Subiz và click "Xác thực webhook" . Hệ thống sẽ báo thành công.

Tiếp theo, bạn thiết lập các điều kiện cho Automation. 

### Dữ liệu Subiz trả về qua webhook

Subiz sẽ gửi dữ liệu dạng JSON sang webhook qua giao thức POST . Dưới đây là dữ liệu sự kiện User cập nhật thông tin. 

```javascript
[
  {
    "account_id": "acpxkgumifuoofoosble",
    "created": 1564997510503088000,
    "data": {
      "automation_event": {
        "account_id": "acpxkgumifuoofoosble",
        "action": {
          "id": "aaqjpvonpqhndkhgvrgbq",
          "type": "send_webhook",
          "webhook_id": "aawhwxwqnffamcdeoqpcsqgxnicwwfbkothyxugh"
        },
        "automation": {
          "account_id": "acpxkgumifuoofoosble",
          "action_id": "aaqjpvonpqhnacekezsol",
          "actions": [
            {
              "id": "aaqjpvonpqhndkhgvrgbq",
              "type": "send_webhook",
              "webhook_id": "aawhwxwqnffamcdeoqpcsqgxnicwwfbkothyxugh"
            }
          ],
          "condition": {
            "conditions": [
              {
                "conditions": [
                  {
                    "event_type": "user_info_updated",
                    "event_type_time": "current",
                    "key": "user.phones",
                    "operator": "notEmpty"
                  }
                ],
                "join": "and"
              }
            ],
            "join": "and"
          },
          "created": 1562130965801560600,
          "id": "atqjpvonpqhmshxkqvtd",
          "metadata": "{\"objAction\":\"user\"}",
          "modified": 1562131122966356000,
          "name": "Test Automation webhook",
          "state": "active"
        },
        "ctx": {
          "sub_topic": "Webhook4Requested"
        },
        "event": {
          "by": {
            "device": {
              "ip": "113.190.233.117",
              "referrer": "https://subiz.com/vi/",
              "user_agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.100 Safari/537.36"
            }
          },
          "created": 1564997510469308200,
          "data": {
            "user": {
              "account_id": "acpxkgumifuoofoosble",
              "attributes": [
                {
                  "key": "fullname",
                  "modified": 1564997510475012900,
                  "state": "live",
                  "text": "David"
                },
                {
                  "key": "emails",
                  "modified": 1564997510475012900,
                  "state": "live",
                  "text": "david@gmail.com"
                },
                {
                  "key": "phones",
                  "modified": 1564997510475012900,
                  "state": "live",
                  "text": "0981234567"
                }
              ],
              "id": "usqkkdnigxytrjxqseoyg"
            }
          },
          "id": "evqkkdnkomqqtsobodcpojfqd",
          "type": "user_info_updated"
        },
        "user": {
          "account_id": "acpxkgumifuoofoosble",
          "attributes": [
            {
              "key": "trace_country_name",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "Vietnam"
            },
            {
              "key": "trace_city_name",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "Hanoi"
            },
            {
              "key": "fullname",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "David"
            },
            {
              "key": "emails",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "david@gmail.com"
            },
            {
              "datetime": "2019-08-05T09:31:32Z",
              "key": "_sg_sgall",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "key": "trace_country_code",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "VN"
            },
            {
              "datetime": "2019-08-05T09:31:32Z",
              "key": "acpxkgumifuoofoosble_subizv4_subikon",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "key": "phones",
              "modified": 1564997510475012900,
              "state": "live",
              "text": "0981234567"
            },
            {
              "datetime": "2019-08-05T09:31:50Z",
              "key": "modified",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "datetime": "2019-08-05T09:31:33Z",
              "key": "seen",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "key": "total_sessions",
              "modified": 1564997510475012900,
              "number": 1,
              "state": "live"
            },
            {
              "datetime": "2019-08-05T09:31:33Z",
              "key": "interacted",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "datetime": "2019-08-05T09:31:32Z",
              "key": "created",
              "modified": 1564997510475012900,
              "state": "live"
            },
            {
              "key": "total_conversations",
              "modified": 1564997510475012900,
              "number": 1,
              "setter": "subiz",
              "setter_type": "subiz",
              "state": "live"
            }
          ],
          "id": "usqkkdnigxytrjxqseoyg",
          "par": 85
        },
        "user_id": "usqkkdnigxytrjxqseoyg"
      }
    },
    "id": "evqkkdnkopmonjptjyogxfjqi",
    "type": "automation_fired"
  }
]
```



