# Làm thế nào để chặn một User

Trong quá trình tương tác với khách hàng trên Subiz, bạn có thể gặp những users gây phiền toái cho cuộc trò chuyện như gửi tin nhắn spam, có những lời nói khiếm nhã hay có những hành vi làm ảnh hưởng đến doanh nghiệp...Vậy làm cách nào để ngăn những user này gửi email/ tin nhắn spam đến doanh nghiệp? Bài viết sau sẽ chia sẻ cho bạn những hướng dẫn cụ thể.

### Chặn một User

Bạn có thể chặn một User theo 2 cách sau:

**1.Chặn trực tiếp User trong tab Activities \(Hoạt động\)**

Trong cuộc hội thoại, bạn có thể chặn user bằng cách click vào biểu tượng ba chấm ở góc phải màn hình và bật nút Block

![Ch&#x1EB7;n user tr&#x1EF1;c ti&#x1EBF;p](../../.gitbook/assets/chan-chat-truc-tiep.png)

**2. Chặn User thông qua Blacklist \(Danh sách đen\)**

Blacklist là danh sách những user mà bạn đã chặn. Để thêm vào danh sách này, bạn vào mục **Cài đặt/ Tài khoản/ Danh sách đen/ Chặn**. Tại đây bạn chỉ cần copy địa chỉ **IP, Email** hoặc **ID** của User muốn chặn.

{% tabs %}
{% tab title="Chặn bằng IP" %}
Mỗi user kết nối internet đều có một địa chỉ IP. Bạn có thể nhập địa chỉ IP vào BlackList Ips để chặn User này.

![Ch&#x1EB7;n theo &#x111;&#x1ECB;a ch&#x1EC9; IP](../../.gitbook/assets/chan-theo-dia-chi-ip%20%281%29.png)

Tuy nhiên, trong trường hợp có nhiều users sử dụng chung 1 IP, cách chặn này sẽ khiến bạn chặn luôn cả những users còn lại.  Ví dụ Subiz Team đang dùng 1 IP là 112.134.233.134, nếu chặn IP này tất cả máy tính tại Văn phòng Subiz sẽ không thấy Widget hiển thị trên cửa sổ website Subiz.com

{% hint style="info" %}
**Lưu ý:** Việc chặn bằng địa chỉ IP được thực hiện khi bạn muốn chặn user qua kênh Subiz Chat. User này sẽ không thấy được cửa sổ Widget trên website.
{% endhint %}
{% endtab %}

{% tab title="Chặn bằng Email" %}
Sau khi nhập email của user bạn muốn chặn, tất cả mail được gửi từ địa chỉ này đều bị chặn.

![Ch&#x1EB7;n theo &#x111;&#x1ECB;a ch&#x1EC9; email](../../.gitbook/assets/chan-theo-email.png)

{% hint style="info" %}
**Lưu ý:** Việc chặn địa chỉ mail được sử dụng khi bạn muốn chặn tương tác trên kênh email.
{% endhint %}
{% endtab %}

{% tab title="Chặn bằng User ID" %}
Mỗi User kết nối được tới Subiz đều được cấp một mã số và gọi là User ID.  Những gì bạn cần làm là copy ID của User muốn chặn trong mục activity và dán vào ô chặn:

![Ch&#x1EB7;n theo User ID](../../.gitbook/assets/chan-theo-id%20%281%29.png)

Đây là cách chặn chính xác và tổng quan nhất trên tất cả các kênh mà User này kết nối như Email,  Subiz Chat, Messenger.

**Cách lấy User ID**: Click vào 1 User trong tab Activities và lấy URL, copy đoạn đánh dấu đỏ như sau:

![L&#x1EA5;y User ID](../../.gitbook/assets/cach-lay-user-id.png)
{% endtab %}
{% endtabs %}

### Xem danh sách chặn

Để theo dõi được danh sách các user bị chặn cũng như lịch sử chặn,  bạn có thể theo dõi trong mục **Blacklist**

{% tabs %}
{% tab title="Spam List" %}
Đây là  danh sách những địa chỉ IP, Email hoặc ID đã bị chặn.

![Spam List](../../.gitbook/assets/spam-list.png)
{% endtab %}

{% tab title="Block User" %}
Bao gồm danh sách các Users đã bị Chặn, Agent thao tác chặn và thời gian chặn 

![Block User](../../.gitbook/assets/block-user.png)
{% endtab %}
{% endtabs %}

### Bỏ chặn một User

Để bỏ chặn một User, bạn có thể thao tác theo 2 cách sau:

* **Bỏ chặn trực tiếp trên trang Activities:**  Từ Tab activities -&gt; Tìm User và tắt Chặn User.
* **Bỏ chặn trong Blacklist:** Trong BlackList , click vào biểu tượng remove đối với User muốn bỏ chặn

![B&#x1ECF; ch&#x1EB7;n User](../../.gitbook/assets/bo-chan.png)

### Điều gì xảy ra khi bạn chặn một User

* **Với Channel Subiz Chat:** User sẽ không nhìn thấy cửa sổ chat và không thể tạo cuộc hội thoại hay gửi tin nhắn.
* **Với Channel Email:** User gửi email và bị chặn tại Subiz Core. Mail đó sẽ không được hiển thị cho Agent.
* **Với Channel Messenger:** Tin nhắn được chặn ở Subiz Core và không hiển thị cho Agent. Lưu  ý: tin nhắn vẫn tồn tại và hiển thị nếu khách dùng Quản trị fanpage.
* Các agent bị chặn có Avatar gạch chéo  

![Avatetr User b&#x1ECB; block](../../.gitbook/assets/avatar-spam.png)



