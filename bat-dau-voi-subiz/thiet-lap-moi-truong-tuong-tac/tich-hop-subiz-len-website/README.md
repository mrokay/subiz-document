# Tích hợp Subiz Chat

### Subiz chat là gì?

[Subiz Chat](https://subiz.com/vi/live-chat.html%20) là một kênh tương tác với khách hàng ghé thăm website của doanh nghiệp. Khi tích hợp cửa sổ chat [Subiz](https://subiz.com/vi/) trên website, **sẽ giúp doanh nghiệp tiếp cận, tương tác và chuyển đổi khách hàng** ghé thăm website của bạn.

### Cách tích hợp Subiz chat lên website

Tích hợp [Subiz](https://subiz.com/vi/) vào website bằng việc **Sao chép đoạn mã nhúng Subiz** đầy đủ và **dán vào các trang code web mà bạn muốn** hiện thị cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20). Bạn thực hiện theo 03 bước sau:

* **Bước 1: Lấy mã nhúng của Subiz**  Để lấy mã nhúng của Subiz, bạn đăng nhập Subiz qua link [**App.subiz.com**](https://app.subiz.com/) &gt; Chọn Cài đặt &gt; Kênh tương tác &gt; Cửa sổ chat Subiz &gt; [**Cài đặt lên website**](https://app.subiz.com/settings/widget-setting/setting-website) Tại đây, bạn chọn nút **Sao chép** để thực hiện sao chép đầy đủ đoạn mã nhúng Subiz.

![Sao ch&#xE9;p m&#xE3; nh&#xFA;ng c&#xE0;i &#x111;&#x1EB7;t c&#x1EED;a s&#x1ED5; chat Subiz](../../../.gitbook/assets/ma-nhung-subiz.png)

{% hint style="info" %}
**Lưu ý:** Mỗi Tài khoản [Subiz](https://subiz.com/vi/) có một mã nhúng khác nhau. Vì thế khi thay đổi tài khoản [Subiz](https://subiz.com/vi/), bạn đồng thời phải tích hợp lại mã nhúng mới trên code web.
{% endhint %}

* **Bước 2: Đặt mã nhúng Subiz vào website**  [Subiz](https://subiz.com/vi/) tương thích với hầu hết các website xây dựng trên các nền tảng khác nhau.  Việc đặt mã nhúng vào website khá đơn giản. Sau khi sao chép mã nhúng [Subiz](https://subiz.com/vi/), bạn dán đoạn mã nhúng dán vào trước thẻ **&lt;/body&gt;** trên tất cả các trang bạn muốn hiện cửa sổ Subiz chat.

![C&#xE1;ch &#x111;&#x1EB7;t m&#xE3; nh&#xFA;ng Subiz](../../../.gitbook/assets/embedcode.gif)

{% hint style="info" %}
**Lưu ý**: Nếu bạn không chuyên về code web, bạn đề nghị người thiết kế website hỗ trợ đặt mã nhúng Subiz bằng cách điền địa chỉ email của thiết kế website vào ô **Gửi mã nhúng tới quản trị viên website của bạn.**  
Subiz sẽ tự động gửi email hướng dẫn chi tiết các bước cài đặt cửa sổ chat lên website.
{% endhint %}

![G&#x1EED;i m&#xE3; nh&#xFA;ng t&#x1EDB;i qu&#x1EA3;n tr&#x1ECB; vi&#xEA;n website c&#x1EE7;a b&#x1EA1;n](../../../.gitbook/assets/gui-mail-ma-nhung.png)

* **Bước 3: Kiểm tra cửa sổ Subiz trên website**  Sau khi tích hợp mã nhúng Subiz, quay lại trình duyệt và truy cập vào website. Bạn sẽ thấy cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20) ở góc dưới cùng bên phải của website.  Nếu bạn không thấy cửa sổ chat trên website, bạn hãy bạn kiểm tra lại mã nhúng Subiz trên website đã đặt đúng vị trí chưa hoặc gửi mail hỗ trợ tới **Support@subiz.com**.

### Tích hợp Subiz qua Google Tag Manager

Subiz kết hợp mạnh mẽ với Google Tag Manager. 

Khi bạn sử dụng Google Tag Manager trên website, bạn có thể tích hợp Subiz chat vào website thông qua Google Tag Manager theo các bước như sau:

1. **Đăng nhập**[ Tagmanager.google.com](https://tagmanager.google.com/#/home)
2. **Chọn account quản lý website** sẽ tích hợp Subiz chat tại All account.
3. **Tạo Tag mới**: Tại WORKSPACE chọn Tags &gt; NEW

![T&#x1EA1;o Tags m&#x1EDB;i](../../../.gitbook/assets/2-tags-copy.jpg)

* **Untitled Tag**: Điền tên Tag để phân biệt các Tag và chức năng của Tag
* **Tag Configuration**: Chọn Custom HTML &gt; [Sao chép mã nhúng Subiz](https://app.subiz.com/settings/install) và dán vào ô HTML
* Chọn ****\(tick\) **Support document.write**
* **Triggering**: Chọn All Pages nếu muốn hiển thị cửa sổ chat Subiz trên tất cả các trang của website

![Tag Subiz chat tr&#xEA;n Google Tag Manager](../../../.gitbook/assets/1-subiz-chat-copy.jpg)

{% hint style="info" %}
**Lưu ý**: Trigger là điều kiện bạn muốn thẻ Tag Subiz chat sẽ hoạt động. Bạn có thể tùy chọn Trigger theo nhu cầu riêng. Ví dụ:

* Tất cả các trang của website \(All Pages\) sẽ hiển thị cửa sổ Subiz chat.
* Chỉ một số trang \(Some Pages\) sẽ hiển thị cửa sổ Subiz chat.
* Khách có một hành động cụ thể như Click, kéo scroll chuột, hay sau một khoảng thời gian vào website,.... sẽ hiển thị cửa sổ Subiz chat.
{% endhint %}

* Chọn **SAVE** &gt;  chọn **SUBMIT** ở góc phải màn hình &gt; Điền thông tin mô tả trong mục **Publish and Create Version** &gt; chọn **PUBLISH** để hoàn thành.

Bạn hãy vào website và chọn F5 tải lại trang, kiểm tra cửa sổ chat Subiz đã hiển thị trên website.

> Bạn còn băn khoăn? Hãy gửi email hỗ trợ tới Support@subiz.com.

