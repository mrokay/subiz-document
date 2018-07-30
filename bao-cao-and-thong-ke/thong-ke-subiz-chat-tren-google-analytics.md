# Thống kê Subiz chat trên Google Analytics

Website của bạn đã tích hợp Subiz và Google Analytics \(GA\). Subiz sẽ tự động xác định được tài khoản của GA và gửi dữ liệu sang GA dưới dạng các sự kiện \(Event\).

Đặc biệt, Subiz có thể làm việc với GA cài đặt thông qua Google Tag Manager.

### **Các loại sự kiện Subiz gửi sang GA**

Subiz gửi 3 loại sự kiện sang GA bao gồm:

* Event message sent: Sự kiện user gửi tin nhắn qua cửa sổ chat Subiz
* Event message received. Sự kiện user nhận tin nhắn trên cửa sổ chat Subiz
* Event Subiz chat windows open: Sự kiện mở cửa sổ Subiz chat

### **Thống kê sự kiện Subiz trên GA**

Trên GA, một sự kiện Subiz gửi sang được được thống kê với 3 thành tố chính:

* **Event Category** - Danh mục sự kiện: Subiz chat
* **Event Action** - Hành động sự kiện: + Received + Sent + Opened
* **Event label** - Nhãn dự kiện: + User + Window opens

### Hướng dẫn xem thống kê Subiz trên GA

Bước 1: Đăng nhập tài khoản Google Analytics của website cần kiểm tra và vào mục Behaviour \(Hành vi\)

Bước 2: 

