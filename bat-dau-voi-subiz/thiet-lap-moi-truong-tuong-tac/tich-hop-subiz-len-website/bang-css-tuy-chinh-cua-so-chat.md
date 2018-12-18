---
description: >-
  Tài liệu này tổng hợp bảng CSS giúp bạn có thể sáng tạo giao diện cửa sổ chat
  bắt mắt và riêng biệt trên website.
---

# Bảng CSS tùy chỉnh cửa sổ chat

CSS là chữ viết tắt của **Cascading Style Sheets**,  được dùng để miêu tả cách trình bày các tài liệu viết bằng ngôn ngữ HTML và XHTML.

Bạn cần sao chép đúng CSS bên dưới và dán vào mục [Tùy chỉnh CSS trong cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting) &gt; Lưu thay đổi tại bảng tùy chỉnh CSS và Lưu thay đổi ở mục Cửa sổ Subiz chat

![T&#xF9;y ch&#x1EC9;nh CSS c&#x1EED;a s&#x1ED5; Subiz chat](../../../.gitbook/assets/tuy-chinh-css.jpg)

### Kích thước chiều rộng, chiều cao cửa sổ chat

Bạn cần xác định [KIỂU CỬA SỔ CHAT](https://app.subiz.com/settings/widget-setting) đang sử dụng là Thu gọn hay Mở rộng để chọn mã CSS tùy chỉnh kích thước cửa sổ chat đúng dưới đây.

{% tabs %}
{% tab title="Kiểu cửa sổ chat THU GỌN" %}
```csharp
.widget_mini .widget_body 
{height: 500px !important;
max-height: 580px !important;}
/* Thay đổi chiều cao 500px */

.widget_mini .widget_body 
{width:360px;}
/* Thay đổi chiều rộng 360px */
```
{% endtab %}

{% tab title="Kiểu cửa sổ chat MỞ RỘNG" %}
```csharp
.widget_full .widget_body 
{height: 700px !important;
max-height: 800px !important;}
/* Thay đổi chiều cao 700px */

.widget_full .widget_body 
{width:400px;}
/* Thay đổi chiểu rộng 400px */
```
{% endtab %}
{% endtabs %}

### Tùy biến màu sắc trên cửa sổ chat

Màu sắc cửa sổ chat sẽ đồng bộ trên cả bản destop và mobile. Bạn có thể sử dụng màu sắc đơn hoặc theo dải màu chuyển tiếp; chọn tùy chỉnh màu sắc chung cho toàn bộ cửa sổ chat hoặc màu sắc riêng của từng khung.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Ví trí thay đổi màu sắc</th>
      <th style="text-align:left">Màu sắc đơn</th>
      <th style="text-align:left">Dải màu chuyển tiếp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Toàn bộ cửa sổ chat</td>
      <td style="text-align:left">
        <p><code>.color-theme-default <br />{background-color:#000000;}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i m&#xE3; m&#xE0;u: #000000;} */</code></em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.color-theme-default <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i d&#x1EA3;i m&#xE3; m&#xE0;u: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f */</code></em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tiêu đề</td>
      <td style="text-align:left">
        <p><code>.widget-header <br />{background-color:#00000;}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i m&#xE3; m&#xE0;u: #000000;} */</code></em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.widget-header <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p><em><code>/*  Thay &#x111;&#x1ED5;i d&#x1EA3;i m&#xE3; m&#xE0;u: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f */</code></em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tin nhắn</td>
      <td style="text-align:left">
        <p><code>.message-body <br />{background-color:#00000;}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i m&#xE3; m&#xE0;u: #000000;} */</code></em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.message-body <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i d&#x1EA3;i m&#xE3; m&#xE0;u: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f */</code></em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Nút "Bắt đầu trò chuyện"</td>
      <td style="text-align:left">
        <p><code>.add-new-conversation {background-color:#000000;}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i m&#xE3; m&#xE0;u: #000000;} */</code></em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.add-new-conversation <br />{background-image: linear-gradient(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p><em><code>/* Thay &#x111;&#x1ED5;i d&#x1EA3;i m&#xE3; m&#xE0;u: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f */ </code></em>
        </p>
      </td>
    </tr>
  </tbody>
</table>### Sáng tạo tiêu đề cửa sổ chat

Thay đổi bố cục của cửa sổ chat gia tăng nhận diện hình ảnh thương hiệu của Doanh Nghiệp.

```csharp
.color-theme-default {background-color:#f44336;} 
.list-agents { float:left; width:45%; } 
.avatar-team { position:absolute; top:-70%; 
background: url(
https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png
); 
height: 100px; background-size: 150px; 
background-repeat: no-repeat; background-position: center; } 
.full { width:160px !important; } 
.avatar-team .avatar-agent{ display:none; } 
.team-intro { width:55%; margin-bottom:12px; } 
.team-intro p{ padding: 0 0 0 0; font-size:13px;}

/* Thay đường link ảnh của bạn tại: https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png */
```

### Tùy chỉnh cỡ chữ của tin nhắn

Cỡ chữ mặc định trong tin nhắn là 13px, bạn có thể thay đổi cỡ chữ nhỏ hơn hoặc lớn hơn:

```csharp
 .message-content
{ font-size:13px;}
/* Thay đổi cỡ chữ 13px */
```

### Vị trí chat button, cửa sổ chat trên website

Bạn muốn thay đổi vị trí chat button và cửa sổ chat lên cao hay xuống thấp trên website , hãy sử dụng mã CSS dưới đây:

* Kiểm tra cài đặt Cửa sổ chat [Kiểu Thu gọn hay Mở rộng](https://app.subiz.com/settings/widget-setting) để dùng đúng CSS. Xem thêm [Tùy chỉnh hình ảnh chat button thu hút](https://help.subiz.com/bat-dau-voi-subiz/thiet-lap-moi-truong-tuong-tac/tich-hop-subiz-len-website/tuy-chinh-cua-so-chat-subiz#tuy-chinh-chat-button)

{% tabs %}
{% tab title="Cửa sổ chat THU GỌN" %}
Trên bản destop:

```csharp
 .widget-button {bottom:0;}
 .widget_mini .widget_body {bottom:0;}
 /* Kích thước thay đổi khoảng 0 - 40px */
```

Trên bản mobile

```csharp
 .widget_mobile .widget-button 
{bottom:40px;right:40px;}
/* Kích thước thay đổi khoảng 0 - 40px */
```
{% endtab %}

{% tab title="Cửa sổ chat MỞ RỘNG" %}
Trên destop:

```csharp
 .widget-button {bottom:0;}
 .widget_full .widget_body {bottom:0;}
 //Kích thước thay đổi khoảng 0 - 40px
```

Trên mobile:

```csharp
.widget_mobile .widget-button 
{ bottom:0;left:0;}
 //Kích thước thay đổi khoảng 0 - 40px
```
{% endtab %}
{% endtabs %}

###  Hạ thấp **chiều cao cửa sổ chat trên mobile**

 Cửa sổ Subiz chat sẽ mặc định hiển thị khoảng 90% màn hình điện thoại, để khách vẫn nhìn thấy link của website mua hàng.

Bạn muốn hạ cửa sổ chat trên mobile sẽ hiển thị thấp hơn so với mặc định, hãy dùng mã CSS dưới đây, có thể thay tỷ lệ 90%:

```csharp
.widget_mobile .widget_body {height: 90%;}
/* Thay đổi tỷ lệ chiều cao 90% */
```

### Tùy chỉnh chat button riêng bản mobile

Website bản destop và bản mobile đang hiển thị chung một chat button. Để sử dụng riêng hình ảnh chat button trên bản mobile, bạn sẽ sử dụng CSS sau:

```csharp
.widget_mobile .button-chat { border-radius: 0; background-image: url(
https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png
); background-repeat: no-repeat; } 
.widget_mobile .button-chat-icon { display: none; } @supports (-ms-ime-align:auto) { .widget_mobile .button-chat { border-radius: 50%; } 
.widget_mobile .button-chat-icon { display: inline-block; } } 
.widget_mobile .widget-button { width: 81px; height: 31px; } 
.widget_mobile .button-chat { border-radius: 0 !important; } 
.widget_mobile .widget-button:after { display: none; } 
.widget_mobile .widget_mini .close-widget-icon { display: none; } 
.widget_mobile .button-chat .avatar-preview img { display: none; } 
.widget_mobile .button-chat { box-shadow: none; background-color: transparent !important; }

.widget_mobile .widget-button {bottom:0;right:40px;}

/* Thay đường link ảnh chat button của bạn: https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png
Thay đổi kích thước ảnh chat button width: 81px; height: 31px
Thay đổi vị trí chat button trên website khoảng 0 đến 40px trong {bottom:0;right:40px;} */
```

### Ẩn cửa sổ chat

{% tabs %}
{% tab title="Trên website bản destop" %}
```text
.widget { display: none; }
```
{% endtab %}

{% tab title="Trên website bản mobile" %}
```csharp
.widget_mobile {display: none; }
```
{% endtab %}
{% endtabs %}

### Ẩn chat button

{% tabs %}
{% tab title="Trên website bạn destop" %}
Kiểu cửa sổ chat THU GỌN:

```csharp
.widget-button {display:none;}
.widget_mini .widget_body {bottom:0;}
```

Kiểu cửa sổ chat MỞ RỘNG:

```csharp
.widget-button {display:none;}
```
{% endtab %}

{% tab title="Trên website bản mobile" %}
```csharp
.widget_mobile .button-chat {
display: none; }
```
{% endtab %}
{% endtabs %}

\`\`

### 






