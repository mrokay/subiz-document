# Sáng tạo cửa sổ chat Subiz ấn tượng

### Sáng tạo cách giới thiệu trên cửa sổ chat

Vào những dịp đặc biệt, hoặc khi có các chương trình khuyến mại, bạn nên thay đổi và sáng tạo lời giới thiệu về doanh nghiệp ngay trên cửa sổ chat để tăng sự thu hút và tạo sự ấn tượng với khách truy cập website.

{% tabs %}
{% tab title="Gắn link trên lời giới thiệu" %}

{% endtab %}

{% tab title="Xuống dòng trên lời giới thiệu" %}
Đoạn mã giúp bạn gắn link trên lời giới thiệu

```text
<p> Normal text <a href="http://example.com"> <font color="yellow">Linked text</font></a></p>
```

Những thành phần bạn có thể thay đổi trong đoạn mã trên:

* **Normal text:** Là đoạn giới thiệu ban đầu bạn muốn trình bày
* [**http://example.com**](http://example.com)**:** Là đường link trang đích bạn muốn khách hàng xem sau khi bấm vào Linked text
* **Yellow:** Là màu bạn muốn chọn cho Linked text
* **Linked text:** Là đoạn chữ chứa đường link trang đích

**Ví dụ:** &lt;p&gt; Kỷ niệm sinh nhật lần thứ 5. Chúng tôi giảm giá 50% nhiều mặt hàng. Vui lòng xem chi tiết &lt;a href="http://example.com"&gt; &lt;font color="yellow"&gt;tại đây!&lt;/font&gt;&lt;/a&gt;&lt;/p&gt;

![S&#xE1;ng t&#x1EA1;o l&#x1EDD;i gi&#x1EDB;i thi&#x1EC7;u k&#xE8;m link](../../../.gitbook/assets/loi-gioi-thieu-1.png)
{% endtab %}
{% endtabs %}



### Tùy chỉnh CSS cho cửa sổ chat Subiz

Bên cạnh việc sử dụng những cài đặt cửa sổ chat trên website mà Subiz đã cung cấp. Bạn có thể dễ dàng tùy chỉnh những thành phần khác trên cửa sổ chat bằng cách sử dụng mã CSS.

CSS là viết tắt của cụm từ “Cascading Style Sheet”, nó là một ngôn ngữ quy định cách trình bày của các thẻ html trên trang web. Với việc sử dụng CSS bạn có thể tùy chỉnh một số thành phần của cửa sổ Subiz chat theo ý muốn một cách dễ dàng và đơn giản.

#### Tùy chỉnh CSS ở đâu? {#tuy-chinh-css-o-dau}

Bạn sẽ đăng nhập vào trang app.subiz.com, vào phần **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Cửa sổ hội thoại &gt; Tùy chỉnh CSS** để thực hiện những thay đổi về CSS này.

![T&#xF9;y ch&#x1EC9;nh CSS](../../../.gitbook/assets/noi-tuy-chinh-css.png)

Tiếp theo, **bạn Copy và paste đoạn css tương ứng để tùy chỉnh thành phần bạn muốn, sau đó quay lại màn hình cài đặt cửa sổ chat và Lưu thay đổi**

Dưới đây là một số tùy chỉnh css một số thành phần trên cửa sổ chat bạn có thể tham khảo.

#### Thay đổi kích thước cửa sổ chat

Bạn có thể thay đổi chiều cao và chiều rộng theo ý muốn:

{% tabs %}
{% tab title="Thay đổi chiều cao" %}
Đoạn mã tùy chỉnh chiều cao cửa sổ chat Subiz

```text
.widget_mini .widget_body {
 height: 800px !important;
 max-height: 900px !important;
}
```

Phần **800**px bạn có thể điều chỉnh con số cho phù hợp với website.

![CSS ch&#x1EC9;nh s&#x1EED;a chi&#x1EC1;u cao c&#x1EED;a s&#x1ED5; chat](../../../.gitbook/assets/css-chieu-cao%20%281%29.png)
{% endtab %}

{% tab title="Thay đổi chiều rộng" %}
Đoạn mã tùy chỉnh chiều rộng cửa sổ chat Subiz

```text
.widget_mini .widget_body{ width:600px;}
```

Phần **600**px bạn có thể điều chỉnh con số cho phù hợp với website.

![T&#xF9;y ch&#x1EC9;nh chi&#x1EC1;u r&#x1ED9;ng c&#x1EED;a s&#x1ED5; chat](../../../.gitbook/assets/css-chieu-rong.png)
{% endtab %}
{% endtabs %}

#### Tùy chỉnh cỡ chữ {#tuy-chinh-co-chu}

Đoạn mã tùy chỉnh cỡ chữ trên cửa sổ chat Subiz

```text
.message-content{ font-size:20px;}
```

![Thay &#x111;&#x1ED5;i c&#x1EE1; ch&#x1EEF; tr&#xEA;n c&#x1EED;a s&#x1ED5; chat](../../../.gitbook/assets/css-size-font.png)

#### Tùy chỉnh màu sắc trên cửa sổ chat Subiz {#tuy-chinh-mau-sac-tung-phan-tren-cua-so-chat}

{% tabs %}
{% tab title="Màu sắc toàn bộ cửa sổ chat" %}
{% hint style="danger" %}
Khi bạn chọn cách tùy chỉnh màu sắc toàn bộ cửa sổ chat, bạn sẽ không thể tùy chỉnh màu sắc cho từng phần riêng biệt như header, khung tin nhắn hay nút tạo mới được nữa
{% endhint %}

Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp.

* **Mã code tùy chỉnh toàn bộ cửa sổ chat theo màu sắc đơn**

```text
.color-theme-default
{background-color:#000000;}
```

Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* **Mã code tùy chỉnh toàn bộ cửa sổ chat theo dải màu chuyển tiếp**

```text
.color-theme-default
{background-image: linear-gradient(to right top, #056587, #0085a3, #00a6ac, #00c59f, #0be17f);}
```

Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.

![T&#xF9;y ch&#x1EC9;nh m&#xE0;u s&#x1EAF;c to&#xE0;n b&#x1ED9; c&#x1EED;a s&#x1ED5; chat theo d&#x1EA3;i m&#xE0;u chuy&#x1EC3;n ti&#x1EBF;p](../../../.gitbook/assets/css-mau-sac-toan-bo.png)
{% endtab %}

{% tab title="Màu sắc header" %}
Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* **Mã code tùy chỉnh màu sắc đơn của header**

```text
.widget-header {background-color:#00000;}
```

Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* **Mã code tùy chỉnh dài màu chuyển tiếp của header**

```text
.widget-header
{background-image: linear-gradient(to right top, #056587, #0085a3, #00a6ac, #00c59f, #0be17f);}
```

Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website

![T&#xF9;y ch&#x1EC9;nh m&#xE0;u s&#x1EAF;c header theo d&#x1EA3;i m&#xE0;u chuy&#x1EC3;n ti&#x1EBF;p](../../../.gitbook/assets/css-mau-header.png)
{% endtab %}

{% tab title="Màu sắc khung tin nhắn" %}
Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* **Mã code tùy chỉnh theo màu sắc đơn cho khung tin nhắn**

```text
.message-body {background-color:#00000;}
```

Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* **Mã code tùy chỉnh theo dài màu chuyển tiếp cho khung tin nhắn**

```text
.message-body
{background-image: linear-gradient(to right top, #056587, #0085a3, #00a6ac, #00c59f, #0be17f);}
```

Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website

![T&#xF9;y ch&#x1EC9;nh m&#xE0;u khung tin nh&#x1EAF;n theo d&#x1EA3;i m&#xE0;u chuy&#x1EC3;n ti&#x1EBF;p](../../../.gitbook/assets/css-khung-tin-nhan.png)
{% endtab %}

{% tab title="Màu sắc nút \"Tạo mới\"" %}
Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* **Mã code tùy chỉnh theo màu sắc đơn cho nút "Tạo mới"**

```text
.add-new-conversation
{background-color:#000000;}
```

Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* **Mã code tùy chỉnh theo dải màu chuyển tiếp cho nút "Tạo mới"**

```text
.add-new-conversation
{background-image: linear-gradient(to right top, #056587, #0085a3, #00a6ac, #00c59f, #0be17f);}
```

Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.

![T&#xF9;y ch&#x1EC9;nh m&#xE0;u n&#xFA;t &quot;T&#x1EA1;o m&#x1EDB;i&quot; theo d&#x1EA3;i m&#xE0;u chuy&#x1EC3;n ti&#x1EBF;p](../../../.gitbook/assets/css-tao-moi.png)
{% endtab %}
{% endtabs %}

### Tùy chỉnh ngôn ngữ cửa sổ Subiz chat qua file .Po

Hiện tại, Subiz hỗ trợ 2 ngôn ngữ là Tiếng Việt và Tiếng Anh. Trên cửa sổ Subiz, bạn có thể tùy chỉnh tiêu đề cửa sổ và lời giới thiệu theo từng ngôn ngữ.

Ngoài ra, nếu bạn muốn sử dụng một ngôn ngữ khác ngoài các ngôn ngữ được hỗ trợ. Giả sử bạn muốn thay ngôn ngữ Tiếng Anh bằng Tiếng Đức. Hoặc bạn có nhu cầu chỉnh sửa nhiều hơn ở phần ngôn ngữ trên cửa sổ, bạn có thể tùy chỉnh theo file ngôn ngữ .po theo các bước dưới đây:

#### Bước 1: Tải file ngôn ngữ mẫu {#buoc-1-tai-file-ngon-ngu-mau}

Đăng nhập tài khoản và vào [Cài đặt cửa sổ hội thoại](https://app.subiz.com/settings/widget-setting), phần **Ngôn ngữ**. Chọn 1 ngôn ngữ cụ thể và click vào “Tùy chỉnh ngôn ngữ”.

![N&#x1A1;i b&#x1EAF;t &#x111;&#x1EA7;u th&#x1EF1;c hi&#x1EC7;n t&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF;](../../../.gitbook/assets/tc-ngon-ngu-1.png)

Chọn “Nhấn để tải xuống file tùy chỉnh ngôn ngữ cho widget” để tải về file .po mẫu.

![T&#x1EA3;i xu&#x1ED1;ng file t&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF; cho widget](../../../.gitbook/assets/tai-file-tuy-chinh-ngon-ngu.png)

#### Bước 2: Tùy chỉnh file ngôn ngữ {#buoc-2-tuy-chinh-file-ngon-ngu}

* Truy cập [https://localise.biz/free/poeditor](https://localise.biz/free/poeditor), tải lên file mẫu mà bạn vừa tải về.

![&#x110;&#x1B0;a file t&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF; l&#xEA;n](../../../.gitbook/assets/drop-a-file.png)

* Tại Source text là phần ngôn ngữ gốc. Bạn có thể dịch ra các ngôn ngữ mà bạn muốn tại phần Translation. Ví dụ, dịch sang tiếng Đức: Email and Name = Email und Name.

![D&#x1ECB;ch c&#xE1;c ng&#xF4;n ng&#x1EEF; b&#x1EA1;n mu&#x1ED1;n t&#xF9;y ch&#x1EC9;nh](../../../.gitbook/assets/edit-file.png)

* Chọn Save để Lưu thay đổi sau khi hoàn tất.

![L&#x1B0;u file &#x111;&#xE3; d&#x1ECB;ch](../../../.gitbook/assets/save-button.png)

* Click vào file để tải về.

![T&#x1EA3;i file &#x111;&#xE3; d&#x1ECB;ch v&#x1EC1; m&#xE1;y t&#xED;nh](../../../.gitbook/assets/save-file.png)

#### Bước 3: Tải lên file .po đã chỉnh sửa và lưu thay đổi {#buoc-3-tai-len-file-po-da-chinh-sua-va-luu-thay-doi}

Tại phần cài đặt Ngôn ngữ, bạn chọn 1 ngôn ngữ và chọn Tùy chỉnh ngôn ngữ. Sau khi tải file mới lên, ngôn ngữ mới sẽ được ghi đè lên ngôn ngữ bạn vừa chọn.

![T&#x1EA3;i file &#x111;&#xE3; t&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF; l&#xEA;n Subiz](../../../.gitbook/assets/upload-file.png)

Sau khi có thông báo file tải lên thành công, bạn thoát ra ngoài và Lưu thay đổi.

![Th&#xF4;ng b&#xE1;o t&#x1EA3;i file &#x111;&#xE3; t&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF; th&#xE0;nh c&#xF4;ng](../../../.gitbook/assets/upload-success.png)

###  {#loi-khi-tich-hop-len-website}



