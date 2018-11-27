---
description: >-
  Là các phương thức tương tác với Subiz Widget (cửa sổ Subiz) thông qua
  Javascript. Nó giúp các website làm việc với Subiz sáng tạo hơn.
---

# API Javascript của Subiz Widget

### Update User Attributes

API cho phép cập nhật dữ liệu khách hàng ngay từ Website. Ví dụ khi khách truy cập Login trên web, bạn có thể cập nhật email, tên...  lên Subiz để quản lý cũng như tương tác.  

```javascript
<script>
    subiz('updateUserAttributes', [{ key: 'fullname',   text : 'David' }]);
</script>
//Cập nhật tên. Trong đó fullname là Attributes Key của trường dữ liệu Fullname.
```

Bạn có thể lấy Attributes Key tại [https://app.subiz.com/settings/user-attributes](https://app.subiz.com/settings/user-attributes)

```javascript
<script>
    subiz('updateUserAttributes', [{ key: 'so_thich',   list :['Máy ', 'EnglDu lịch']);
</script>
//Cập nhật một trường dữ liệu khách hàng tùy chỉnh, và là dạng nhiều giá trị. 
```

Bạn cũng có thể cập nhật nhiều trường giá trị cùng lúc. 

```javascript
<script>
    subiz('updateUserAttributes', [{ key: 'fullname',   text : 'David' },{ key: 'phones',   text : '+84983123456' }]);
</script>
//Update trường fullname và phones cùng lúc. 
```

### Lấy dữ liệu User từ Subiz \(get user attributes\)

API cho phép lấy dữ liệu Khách truy cập từ Subiz để cho website sử dụng. Ví dụ, một khách truy cập quay lại, bạn có thể lấy dữ liệu đã lưu trong Subiz và hiển thị lên website. Ví dụ như dữ liệu Vị trí địa lý để web hiển thị thông tin phù hợp.

```javascript
<script>
    subiz('getUserAttributes', (attributes) => {console.log('user attributes', attributes)});
</script>
//Lấy dữ liệu User Attributes từ Subiz về.
```

### ForgetMe - API xóa toàn bộ dữ liệu một User

Chức năng cho phép bạn thiết kế cơ chế để Khách truy cập có thể xóa dữ liệu của họ. Dữ liệu bị xóa bao gồm tất cả thông tin trên trình duyệt của khách truy cập và trong Subiz. Do vậy, khi bị xóa thì agents cũng không nhìn thấy User này.

```javascript
<script>
    subiz('forgetMe');
</script>
//API Để xóa dữ liệu User.
```

### Chỉ định ngôn ngữ cho Subiz Widget

API cho phép web chỉ định ngôn ngữ hiển thị của Subiz Widget.  Khi đó, bạn có thể quyết định trang nào hiển thị tiếng Việt, trang nào hiển thị tiếng Anh.

```javascript
<script>
    subiz('setLanguage', 'en');
</script>
//Chỉ định ngôn ngữ tiếng Anh. Trong đó 'en' là mã ngôn ngữ.  
```

Mã ngôn ngữ là Mã đại diện của ngôn ngữ theo chuẩn [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1)  \( hai ký tự\) và là những ngôn ngữ mà Subiz hiện đang có. [Xem danh sách ngôn ngữ Subiz đang hỗ trợ](http://help.subiz.com/bat-dau-voi-subiz/thiet-lap-moi-truong-tuong-tac/tich-hop-subiz-len-website/cac-ngon-ngu-ho-tro-tren-cua-so-subiz-chat). 

### Mở /  Subiz 

API cho phép bạn ra lệnh mở Subiz Widget. Ví dụ, bạn có thể tạo một nút trên website để khi khách truy cập click vào nút đó, cửa sổ Subiz sẽ mở ra.

```javascript
<script type="text/javascript">
    window.subiz('expandWidget')
</script>
// API mở Subiz widget qua function Javascript. 
```

```markup
<a href="#nogo" onclick="subiz('expandWidget')">Text của </a>
//Gắn vào một link để ra lệnh mở Subiz widget.
```

```javascript
<script type="text/javascript">
    window.subiz('shrinkWidget')
</script>
//API đóng cửa sổ Subiz.
```

```markup
<a href="#nogo" onclick="subiz('shrinkWidget')">text của </a>
//Gắn vào link để đóng Subiz widget.
```

### Tùy chỉnh CSS

API cho phép bạn truyền một đoạn mã CSS để thay đổi lại Subiz Widget theo nhu cầu của bạn.  Chức năng giúp bạn có thể sáng tạo ra cửa sổ Subiz cho từng website với phong cách riêng của nó.

```javascript
<script type="text/javascript">
    window.subiz('changeCss', '.widget_mini .widget_body {height: 750px !important; max-height: 800px !important;}')
</script>
```







