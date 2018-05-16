# Tùy chỉnh cửa sổ chat Subiz trên website

Cửa sổ tương tác Subiz trên website của doanh nghiệp là nơi khách truy cập trò chuyện với tư vấn viên của doanh nghiệp. Không đơn giản là nơi bạn tương tác hỗ trợ khách hàng, mà còn là nơi bạn khẳng định thương hiệu, chất lượng dịch vụ và tiếng nói của doanh nghiệp.

Để tùy chỉnh cửa sổ chat, bạn đăng nhập tài khoản Subiz &gt; Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Cửa sổ hội thoại

Tại trang **Cửa sổ hội thoại**, bạn có thể thực hiện các cài đặt để tùy chỉnh cửa sổ phù hợp với nhu cầu:

### Chọn l**oại cửa sổ**

Subiz đã tạo sẵn 2 dạng kích thước thu gọn hoặc mở rộng cho cửa sổ chat trên website của bạn. Ngoài ra bạn có thể tùy chỉnh CSS để điều chỉnh chiều cao và chiều rộng phù hợp với yêu cầu của bạn

{% tabs %}
{% tab title="Chọn loại cửa sổ có sẵn" %}
Bạn có thể chọn một trong 2 dạng kích thước **thu gọn** hoặc **mở rộng** cho cửa sổ chat trên website của bạn. 

* **Thu gọn:** Kích thước tiêu chuẩn
* **Mở rộng:** Chiều dài cửa sổ toàn màn hình, giúp khách hàng dễ theo dõi cuộc chat với bạn

![Ch&#x1ECD;n ki&#x1EC3;u c&#x1EED;a s&#x1ED5; c&#xF3; s&#x1EB5;n Thu g&#x1ECD;n ho&#x1EB7;c M&#x1EDF; r&#x1ED9;ng](../../../.gitbook/assets/loai-cua-so.png)
{% endtab %}

{% tab title="Tùy chỉnh chiều cao" %}
```text
 height: 800px !important;
 max-height: 900px !important;
}
```

 Phần **800**px bạn có thể điều chỉnh con số cho phù hợp với website.

![T&#xF9;y ch&#x1EC9;nh chi&#x1EC1;u cao c&#x1EED;a s&#x1ED5; chat](../../../.gitbook/assets/css-chieu-cao%20%281%29.png)
{% endtab %}

{% tab title="Chiều rộng" %}

{% endtab %}
{% endtabs %}

### Chọn v**ị trí cửa sổ chat**

Bạn có thể chọn vị trí cửa sổ chat xuất hiện trên website tại **Góc trái** hoặc **Góc phải**

![](https://docv4.subiz.com/wp-content/uploads/2018/02/widgetposition-1.png)

{% hint style="info" %}
**Vị trị đặt cửa sổ Subiz cần phù hợp với thiết kế của website, sao cho dễ nhận biết, không đè lên các thiết kế hay ứng dụng khác của website.** Hiện tại, một tỷ lệ lớn các doanh nghiệp đặt cửa sổ Subiz tại góc bên phải.
{% endhint %}

### Chỉnh sửa **màu sắc**

{% hint style="info" %}
Lưu ý, **cần chọn màu sắc cửa sổ chat tương đồng với màu sắc của thương hiệu,** nhưng cũng cần chọn màu sắc để dễ nhận biết trên website của bạn
{% endhint %}

Bạn có thể tùy chỉnh màu sắc cho cửa sổ Subiz bằng cách chọn 1 trong các màu được gợi ý, hoặc tùy chỉnh màu riêng biệt của doanh nghiệp.

#### Chỉnh sửa theo màu sắc gợi ý từ Subiz

![](https://docv4.subiz.com/wp-content/uploads/2018/02/widgetcolour-1.png)

#### Tùy chỉnh CSS để có màu sắc riêng biệt của doanh nghiệp



### **4. Tùy chỉnh bubble**

Tại phần Bubble Button, bạn click chọn Thư viện Bubble Button và chọn mẫu Bubble theo ý muốn.

Lưu ý, **màu sắc của bubble sẽ tương ứng với màu sắc của cả cửa sổ Subiz mà bạn đã chọn.**![](https://docv4.subiz.com/wp-content/uploads/2018/02/bubble-button-1.png)![](http://docv4.subiz.com/wp-content/uploads/2018/02/bubble-library.png)

### **5. Tùy chỉnh ngôn ngữ**

Bạn chọn ngôn ngữ sử dụng cho cửa sổ Subiz tại mục **Ngôn ngữ**.

* Khi chọn chế độ **Tự động**, Subiz sẽ tự động nhận diện vị trí của khách truy cập và hiển thị ngôn ngữ phù hợp theo nội dung đã được thiết lập trước.
* Khi bạn chọn **1 ngôn ngữ cụ thể**, bạn cần **tùy chỉnh tiêu đề và lời giới thiệu hiển thị trên cửa sổ**. Ví dụ với ngôn ngữ Tiếng Việt:

![](https://docv4.subiz.com/wp-content/uploads/2018/02/language-1.png)

**. Hãy chỉnh sửa lời chào, lời giới thiệu theo đúng bản sắc văn hóa và điều bạn muốn phục vụ khách hàng.**

Các tùy chỉnh sẽ hiển thị trên cửa sổ như sau:

![](http://docv4.subiz.com/wp-content/uploads/2018/01/Title-and-introduction.png)

* **Nếu bạn muốn sử dụng một ngôn ngữ chưa được hỗ trợ**, hoặc muốn tùy chỉnh thêm các phần ngôn ngữ khác, bạn có thể tùy chỉnh ngôn ngữ bằng cách tải lên file ngôn ngữ dạng po \([hướng dẫn chi tiết tùy chỉnh ngôn ngữ qua file .Po](https://docv4.subiz.com/tuy-chinh-ngon-ngu-cua-so-subiz-qua-file-po/)\):
  * Chọn **Tùy chỉnh ngôn ngữ**
  * Tải về file mẫu
  * Chỉnh sửa file mẫu qua trang [https://localise.biz](https://localise.biz/)​
  * Tải lên file ngôn ngữ đã chỉnh sửa

![](https://docv4.subiz.com/wp-content/uploads/2018/02/customize-language.png)

### **6. Tùy chỉnh CSS**

CSS là viết tắt của “Cascading Style Sheet”, nếu có kiến thức về HTML, bạn có thể sáng tạo một cửa sổ riêng bằng cách nhập các đoạn CSS tại phần **Tùy chỉnh CSS**.![](https://docv4.subiz.com/wp-content/uploads/2018/02/csscustomize.png)

Chọn **Lưu thay đổi** để lưu tùy chỉnh. Chọn **Đưa về ban đầu** để trở về cửa sổ mặc định ban đầu.

### **7. Cài đặt Whitelist domain**

**Whitelist domain** là danh sách các tên miền mà bạn cho phép hiển thị cửa sổ Subiz trên trang đó. Các trang ngoài danh sách whitelist sẽ không thể hiển thị cửa sổ Subiz sau khi đặt mã nhúng.

Ví dụ: Bạn nhập _domain1.com_ và _domain2.com_ tại whitelist thì chỉ có thể đặt mã nhúng cài đặt cửa sổ Subiz trên 2 trang này. Nếu bạn đặt mã nhúng tại trang _domain3.com_ thì cửa sổ sẽ không hiển thị tại trang đó.

Khi danh sách whitelist domain trống, mặc định cửa sổ sẽ hiển thị trên tất cả các trang được đặt mã nhúng.

Cài đặt whitelist domain giúp bạn kiểm soát các trang hiển thị cửa sổ Subiz, tránh trường hợp mã nhúng bị đặt trên các trang bạn không mong muốn.

Thực hiện cài đặt tại phần **Quản lý Whitelist Domain**.![](http://docv4.subiz.com/wp-content/uploads/2018/02/whitelist-domain-manage.png)

Tại trang Whitelist Domain, click chọn Thêm Whitelist Domain mới.![](http://docv4.subiz.com/wp-content/uploads/2018/02/whitelist-domain-page.png)

Nhập tên miền và chọn **Thêm** để thêm domain vào danh sách whitelist.![](http://docv4.subiz.com/wp-content/uploads/2018/02/add-whitelist.png)

**Để xóa một domain khỏi whitelist,** bạn ấn vào biểu tượng xóa bên cạnh tên domain trong danh sách.![](http://docv4.subiz.com/wp-content/uploads/2018/02/delete-domain.png)

