# Thống kê Subiz chat trên Google Analytics

Website của bạn đã tích hợp Subiz và Google Analytics \(GA\). Subiz sẽ tự động xác định được tài khoản của GA và gửi dữ liệu sang GA dưới dạng các sự kiện \(Event\).

Đặc biệt, Subiz có thể làm việc với GA cài đặt thông qua Google Tag Manager.

### **Các loại sự kiện Subiz gửi sang GA**

Subiz gửi 3 loại sự kiện sang GA bao gồm:

* Event message sent: Sự kiện user gửi tin nhắn qua cửa sổ Subiz chat
* Event message received. Sự kiện user nhận tin nhắn qua cửa sổ Subiz chat
* Event Subiz chat windows open: Sự kiện mở cửa sổ Subiz chat

### **Thống kê sự kiện Subiz trên GA**

Trên GA, một sự kiện Subiz gửi sang được được thống kê với 3 thành tố chính:

* **Danh mục sự kiện - Event Category** - : Subiz chat
* **Hành động sự kiện - Event Action**: + Received - Hành động nhận tin nhắn qua Subiz + Sent - Hành động gửi tin nhắn qua Subiz + Opened - Hành động mở cửa sổ Subiz chat
* **Nhãn sự kiện - Event label**: + User - Khách hàng có nhận và gửi tin nhắn qua Subiz + Subiz windows - Cửa sổ Subiz chat mở

### Hướng dẫn xem thống kê Subiz trên GA

**Bước 1**: [Đăng nhập tài khoản Google Analytics](https://analytics.google.com/analytics/) của website cần kiểm tra 

**Bước 2**: Trong mục Báo cáo &gt; chọn HÀNH VI &gt; Sự kiện 

![Xem th&#x1ED1;ng k&#xEA; S&#x1EF1; ki&#x1EC7;n tr&#xEA;n Google Analytics](../.gitbook/assets/buoc-2.jpg)

**Bước 3**: Chọn Tổng quan để xem thống kê Danh mục sự kiện

![Xem th&#x1ED1;ng k&#xEA; Subiz chat trong Danh m&#x1EE5;c s&#x1EF1; ki&#x1EC7;n](../.gitbook/assets/buoc-2-copy.jpg)

**Bước 4**: Để xem thống kê chi tiết các Hành động sự kiện của Subiz: vào Sự kiện hàng đầu &gt; Danh mục sự kiện &gt;  chọn Subiz chat &gt; Hành động sự kiện

![Xem th&#x1ED1;ng k&#xEA; chi ti&#x1EBF;t H&#xE0;nh &#x111;&#x1ED9;ng s&#x1EF1; ki&#x1EC7;n c&#x1EE7;a Subiz](../.gitbook/assets/buoc-7-copy.jpg)

**Bước 5**: Để xem thống kê chi tiết các Nhãn sự kiện của Subiz: vào Sự kiện hàng đầu &gt; Danh mục sự kiện &gt;  chọn Subiz chat &gt;  Nhãn sự kiện

![Xem th&#x1ED1;ng k&#xEA; chi ti&#x1EBF;t Nh&#xE3;n s&#x1EF1; ki&#x1EC7;n c&#x1EE7;a Subiz](../.gitbook/assets/buoc-8-copy.jpg)

> Bạn đã đọc được thống kê Subiz chat trên Google Analytics?   
> Cần hỗ trợ thêm, bạn hãy chat với tư vấn viên ngay trên website [Subiz.com](https://subiz.com/vi/feature.html) nhé.

