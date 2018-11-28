# Tạo Automation mới

Dựa trên các đối tượng khách hàng bạn có, cách thức bạn muốn chăm sóc và theo đuổi khách hàng, bạn  có thể thiết lập nhiều hành động Automation với các điều kiện nhất định để thực hiện các hành động tự động hóa tương tác với khách hàng vào những thời điểm khác nhau theo ý muốn của bạn.

Để tạo mới một Automation, bạn vào phần tạo [**Tạo Automation mới**](https://app.subiz.com/settings/automation-list) và thực hiện các bước sau:

**Nhập Tên và Mô tả cho Automation**

Tên và Mô tả giúp bạn nhận diện và phân biệt các Automation đã cài đặt

![Nh&#x1EAD;p T&#xEA;n v&#xE0; M&#xF4; t&#x1EA3; v&#x1EC1; Automation](../../.gitbook/assets/tao-automation.png)

### Lựa chọn điều kiện cho Automation

Lựa chọn điều kiện để xác định Automation sẽ hướng đến đối tượng nào. Bạn có thể lựa chọn nhiều điều kiện đồng thời hoặc thỏa mãn một trong các điều kiện.

Để nhập điều kiện, trước hết bạn lựa chọn loại điều kiện:

![V&#xED; d&#x1EE5;: L&#x1EF1;a ch&#x1ECD;n &#x111;i&#x1EC1;u ki&#x1EC7;n l&#xE0; URL c&#x1EE7;a trang](../../.gitbook/assets/lua-chon-dieu-kien-automation.png)

Sau đó bạn nhập phép so sánh và giá trị cho điều kiện đó để tạo một điều kiện hoàn chỉnh.

![Ch&#x1ECD;n ph&#xE9;p so s&#xE1;nh v&#xE0; gi&#xE1; tr&#x1ECB; cho &#x111;i&#x1EC1;u ki&#x1EC7;n Automation](../../.gitbook/assets/phep-so-sanh-automation.png)

Click **Thêm điều kiện** khi bạn muốn thêm điều kiện khác. Chọn “Khách hàng đáp ứng tất cả các điều kiện” hoặc “Khách hàng đáp ứng một trong các điều kiện” để tạo lập mối quan hệ giữa các điều kiện: Và/ Hoặc.

![Th&#xEA;m &#x111;i&#x1EC1;u ki&#x1EC7;n cho Automation](../../.gitbook/assets/them-dieu-kien-auto.png)

**Bạn nên tham khảo danh sách các điều kiện**, với những hướng dẫn về cách sử dụng và có những ví dụ cụ thể sau đây:

| **CÁC ĐIỀU KIỆN** | **CÁCH SỬ DỤNG** | **VÍ DỤ** |
| :--- | :--- | :--- |
| **User** |  |  |
| Tên | Thực hiện automation với các user có tên cụ thể | Gửi lời chào đặc biệt hoặc email thông báo chương trình khuyến mãi tới các user có tên là SơnĐiều kiện: Tên – bằng – Sơn |
| Địa chỉ Email | Thực hiện automation với các user có địa chỉ email cụ thể | Gửi lời chào đặc biệt hoặc email tới tất cả các user có địa chỉ email chứa subiz.comĐiều kiện: Địa chỉ email – chứa – [Subiz.com](https://subiz.com/vi/) |
| Số điện thoại | Thực hiện automation với các user có số điện thoại cụ thể | Gửi lời chào hoặc email tới các user đã có thông tin số điện thoạiGửi tin nhắn SMS tự động tới user đã có thông tin số điện thoại về các chương trình khuyến mãi \(chỉ áp dụng được khi tích hợp kênh SMS vào [Subiz](https://subiz.com/vi/)\) |
| Quốc gia | Thực hiện automation dựa trên quốc gia của userTên quốc gia là tên tiếng Anh của quốc gia, chỉ viết hoa các chữ cái đầu tiên của từ. Ví dụ: Vietnam, United States[Tham khảo danh sách các quốc gia](https://countrycode.org/) | Gửi lời chào đến khách hàng tới từ Việt Nam bằng automation chứa lời chào tiếng Việt.Điều kiện: Quốc gia – bằng – Vietnam |
| Mã quốc gia | Thực hiện automation dựa trên mã quốc giaMã quốc gia căn cứ theo ISO Code \(2 ký tự\), viết hoa cả 2 chữ cái Ví dụ: Việt Nam = VN, Mỹ = US, Trung Quốc = CN, Hàn Quốc = KR, Nhật Bản = JP[Tham khảo danh sách mã quốc gia](https://en.wikipedia.org/wiki/ISO_3166-2) | Gửi tin nhắn đến khách hàng tới từ Việt Nam bằng automation chứa lời chào tiếng Việt.Điều kiện: Mã quốc gia – bằng – VN |
| Thành phố | Thực hiện automation với các user đến từ một thành phố cụ thểLà tên tiếng Anh của các thành phố, chỉ viết hoa các chữ cái đầu tiên của từ. Ví dụ: Hanoi, Ho Chi Minh City, New York, Hong KongDanh sách [mã thành phố của các quốc gia](https://countrycode.org/) \(Click vào từng quốc gia để tra cứu tên thành phố\) | Gửi lời chào đến khách hàng tới từ Hà Nội bằng automationĐiều kiện: Thành phố – bằng – Hanoi |
| **Sự kiện** |  |  |
| Tiêu đề trang | Các website thường đặt tiêu đề trang liên quan đến một chủ đề nhất định, với mỗi chủ đề, bạn có thể đặt một automation để hỗ trợ và hướng dẫn khách hàng đúng thời điểm | Gửi lời chào tới các khách hàng vào xem các trang có tiêu đề chứa từ “máy ảnh”. Điều kiện: Tiêu đề trang – chứa – máy ảnh. Gửi lời chào tới các khách hàng vào xem trang có tiêu đề chứa từ “giá” |
| URL trang | Thực hiện automation khi khách hàng truy cập vào một trang cụ thể | Gửi tin nhắn tới khách hàng đang xem trang bảng giá: Điều kiện: URL của trang – bằng – https://subiz.com/vi/pricing.html |

### C**họn kênh thực hiện Automation**

Tiếp theo bạn chọn kênh áp dụng Automation. Mỗi kênh sẽ có các hành động tương ứng phù hợp.

![Ch&#x1ECD;n k&#xEA;nh th&#x1EF1;c hi&#x1EC7;n Automation](../../.gitbook/assets/chon-kenh-automation.png)

### **Thiết lập hành động cho Automation**

{% hint style="info" %}
Mỗi Automation sẽ thực hiện 1 hành động duy nhất.
{% endhint %}

{% tabs %}
{% tab title="Hành động trên Subiz Chat" %}
#### Với kênh [Subiz Chat](https://subiz.com/vi/live-chat.html), bạn có thể thực hiện 1 trong 2 hành động:

* **Gửi tin nhắn cho User**: bạn có thể gửi tin nhắn ngay khi khách hàng vào website như một lời chào tự động, hoặc gửi tin nhắn với thông điệp riêng cho một đối tượng khách hàng cụ thể.

![Ch&#x1ECD;n h&#xE0;nh &#x111;&#x1ED9;ng g&#x1EED;i tin nh&#x1EAF;n t&#x1EDB;i kh&#xE1;ch h&#xE0;ng](../../.gitbook/assets/chon-kenh-hanh-dong-automation.png)

Khách hàng sẽ nhìn thấy tin nhắn tự động giống như một tin nhắn thông thường được gửi từ Agent.

![G&#x1EED;i tin nh&#x1EAF;n cho kh&#xE1;ch h&#xE0;ng](../../.gitbook/assets/chon-kenh-automation1.png)

* **Gửi form hỏi thông tin tới User**: thường dùng trong trường hợp bạn không online hoặc không thể trả lời ngay lập tức. Khách hàng sẽ nhập thông tin để bạn có thể liên hệ lại sau.

![Automation h&#x1ECF;i email kh&#xE1;ch h&#xE0;ng](../../.gitbook/assets/automation-email%20%281%29.png)
{% endtab %}

{% tab title="Hành động trên Subiz Email" %}
#### Với kênh [Email](https://subiz.com/vi/email.html), bạn có thể thực hiện hành động **Gửi** [**email**](https://subiz.com/vi/email.html) **tới user**. 

{% hint style="info" %}
Hành động này chỉ có thể thực hiện với các user đã có địa chỉ [email.](https://subiz.com/vi/email.html)
{% endhint %}

Chọn hành động **Gửi email tới user** trên kênh [Email](https://subiz.com/vi/email.html)

![Ch&#x1ECD;n h&#xE0;nh &#x111;&#x1ED9;ng g&#x1EED;i email &#x111;&#x1EBF;n kh&#xE1;ch h&#xE0;ng](../../.gitbook/assets/automation-hd-email.png)

Chọn Agent gửi[ email](https://subiz.com/vi/email.html), tiêu đề [email ](https://subiz.com/vi/email.html)và nhập nội dung [email](https://subiz.com/vi/email.html):

![Nh&#x1EAD;p ti&#xEA;u &#x111;&#x1EC1;, n&#x1ED9;i d&#x1EE5;ng cho email](../../.gitbook/assets/gui-email-den-khach-hang.png)

Xem trước nội dung [email](https://subiz.com/vi/email.html):

![Xem tr&#x1B0;&#x1EDB;c n&#x1ED9;i dung Email](../../.gitbook/assets/preview-email.png)
{% endtab %}
{% endtabs %}

{% hint style="info" %}
* Bạn có thể cài đặt Agent đại diện để gửi tin nhắn và email đi.

                                         ![](../../.gitbook/assets/image%20%2817%29.png)

* Bạn có thể tùy chỉnh tin nhắn cho sinh động hơn \(đậm/ nghiêng/ chèn link/ gửi ảnh…\) thông qua công cụ tùy chỉnh văn bản.
{% endhint %}

### **Lưu Automation**

Sau khi cài đặt xong, bạn click nút **Tạo** để lưu lại Automation.

