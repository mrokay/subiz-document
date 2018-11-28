# Tạo Rule mới

Rule là tính năng tự động phân phối cuộc hội thoại của khách hàng cho các agent theo các điều kiện cài đặt. Bạn nên dựa trên tình hình thực tế, cách thức quản lý, điều hành của doanh nghiệp, cách thức phân chia công việc của tư vấn viên để sáng tạo ra các Rule mới, giúp cho việc phân phối và xử lý các cuộc hội thoại được hiệu quả.

Để tạo rule mới, bạn [đăng nhập tài khoản](https://app.subiz.com/login) và vào phần[ **Cài đặt &gt; Tài khoản &gt; Tin nhắn &gt; Rule &gt; Tạo Rule mới**](https://app.subiz.com/settings/add-rule)\*\*\*\*

![T&#x1EA1;o Rule m&#x1EDB;i](../../../.gitbook/assets/tao-rule.jpg)

### Bước 1: Đặt tên và mô tả Rule

* **Tên:** Đặt tên để gọi và phân biệt các Rule cài đặt
* **Mô tả**: Mô tả mục đích cài đặt Rule

![&#x110;i&#x1EC1;n t&#xEA;n v&#xE0; m&#xF4; t&#x1EA3; Rule](../../../.gitbook/assets/ten-rule.jpg)

### Bước 2: Chọn Điều kiện cho Rule

Điều kiện trong Rule là những logic để một Rule hoạt động, tự động phân phối cuộc hội thoại của đúng khách hàng tới đúng agent phụ trách.

Bạn có thể chọn nhiều điều kiện để cài đặt Rule:

* Click Thêm điều kiện để thêm điều kiện cài đặt Rule
* Chọn Và / Hoặc để xác định mối quan hệ giữa các điều kiện.

  **Ví dụ:** Rule cài đặt Phân phối hội thoại của khách Việt Nam và nhắn tin từ web Subiz.com 

![](../../../.gitbook/assets/dieu-kien-rule%20%281%29.jpg)

**Bạn có thể chọn một hay nhiều điều kiện trong danh sách các điều kiện trong Rule dưới đây:​**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>CÁC ĐIỀU KIỆN</b>
      </th>
      <th style="text-align:left"><b>CÁCH SỬ DỤNG</b>
      </th>
      <th style="text-align:left"><b>VÍ DỤ</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Bất kì điều kiện nào</td>
      <td style="text-align:left">Khi lựa chọn điều kiện này, tất cả cuộc hội thoại sẽ luôn được phân phối
        tới các agent.</td>
      <td style="text-align:left">Điều kiện:<em>Bất kì điều kiện nào</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Date Time</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Giờ trong ngày</td>
      <td style="text-align:left">Dùng khi bạn muốn phân chia cuộc thoại theo các khung giờ trong ngày.
        Giờ trong ngày từ 0 - 23.</td>
      <td style="text-align:left">
        <p>Bạn cài đăt 3 rule tương ứng: Ca sáng cho Agent A - Ca chiều cho Agent
          B - Ca tối cho Agent C.</p>
        <p>Điều kiện:
          <br /><em>Giờ trong ngày - lớn hơn hoặc bằng - 7<br />Và<br />Giờ trong ngày - nhỏ hơn - 12</em>
        </p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Ngày trong tuần</td>
      <td style="text-align:left">Dùng khi bạn muốn phân chia cuộc thoại theo ngày trong tuần.
        <br />Lưu ý: Ngày trong tuần được ghi nhận theo số thứ tự từ 2-8. Thứ Hai =
        2, Thứ Ba = 3… , Chủ nhật = 8.</td>
      <td style="text-align:left">
        <p>Bạn cài đặt 2 Rule: 3 ngày đầu tuần cho Agent A và 3 ngày cuối tuần cho
          Agent B</p>
        <p>Điều kiện:
          <br /><em>Ngày trong tuần - bằng - 2<br />Hoặc <br />Ngày trong tuần - bằng - 3<br />Hoặc <br />Ngày trong tuần - bằng - 4</em>
        </p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Hội thoại</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Kênh</td>
      <td style="text-align:left">Dùng khi bạn muốn phân phối hội thoại theo kênh tương tác khách hàng.
        Ví dụ kênh Subiz chat trên website, Kênh Fanpage, kênh Subiz Email</td>
      <td
      style="text-align:left">
        <p>Bạn tạo 3 Rule phân chai hội thoại trên 3 kênh Subiz chat, Fanpage, Email
          như sau:</p>
        <p>Điều kiện:
          <br /><em>1.  Kênh - bằng - Subiz chat</em>
        </p>
        <p><em>2. Kênh - bằng - Subiz Email</em>
        </p>
        <p><em>3. Kênh - bằng - Fanpage</em>
        </p>
        </td>
    </tr>
    <tr>
      <td style="text-align:left">URL của trang</td>
      <td style="text-align:left">Dùng khi bạn muốn phân chia cuộc hội thoại theo từng URL website riêng
        hay URL page sản phẩm/ dịch vụ trên 1 website</td>
      <td style="text-align:left">
        <p>Khách vào website của Subiz sẽ được phân phối cho Agent A</p>
        <p>Điều kiện: <em>URL của trang - chứa - Subiz.com</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Tiêu đề trang</td>
      <td style="text-align:left">Tiêu đề trang gần giống URL trang, dùng để phân phối hội thoại theo từng
        tiêu đề của trang sản phẩm/ dịch vụ</td>
      <td style="text-align:left">
        <p>Khách vào trang có tiêu đề chứa từ khóa “Máy Ảnh” phân phối cuộc hội thoại
          cho Agent A.</p>
        <p>Điều kiện: <em>Tiêu đề trang - chứa - máy ảnh</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Nội dung tin nhắn</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào nội dung tin nhắn đầu tiên của khách gửi để
        phân phối hội thoại cho agent</td>
      <td style="text-align:left">
        <p>Khi tin nhắn đầu tiên của khách hàng có chứa từ “giá”, cuộc hội thoại
          này sẽ được phân phối cho Agent A.</p>
        <p>Điều kiện: <em>Nội dung tin nhắn - chứa - giá</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Ngôn ngữ trên trình duyệt</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào ngôn ngữ trình duyệt của khách để phân phối
        hội thoại. Ngôn ngữ trên trình duyệt theo chuẩn <a href="http://www.lingoes.net/en/translator/langcode.htm">ISO Language Code</a>,
        ví dụ: vi- VN, en - US.</td>
      <td style="text-align:left">
        <p>Khách hàng sử dụng ngôn ngữ English trên trình sẽ phân phối hội thoại
          cho nhóm agent quốc tế.</p>
        <p>Điều kiện: <em>Ngôn ngữ trên trình duyệt - bằng - en- US</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>User</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Quốc gia</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào Quốc gia của khách hàng để phân phối hội thoại
        cho agent. Tên Quốc gia theo chuẩn quốc tế, <a href="https://countrycode.org/">tham khảo danh sách quốc gia.</a>
        <br
        />Ví dụ: Vietnam, United States</td>
      <td style="text-align:left">
        <p>Khách hàng ở Việt Nam sẽ phân phối hội thoại cho các agent nội địa</p>
        <p>Điều kiện: <em>Quốc gia - bằng - Vietnam </em>
        </p>
        <p><em></em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Mã quốc gia</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào Mã Quốc gia của khách để phân phối hội thoại.
        Mã quốc gia căn cứ theo ISO Code (2 ký tự), viết hoa cả 2 chữ cái. <a href="https://en.wikipedia.org/wiki/ISO_3166-2">Tham khảo danh sách mã quốc gia</a>
        <br
        />Ví dụ: Việt Nam = VN, Mỹ = US, Trung Quốc = CN, Hàn Quốc = KR, Nhật Bản
        = JP.</td>
      <td style="text-align:left">
        <p>Phân phối hội thoại khách hàng nước ngoài cho các agent quốc tế</p>
        <p>Điều kiện: <em>Mã quốc gia - không phải là - VN</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Thành phố</td>
      <td style="text-align:left">
        <p>Dùng khi bạn muốn dựa vào địa chỉ Thành phố của khách để phân phối hội
          thoại. Là tên tiếng Anh của các thành phố, chỉ viết hoa các chữ cái đầu
          tiên của từ. <a href="https://countrycode.org/vietnam">Tham khảo tên Thành phố từng quốc gia</a>
          <br
          />Ví dụ: Hanoi, Ho Chi Minh City, New York, Hong Kong.</p>
        <p></p>
      </td>
      <td style="text-align:left">
        <p>Phân phối hội thoại cho khách hàng đến từ Hà Nội cho agent Hà Nội</p>
        <p>Điều kiện : <em>Thành phố - bằng - Hanoi</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Múi giờ</td>
      <td style="text-align:left">
        <p>Thực hiện phân phối hội thoại dựa trên múi giờ của user. Mã múi giờ được
          căn cứ theo giờ UTC. <a href="https://vi.wikipedia.org/wiki/M%C3%BAi_gi%E1%BB%9D">Tham khảo danh sách múi giờ các khu vực</a>
        </p>
        <p>Ví dụ: Việt Nam và khu vực Đông Nam Á - UTC +7 G</p>
      </td>
      <td style="text-align:left">
        <p>Phân phối hội thoại cho khách hàng đến từ khu vực Đông Nam Á cho agent
          A Đông Nam Á.</p>
        <p>Điều kiện: <em>Múi giờ - bằng - UTC +7 G</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Tên</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào thông tin Họ tên của khách để phân phối hội
        thoại cho agent.</td>
      <td style="text-align:left">
        <p>Phân phối cuộc hội thoại của khách hàng đã có thông tin Họ tên cho Agent
          Dịch vụ</p>
        <p>Điều kiện: <em>Tên  - Không trống</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Địa chỉ email</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào thông tin địa chỉ email của khách để phân phối
        hội thoại cho agent.</td>
      <td style="text-align:left">
        <p>Phân phối cuộc hội thoại của khách hàng đã có địa chỉ email cho Agent
          Kinh doanh</p>
        <p>Điều kiện:<em> Địa chỉ email  - Không trống</em>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Số điện thoại</td>
      <td style="text-align:left">Dùng khi bạn muốn dựa vào thông tin số điện thoại của khách để phân phối
        hội thoại cho agent.</td>
      <td style="text-align:left">
        <p>Phân phối cuộc hội thoại của khách hàng đã có địa chỉ email cho Agent
          Tổng đài</p>
        <p>Điều kiện: <em>Số điện thoại  - Không trống</em>
        </p>
      </td>
    </tr>
  </tbody>
</table>### Bước 3: Chọn cách thức phân phối tới Agent

Bây giờ, bạn chọn cách thức phân phối cuộc các cuộc hội thoại thỏa mãn các điều kiện đã đặt ở trên.

* **Phân phối tới tất cả available agents**: Available agent là những agent đang đăng nhập Subiz trên máy tính hoặc app Subiz trên điện thoại.  Khi các agent không đăng nhập Subiz, cuộc hội thoại của khách chuyển về phân khúc Hội thoại chưa được phân phối. Agent có thể xem và trả lời khách hàng sau khi đăng nhập Subiz.
* **Phân phối tới các agents**: Chọn cụ thể Agent bạn muốn phân phối hội thoại của khách hàng
* **Phân phối tới các nhóm**: Chọn nhóm agent bạn đã tạo để phân phối hội thoại của khách hàng
* **Phân phối tới agent có tương tác cuối cung với khách hàng**: Khi agent đã hỗ trợ khách hàng trước đó, bạn sẽ chọn chỉ định các cuộc hội thoại tiếp theo của khách cho agent tiếp tục chăm sóc và tư vấn.
* **Phân phối cuộc hội thoại đồng đều theo vòng**: Bạn có nhiều agent và muốn chỉ định theo vòng chia đều cuộc hội thoại của khách cho các agent. 

![Rule Ph&#xE2;n ph&#x1ED1;i h&#x1ED9;i tho&#x1EA1;i cho available agent ](../../../.gitbook/assets/rule-moi.jpg)

{% hint style="info" %}
* Rule là cài đặt **bắt buộc** để agent nhận được cuộc chat. Khi bạn xóa Rule mặc định nhưng không tạo Rule mới, tất cả các agent sẽ không nhận tương tác của khách hàng. Lúc này, tất cả hội thoại sẽ nằm trong phân khúc **Hội thoại chưa phân phối** trong phần **Hoạt động**.
* Bạn có thể tạo nhiều Rule và thay đổi Rule theo thời gian, cho phù hợp với số lượng Agent và cách phân chia công việc của doanh nghiệp.
{% endhint %}





