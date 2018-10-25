# Thống kê Subiz chat theo nguồn khách truy cập

Bạn là một nhà quản trị hay một Marketer, bạn cần thống kê số lượng khách hàng có cuộc hội thoại và tương tác qua Subiz chat theo từng nguồn truy cập? Từ đó, bạn sẽ có những quyết định phù hợp chăm sóc khách hàng và Marketing hiệu quả.

{% hint style="info" %}
**Lưu ý**: 

* Subiz tự động gửi 3 dữ liệu sự kiện qua Google Analytics bao gồm: Khách hàng gửi tin nhắn trên cửa sổ Subiz chat, Khách hàng nhận tin nhắn trên cửa sổ Subiz chat, Khách hàng mở cửa sổ Subiz chat.
* Trên Google Analytics, mỗi dữ liệu sự kiện Subiz được chia thành 3 thành tố sự kiện là: Danh mục sự kiện, Hành động sự kiện, Nhãn sự kiện. [Xem thêm cách đọc sự kiện Subiz trên Google Analytics](https://help.subiz.com/bao-cao-and-thong-ke/thong-ke-subiz-chat-tren-google-analytics#cac-loai-su-kien-subiz-gui-sang-ga). 
{% endhint %}

Để xem thống kê số lượng khách hàng có tương tác qua Subiz chat theo nguồn truy cập trên Google analytics, bạn sẽ thao tác 4 bước như sau:

### Bước 1: Đăng nhập [Google Analytics](https://analytics.google.com).

Vào mục Chuyển đổi &gt; Tất cả lưu lượng truy cập &gt; Kênh

### Bước 2: Thêm phân đoạn thống kê sự kiện SUBIZ chat

 Chọn Thêm phân đoạn &gt; Phân đoạn mới 

### Bước 3: Cài đặt điều kiện thống kê

Chọn Điều kiện &gt; Biến thể chọn Danh mục sự kiện - chứa - SUBIZ chat

Tùy từng mục đích thống kê, bạn sẽ chọn các điều kiện tương ứng. Một số ví dụ thống kê thường dùng.

* Ví dụ 1: Xem thống kê tổng số khách hàng có tương tác qua Subiz gồm gửi tin nhắn, nhận tin nhắn và mở cửa sổ Subiz chat, bạn chọn Điều kiện là Danh mục sự kiện - chứa - SUBIZ chat

  


* Ví dụ 2: Xem thống kê tổng số khách có nhận tin nhắn qua cửa sổ Subiz chat, chọn Điều kiện là Hành động sự kiện - chứa  - Received 



* Ví dụ 3: Xem thống kê tổng số khách có gửi tin nhắn qua cửa sổ Subiz chat, chọn Điều kiện là Hành động - sự kiện chứa - Sent



* Ví dụ 4: Xem thống kê tổng số khách có nhận tin nhắn và trả lời qua cửa sổ Subiz chat, chọn Điều kiện là Nhãn sự kiện - chứa - User



* Ví dụ 5: Xem thống kê tổng số khách đã mở cửa sổ Subiz chat, chọn Điều kiện là Hành động sự kiện - chứa - Opend

### Bước 4: Đặt tên phân đoạn & Lưu để cập nhật thống kê

{% hint style="info" %}
**Lưu ý**: Để so sánh thống kê của phân đoạn Subiz chat và các phân đoạn khác, bạn chọn Thêm phân đoạn &gt; tìm kiếm phân đoạn đã cài đặt của bạn và chọn Áp dụng.
{% endhint %}

