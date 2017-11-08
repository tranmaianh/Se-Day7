**- Bài Toán: Quản lý khách sạn.**

*Khách hàng đến dặt hàng chúng ta xây dựng một phần mềm quản lí khách sạn với yêu cầu như sau (đây có thể coi như là một bản mô tả yêu cầu của khách hàng bằng ngôn ngữ tự nhiên):*

- Phần mềm dạng ứng dụng cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng

- Nhân viên lễ tân có thể tìm phòng trống theo yêu cầu trực tiếp của khách, checkin cho khách đã đặt phòng hoặc đặt phòng trực tiếp, checkout cho khách và in hóa đơn thanh toán cho khách

- Nhân viên bán hàng có thể tìm phòng trống và đặt phòng theo yêu cầu của khách.

- Quản lí có thể: thêm/sửa/xóa thông tin phòng, xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng, xem báo cáo tỉ lệ phòng trống theo thời gian/theo phòng/theo loại phòng, xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng.

- Thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả (bao gồm mô tả bằng text và bằng hình ảnh).

- Trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.

- Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...

- Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.

- Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.

- Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.

- Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.

- Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.

- Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán.

- Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo.
### 1. Mục tiêu của đề tài:
- Xây dựng một hệ thống phần mềm quản lí khách sạn chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng.
- Hỗ trợ nhân viên lễ tân có thẻ tìm phòng trống theo yêu cầu trực tiếp của khách, checkin cho khách đã đặt phòng hoặc đặt phòng trực tiếp, checkout cho khách và in hóa đơn thanh toán cho khách.
-	Nhân viên bán vé có thể dễ dàng cập nhật khách hàng gọi điện thoại đến đặt vé.
-	Hệ thống hỗ trợ phân quyền người dùng, đảm bảo tính bảo mật, an toàn của hệ thống.
-	Giúp nhân viên bán hàng có thẻ tìm phòng trông và đặt phòng theo yêu cầu của khách.
- Quản lí có thể : thêm/sửa/xóa thông tin phòng, xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng, xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng.
- Mỗi khách hàng có thể đặt/ ở nhiều phòng khác nhau tại những thời điểm khác nhau, khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.Khách hàng có thể hủy đặt phòng (miễn phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu và danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo.
- Người quản lí khách sạn: quản lí thông tin phòng và khách sạn, tạo và xem các loại báo cáo.
- Nhân viên tiếp tân: giao dịch với khách hàng qua điện thoại đặt chỗ hoặc hủy đặt chỗ. 
### 2. Goals
- Quản lý thông tin khách hàng.
- Quản lý thông tin phòng, khách sạn.
- Đặt phòng, hủy đặt phòng.
- Thanh toán cho khách hàng.
- Quản lý báo cáo : xem báo cáo, tạo hóa đơn,...
### 2. Business Objectives
**2.1 Quản lý thông tin phòng,thông tin khách sạn.**
 <ul>
 <li>Tìm đặt phòng theo yêu cầu</li>
 <li>Thêm/sửa/xóa thông tin phòng</li>
 <li>Thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả (bao gồm mô tả bằng text và bằng hình ảnh). </li>
 <li> Trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.</li>
 </ul>
 
**2.2 Quản lý thông tin khách hàng.**
 <ul>
 <li>*Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm:*</li>
 <li>Số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport)</li>
 <li>Họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...</li>
 </ul>
 
 **2.3 Đặt phòng, hủy đặt phòng.**
 <ul>
 <li>Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt. Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến</li>
 <li>Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo Khách hàng có thể đặt nhiều phòng</li>
 </ul>
 
**2.4 Thanh toán cho khách hàng.**
 <ul>
 <li>*Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin:*</li>
 <li>Họ tên và địa chỉ khách hàng</li>
 <li>Số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán</li>
 <li>Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng</li>
 </ul>
 
**2.5 Quản lý báo cáo:**
 <ul>
 <li>Xem báo cáo</li>
 <li> tạo báo cáo</li>
 <li>Báo cáo thu chi Báo cáo số lượng khách hàng theo tháng/quý/năm....</li>
 </ul>

