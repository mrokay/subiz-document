# Tích hợp Subiz Chat

### Subiz chat là gì?

[Subiz Chat](https://subiz.com/vi/live-chat.html%20) là một kênh tương tác với khách hàng ghé thăm website của doanh nghiệp. Khi tích hợp cửa sổ tương tác [Subiz](https://subiz.com/vi/) trên Website, **sẽ giúp doanh nghiệp theo dõi, tiếp cận, tương tác và chuyển đổi khách hàng** ghé thăm website của bạn.

### Cách tích hợp Subiz chat lên website

Tích hợp [Subiz](https://subiz.com/vi/) vào website bằng việc **Sao chép đoạn mã nhúng Subiz** \(không được thay đổi, sao chép toàn bộ mã\) và **dán vào các trang mà bạn muốn** đặt cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20). Bạn thực hiện theo 03 bước sau:

#### Bước 1: Lấy mã nhúng của Subiz

Để lấy mã nhúng của [Subiz](https://subiz.com/vi/) bạn làm theo các bước sau:

1. [**Đăng nhập tài khoản Subiz**](http://app.subiz.com/) ****&gt; [**Cài đặt &gt; Tài khoản &gt; Tích hợp**](https://app.subiz.com/settings/install)
2. Tại phần **Mã nhúng Subiz**, click nút **Sao chép** để thực hiện sao chép nhanh đoạn mã nhúng.

![Sao ch&#xE9;p m&#xE3; nh&#xFA;ng Subiz](../../../.gitbook/assets/copy-embed-code.png)

{% hint style="info" %}
**Lưu ý:** Mỗi Tài khoản [Subiz](https://subiz.com/vi/) có một mã nhúng khác nhau, vì thế khi thay đổi Tài khoản [Subiz](https://subiz.com/vi/), bạn đồng thời phải tích hợp lại mã nhúng mới trên code web.
{% endhint %}

#### Bước 2: Đặt mã nhúng Subiz vào website

[Subiz](https://subiz.com/vi/) tương thích với hầu hết các website xây dựng trên các nền tảng khác nhau. Việc đặt mã nhúng vào website khá đơn giản, chỉ cần Sao chép mã nhúng [Subiz](https://subiz.com/vi/) và dán vào mọi trang bạn muốn có cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20). Code mã nhúng Subiz phải được **đặt ngay trước thẻ đóng &lt;/body&gt;.**

![C&#xE1;ch &#x111;&#x1EB7;t m&#xE3; nh&#xFA;ng Subiz](../../../.gitbook/assets/embedcode.gif)

#### Bước 3: Kiểm tra cửa sổ Subiz trên website

Sau khi tích hợp mã nhúng Subiz, quay lại trình duyệt và truy cập vào website. Bạn sẽ thấy cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20) ở góc dưới cùng bên phải của website.

Nếu bạn vẫn không thấy cửa sổ [Subiz Chat](https://subiz.com/vi/live-chat.html%20), bạn có thể kiểm tra trực tiếp trong trang Quản lý theo các bước sau:

1. [Đăng nhập tài khoản](http://app.subiz.com/)​ Subiz
2. Chọn[ **Cài đặt** &gt; **Tài khoản** &gt; **Tích hợp**](https://app.subiz.com/settings/install)
3. Nhập đường dẫn **website** bạn và click nút **Kiểm tra**.

![Ki&#x1EC3;m tra xem m&#xE3; nh&#xFA;ng Subiz tr&#xEA;n website c&#x1EE7;a b&#x1EA1;n](../../../.gitbook/assets/kiem-tra-cai-ma-nhung.png)

{% hint style="danger" %}
Nếu hệ thống báo không tìm thấy cửa sổ Chat, bạn kiểm tra lại mã nhúng Subiz trên website hoặc liên hệ với [Subiz](https://subiz.com/vi/) để được hỗ trợ.
{% endhint %}

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

> Bạn còn băn khoăn? Hãy chat trực tuyến với hỗ trợ viên ngay trên website [Subiz.com](https://subiz.com/vi/feature.html)!

