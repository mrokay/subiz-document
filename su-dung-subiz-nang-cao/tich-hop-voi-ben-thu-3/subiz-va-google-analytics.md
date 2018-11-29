---
description: >-
  Tài liệu này mô tả cách tích hợp Subiz với Google Analytics. Từ đó, bạn có thể
  dùng để phân tích khách hàng trên Google Analytics.
---

# Subiz và Google Analytics

### Cách tích hợp

Để tích hợp [Subiz](https://subiz.com) với [Google Analytics](https://analytics.google.com/analytics/web/), bạn chỉ cần [đặt mã nhúng Google Analytics](https://developers.google.com/analytics/devguides/collection/) lên website của bạn. Subiz sẽ tự động tìm mã nhúng và làm việc với tài khoản Google Analytics được cài trên web.  Chúng tôi hỗ trợ các loại Google Analytics tracking sau: 

1. [gtagjs](https://developers.google.com/analytics/devguides/collection/gtagjs/)
2. [analytics.js](https://developers.google.com/analytics/devguides/collection/analyticsjs/)

### Cách làm việc của Subiz với Google Analytics 

 Subiz sẽ gửi các dữ liệu sự kiện \(event data\) sang Google Analytics. Khi đó, bạn có thể xem được các dữ liệu này tại mục Sự kiện \(event\) của Google Analytics. Các sự kiện mà Subiz gửi : 

{% tabs %}
{% tab title="Cửa sổ Subiz Mở" %}
Cửa sổ Subiz được mở bởi bất kỳ lý do gì: User mở; API Javascript mở; Automation mở... 

Event Category: _SUBIZ Chat_ 

Event Action: _Opened_

Event Label: _Subiz Windows_
{% endtab %}

{% tab title="User nhận tin nhắn" %}
User nhận được tin nhắn của agents hay automation.... 

Event Category: _SUBIZ Chat_ 

Event Action: _Received_

Event Label: _User_
{% endtab %}

{% tab title="User gửi tin nhắn" %}
Event Category: _SUBIZ Chat_ 

Event Action: _Received_

Event Label: _User_
{% endtab %}
{% endtabs %}

![D&#x1EEF; li&#x1EC7;u Subiz g&#x1EED;i sang Google Analytics](../../.gitbook/assets/screenshot-from-2018-11-29-12-38-32.png)

### Khai thác dữ liệu



