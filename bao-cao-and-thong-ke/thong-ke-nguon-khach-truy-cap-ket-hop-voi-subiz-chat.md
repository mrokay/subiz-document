# Thống kê Subiz chat theo nguồn khách truy cập

Subiz kết hợp mạnh mẽ với Google Analytics thống kê dữ liệu sự kiện Subiz chat với nhiều mục tiêu khác nhau. Trong đó, bạn có thể thống kê số lượng khách hàng có cuộc hội thoại và tương tác qua Subiz chat theo từng nguồn khách truy cập.

{% hint style="info" %}
**Lưu ý**: 

* Subiz tự động gửi 3 dữ liệu sự kiện qua Google Analytics bao gồm: Khách hàng gửi tin nhắn trên cửa sổ Subiz chat, Khách hàng nhận tin nhắn trên cửa sổ Subiz chat, Khách hàng mở cửa sổ Subiz chat.
* Trên Google Analytics, mỗi dữ liệu sự kiện Subiz được chia thành 3 thành tố sự kiện là: Danh mục sự kiện, Hành động sự kiện, Nhãn sự kiện. [Xem thêm cách đọc sự kiện Subiz trên Google Analytics](https://help.subiz.com/bao-cao-and-thong-ke/thong-ke-subiz-chat-tren-google-analytics#cac-loai-su-kien-subiz-gui-sang-ga). 
{% endhint %}

Để xem thống kê số lượng khách hàng có tương tác qua Subiz chat theo nguồn truy cập trên Google analytics, bạn sẽ thao tác 4 bước như sau:

### Bước 1: Đăng nhập [Google Analytics](https://analytics.google.com).

Vào mục CHUYỂN ĐỔI &gt; Tất cả lưu lượng truy cập &gt; Kênh

![Truy c&#x1EAD;p K&#xEA;nh trong Google Analytics](../.gitbook/assets/1-kenh-1-copy.jpg)

### Bước 2: Thêm phân đoạn thống kê sự kiện SUBIZ chat

 Chọn Thêm phân đoạn &gt; Phân đoạn mới 

![Th&#xEA;m ph&#xE2;n &#x111;o&#x1EA1;n m&#x1EDB;i th&#x1ED1;ng k&#xEA; Subiz chat](../.gitbook/assets/2-pd-moi-copy.jpg)

### Bước 3: Cài đặt điều kiện thống kê

Chọn Điều kiện &gt; Ô Biến thể sẽ chọn điều kiện tương ứng tùy theo từng mục tiêu thống kê.

![C&#xE0;i &#x111;&#x1EB7;t &#x111;i&#x1EC1;u ki&#x1EC7;n th&#x1ED1;ng k&#xEA;](../.gitbook/assets/3.1-dieu-kien-copy.jpg)

Tùy từng mục đích thống kê, bạn sẽ chọn các điều kiện tương ứng. Một số ví dụ thống kê thường dùng.

* Ví dụ 1: Xem thống kê tổng số khách hàng có hành động tương tác qua Subiz chat như gửi tin nhắn hoặc nhận tin nhắn hoặc mở cửa sổ Subiz chat, chọn Điều kiện là **Danh mục sự kiện** - **chứa** - **SUBIZ chat**

![Th&#x1ED1;ng k&#xEA; kh&#xE1;ch h&#xE0;ng c&#xF3; t&#x1B0;&#x1A1;ng t&#xE1;c qua Subiz chat](../.gitbook/assets/5.-subiz-chat-copy.jpg)

* Ví dụ 2: Xem thống kê tổng số khách có nhận tin nhắn qua cửa sổ Subiz chat,  chọn Điều kiện là **Hành động sự kiện - chứa  - Received** 

![Th&#x1ED1;ng k&#xEA; s&#x1ED1; kh&#xE1;ch h&#xE0;ng c&#xF3; nh&#x1EAD;n tin nh&#x1EAF;n qua Subiz](../.gitbook/assets/6.-receivced-copy.jpg)

* Ví dụ 3: Xem thống kê tổng số khách có gửi tin nhắn qua cửa sổ Subiz chat,  chọn Điều kiện là **Hành động sự kiện - chứa - Sent**

![Th&#x1ED1;ng k&#xEA; s&#x1ED1; kh&#xE1;ch h&#xE0;ng c&#xF3; g&#x1EED;i tin nh&#x1EAF;n qua Subiz](../.gitbook/assets/6.-sent-copy.jpg)

* Ví dụ 4: Xem thống kê tổng số khách có nhận và gửi tin nhắn qua cửa sổ Subiz chat, chọn Điều kiện  **Hành động sự kiện - chứa  - Received** và **Hành động sự kiện - chứa - Sent**

![ Th&#x1ED1;ng k&#xEA; s&#x1ED1; kh&#xE1;ch c&#xF3; nh&#x1EAD;n v&#xE0; g&#x1EED;i tin nh&#x1EAF;n qua Subiz](../.gitbook/assets/10-copy.jpg)

* Ví dụ 5: Xem thống kê tổng số khách có nhận tin nhắn HOẶC gửi tin nhắn qua cửa sổ Subiz chat,  chọn Điều kiện là **Nhãn sự kiện - chứa - User**

![Th&#x1ED1;ng k&#xEA; s&#x1ED1; kh&#xE1;ch c&#xF3; nh&#x1EAD;n HO&#x1EB6;C g&#x1EED;i tin nh&#x1EAF;n qua Subiz](../.gitbook/assets/8.-nhan-user-copy.jpg)

* Ví dụ 6: Xem thống kê tổng số khách đã mở cửa sổ Subiz chat,  chọn Điều kiện là **Hành động sự kiện - chứa - Opened**

![Th&#x1ED1;ng k&#xEA; s&#x1ED1; kh&#xE1;ch c&#xF3; m&#x1EDF; c&#x1EED;a s&#x1ED5; Subiz chat](../.gitbook/assets/7.-opened-copy.jpg)

### Bước 4: Đặt tên phân đoạn & Lưu để cập nhật thống kê

![&#x110;&#x1EB7;t t&#xEA;n ph&#xE2;n &#x111;o&#x1EA1;n v&#xE0; L&#x1B0;u](../.gitbook/assets/9.-luu-copy.jpg)

{% hint style="info" %}
**Lưu ý**: Để so sánh thống kê của phân đoạn Subiz chat và các phân đoạn khác, bạn chọn Thêm phân đoạn &gt; tìm kiếm phân đoạn đã cài đặt của bạn và chọn Áp dụng.
{% endhint %}

> Bạn cần hỗ trợ thêm về thống kê Subiz, hãy gửi yêu cầu cho Subiz qua Support@Subiz.com hoặc chat online tại [Subiz.com](https://subiz.com/vi/feature.html)!



