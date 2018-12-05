# Bảng CSS tùy chỉnh cửa sổ chat

Bạn đang muốn tùy biến giao diện cửa sổ chat bắt mắt và riêng biệt trên website của mình, hãy tham khảo  các kiểu CSS dưới đây. 

Đảm bảo sao chép đúng CSS và dán vào mục [Tùy chỉnh CSS trong cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting).

###  Thay đổi chiều rộng, chiều cao cửa sổ chat

Bạn cần xác định [KIỂU CỬA SỔ CHAT](https://app.subiz.com/settings/widget-setting) đang sử dụng là Thu gọn hay Mở rộng để chọn mã CSS tùy chỉnh kích thước cửa sổ chat đúng dưới đây.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Kích thước</th>
      <th style="text-align:left">Kiểu cửa sổ chat THU GỌN</th>
      <th style="text-align:left">Kiều cửa sổ chat MỞ RỘNG</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Chiều cao</td>
      <td style="text-align:left">
        <p><code>.widget_mini .widget_body <br />{height: 500px !important;<br />max-height: 580px !important;}</code>
        </p>
        <p><em>Thay đổi kích thước: 500px</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.widget_full .widget_body <br />{height: 700px !important;<br />max-height: 800px !important;}</code>
        </p>
        <p><em>Thay đổi kích thước: 500px</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Chiều rộng</td>
      <td style="text-align:left">
        <p><code>.widget_mini .widget_body <br />{width:360px;}</code>
        </p>
        <p><em>Thay đổi kích thước: 360px</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.widget_full .widget_body <br />{width:400px;}</code>
        </p>
        <p><em>Thay đổi kích thước: 400px</em>
        </p>
      </td>
    </tr>
  </tbody>
</table>###  Tùy chỉnh cỡ chữ của tin nhắn

 `.message-content  
{ font-size:13px;}`  
_Thay đổi cỡ chữ: 13px_

### Tùy biến màu sắc trên cửa sổ chat <a id="tuy-chinh-mau-sac-tren-cua-so-chat-subiz"></a>

 Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp; chọn tùy chỉnh màu sắc chung cho toàn bộ cửa sổ chat hoặc màu sắc riêng của từng khung.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Ví trí</th>
      <th style="text-align:left">Màu sắc đơn</th>
      <th style="text-align:left">Dải màu chuyển tiếp</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Toàn bộ cửa sổ chat</td>
      <td style="text-align:left">
        <p><code>.color-theme-default <br />{background-color:#000000;}</code>
          <br
          />
        </p>
        <p><em>Thay đổi mã màu: #000000;}</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.color-theme-default <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
          <br
          />
        </p>
        <p><em>Thay đổi dải mã màu: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tiêu đề</td>
      <td style="text-align:left">
        <p><code>.widget-header <br />{background-color:#00000;}</code>
          <br />
        </p>
        <p><em>Thay đổi mã màu: #000000;}</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.widget-header <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p></p>
        <p><em>Thay đổi dải mã màu: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tin nhắn</td>
      <td style="text-align:left">
        <p><code>.message-body <br />{background-color:#00000;}</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu: #000000;}</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.message-body <br />{background-image: linear-gradient<br />(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p></p>
        <p><em>Thay đổi dải mã màu: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Nút "Bắt đầu trò chuyện"</td>
      <td style="text-align:left">
        <p><code>.add-new-conversation {background-color:#000000;}</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu: #000000;}</em>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.add-new-conversation <br />{background-image: linear-gradient(to right top, #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f);}</code>
        </p>
        <p></p>
        <p><em>Thay đổi dải mã màu: #056587, #0085a3, <br />#00a6ac, #00c59f, #0be17f</em>
        </p>
      </td>
    </tr>
  </tbody>
</table>### Sáng tạo tiêu đề cửa sổ chat

Thay đổi bố cục của cửa sổ chat gia tăng nhận diện hình ảnh thương hiệu của Doanh Nghiệp.  
[`https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png`](https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png): Thay link ảnh logo của Doanh Nghiệp

`.color-theme-default {background-color:#f44336;}   
.list-agents { float:left; width:45%; }   
.avatar-team { position:absolute; top:-70%;   
background: url(`[`https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png`](https://filev4.subiz.com/fiqbqxbalnpxeeandtdr-image.png)`);   
height: 100px; background-size: 150px;   
background-repeat: no-repeat; background-position: center; }   
.full { width:160px !important; }   
.avatar-team .avatar-agent{ display:none; }   
.team-intro { width:55%; margin-bottom:12px; }   
.team-intro p{ padding: 0 0 0 0; font-size:13px; }`

### Thay đổi màu sắc cửa sổ chat trên mobile

Trên cửa sổ chat bản mobile, bạn có thể thay đổi màu sắc chung cho toàn bộ cửa sổ chat hoặc màu sắc riêng của từng khung.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Vị trí thay đổi màu sắc</th>
      <th style="text-align:left">CSS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Toàn bộ cửa sổ chat</td>
      <td style="text-align:left">
        <p><code>.widget_mobile .color_theme_default <br />{ background-color: #0000; }</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu #0000</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tiêu đề</td>
      <td style="text-align:left">
        <p><code>.widget_mobile .widget-header <br />{ background-color: #0000; }</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu #0000</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Khung tin nhắn</td>
      <td style="text-align:left">
        <p><code>.widget_mobile .message-body <br />{ background-color: #0000; }</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu #0000</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Nút "Bắt đầu trò chuyện"</td>
      <td style="text-align:left">
        <p><code>.widget_mobile .add-new-conversation <br />{ background-color: #0000; }</code>
        </p>
        <p></p>
        <p><em>Thay đổi mã màu #0000</em>
        </p>
      </td>
    </tr>
  </tbody>
</table>###  Hạ thấp **chiều cao cửa sổ chat trên mobile**

 Cửa sổ Subiz chat sẽ mặc định hiển thị khoảng 90% màn hình điện thoại, để khách vẫn nhìn thấy link của website mua hàng.

Bạn muốn hạ cửa sổ chat trên mobile sẽ hiển thị thấp hơn so với mặc định, hãy dùng mã CSS dưới đây, có thể thay tỷ lệ 90%

 `.widget_mobile .widget_body {height: 90%;}`

### Tải lên chat button bản mobile

Website bản destop và bản mobile đang hiển thị chung một chat button. Để sử dụng riêng hình ảnh chat button trên bản mobile, bạn sẽ sử dụng CSS sau:  
Trong đó:   
_Thay đổi link ảnh chat button:_ [`https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png`](https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png)  
_Thay đổi kích thước ảnh chat button:_`width: 190px; height: 60px`

 `.widget_mobile .button-chat { border-radius: 0; background-image: url(`[`https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png`](https://filev4.subiz.com/fiqeoiwaoownfszxoyju-button_chat_10.png)`); background-repeat: no-repeat; }   
.widget_mobile .button-chat-icon { display: none; } @supports (-ms-ime-align:auto) { .widget_mobile .button-chat { border-radius: 50%; }   
.widget_mobile .button-chat-icon { display: inline-block; } }   
.widget_mobile .widget-button { width: 190px; height: 60px; }   
.widget_mobile .button-chat { border-radius: 0 !important; }   
.widget_mobile .widget-button:after { display: none; }   
.widget_mobile .widget_mini .close-widget-icon { display: none; }   
.widget_mobile .button-chat .avatar-preview img { display: none; }   
.widget_mobile .button-chat { box-shadow: none; background-color: transparent !important; }`

### Ẩn cửa sổ chat destop

### Ẩn cửa sổ chat mobile

### Ẩn chat button destop

### Ẩn chat button mobile

### Tùy chỉnh vị trí cửa sổ chat so với chân màn hình

### Tùy chỉnh vị trí chat button so với chân màn hình







