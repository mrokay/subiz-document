# Các ngôn ngữ hỗ trợ trên cửa sổ Subiz chat

Cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) là nơi đầu tiên khách truy cập website tiếp cận và tương tác với doanh nghiệp. Thiết lập ngôn ngữ hiển thị trên cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) giúp khách hàng dễ dàng liên hệ và yêu cầu hỗ trợ khi cần thiết.

Hiện tại cửa sổ Subiz chat hỗ trợ hai ngôn ngữ mặc định: Tiếng Việt và Tiếng Anh. Dưới đây là bảng tên ngôn ngữ và mã ký hiệu dùng cho API:

| **TÊN NGÔN NGỮ** | **MÃ** |
| :--- | :--- |
| English | en |
| Tiếng Việt | vi |

\*\*\*\*

### **1.Tùy chỉnh ngôn ngữ cửa sổ Subiz chat**

Bạn có thể tùy chọn ngôn ngữ phù hợp với đối tượng khách hàng của mình.  


![T&#xF9;y ch&#x1EC9;nh ng&#xF4;n ng&#x1EEF; c&#x1EED;a s&#x1ED5; Subiz chat](../../../.gitbook/assets/ngon-ngu.jpg)

Trong đó :

* **Tự động**: Cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) tự động nhận diện và hiển thị ngôn ngữ tiếng Anh hoặc tiếng Việt theo địa chỉ IP của khách hàng.
* **Tiếng Việt**: chọn khi doanh nghiệp chỉ phục vụ khách hàng Việt Nam và website hỗ trợ chỉ ngôn ngữ Việt Nam.
* **English**: chọn khi doanh nghiệp phục vụ khách quốc tế và website chỉ hỗ trợ ngôn ngữ tiếng Anh.

### **2. Sử dụng API tùy biến ngôn ngữ cửa sổ Subiz chat theo ngôn ngữ website**

Website của bạn đang hỗ trợ hai ngôn ngữ English và tiếng Việt.

Cửa sổ [Subiz chat](https://subiz.com/vi/live-chat.html) sẽ tùy biến hiển thị ngôn ngữ tiếng Anh hoặc tiếng Việt theo ngôn ngữ trên website.

Rất đơn giản, bạn chỉ cần đặt mã API này ngay sau mã nhúng Subiz trong code website.

**API thiết lập ngôn ngữ tiếng Anh**

```text
<script>
subiz('setLanguage', 'en');
</script>
```

**API thiết lập ngôn ngữ tiếng Việt**

```text
<script>
subiz('setLanguage', 'vi');
</script>
```

> Bạn đang cần hỗ trợ ngôn ngữ khác, vui lòng chat trực tiếp với Subiz trên website [Subiz.com](https://subiz.com/vi/feature.html) nhé!

### 3. Tùy chỉnh ngôn ngữ cửa sổ chat với file .po

Hiện tại, [Subiz](https://subiz.com/vi/) hỗ trợ 2 ngôn ngữ là Tiếng Việt và Tiếng Anh để bạn có thể tùy chỉnh mục **tiêu đề cửa sổ chat và lời giới thiệu** theo từng ngôn ngữ này.

Đặc biệt,  Subiz cung cấp thêm file tùy chỉnh ngôn ngữ gốc .po khi bạn có nhu cầu riêng như:

* Sử dụng một ngôn ngữ khác ngoài Tiếng Việt và Tiếng Anh. Ví dụ: Tiếng Pháp, Tiếng Nhật,..
* Tùy chỉnh phần dịch ngôn ngữ của nhiều mục khác trên cửa sổ chat. Ví dụ: Tin nhắn trong Automation hỏi thông tin,...

Hướng dẫn các bước tùy chỉnh ngôn ngữ cửa sổ chat với file .po

**Bước 1: Tải xuống file gốc .po**

* [Đăng nhập App.subiz.com &gt; Cài đặt &gt; Tài khoản &gt; Cửa sổ hội thoại ](https://app.subiz.com/settings/widget-setting)
* Tại mục **NGÔN NGỮ** &gt; chọn **Tiếng Việt** &gt; chọn **Tùy chỉnh ngôn ngữ**
* Chọn **Tải xuống file gốc .po**
* **File .po sẽ được mở ở tab khác** &gt; **Nhấp chuột phải** và chọn **Lưu thành** \(hay **Save as**\) &gt; File lưu về máy tính định dạng **PO translation**

**Bước 2: Tùy chỉnh file ngôn ngữ .po**

*  Truy cập [https://localise.biz/free/poeditor](https://localise.biz/free/poeditor), tải lên file mẫu mà bạn vừa tải về.
* Source text là phần ngôn ngữ gốc, **Translation là phần dịch để bạn tùy chỉnh ngôn ngữ**
* chọn **Save** sau khi tùy chỉnh xong và chọn Tải file về máy tính

**Bước 3: Tải lên Subiz file .po đã tùy chỉnh** 

* Tại bảng **Tùy chỉnh ngôn ngữ** của Subiz, bạn tải lên file .po đã tùy chỉnh
* Khi tải lên thành công, bạn chọn X để thoát và Lưu thay đổi 



\*\*\*\*

\*\*\*\*















