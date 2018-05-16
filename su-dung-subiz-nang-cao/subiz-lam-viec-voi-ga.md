# Subiz làm việc với GA

Subiz làm việc với [Google Analytics](https://www.google.com/analytics/) \(GA\) để ghi lại tương tác với khách truy cập. Qua đó bạn dễ dàng đánh giá được hiệu quả cũng như hiểu hơn về đối tượng khách truy cập.

### Tích hợp Subiz và GA {#google-analytics-integrated}

Website của bạn có đặt mã nhúng của GA và là thư viện mới nhất \( [analytics.js](https://developers.google.com/analytics/devguides/collection/analyticsjs/) \). Subiz sẽ tự xác định và tích hợp với tài khoản GA đặt trên web.

Bạn cũng cần chú ý rằng Subiz chưa làm việc với [Google Tag Manager](https://www.google.com/analytics/tag-manager/).

### Các loại sự kiện Subiz gửi sang GA {#subiz-google-analytics-events}

_SUBIZ Chat_: Là [Event Category](https://support.google.com/analytics/answer/1033068?hl=en) ghi nhận những hành động gửi tin nhắn trong cuộc chat. Mỗi tin nhắn là một Event \(sự kiện\). Các tin nhắn có thể được gửi từ Agent \(Agent chat\) hoặc Khách truy cập \(Visitor chat\).

_Subiz Labels_: Là Event Category ghi nhận hành động gắn nhãn hoặc xóa nhãn của Subiz. Các hành động gắn nhãn và xóa nhãn thường được thực hiện bằng [Trigger](https://docs.subiz.com/trigger/). Các hành động của Event là: _TriggerAddLabel_ cho gắn nhãn và _TriggerRemovedLabel_ cho xóa nhãn.

### Cách xem dữ liệu trong GA {#view-report-in-google-analytics}

* Bước 1: Đăng nhập GA, click vào Behavior tại menu trái.

![subiz-google-analytics-1](https://docs.subiz.com/wp-content/uploads/2015/12/subiz-google-analytics-11.png)

* Bước 2:  Click Events và chọn Overview để xem danh sách Event Category.

![subiz-google-analytics-2](https://docs.subiz.com/wp-content/uploads/2015/12/subiz-google-analytics-21.png)

* Bước 3: Lựa chọn để xem dữ liệu theo Category, Label hoặc Action.

![subiz-google-analytics-3](https://docs.subiz.com/wp-content/uploads/2015/12/subiz-google-analytics-31.png)

Bây giờ, bạn có thể truy cập GA và bắt đầu đọc dữ liệu thống kê. Cũng đừng quên thiết lập những mục tiêu \(Goal\) cho website của bạn.

