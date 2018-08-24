# Tạo Rule mới

Rule là tính năng tự động phân phối cuộc hội thoại của khách hàng cho các agent theo các điều kiện cài đặt. Bạn nên dựa trên tình hình thực tế, cách thức quản lý, điều hành của doanh nghiệp, cách thức phân chia công việc của tư vấn viên để sáng tạo ra các Rule mới, giúp cho việc phân phối và xử lý các cuộc hội thoại được hiệu quả.

Để tạo rule mới, bạn [đăng nhập tài khoản](https://app.subiz.com/login) và vào phần[ **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Rule &gt; Tạo Rule mới**](https://app.subiz.com/settings/add-rule)\*\*\*\*

![T&#x1EA1;o Rule m&#x1EDB;i](../../../.gitbook/assets/taorulemoi.png)

### Bước 1: Đặt tên và mô tả Rule

* **Tên:** Đặt tên để quản lý trong bảng danh sách các rule.
* **Mô tả**: Mô tả điều kiện và đối tượng của rule để dễ nhận biết.

![Nh&#x1EAD;p t&#x1EC7;p v&#xE0; m&#xF4; t&#x1EA3; v&#x1EC1; Rule](../../../.gitbook/assets/ten-va-mo-ta-rule.png)

### Bước 2: Đặt các điều kiện cho Rule

Điều kiện trong Rule là các tiêu chuẩn để một Rule được thực thi, giúp thiết lập các kịch bản phân phối cuộc hội thoại tới Agent một cách thông minh và hoạt động đúng lúc. 

{% hint style="info" %}
**Lưu ý:** Một Rule **chỉ áp dụng cho một quy tắc phân phối hội thoại**. Tuy nhiên, bạn có thể kết hợp nhiều điều kiện để phân phối tới một hay nhóm agent tương ứng với điều kiện đó. 
{% endhint %}

  
Cách thiết lập các điều kiện trong Rule: 

* Click Thêm điều kiện để kết hợp nhiều điều kiện trong một rule.
* Chọn Và/ Hoặc để xác định mối quan hệ giữa các điều kiện.

  **Ví dụ:** Khách hỏi nội dung có ký tự “giá” hội thoại sẽ chuyển đến agent Linh Chi.

![Kh&#xE1;ch h&#x1ECF;i n&#x1ED9;i dung c&#xF3; k&#xFD; t&#x1EF1; &#x201C;gi&#xE1;&#x201D; h&#x1ED9;i tho&#x1EA1;i s&#x1EBD; chuy&#x1EC3;n &#x111;&#x1EBF;n agent Linh Chi.](../../../.gitbook/assets/khach-hoi-bao-gia.png)

**Bạn có thể chọn một hay nhiều điều kiện trong danh sách các điều kiện trong Rule dưới đây:​**

| **CÁC ĐIỀU KIỆN** | **CÁCH SỬ DỤNG** | **VÍ DỤ** |
| :--- | :--- | :--- |
| Any condition | Khi lựa chọn điều kiện này, các cuộc hội thoại sẽ luôn được phân phối cho các agent được thiết lập trong rule. |  |
| **Date Time** |  |  |
| Giờ trong ngày | Dùng khi bạn muốn phân chia cuộc thoại cho các Agent theo các khung giờ trong ngày. Giờ trong ngày từ 0 - 23. | Ca sáng cho Agent A - Ca chiều cho Agent B - Ca tối cho Agent C. |
| Ngày trong tuần | Dùng điều kiện này để phân chia cuộc hội thoại theo ngày. Lưu ý: Ngày trong tuần được ghi nhận theo số thứ tự từ 2-8. Thứ Hai = 2, Thứ Ba = 3… , Chủ nhật = 8. | Ngày chẵn cho Agent A - Ngày lẻ cho Agent B, 3 ngày đầu tuần cho Agent C - 3 ngày cuối tuần cho Agent D. |
| **Hội thoại** |  |  |
| URL của trang | Mỗi trang URL thường tập trung giới thiệu về một Sản phẩm và Dịch vụ cụ thể, bạn có thể nhận diện khách hàng đang xem các trang cụ thể này và phân phối cuộc hội thoại cho từng Agent chuyên trách | Khách vào trang sản phẩm 1, phân phối cho sale 1. Khách vào trang sản phẩm 2, phân phối cho sale 2. Khách vào trang Bảo hành, phân phối cuộc hội thoại cho nhân viên chăm sóc khách hàng. Khách vào trang Báo giá, phân phối cuộc hội thoại cho nhân viên kinh doanh. |
| Tiêu đề trang | Tiêu đề trang gần giống URL trang, dùng để phân phối cuộc hội thoại cho các trang cụ thể cho từng Agent chuyên trách | Tiêu đề trang chứa các từ khóa sau: Các trang có tiêu đề chứa từ khóa “Máy Ảnh” phân phối cuộc hội thoại cho Agent A, Các trang có tiêu đề chứa từ khóa “laptop” phân phối cuộc hội thoại cho Agent A |
| Nội dung tin nhắn | Khi khách hàng gửi tin nhắn đầu tiên có liên quan đến một nội dung nhất định, bạn có thể phân phối cuộc hội thoại này cho người chuyên trách về nội dung đó | Cho xin “giá” sản phẩm A. Khi tin nhắn đầu tiên của khách hàng có chứa từ “giá”, cuộc hội thoại này sẽ được phân phối cho Agent kinh doanh |
| Ngôn ngữ trên trình duyệt | Ngôn ngữ trên trình duyệt tuân theo chuẩn [ISO Language Code](http://www.lingoes.net/en/translator/langcode.htm), ví dụ: vi- VN, en- US. Khách hàng sử dụng ngôn ngữ trình duyệt nào thì hãy phân phối cuộc hội thoại cho Agent biết ngôn ngữ đó | Khách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Anh phân phối cuộc chat cho Agent Tiếng Anh. Khách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Pháp phân phối cuộc chat cho Agent Tiếng Pháp. Khách hàng sử dụng ngôn ngữ trên trình duyệt là Tiếng Việt phân phối cuộc chat cho Agent Tiếng Việt |
| **User** |  |  |
| Tên | Chuyển cuộc thoại của khách hàng có tên cụ thể cho 1 Agent nào đó | Phân phối cuộc hội thoại của khách hàng Nguyễn Văn A cho Agent A |
| Địa chỉ email | Chuyển cuộc thoại của khách hàng có email cụ thể cho 1 Agent nào đó | Phân phối cuộc hội thoại của khách hàng có email là abc@gmail.com cho Agent A |
| Số điện thoại | Chuyển cuộc thoại của khách hàng có số điện thoại cụ thể cho 1 Agent nào đó. Số điện thoại là tập hợp các chữ số, viết liền không chứa ký tự đặc biệt | Phân phối cuộc hội thoại của khách hàng có số điện thoại 0123456789 cho Agent A |

### Bước 3: Chọn cách thức phân phối các cuộc tương tác cho Agent

Bây giờ, bạn chọn cách thức phân phối cuộc các cuộc hội thoại thỏa mãn các điều kiện đã đặt ở trên.

![Kh&#xE1;ch h&#x1ECF;i n&#x1ED9;i dung c&#xF3; k&#xFD; t&#x1EF1; &#x201C;gi&#xE1;&#x201D; h&#x1ED9;i tho&#x1EA1;i s&#x1EBD; chuy&#x1EC3;n &#x111;&#x1EBF;n agent Linh Chi.](../../../.gitbook/assets/khach-hoi-bao-gia-chuyen-cho-lc.png)

{% hint style="info" %}
* Rule là **điều kiện bắt buộc** để agent nhận được cuộc chat. Khi bạn xóa Rule mặc định nhưng không tạo Rule mới, tất cả các agent sẽ không nhận tương tác của khách hàng. Lúc này, tất cả hội thoại sẽ nằm trong mục **hội thoại chưa phân phối** trong phần **Hoạt động**.
* Bạn có thể tạo nhiều Rule, quản lý các Rule và thay đổi Rule theo thời gian, cho phù hợp với số lượng Agent và cách quản lý của bạn.
{% endhint %}





