# Cách tùy chỉnh CSS cho cửa sổ Subiz chat

Bên cạnh việc sử dụng những cài đặt cửa sổ chat trên website mà Subiz đã cung cấp. Bạn có thể dễ dàng tùy chỉnh những thành phần khác trên cửa sổ chat bằng cách sử dụng mã CSS.

CSS là viết tắt của cụm từ “Cascading Style Sheet”, nó là một ngôn ngữ quy định cách trình bày của các thẻ html trên trang web. Với việc sử dụng CSS bạn có thể tùy chỉnh một số thành phần của cửa sổ Subiz chat theo ý muốn một cách dễ dàng và đơn giản.

#### Tùy chỉnh CSS ở đâu? {#tuy-chinh-css-o-dau}

Bạn sẽ đăng nhập vào trang app.subiz.com, vào phần **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Cửa sổ hội thoại &gt; Tùy chỉnh CSS** để thực hiện những thay đổi về CSS này.![](https://docv4.subiz.com/wp-content/uploads/2018/05/Tuy-chinh-CSS.png)

Tiếp theo, **bạn Copy và paste đoạn css tương ứng để tùy chỉnh thành phần bạn muốn, sau đó quay lại màn hình cài đặt cửa sổ chat và Lưu thay đổi**

Dưới đây là một số tùy chỉnh css một số thành phần trên cửa sổ chat bạn có thể tham khảo.

* ​[Thay đổi chiều rộng cửa sổ chat](https://docv4.subiz.com/cach-tuy-chinh-css-cho-cua-so-subiz-chat/#width)​
* ​[Thay đổi chiều cao cửa sổ chat](https://docv4.subiz.com/cach-tuy-chinh-css-cho-cua-so-subiz-chat/#height)​
* ​[Tùy chỉnh cỡ chữ](https://docv4.subiz.com/cach-tuy-chinh-css-cho-cua-so-subiz-chat/#sizefont)​
* ​[Tùy chỉnh màu sắc toàn bộ cửa sổ chat](https://docv4.subiz.com/cach-tuy-chinh-css-cho-cua-so-subiz-chat/#totalcolour)​
* ​[Tùy chỉnh màu sắc từng phần cửa sổ chat](https://docv4.subiz.com/cach-tuy-chinh-css-cho-cua-so-subiz-chat/#colour)​

#### Thay đổi chiều rộng cửa sổ chat {#thay-doi-chieu-rong-cua-so-chat}

| 123 | .widget\_mini .widget\_body{ width:600px;} |
| --- |


Phần **600**px bạn có thể điều chỉnh con số cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-chieu-rong.png)

### ​ {#undefined}

#### Thay đổi chiều cao cửa sổ chat {#thay-doi-chieu-cao-cua-so-chat}

| 1234 | .widget\_mini .widget\_body{ height: 800px !important; max-height: 900px !important;} |
| --- |


Phần **800**px bạn có thể điều chỉnh con số cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-chieu-cao.png)

#### Tùy chỉnh cỡ chữ {#tuy-chinh-co-chu}

| 123 | .message-content{ font-size:20px;} |
| --- |


Phần **20**px bạn có thể điều chỉnh con số cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/Css-Size-font-1.png)

### ​ {#undefined-1}

#### Tùy chỉnh màu sắc toàn bộ cửa sổ chat {#tuy-chinh-mau-sac-toan-bo-cua-so-chat}

Khi bạn chọn cách tùy chỉnh màu sắc toàn bộ cửa sổ chat, bạn sẽ không thể tùy chỉnh màu sắc cho từng phần riêng biệt như header, khung tin nhắn hay nút tạo mới được nữa

Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp.

* Màu sắc đơn

| 12 | .color-theme-default{background-color:\#000000;} |
| --- |


Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* Dài màu chuyển tiếp

| 12 | .color-theme-default{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/CSS-mau-sac-toan-bo.png)

#### Tùy chỉnh màu sắc từng phần trên cửa sổ chat {#tuy-chinh-mau-sac-tung-phan-tren-cua-so-chat}

**1. Tuy chỉnh màu sắc header cửa sổ chat**

Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* Màu sắc đơn

| 1 | .widget-header {background-color:\#00000;} |
| --- |


Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* Dài màu chuyển tiếp

| 12 | .widget-header{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/CSS-mau-header.png)

**2. Tùy chỉnh màu sắc khung tin nhắn trên cửa sổ chat**

Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* Màu sắc đơn

| 1 | .message-body {background-color:\#00000;} |
| --- |


Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* Dài màu chuyển tiếp

| 12 | .message-body{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/css-khung-tin-nhan.png)

**3. Tùy chỉnh màu sắc nút “Tạo mới” tin nhắn trên cửa sổ chat**

Bạn có thể tùy chỉnh theo màu sắc đơn hoặc theo dải màu chuyển tiếp:

* Màu sắc đơn

| 1 | .add-new-conversation {background-color:\#00000;} |
| --- |


Phần **\#00000** bạn có thể điều chỉnh cho phù hợp với website.

* Dài màu chuyển tiếp

| 12 | .add-new-conversation{background-image: linear-gradient\(to right top, \#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f\);} |
| --- |


Phần dải màu **\#056587, \#0085a3, \#00a6ac, \#00c59f, \#0be17f** bạn có thể điều chỉnh cho phù hợp với website.![](https://docv4.subiz.com/wp-content/uploads/2018/05/Css-tao-moi.png)

