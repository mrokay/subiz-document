# Quan sát khách truy cập

### Làm thế nào để quan sát khách truy cập?

Doanh nghiệp có thể quan sát khách truy cập website của mình, nắm rõ nhu cầu thông tin, sản phẩm và dịch vụ mà khách hàng mong muốn, từ đó chủ động tiếp cận hỗ trợ họ. 

**Bạn có thể theo dõi các khách đang truy cập website của bạn** tại trang **Khách**. Mỗi khách truy cập được nhận diện bằng [cookie](http://vi.wikipedia.org/wiki/Cookie) trên trình duyệt của họ.

![Quan s&#xE1;t kh&#xE1;ch truy c&#x1EAD;p Website t&#x1EA1;i trang Kh&#xE1;ch](../../.gitbook/assets/visitor.png)

Với mỗi khách truy cập, bạn sẽ biết được những thông tin sau:

* **Ảnh đại diện:** Hiển thị chữ cái đầu tiên trong tên của visitor
* **Họ tên, Email**: Các thông tin này được lưu từ lần truy cập trước hoặc chuyển từ website của bạn vào hệ thống Subiz qua API Javascript
* **Vị trí địa lý**: vị trí của khách truy cập được xác định thông qua địa chỉ IP
* **Trang đang xem**: Địa chỉ trang mà khách đang xem trên website của bạn

Khi click vào từng khách truy cập trên trang **Khách**, bạn sẽ bắt đầu để tương tác trực tiếp với khách hàng đó trên mục **Hoạt động**

![](../../.gitbook/assets/assets2f-lcrbjdxgv2cwmzzedgk2f-lccwktkrblkqygrim-l2f-lccwuvt7zd7uvvi3suq2fagent-chu-dong-tao-tuong-t.png)

### [Subiz](https://subiz.com/vi/) xác định thông tin vị trí khách truy cập dựa vào đâu?

![X&#xE1;c &#x111;&#x1ECB;nh v&#x1ECB; tr&#xED; kh&#xE1;ch truy c&#x1EAD;p d&#x1EF1;a tr&#xEA;n &#x111;&#x1ECB;a ch&#x1EC9; IP](../../.gitbook/assets/assets2f-lcrbjdxgv2cwmzzedgk2f-lcfnbeua9alvfvpn-6j2f-lcfosmb7mvcu3afmx_w2fscreenshot_52.png)

Để xác định vị trí địa lý khách hàng, [Subiz ](https://subiz.com/vi/)sử dụng dịch vụ của bên thứ 3 là **Maxmind**. Nó được xác định dựa trên địa chỉ IP. Các địa chỉ IP này đôi khi được liên kết với một ISP \(Internet Service Provider\) hoặc VPN \(Virtual Private Network\) nên sự khác biệt với địa điểm thực của khách hàng hoàn toàn có thể xảy ra.

Một trong những lý do khác khiến những thông tin này không chính xác 100% là do các cơ sở dữ liệu của bên thứ 3 cập nhật không chính xác hoặc bị cũ do chưa cập nhật kịp thời sự thay đổi.

Để điều chỉnh sự không chính xác này, bạn có thể gửi yêu cầu trực tiếp tới Maxmind để yêu cầu cập nhật chính xác: [https://support.maxmind.com/geoip-data-correction-request/](https://support.maxmind.com/geoip-data-correction-request/)

Với tình trạng sai khác thông tin vị trí khi thực hiện truy cập giữa các máy trong cùng một công ty, bạn có thể kiểm tra thông tin địa chỉ IP của các máy tính này.

