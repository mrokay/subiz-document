# Các ngôn ngữ hỗ trợ trên cửa sổ Subiz chat

[Cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting/set-up-subiz-chat) là nơi đầu tiên khách truy cập website tiếp cận và tương tác với doanh nghiệp. Thiết lập ngôn ngữ hiển thị trên cửa sổ Subiz chat giúp khách hàng dễ dàng liên hệ và yêu cầu hỗ trợ khi cần thiết.

Hiện tại cửa sổ Subiz chat hỗ trợ hai ngôn ngữ mặc định: Tiếng Việt và Tiếng Anh. Dưới đây là bảng tên ngôn ngữ và mã ký hiệu dùng cho API:

| **TÊN NGÔN NGỮ** | **MÃ** |
| :--- | :--- |
| English | en |
| Tiếng Việt | vi |

Mã ngôn ngữ là Mã đại diện của ngôn ngữ theo chuẩn [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1) \(hai ký tự\).

### **1.Tùy chỉnh ngôn ngữ cửa sổ Subiz chat**

Bạn có thể tùy chọn ngôn ngữ phù hợp với đối tượng khách hàng của mình tại trang [**Cài đặt Cửa sổ Subiz chat &gt; Thiết kế cửa sổ Subiz chat**](https://app.subiz.com/settings/widget-setting/set-up-subiz-chat)\*\*\*\*

![](../../../.gitbook/assets/language-11.png)

Trong đó :

* **Tự động**: Cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) tự động nhận diện và hiển thị ngôn ngữ tiếng Anh hoặc tiếng Việt theo địa chỉ IP của khách hàng.
* **Tiếng Việt**: chọn khi doanh nghiệp chỉ phục vụ khách hàng Việt Nam và website hỗ trợ chỉ ngôn ngữ Việt Nam.
* **English**: chọn khi doanh nghiệp phục vụ khách quốc tế và website chỉ hỗ trợ ngôn ngữ tiếng Anh.

### 2. Thay đổi ngôn ngữ cửa sổ chat theo từng website

[Cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting/set-up-subiz-chat) sẽ tùy biến hiển thị ngôn ngữ tiếng Anh hoặc tiếng Việt theo ngôn ngữ trên website.

Rất đơn giản, bạn chỉ cần đặt mã API javascript này ngay sau mã nhúng Subiz trong code website.

**API thiết lập ngôn ngữ tiếng Anh**

```javascript
<script>
subiz('setLanguage', 'en');
</script>
```

**API thiết lập ngôn ngữ tiếng Việt**

```javascript
<script>
subiz('setLanguage', 'vi');
</script>
```

### 3. Tùy chỉnh nội dung cửa sổ chat với file .po

Hiện tại, [Subiz](https://subiz.com/vi/) hỗ trợ 2 ngôn ngữ là Tiếng Việt và Tiếng Anh để bạn có thể tùy chỉnh nội dung **tiêu đề cửa sổ chat và lời giới thiệu** theo từng ngôn ngữ này.

Đặc biệt,  Subiz cung cấp thêm file tùy chỉnh ngôn ngữ gốc .po khi bạn có nhu cầu riêng như:

* Sử dụng một ngôn ngữ khác ngoài Tiếng Việt và Tiếng Anh. Ví dụ: Tiếng Pháp, Tiếng Nhật,..
* Tùy chỉnh nội dung của nhiều mục khác trên cửa sổ chat. Ví dụ: Tin nhắn trong Automation hỏi thông tin,...

**Hướng dẫn các bước tùy chỉnh ngôn ngữ cửa sổ chat với file .po gồm 3 bước sau:**

**Bước 1: Tải xuống tệp tùy chỉnh nội dung cửa sổ chat**

* [Đăng nhập App.subiz.com &gt; Cài đặt &gt;  Cửa sổ Subiz chat](https://app.subiz.com/settings/widget-setting/set-up-subiz-chat)
* Tại mục NGÔN NGỮ &gt; chọn Tiếng Việt &gt; chọn **Bạn có thể sửa tất cả nội dung Tiếng Việt tại đây**
* Chọn **Tải về tệp nội dung gốc** **&gt;** Tệp định dạng .po sẽ được lưu về máy tính

**Bước 2: Tùy chỉnh tệp nội dung gốc .po**

*  Truy cập [https://localise.biz/free/poeditor](https://localise.biz/free/poeditor), tải lên tệp .po mà bạn vừa lưu trong máy tính

![T&#x1EA3;i l&#xEA;n t&#x1EC7;p t&#xF9;y ch&#x1EC9;nh n&#x1ED9;i dung](../../../.gitbook/assets/4.-tai-len-po.jpg)

* Source text là phần ngôn ngữ gốc, **Translation là phần dịch để bạn tùy chỉnh, thay đổi ngôn ngữ theo nhu cầu.** Kéo chuột hoặc tìm kiếm nội dung cần thay đổi.

![T&#xF9;y ch&#x1EC9;nh n&#x1ED9;i dung ng&#xF4;n ng&#x1EEF; theo nhu c&#x1EA7;u](../../../.gitbook/assets/5.-dich.jpg)

* Chọn **Save** sau khi tùy chỉnh xong và chọn Save to your computer tải tệp .po đã tùy chỉnh về máy tính.

![L&#x1B0;u t&#x1EC7;p &#x111;&#xE3; t&#xF9;y ch&#x1EC9;nh v&#x1EC1; m&#xE1;y t&#xED;nh](../../../.gitbook/assets/6.-luu-ve-may.jpg)

**Bước 3: Tải lên Subiz tệp nội dung đã tùy chỉnh** 

* Tại bảng **Bạn có thể sửa tất cả nội dung Tiếng Việt tại đây** của Subiz, bạn chọn Tệp .po đã sửa để tải lên.

![](../../../.gitbook/assets/language-22.png)

* Khi tải lên thành công, bạn chọn **X** để hoàn thành và chọn Lưu thay đổi.

![](../../../.gitbook/assets/language-33.png)

> Bạn đang cần hỗ trợ thêm, vui lòng chat trực tiếp với Subiz trên website [Subiz.com](https://subiz.com/vi/feature.html) nhé!















