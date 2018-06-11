# Các ví dụ tự động gửi tin nhắn

Hành động Gửi tin nhắn tới user được thực hiện trên kênh Subiz Chat. Hành động này sẽ khởi tạo cuộc hội thoại với khách truy cập website thỏa mãn điều kiện đặt trước và gửi kèm 1 tin nhắn. **Tin nhắn có chức năng như lời mời chat tự động, giúp bạn gửi lời chào riêng biệt tới từng đối tượng khách hàng.**

Xem thêm [Tại sao phải chào hỏi khách hàng ghé thăm website](https://subiz.com/blog/tai-sao-phai-chao-hoi-khach-hang-ghe-tham-website.html)​

**Bạn có thể sử dụng nhiều Automation cùng lúc để gửi nhiều tin nhắn với các mục đích khác nhau.** Sau đây là một số gợi ý về điều kiện cài đặt Automation để bạn thuận tiện lựa chọn.

### Gửi tin nhắn tới khách vào 1 trang cụ thể trên website {#1-gui-tin-nhan-toi-khach-vao-1-trang-cu-the-tren-website}

Khi khách hàng mới ghé thăm website, bạn muốn gửi đến khách hàng một lời chào đến họ, để họ biết sự hiện diện của bạn và luôn sẵn sàng giúp họ bất cứ khi nào trong quá trình mua sắm.

Ví dụ: URL của trang – chứa – http://abc.com.vn/

![Ch&#xE0;o kh&#xE1;ch h&#xE0;ng v&#xE0;o website ](../../.gitbook/assets/chao-khach-hang-vao-website.png)

### Gửi tin nhắn đến khách chưa có thông tin cá nhân {#2-gui-tin-nhan-den-khach-chua-co-thong-tin-ca-nhan}

Với các khách hàng chưa có thông tin cá nhân trên hệ thống, bạn có thể gửi chào kèm theo lời mời khách để lại thông tin cá nhân để bạn có thể liên hệ lại bất cứ lúc nào.

![Ch&#xE0;o kh&#xE1;ch h&#xE0;ng kh&#xF4;ng c&#xF3; th&#xF4;ng tin](../../.gitbook/assets/chao-khach-hang-khong-co-thong-tin.png)

### Gửi tin nhắn cho khách hàng khi xem một sản phẩm cụ thể {#3-gui-tin-nhan-cho-khach-hang-theo-khu-vuc-dia-ly}

Bạn muốn gửi thông điệp quảng cáo tới các khách vào 1 trang sản phẩm cụ thể, hoặc muốn gửi chương trình khuyến mãi cho khách vào trang thanh toán? Bạn chỉ cần thiết lập Automation theo điều kiện URL của trang chứa link sản phẩm:

![Ch&#xE0;o kh&#xE1;ch khi kh&#xE1;ch xem m&#x1ED9;t s&#x1EA3;n ph&#x1EA9;m c&#x1EE5; th&#x1EC3;](../../.gitbook/assets/chao-khach-khi-xem-mot-san-pham-cu-the.png)

### Gửi tin nhắn cho khách hàng đến từ một thành phố cụ thể

Nếu bạn có những khách hàng đến từ những thành phố khác nhau và bạn muốn có thể dễ dàng nhận diện được những khách hàng này và gửi lời chào đến họ, bạn hãy cài đặt automation theo hướng dẫn sau:

![Ch&#xE0;o kh&#xE1;ch h&#xE0;ng &#x111;&#x1EBF;n t&#x1EEB; m&#x1ED9;t th&#xE0;nh ph&#x1ED1; c&#x1EE5; th&#x1EC3;](../../.gitbook/assets/chao-khach-den-tu-mot-thanh-pho-cu-the.png)

### Gửi tin nhắn cho khách hàng theo khu vực địa lý

Subiz hỗ trợ bạn gửi tin nhắn riêng biệt tới từng đối tượng khách hàng chia theo khu vực địa lý theo Quốc gia. Bạn có thể sử dụng để gửi tin nhắn với ngôn ngữ phù hợp tới từng đối tượng khách hàng. Ví dụ, với khách hàng đến từ Việt Nam, bạn cài đặt tin nhắn bằng ngôn ngữ Tiếng Việt.

Điều kiện: Mã quốc gia – bằng – VN

![Ch&#xE0;o kh&#xE1;ch h&#xE0;ng &#x111;&#x1EBF;n t&#x1EEB; Vi&#x1EC7;t Nam](../../.gitbook/assets/chao-khach-hang-den-tu-viet-nam.png)

Với khách hàng nước ngoài, bạn cài đặt tin nhắn bằng ngôn ngữ Tiếng Anh.

Điều kiện: Mã quốc gia – không phải là – VN

![Ch&#xE0;o kh&#xE1;ch h&#xE0;ng &#x111;&#x1EBF;n t&#x1EEB; n&#x1B0;&#x1EDB;c ngo&#xE0;i](../../.gitbook/assets/chao-khach-hang-nuoc-ngoai.png)

Về điều kiện Quốc gia và Mã quốc gia, bạn đối chiếu theo chuẩn tại [https://countrycode.org/](https://countrycode.org/). Trong đó: Tên Quốc gia xem tại cột COUNTRY và Mã quốc gia xem tại cột ISO CODES, phần mã 2 kí tự.

Ví dụ:

Quốc gia – Afghanistan. Mã quốc gia – AF

![C&#xE1;ch xem m&#xE3; code c&#xE1;c qu&#x1ED1;c gia](../../.gitbook/assets/countrycode.png)

### Loại trừ 1 địa chỉ IP cụ thể {#4-loai-tru-1-dia-chi-ip-cu-the}

Trong trường hợp bạn muốn gửi tin nhắn tự động tới khách hàng, nhưng không muốn làm ảnh hưởng tới các nhân viên công ty thường xuyên vào website để làm việc, bạn có thể loại trừ địa chỉ IP nội bộ khi gửi tin nhắn.

Điều kiện: Địa chỉ IP của user – không phải là –

![&#x110;i&#x1EC1;u ki&#x1EC7;n lo&#x1EA1;i tr&#x1EEB; m&#x1ED9;t &#x111;&#x1ECB;a ch&#x1EC9; IP](../../.gitbook/assets/ip.png)

### Lưu ý khi tạo Automation gửi tin nhắn tự động {#luu-y-khi-tao-automation-gui-tin-nhan-tu-dong}

{% hint style="info" %}
* Nhấn Enter để xuống dòng khi tạo tin nhắn
* Khi viết URL hệ thống sẽ hiển thị dạng link để khách hàng click trực tiếp
* Một automation chỉ chạy 1 lần với 1 khách truy cập. Bạn có thể tạo nhiều Automation để gửi nhiều tin nhắn tùy theo chiến lược của công ty.
* Khi khách vừa truy cập website, cửa sổ Subiz chat sẽ tự bật với lời chào bạn đã thiết lập.
{% endhint %}

Nếu khách truy cập “không thực hiện ẩn” cửa sổ chat này, các tin nhắn tự động tiếp theo sẽ được thông báo bằng số lượng, nằm ở trên cùng bên trái của cửa số chat. Khi khách truy cập nhấn vào thông báo đó, thì tất cả các tin nhắn sẽ hiển thị ra.

![Tin nh&#x1EAF;n hi&#x1EC7;n tr&#xEA;n c&#x1EED;a s&#x1ED5; chat kh&#xF4;ng b&#x1ECB; &#x1EA9;n](../../.gitbook/assets/cua-so-ko-bi-an.png)

Nếu khách truy cập “thực hiện ẩn” cửa sổ chat và đọc những trang tiếp theo mà bạn có thiết lập trang thiết lập tin nhắn tự động của trang đó, thì tin nhắn sẽ hiển thị dưới dạng preview.

![Tin nh&#x1EAF;n hi&#x1EC7;n khi kh&#xE1;ch h&#xE0;ng &#x1EA9;n c&#x1EED;a s&#x1ED5; chat](../../.gitbook/assets/loi-chao-automation-300x250.jpg)

