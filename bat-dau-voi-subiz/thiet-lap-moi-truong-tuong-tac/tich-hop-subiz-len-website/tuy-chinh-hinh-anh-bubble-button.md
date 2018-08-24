# Tùy chỉnh hình ảnh bubble button

### 1. Bubble button là gì?

Bubble button là hình ảnh kêu gọi và thu hút khách hàng chat trực tuyến trên cửa sổ Subiz chat. 

Mỗi doanh nghiệp có thể chủ động thiết kế hình ảnh bubble button để truyền tải thông điệp riêng và mang đến cho khách hàng những trải nghiệm thú vị khi truy cập website.

Bạn có thể lựa chọn sử dụng bubble button từ thư viện button của Subiz, hoặc tùy chọn hình ảnh button bất kỳ khác và tải lên Subiz.

Cách tùy chỉnh bubble button: Đăng nhập Subiz qua link [App.subiz.com &gt; Cài đặt &gt; Tài khoản &gt; Cửa sổ hội thoại &gt; Tùy chỉnh bubble button](https://app.subiz.com/settings/widget-setting)\*\*\*\*

### **2. Sử dụng thư viện button của Subiz**

Bạn chọn hình ảnh trong Thư viện button và Lưu thay đổi là sử dụng được luôn.

### **3. Sử dụng button bất kỳ**

Để sử dụng button bất kỳ, bạn cần có một hình ảnh button theo mong muốn của bạn giúp tạo ấn tượng riêng dành cho khách hàng. Kích thước chuẩn của hình ảnh button là 240 x 120 px.

Hướng dẫn 3 bước sử dụng bất kỳ button khác như sau:

**Bước 1**: Để tải hình ảnh button bất kỳ khác  
&gt; Chọn Tùy chỉnh bubble button   
&gt; Tải lên button tùy chỉnh   
&gt; Chọn tệp hoặc Kéo tệp để tải lên   
&gt; Nhấp "X" để thoát

**Bước 2**: Tối ưu hiển thị hình ảnh button  
&gt; Chọn Tùy chỉnh CSS   
&gt; Sao chép và dán đoạn mã CCS ngay phía sau đoạn mã có chứa /\* END: BUTTON CHAT \*/   
&gt; Lưu thay đổi 

| Kiểu cửa sổ hội thoại Thu gọn  | Kiểu cửa sổ hội thoại Mở rộng |
| :--- | :--- |
| .widget\_mini .close-widget-icon {display: none;}.button-chat .avatar-preview img {display: none;}.button-chat {box-shadow: none;background-color: transparent !important;}  | .widget\_full .close-widget-icon {display: none;}.button-chat .avatar-preview img {display: none;}.button-chat {box-shadow: none;background-color: transparent !important;}  |
|  |  |

{% hint style="info" %}
Lưu ý: Bạn cần xác định đúng **CỬA SỔ HỘI THOẠI** đang sử dụng **KIỂU**: **Thu gọn** hay **Mở rộng**, để chọn đúng mã CSS.
{% endhint %}

**Bước 3**: Lưu thay đổi tại Cửa sổ hội thoại



### 3. Một số mã CSS tối ưu hiển thị button bất kỳ khác 

  
****



