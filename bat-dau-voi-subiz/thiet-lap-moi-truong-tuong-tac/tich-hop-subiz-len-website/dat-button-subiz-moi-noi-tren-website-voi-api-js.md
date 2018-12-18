# Đặt button Subiz mọi nơi trên website với API Js

Button [Subiz](https://subiz.com/vi/) là hình ảnh logo của [Subiz](https://subiz.com/vi/), được hiển thị mặc định góc bên phải hoặc bên trái trên website sau khi tích hợp. Khách hàng click vào Button sẽ mở ra cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html).

Bạn hoàn toàn có thể sáng tạo hình ảnh Button Subiz và linh hoạt đặt Button này ở bất cứ vị trí nào trên website, với bất cứ hình dáng nào phù hợp với giao diện trang web.

![S&#xE1;ng t&#x1EA1;o Button Subiz tr&#xEA;n website](../../../.gitbook/assets/tuy-chinh-button.gif)

Bạn cần thực hiện hai bước sau:

### Bước 1: Ẩn hình ảnh Button Subiz mặc định

Bạn sẽ sử dụng mã CSS trong app.subiz.com để ẩn hình ảnh Button mặc định

[Đăng nhập App.subiz.com &gt; Cài đặt &gt; Tài khoản &gt; Cửa sổ hội thoại &gt; Tùy chỉnh CSS](https://app.subiz.com/settings/widget-setting)

Cửa sổ hội thoại có hai kiểu: Thu gọn và Mở rộng. 

![C&#xE1;ch x&#xE1;c &#x111;&#x1ECB;nh ki&#x1EC3;u c&#x1EED;a s&#x1ED5; h&#x1ED9;i tho&#x1EA1;i Subiz tr&#xEA;n website](../../../.gitbook/assets/kieu-1.jpg)

Dưới đây là 2 mã CSS ẩn chat button [Subiz ](https://subiz.com/vi/) tương ứng với từng kiểu cửa sổ hội thoại. Bạn sao chép và đặt mã CSS này trong bảng Tùy chỉnh CSS rồi Lưu thay đổi.

|                     **Kiểu: Thu gọn** |                 **Kiểu: Mở rộng** |
| :--- | :--- |
| .widget-button {display:none;} .widget\_mini .widget\_body {bottom:0;} | .widget-button {display:none;} |

{% hint style="info" %}
Lưu ý: Mã CSS sử dụng để ẩn riêng chat button trên phiên bản điện thoại:  
`.widget_mobile .button-chat {  
display: none;  
}`
{% endhint %}

![D&#xE1;n m&#xE3; CSS &#x1EA9;n button Subiz](../../../.gitbook/assets/kieu-2.jpg)

###  **Bước 2: Gắn link cửa sổ Subiz chat vào bất kỳ vị trí trên website**

Khi cài đặt ẩn button[ Subiz](https://subiz.com/vi/), khách hàng sẽ không nhìn thấy hình ảnh button và cửa sổ [Subiz chat.](https://subiz.com/vi/live-chat.html)

Sử dụng API trong code website sẽ giúp bạn gắn link cửa sổ chat Subiz vào hình ảnh hoặc đoạn text bất kỳ trên website và tự động mở cửa sổ chat.

* API phổ thông đặt vào vùng chứa trong code website , vùng sẽ gắn link cửa sổ Subiz chat  `<script type="text/javascript">window.subiz('expandWidget') </script>` 
* API gắn link cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) vào hình ảnh

```text
<a href="#nogo" onclick="subiz('expandWidget')"><img src="đường dẫn ảnh của bạn"></a>
```

* API gắn link cửa sổ [Subiz chat ](https://subiz.com/vi/live-chat.html)vào đoạn text

```text
<a href="#nogo" onclick="subiz('expandWidget')">đoạn text của bạn</a>
```

{% hint style="info" %}
Lưu ý: Bạn cần đặt API này vào trong trang code website. Nếu bạn không hiểu rõ code, bạn có thể gửi hướng dẫn này cho người thiết kế website để họ cài đặt nhanh chóng nhất.
{% endhint %}

> Bạn gặp khó khăn khi cài đặt, vui lòng chat trực tiếp với tư vấn viên trên website [Subiz.com](https://subiz.com/vi/) hoặc gửi email Support@Subiz.com.



