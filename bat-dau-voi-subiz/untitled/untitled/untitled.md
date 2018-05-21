# Tạo Rule mới

Tạo Rule mới **là tạo quy tắc mới** để thiết lập tự động phân phối cuộc hội thoại tới một hoặc một nhóm Agent của bạn.

Để tạo rule mới, bạn [đăng nhập tài khoản](https://app.subiz.com/login) và vào phần **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Rule &gt; Tạo Rule mới**

![](http://docv4.subiz.com/wp-content/uploads/2018/01/create-rule.png)

### Bước 1: Đặt tên và mô tả Rule

* **Tên:** Đặt tên để quản lý trong bảng danh sách các rule.
* **Mô tả**: Mô tả điều kiện và đối tượng của rule để dễ nhận biết.

![](https://docv4.subiz.com/wp-content/uploads/2018/01/rule-name.png)

### Bước 2: Đặt các điều kiện cho Rule

Điều kiện trong Rule là các tiêu chuẩn để một Rule được thực thi, giúp thiết lập các kịch bản phân phối cuộc hội thoại tới Agent một cách thông minh và hoạt động đúng lúc. Một rule chỉ được thực thi khi các điều kiện trong rule được đáp ứng.

{% hint style="info" %}
Lưu ý: Một rule chỉ được thực thi khi thông tin của cuộc hội thoại và user khởi tạo cuộc hội thoại đáp ứng các điều kiện đã được cài đặt \(một cuộc hội thoại chỉ được phân phối theo một rule\)
{% endhint %}

**Cách thiết lập các điều kiện trong Rule:**

* Click **Thêm điều kiện** để kết hợp nhiều điều kiện trong một rule.
* Chọn **Và/ Hoặc** để xác định mối quan hệ giữa các điều kiện.

![](https://docv4.subiz.com/wp-content/uploads/2018/02/Dieu-kien-trong-rule-1.png)

**Bạn có thể chọn một hay nhiều điều kiện trong danh sách các điều kiện trong Rule dưới đây:​**



| **CÁC ĐIỀU KIỆN** | **CÁCH SỬ DỤNG** | **VÍ DỤ** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Any condition | Bất cứ điều kiện nàoKhi lựa chọn điều kiện này, các cuộc hội thoại sẽ luôn được phân phối cho các agent được thiết lập trong rule |  |
| **Date Time** |  |  |
| Giờ trong ngày | Dùng khi bạn muốn phân chia cuộc thoại cho các Agent theo các khung giờ trong ngày.Giờ trong ngày từ 0-23 | Ca sáng cho Agent ACa chiều cho Agent BCa tối cho Agent C |
| Ngày trong tuần | Dùng điều kiện này để phân chia cuộc hội thoại theo ngàyLưu ý: Ngày trong tuần được ghi nhận theo số thứ tự từ 2-8. Thứ Hai = 2, Thứ Ba = 3… , Chủ nhật = 8 | Ngày chẵn cho Agent ANgày lẻ cho Agent B3 ngày đầu tuần cho Agent C3 ngày cuối tuần cho Agent D |
| **Hội thoại** |  |  |
| URL của trang | Mỗi trang Url thường tập trung giới thiệu về một Sản phẩm và Dịch vụ cụ thể, bạn có thể nhận diện khách hàng đang xem các trang cụ thể này và phân phối cuộc hội thoại cho từng Agent chuyên trách | Khách vào trang sản phẩm 1, phân phối cho sale 1Khách vào trang sản phẩm 2, phân phối cho sale 2Khách vào trang Bảo hành, phân phối cuộc hội thoại cho nhân viên chăm sóc khách hàngKhách vào trang Báo giá, phân phối cuộc hội thoại cho nhân viên kinh doanh |
| Tiêu đề trang | Tiêu đề trang gần giống Url trang, dùng để phân phối cuộc hội thoại cho các trang cụ thể cho từng Agent chuyên trách | Tiêu đề trang chứa các từ khóa sau:Các trang có tiêu đề chứa từ khóa “Máy Ảnh” phân phối cuộc hội thoại cho Agent ACác trang có tiêu đề chứa từ khóa “laptop” phân phối cuộc hội thoại cho Agent A |
| Nội dung tin nhắn | Khi khách hàng gửi tin nhắn đầu tiên có liên quan đến một nội dung nhất định, bạn có thể phân phối cuộc hội thoại này cho người chuyên trách về nội dung đó | Cho xin “giá” sản phẩm A. Khi tin nhắn đầu tiên của khách hàng có chứa từ “giá”, cuộc hội thoại này sẽ được phân phối cho Agent kinh doanh |
| Ngôn ngữ trên trình duyệt | Ngôn ngữ trên trình duyệt tuân theo chuẩn [ISO Language Code](http://www.lingoes.net/en/translator/langcode.htm), ví dụ: vi-VN, en-USKhách hàng sử dụng ngôn ngữ trình duyệt nào thì hãy phân phối cuộc hội thoại cho Agent biết ngôn ngữ đó | Khách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Anh phân phối cuộc chat cho Agent Tiếng AnhKhách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Pháp phân phối cuộc chat cho Agent Tiếng PhápKhách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Việt phân phối cuộc chat cho Agent Tiếng Việt |
| **User** |  |  |
| Tên | Chuyển cuộc thoại của khách hàng có tên cụ thể cho 1 Agent nào đó | Phân phối cuộc hội thoại của khách hàng Nguyễn Văn A cho Agent A |
| Địa chỉ email | Chuyển cuộc thoại của khách hàng có email cụ thể cho 1 Agent nào đó | Phân phối cuộc hội thoại của khách hàng có email là abc@gmail.com cho Agent A |
| Số điện thoại | Chuyển cuộc thoại của khách hàng có số điện thoại cụ thể cho 1 Agent nào đó. Số điện thoại là tập hợp các chữ số, viết liền không chứa ký tự đặc biệt | Phân phối cuộc hội thoại của khách hàng có số điện thoại 0123456789 cho Agent A |

### Bước 3: Chọn cách thức phân phối các cuộc tương tác cho Agent

Bây giờ, bạn chọn cách thức phân phối cuộc các cuộc thội thoại thỏa mãn các điều kiện đã đặt ở trên.![](http://docv4.subiz.com/wp-content/uploads/2018/01/rule-assign.png)

#### **1. Phân phối tới các Agent hoặc nhóm Agent**

Khi chọn cách phân phối tới các Agent hoặc nhóm Agent thì bất cứ Agent nào trong nhóm được phân phối đều có thể tham gia cùng lúc vào cuộc hội thoại.

Bạn cần chọn một trong những kiểu phân phối sau:

* _**Phân phối tới tất cả các available Agent:**_ phân phối cuộc hội thoại cho tất cả Agent đang được kích hoạt
* _**Phân phối tới các agents:**_ Phân phối cuộc hội thoại cho một hoặc một số Agent cụ thể. Click để chọn Agent trong list các Agent, sau khi chọn bạn không muốn chọn phân phối cho Agent đó nữa thì nhấn vào nút loại bỏ bên tay phải. Ví dụ sau, đã chọn 02 Agent

![](https://docv4.subiz.com/wp-content/uploads/2018/02/Phan-phoi-toi-cac-agent.png)

* _**Phân phối tới các nhóm:**_ Phân phối cuộc hội thoại cho nhóm Agent. Ví dụ dưới đây thì cuộc hội thoại đươc chọn phân phối cho nhóm bán hàng \(Sales\)

![](https://docv4.subiz.com/wp-content/uploads/2018/02/Phan-phoi-toi-cac-nhom.png)

* _**Phân phối tới agent có tương tác cuối cùng với user:**_ Phân phối cuộc hội thoại cho Agent có tương tác gần nhất với user \(khách hàng\)

#### **2. Phân phối cuộc chat đồng đều theo vòng** {#2-phan-phoi-cuoc-chat-dong-deu-theo-vong}

Các cuộc hội thoại sẽ được chia đều lần lượt theo vòng cho các Agent được chọn. Ví dụ, bạn chọn 3 agent trong danh sách agent, khi có 6 cuộc hội thoại, thì sẽ phân phối theo thứ tự 1,2,3 sau đó quay vòng 4,5,6![](https://docv4.subiz.com/wp-content/uploads/2018/02/phan-phoi-dong-deu-theo-vong.png)





