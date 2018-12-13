# Tùy chỉnh hình ảnh chat button

### Chat button là gì?

Chat button là hình ảnh kêu gọi và thu hút khách hàng chat trực tuyến trên cửa sổ Subiz chat. Khi khách hàng click vào chat button sẽ mở ra cửa sổ chat.

Mỗi doanh nghiệp có thể chủ động thiết kế hình ảnh chat button để truyền tải thông điệp riêng và mang đến cho khách hàng những trải nghiệm thú vị khi truy cập website.

### Hướng dẫn cài đặt chat button

Hướng dẫn cài đặt chat button: Đăng nhập Subiz qua link [App.subiz.com &gt; Cài đặt &gt; Tài khoản &gt; Cửa sổ hội thoại &gt; Tùy chỉnh chat button](https://app.subiz.com/settings/widget-setting?button=library)

![](../../../.gitbook/assets/chat-button-copy.jpg)

### **1. Sử dụng Thư viện button**

Chọn button trong [Thư viện button](https://app.subiz.com/settings/widget-setting?button=default) và Lưu thay đổi để cập nhật sử dụng.

![Th&#x1B0; vi&#x1EC7;n button](../../../.gitbook/assets/thu-vien-button-copy.jpg)

### 2. Sử dụng Button large

Tham khảo [một số mẫu Button larger](https://app.subiz.com/settings/widget-setting?button=library), chọn và lưu thay đổi để sử dụng.

![M&#x1EAB;u Button large](../../../.gitbook/assets/button-large-copy%20%281%29.jpg)

### **3. Sử dụng button tùy chỉnh** 

Để sử dụng mẫu button thiết kế của riêng bạn, bạn sẽ vào [Sử dụng button tùy chỉnh](https://app.subiz.com/settings/widget-setting?button=custom) &gt; Click **Chọn** hoặc Kéo tệp để tải lên &gt; Nhấp "**X**" để thoát &gt; Lưu thay đổi 

![S&#x1EED; d&#x1EE5;ng button t&#xF9;y ch&#x1EC9;nh](../../../.gitbook/assets/button-tuy-chinh-copy.jpg)

{% hint style="success" %}
Một số lưu ý:

* Hình ảnh button thiết kế cần định dạng Png, phông nền là transparent.
* Kích thước chuẩn là 240 x 120 px.
* Xem thêm một số mẫu hình ảnh button: [button 1](https://filev4.subiz.com/fiqcggngypeovdudlqyu-button_chat_01.png) -  [button 2](https://filev4.subiz.com/fiqcgvyibtxjcxnbjysc-button1_vn.png) - [button 3](https://filev4.subiz.com/fiqcggnolwzgyzltheem-button_chat_05.png) - [button 4](https://filev4.subiz.com/fiqcgvyssbundnpuqkqs-button4_vn.png) -  [button 5](https://filev4.subiz.com/fiqcqpihreurxviwekol-artboard_1_copy_9.png) - [button 6](https://filev4.subiz.com/fiqcqpimprgfdctpdtht-artboard_1_copy_10.png) -  [button 7](https://filev4.subiz.com/fiqcqpitaljpxccvhmow-artboard_1_copy_11.png) - [button 8](https://filev4.subiz.com/fiqcggnpqqrmggiofklb-button_chat_07.png) - [button 9](https://filev4.subiz.com/fiqcgvyqfhiokhwiqmnz-button3_en.png) - [button 10](https://filev4.subiz.com/fiqcgvysbxbykjcrorum-button4_en.png).
* Một số mẫu button chào mừng ngày Quốc Khánh 2/9: [Xem chi tiết](https://subiz.com/blog/viet-nam-tren-website-cua-ban.html)
* Mẫu button Giáng sinh:
* Mẫu button Năm mới: 
{% endhint %}

### CSS tối ưu hiển thị chat button trên website

Khi bạn sử dụng button large hoặc button tùy chỉnh của bạn thiết kế, Subiz có các mã CSS giúp thay đổi và tối ưu hiển thị button trên website.  
Các bước cài đặt: [Cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting) &gt; Tùy chỉnh CSS &gt; Sao chép và dán mã CSS phù hợp vào bảng Tùy chỉnh CSS  &gt; Lưu thay đổi  tại bảng &gt; Lưu thay đổi tại Cửa sổ Subiz chat.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Chức năng CSS</th>
      <th style="text-align:left">Cửa sổ hội thoại kiểu Thu gọn</th>
      <th style="text-align:left">Cửa số hội thoại kiểu Mở Rộng</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>CSS tùy chỉnh vị trí button</p>
        <p>so với chân màn hình</p>
        <p>(Tối đa 150px)</p>
      </td>
      <td style="text-align:left"><code>.widget-button<br />{bottom:0;}</code>
      </td>
      <td style="text-align:left"><code>.widget-button<br />{bottom:0;}</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>CSS tùy chỉnh vị trí cửa sổ chat
          <br />so với chân màn hình</p>
        <p>(Tối đa 140 px)</p>
      </td>
      <td style="text-align:left"><code>.widget_mini .widget_body<br />{bottom:0;}</code>
      </td>
      <td style="text-align:left"><code>.widget_full .widget_body<br />{bottom:0;}</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>CCS tùy chỉnh chiều cao
          <br />preview tin nhắn mới</p>
        <p>(Tối đa 110px)</p>
      </td>
      <td style="text-align:left">
        <p><code>.button-chat .bubble-chat {</code>
        </p>
        <p><code>bottom: 75px;</code>
        </p>
        <p><code>}</code>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>.button-chat .bubble-chat {</code>
        </p>
        <p><code>bottom: 75px;</code>
        </p>
        <p><code>}</code>
        </p>
      </td>
    </tr>
  </tbody>
</table>

> Bạn có băn khoăn và cần hỗ trợ, vui lòng chat trực tiếp với tư vấn viên trên website [Subiz.com.](https://subiz.com/vi/feature.html)

