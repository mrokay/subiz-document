---
description: Bài viết hướng dẫn bạn sử dụng điều kiện đối tượng khách hàng chạy pop-up.
---

# Hướng dẫn sử dụng điều kiện đối tượng khách hàng chạy pop-up

Subiz cung cấp cho bạn các loại đối tượng khách hàng mà pop up hiển thị, dựa trên các điều kiện:

* **Phiên truy cập** + Khách hàng quay lại/khách mới. + Nguồn truy cập như Direct, Organic, Social, Advertising hoặc nguồn truy cập từ URL trang bất kỳ. + Vị trí địa lý + Thiết bị như điện thoại, máy tính, table
* **Xem trang trên website** + URL khách đang xem  + Loại trừ khách đã xem URL 
* **Thời gian trên trang** + Thời gian trên trang: Thời gian tối thiểu khách hàng ở trên trang web. + Tần suất hiện thị: Số lần hiển thị pop-up đối với 1 khách hàng. 

### 1. Khách hàng quay lại/khách mới

Khách hàng vào website lần đầu tiên và khách hàng vào web lần 2 trở đi là 2 nhóm khách hàng có nhận thức và hành vi khác nhau. Bạn có thể dùng điều kiện này để tạo chiến dịch khác nhau phù hợp cho các nhóm này. 

#### Một số điểm lưu ý với điều kiện này:

* Điều kiện này có tính cá nhân hóa cao tương ứng với hành trình khách hàng trên phễu chuyển đổi.  Ví dụ: Pop up A chỉ dành riêng cho khách hàng mới vào web, khách hàng truy cập lần 2 không thể nhìn thấy A mà sẽ nhìn thấy Pop up B. 
* Điều kiện “Khách hàng quay lại/khách mới” bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào. Ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý.  Ví dụ: Cài điều kiện Ý định thoát web với đối tượng khách hàng mới để Khách mới định tắt web sẽ nhận được Pop up chào mừng và đề nghị giảm giá.  
* Điều kiện này hoạt động tốt trên tất cả các thiết bị truy cập như máy tính bàn, điện thoại hay máy tính bảng

#### Những câu hỏi thường gặp

* _**Điều kiện này hoạt động như thế nào trên các thiết bị?**_ Subiz sử dụng các cookie cụ thể được đặt trong trình duyệt để xác định xem khách truy cập là người mới hay quay lại trang web của bạn. Cụ thể, là cookie dành cho khách đã truy cập và cookie dành cho phiên khách truy cập \(hết hạn sau X phút không hoạt động\). Nếu không có cookie tồn tại, chúng tôi biết khách truy cập là mới. Nếu chỉ tồn tại cookie cho khách đã truy cập , chúng tôi biết khách truy cập đang quay lại. 
* _**Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?**_ Trên trình duyệt ẩn danh, điều kiện này vẫn hoạt động nếu khách hàng chưa tắt tab hoặc tắt tab đó, mở tab mới nhưng vẫn dùng cửa sổ \(window cũ\). Nếu khách hàng tắt hẳn cửa sổ cũ \(window cũ\) và mở một cửa sổ mới \(window mới\) thì Page Viewed  không tính được. Vì vậy, điều kiện này có khả năng hoạt động không chính xác trên trình duyệt ẩn danh. 
* _**Điều kiện này có bị chặn bởi Google Pop up Policy không?**_ Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 2. **Theo nguồn truy cập**

Mỗi nguồn truy cập của khách hàng có thể là một chỉ báo cho một chiến dịch marketing riêng biệt. Điều kiện này cho phép bạn tạo chiến dịch riêng rẽ  hướng tới những đối tượng theo nguồn truy cập khác nhau.

#### Một số lưu ý với điều kiện này:

* Điều kiện này giúp bạn phân biệt được các nguồn như Direct, Organic, Paid Search hoặc Referral để tạo thông điệp phù hợp với từng nhóm riêng rẽ. Ví dụ như bạn có thể tạo pop up về khuyến mại giảm 5% cho nguồn tới từ Referal A và tạo pop up giảm 7% đối với nguồn từ Referal B, giảm 10% với nguồn từ Ads và voucher tặng quà với nguồn Direct.. 
* Điều kiện “Theo nguồn truy cập” bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào. Ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý. Ví dụ bạn có thể chọn Pop up hiện ra khi thỏa mãn điều kiện thời điểm: Ý định thoát web và điều kiện đối tượng: Khách ở Hà Nội, đến từ nguồn Quảng cáo \(Paid Search\). 

#### Những câu hỏi thường gặp:

* _**Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?**_ Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* _**Điều kiện này có bị chặn bởi Google Pop up Policy không?**_ Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 3. Theo vị trí địa lý

Điều kiện này cho phép bạn tạo chiến dịch nhắm tới các nhóm đối tượng khách hàng sinh sống ở các thành phố cụ thể. 

#### Một số điểm lưu ý với điều kiện này:

* Điều kiện này có thể sử dụng để chạy ưu đãi riêng biệt cho từng thành phố, quốc gia, phù hợp theo điều kiện thời tiết, xu hướng của khu vực đó. Ví dụ tạo pop up A giảm giá áo len cho khách hàng Miền Bắc và pop up B giảm giá áo mưa cho khách hàng miền Nam. 
* Điều kiện ”Theo vị trí địa lý” bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào. Ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý. Ví dụ bạn có thể cài cùng Ý định thoát web để cá nhân hóa mạnh mẽ hơn nữa tới khách hàng.

#### Những câu hỏi thường gặp:

* _**Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?**_ Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* _**Điều kiện này có bị chặn bởi Google Pop up Policy không?**_ Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 4. **Theo thiết bị**

Mỗi khách hành truy cập website từ thiết bị khác nhau sẽ có những hành vi khác nhau. Điều kiện này cho phép bạn tạo chiến dịch riêng rẽ tới khách truy cập từ máy tính bàn, điện thoại hay máy tính bảng.

#### Một số lưu ý với điều kiện này: 

* Theo thiết bị là giúp bạn tập trung vào khác biệt trong hành vi khách hàng khi họ sử dụng máy tính và điện thoại. Ví dụ : Tạo Pop up A dành riêng cho khách hàng từ máy tính với ưu đãi miễn phí ship trong giờ hành chính, Tạo Pop up B dành riêng cho khách hàng truy cập từ điện thoại với ưu đãi giảm ngay 10% nếu gọi điện đặt hàng ngay.  
* Điều kiện “Theo thiết bị” hỗ trợ rất tốt cho các điều kiện “Sau X giây trên trang” hoặc “Sau X giây không hoạt động” để bạn có thể tùy biến X phù hợp với từng nhóm đối tượng. Vẫn ví dụ trên: Pop up A hiển thị sau X1 = 7 giây khách hàng không hoạt động trên web và Pop up B hiển thị sau X2 = 5 giây khách hàng không hoạt động trên điện thoại. 
* Theo thiết bị bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào, ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý.

#### Những câu hỏi thường gặp:

* _**Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?**_ Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* _**Điều kiện này có bị chặn bởi Google Pop up Policy không?**_ Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 5. URL khách đang xem

Trang đang truy cập cho phép bạn hiển thị pop up dành riêng cho những khách hàng đang ở trên một số trang cụ thể.

#### Điểm lưu ý với điều kiện này

* Sử dụng điều kiện này nếu muốn tăng tỷ lệ chuyển đổi mạnh mẽ tại một trang cụ thể nào đó. Bạn có thể tạo các chiến dịch khác nhau dành cho khách hàng đang xem các trang đích khác nhau: Ví dụ tạo pop up ưu đãi giảm giá mặt hàng A với khách hàng đang truy cập trang A, hoặc miễn phí ship với khách hàng đang ở trang thanh toán B.  
* Trang truy cập bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào, ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý.

#### Những câu hỏi thường gặp

* **Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?** Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* **Điều kiện này có bị chặn bởi Google Pop up Policy không?** Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 6. **Loại trừ  URL khách đã xem**

Loại trừ khách đã xem trang cho phép ẨN Pop up đối với khách hàng đã xem 1 trang nhất định. Thuật toán Subiz xác định lịch sử URL của khách hàng và chỉ hiển thị pop up với các khách phù hợp.

#### Điểm lưu ý với điều kiện này: 

* Đây là điều kiện giúp bạn tối ưu thông điệp tới khách hàng. Ví dụ: Trên trang báo giá bạn đưa ra chương trình giảm giá 30% cho gói dài hạn, trên trang sản phẩm bạn đưa ra chương trình ưu đãi 30% cho tất cả các gói ngắn hạn và dài hạn.  Vậy bạn có thể : Ẩn pop up đối với những khách đã xem tráng báo giá khi họ truy cập trang sản phẩm và ẨN pop up với những khách đã xem trang sản phẩm khi họ truy câp trang báo giá.  
* Trang truy cập bắt buộc phải được kết hợp với 1 điều kiện thời điểm để ra lệnh cho pop up hiển thị khi nào, ngoài ra nó thể kết hợp được với nhiều điều kiện khác thuộc nhóm đối tượng và hẹn giờ tùy ý.

#### Những câu hỏi thường gặp

* Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không? Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* Điều kiện này có bị chặn bởi Google Pop up Policy không? Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn

### 7. **Thời gian tối thiểu trên trang**

Điều kiện này cho phép gửi thông điệp tới các khách hàng đã ở trên trang X giây nhất định. 

#### Điểm lưu ý với điều kiện này

* Điều kiện này phù hợp để đưa ra pop up cho những khách hàng có mức độ quan tâm nhất định. ****
* Bạn cần nghiên cứu hành vi khách hàng tại Google Analytics để xác định khách thường lưu lại trên trang sau bao lâu và chọn X cho phù hợp. Nếu chọn X =0, pop up hiện ra ngay lập tức và có thể gây phiền tới khách hàng. 
* Thời gian tối thiểu trên trang cho ra kết quả khá giống với sau X giây trên trang, điểm khác biệt là bạn không thể sử dụng đơn lẻ mà phải kết hợp nó với 01 điều kiện thời điểm khác. Ngoài ra bạn có thể kết hợp thêm với các điều kiện đối tượng hoặc hẹn giờ tùy ý. Ví dụ: Pop up A hiển thị với điều kiện đối tượng: khách hàng có ít nhất 5 giây trên trang, với điều kiện thời điểm khách định thoát trang.

**Những câu hỏi thường gặp**

* _**Điều kiện này có hoạt động được trên trình duyệt ẩn danh hay không?**_ Có, điều kiện này hoạt động tốt kể cả trên trình duyệt ẩn danh hay không. 
* _**Điều kiện này có bị chặn bởi Google Pop up Policy không?**_ Không. Bạn có thể yên tâm bởi Subiz thường xuyên được Google cập nhật chính sách mới để đảm bảo hoạt động hiệu quả trên website của bạn.

