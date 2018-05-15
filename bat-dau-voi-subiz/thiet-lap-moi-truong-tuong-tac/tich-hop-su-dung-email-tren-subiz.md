# Tích hợp sử dụng Email trên Subiz

### THIẾT LẬP CHUYỂN TIẾP EMAIL TRÊN SUBIZ {#thiet-lap-chuyen-tiep-email-tren-subiz}

Khi đăng ký tài khoản Subiz, **bạn sẽ được cung cấp một địa chỉ email có dạng abc@mail.subiz.com**. Tất cả các email được gửi về địa chỉ này sẽ được coi như một cuộc hội thoại trên Subiz.

Với các email bạn đang sử dụng để tương tác với khách hàng, **bạn cần thiết lập để chuyển tiếp các email này về địa chỉ abc@mail.subiz.com**. Khi đó, bạn có thể dễ dàng quản lý tất cả các email và làm việc qua email ngay trên Subiz. Việc thiết lập chuyển tiếp gồm 2 bước:

**Bước 1: Tạo danh sách Income Email**

Để thêm 1 địa chỉ email vào danh sách Income Email, bạn làm theo các bước:

* * * Đăng nhập tài khoản và vào phần **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Email**
    * Chọn **Thêm Income Email**
    * Nhập địa chỉ email muốn chuyển tiếp vào phần **Nhập địa chỉ email**
    * Chọn **Thêm**

![](http://docv4.subiz.com/wp-content/uploads/2018/02/new-income-email.png)

**Bước 2: Cài đặt chuyển tiếp trên email của bạn**

**Cài đặt chuyển tiếp email Gmail**

Nếu bạn sử dụng tài khoản gmail, bạn cài đặt chuyển tiếp theo hướng dẫn sau:

* * Đăng nhập tài khoản gmail mà bạn đã nhập trong Income Email
  * Click vào biểu tượng bánh xe và chọn **Setting**
  * Tại phần Setting, chọn **Forwarding and POP/IMAP**
  * Click vào **Add a forwarding address**
  * Nhập địa chỉ email mà Subiz đã cung cấp cho bạn \(để tránh sai sót, bạn ấn vào nút **Sao chép** tại trang **Cài đặt email** trên app.Subiz.com để copy địa chỉ email này\)![](http://docv4.subiz.com/wp-content/uploads/2018/02/button-copy.png)​
  * Chọn **Next &gt; Proceed**
  * Gmail sẽ gửi một thư xác nhận tới địa chỉ email mà Subiz đã cấp cho bạn. Bạn kiểm tra thư này ngay tại phần Activities trên trang app. subiz.com như một đoạn hội thoại mới. Click vào link xác nhận được gửi trong thư.
  * Trở lại trang Setting trong tài khoản Gmail và tải lại trang \(nhấn F5\)
  * Chọn Forward a copy of incoming mail to
  * Chọn Keep Gmail’s copy in the Inbox nếu bạn muốn giữ các email đến trong hộp thư \(khuyến nghị sử dụng\)

Tham khảo hướng dẫn cài đặt chuyển tiếp với [Yahoo Mail](https://help.yahoo.com/kb/SLN22028.html), [Office 365](https://support.office.com/en-us/article/forward-email-from-office-365-to-another-email-account-1ed4ee1e-74f8-4f53-a174-86b748ff6a0e), [Outlook](https://support.office.com/en-us/article/turn-on-automatic-forwarding-in-outlook-on-the-web-7f2670a1-7fff-4475-8a3c-5822d63b0c8e) …

Sau khi hoàn thành 2 bước trên, thư gửi tới địa chỉ mail trong danh sách Income Email cũng sẽ được chuyển về Subiz như một hội thoại \(conversation\) mới. Khi bạn trả lời thư, người nhận sẽ nhìn thấy địa chỉ gửi đến là địa chỉ đã nhận thư \(địa chỉ email của bạn\).

​

### Cài đặt DKIM/ SPF cho tên miền để tối ưu việc gửi email {#cai-dat-dkim-spf-cho-ten-mien-de-toi-uu-viec-gui-email}

**DKIM \(Domain Keys Indentified Mail\)** là phương thức xác thực e-mail bằng chữ ký số của tên miền gửi thư. Việc thiết lập DKIM cho domain sẽ giúp thư của bạn gửi đi được xác thực và tránh vào hòm thư spam.

Để việc gửi email trên Subiz đạt hiệu quả cao nhất, bạn nên thiết lập DKIM và SPF trên domain của mình.

* ​[Đăng nhập tài khoản Subiz](http://app.subiz.com/), vào phần **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Email**
* Chọn **Configure DKIM**
* Nhập tên miền hòm thư của bạn \(dạng company.com\)
* Liên hệ người quản lý domain công ty để thiết lập DKIM và SPF cho domain

### TƯƠNG TÁC QUA KÊNH EMAIL {#tuong-tac-qua-kenh-email}

Chọn Tạo cuộc hội thoại mới và chọn kênh Email.

Trên cửa sổ New Email, bạn có thể soạn thảo email mới gửi tới user.

* **From:** Địa chỉ tin nhắn gửi đi. Bạn có thể lựa chọn trong danh sách các email đã được cài đặt trong income email.
* **To:** Địa chỉ email của user \(khách hàng\)
* **CC:** Nhập địa chỉ email của khách hàng mà bạn muốn gửi cùng nội dung email này
* **Tiêu đề:** Bạn nhập tiêu đề của email muốn gửi đi

![](https://docv4.subiz.com/wp-content/uploads/2018/02/Email.png)
