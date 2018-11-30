# Tùy chỉnh cửa sổ chat Subiz trên điện thoại

Cửa sổ chat Subiz trên điện thoại di động được thiết kế tối ưu phù hợp với màn hình nhỏ gọn của khách hàng và nâng cao trải nghiệm khách hàng khi vừa tương tác với tư vấn viên vừa lướt web mua hàng.

### 1. Một số điều cần biết về cửa sổ chat trên điện thoại 

* **Chat button** sẽ mặc định hiển thị giống nhau trên phiên bản máy tính và điện thoại
* Bạn có thể tùy chỉnh hình ảnh **chat button** riêng trên điện thoại với mã CSS
* Khi khách click vào **chat button** sẽ mở ra **cửa sổ chat** Subiz
* **Cửa sổ chat** sẽ hiển thị khoảng 90% màn hình, để khách vẫn nhìn thấy link của website mua hàng
* Bạn có thể tùy chỉnh các thành phần của giao diện **cửa sổ chat** với mã CSS
* Tin nhắn tự động của Automation sẽ hiển thị thông báo tin nhắn dạng số tại chat button, không mở cửa sổ chat.

![C&#x1EED;a s&#x1ED5; Subiz chat tr&#xEA;n &#x111;i&#x1EC7;n tho&#x1EA1;i](../../../.gitbook/assets/widget-vn.png)

### 2. Các bước tùy chỉnh cửa sổ chat trên điện thoại với mã CSS

Để sử dụng mã CSS tùy chỉnh cửa sổ chat, bạn thao tác: [Đăng nhập App.subiz.com &gt; Cài đặt &gt; Tài khoản &gt; Cửa sổ hội thoại &gt; Tùy chỉnh CSS](https://app.subiz.com/settings/widget-setting) &gt; Sao chép mã CSS tương ứng và dán vào phía dưới bảng tùy chỉnh CSS  
&gt; Lưu thay đổi tại bảng Tùy chỉnh CSS   
&gt; Lưu thay đổi tại mục Cửa sổ hội thoại để hoàn thành

![B&#x1EA3;ng t&#xF9;y ch&#x1EC9;nh CSS](../../../.gitbook/assets/2.-box-copy.jpg)

### 2.1 CSS tùy chỉnh cửa sổ chat trên điện thoại

* **Tùy chỉnh màu sắc chung của cả cửa sổ chat và chat button** Bạn có thể thay đổi mã màu \#0000

```text
.widget_mobile .color_theme_default {
background-color: #0000;
}
```

* **Tùy chỉnh màu sắc thanh tiêu đề cửa sổ chat** Bạn có thể thay đổi mã màu \#0000

```text
.widget_mobile .widget-header {
background-color: #0000;
}
```

* **Tùy chỉnh màu sắc ô tin nhắn trong cửa sổ chat** Bạn có thể thay đổi mã màu \#0000

```text
.widget_mobile .message-body {
background-color: #0000;
}
```

* **Tùy chỉnh màu sắc nút Bắt đầu trò chuyện trong cửa sổ chat** Bạn có thể thay đổi mã màu \#0000

```text
.widget_mobile .add-new-conversation {
background-color: #0000;
}
```

* **Tùy chỉnh chiều cao cửa sổ chat so với màn hình điện thoại** `.widget_mobile .widget_body {height: 90%;}`  
* **Ẩn cửa sổ chat trên phiên bản điện thoại** 

  `.widget_mobile   
  {display: none;  
  }`

### 2.2 CSS tùy chỉnh chat button trên điện thoại

* **Thay đổi chat button trên bản điện thoại** Trong đó:    [https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button\_chat\_10.png](https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png): Bạn có thể thay đổi chọn link ảnh của bạn. 190px và 60 px: là kích thước chiều dài và chiều cao của hình ảnh chat button. `.widget_mobile .button-chat { border-radius: 0; background-image: url(`[`https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png`](https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png)`); background-repeat: no-repeat; } .widget_mobile .button-chat-icon { display: none; } @supports (-ms-ime-align:auto) { .widget_mobile .button-chat { border-radius: 50%; } .widget_mobile .button-chat-icon { display: inline-block; } } .widget_mobile .widget-button { width: 190px; height: 60px; } .widget_mobile .button-chat { border-radius: 0 !important; } .widget_mobile .widget-button:after { display: none; } .widget_mobile .widget_mini .close-widget-icon { display: none; } .widget_mobile .button-chat .avatar-preview img { display: none; } .widget_mobile .button-chat { box-shadow: none; background-color: transparent !important; }` ****
* **Tùy chỉnh vị trí chat button so với chân màn hình điện thoại** Trong đó: 0 - 40px là vị trí của chat button so với chân màn hình \(buttom\), bên phải màn hình \(right\), bên trải màn hình \(left\) Nếu chọn vị trí cửa sổ chat là bên phải: `.widget_mobile .widget-button {bottom:40px;right:40px;}`  Nếu chọn vị trí cửa sổ chat là bên trái: .`widget_mobile .widget-button { bottom:0; left:0; }` 
* **Ẩn chat button trên bản điện thoại**  
  `.widget_mobile .button-chat {`

  `display: none;  
  }`  
  **``**  

> Bạn đang có mong muốn tùy chỉnh khác trên cửa sổ chat, hãy  gửi yêu cầu qua Support@Subiz.com để được hỗ trợ tốt nhất!

