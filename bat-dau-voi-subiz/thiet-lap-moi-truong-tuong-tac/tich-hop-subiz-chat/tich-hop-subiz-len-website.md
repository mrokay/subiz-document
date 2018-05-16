# Tích hợp Subiz lên Website

Subiz Live Chat là một kênh tương tác với khách hàng ghé thăm website của doanh nghiệp. Khi tích hợp cửa sổ tương tác Subiz trên Website, **sẽ giúp doanh nghiệp theo dõi, tiếp cận, tương tác và chuyển đổi khách hàng** ghé thăm website của bạn.

### Cách tích hợp Subiz lên website

Để tích hợp cửa sổ Subiz trên website, bạn thực hiện theo 03 bước sau:

#### Bước 1: Lấy mã nhúng của Subiz

Tích hợp Subiz vào website bằng việc copy đoạn mã nhúng Subiz \(không được thay đổi, copy toàn bộ mã\) và dán vào các trang mà bạn muốn đặt cửa sổ Subiz Chat.

Để lấy mã nhúng của Subiz bạn làm theo các bước sau:

1. [Đăng nhập tài khoản Subiz](http://app.subiz.com/)
2. Vào phần **Cài đặt &gt; Tài khoản &gt; Tích hợp**

Tại phần Mã nhúng Subiz, click nút Sao chép để thực hiện sao chép nhanh đoạn mã nhúng.![](http://docv4.subiz.com/wp-content/uploads/2018/02/copy-embed-code.png)

{% hint style="info" %}
**Lưu ý:** Mỗi Tài khoản Subiz có một mã nhúng khác nhau, vì thế khi thay đổi Tài khoản Subiz, bạn đồng thời phải tích hợp lại mã nhúng.
{% endhint %}



#### Bước 2: Đặt mã nhúng Subiz vào website

Subiz tương thích với hầu hết các website xây dựng trên các nền tảng khác nhau. Việc đặt mã nhúng vào website khá đơn giản, chỉ cần Copy mã nhúng Subiz và dán vào mọi trang bạn muốn có cửa sổ Subiz Chat. Code nhúng Subiz phải được đặt ngay trước thẻ đóng &lt;/body&gt;.![](http://docv4.subiz.com/wp-content/uploads/2018/01/embedcode.gif)

#### Bước 3: Kiểm tra cửa sổ Subiz trên website

Sau khi tích hợp mã nhúng Subiz, quay lại trình duyệt và truy cập vào website. Bạn sẽ thấy cửa sổ Subiz Chat ở góc dưới cùng bên phải của website.

Nếu bạn vẫn không thấy cửa sổ Subiz Chat, bạn có thể kiểm tra trực tiếp trong trang Quản lý theo các bước sau:

**1.** [Đăng nhập tài khoản](http://app.subiz.com/)​

**2.** Chọn **Cài đặt** &gt; **Tài khoản** &gt; **Tích hợp**

**3.** Nhập đường dẫn **website** bạn và click nút **Kiểm tra**.

Nếu hệ thống báo không tìm thấy cửa sổ Chat, bạn kiểm tra lại mã nhúng Subiz trên website hoặc liên hệ với Subiz để được hỗ trợ.

![](http://docv4.subiz.com/wp-content/uploads/2018/02/check-embed-code.png)

### Tích hợp Subiz trên các nền tảng

Nếu website của bạn được xây dựng trên các nền tảng khác, vui lòng xem hướng dẫn tích hợp cho từng nền tảng dưới đây:

{% tabs %}
{% tab title="WordPress" %}
1. Mở **WordPress Admin Panel** &gt; **Appearance** &gt; **Editor**
2. Tìm file **footer.php** bên cột bên phải và mở file này
3. Nhán mã nhúng Subiz vào ngay trước thẻ &lt;/body&gt; trong file **footer.php**
{% endtab %}

{% tab title="Shopify" %}
1. Đăng nhập tài khoản Shopify, tìm đến **Online Store** &gt; **Themes**.
2. Sau đó nhấn vào nút **Action** và chọn **Edit code**
3. Tìm file **theme.liquid** tại menu bên trái và nhúng mã Subiz trước thẻ &lt;/body&gt;. Nhấn **Save**.
{% endtab %}

{% tab title="Wix" %}
1. Đăng nhập màn hình Dashboard của Win, chọn Manage & Edit Site
2. Nhấn vào **Edit Site** &gt; **Add button** &gt; **More** &gt; **HTML iframe**. Kéo phần **iframe** vừa được chọn xuống dưới **footer** \(có thể điều chỉnh vị trí của iframe\)
3. Nhần vào **Add code**  chèn code của Subiz. Nhấn **Save**
{% endtab %}

{% tab title="Magento" %}
To embed Subiz code on your Magento, go to your Magento them files and check if the file indicated exists or not, so please refer two options below:

**Option 1**

1. Look for your Magento tempale in app/design/frontend/{template}/page/html/head.phtml. If this file doesn’t exist, then you will need to check if the app/design/frontend/{template}/default/page/html/head.phtml file exists.
2. Paste Subiz embed code right before the &lt;/head&gt; section of the file.

**Option 2**

You only need to do this option if the template files described in the option 1 don’t exist.  This situation due to some custom Magento templates might not have a head.phtml file and the template would be using the base template file.

1. Copy the app/design/frontend/default/page/html/head.phtml file from your default base template to your custom template folder at app/design/frontend/{template}/page/html/head.phtml.
2. Open the file and paste Subiz chat code before the &lt;/head&gt;
{% endtab %}

{% tab title="Joomla" %}
1. Open Joomla Admin &gt; Template Manager &gt; Choose your **Template and** Filter by **site** 
2. Choose your templte &gt; Open **Index.php** file 
3. Paste Subiz embed code right before &lt;/body&gt; tag &gt; Finish 
{% endtab %}
{% endtabs %}

Nếu bạn đang dùng nền tảng **không** có trong danh sách này, hãy liên lạc ngay cho Subiz để được trợ giúp.

