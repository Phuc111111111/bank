# đây là một dự án về ứng dụng java, quản lý ngân hàng
1.1. Mô tả ứng dụng

Phần mềm ngân hàng cho phép quản trị ngân hàng quản lý danh sách khách hàng, tạo tài khoản ATM cho từng khách hàng, cho phép chuyển tiền giữa các tài khoản và rút tiền, tra cứu lịch sử giao dịch.

1.2.  Thiết kế giao diện
Yêu cầu giao diện dạng console đơn giản.
Hiển thị thông tin thành khối rõ ràng và dễ nhìn.

1.3.  Yêu cầu chức năng cơ bản

Khi chương trình được khởi chạy đầu tiên sẽ hiển thị mô tả ngắn gọn về chương trình để người dùng hiểu được hệ thống này sẽ hoạt động thế nào, có chức năng gì ví dụ như hiển thị tên phần mềm viết in hoa: NGAN HANG SO

Hiển thị tên tác giả (mã số học viên) và phiên bản (version) phần mềm theo mẫu: FX123456@v4.0.0 (FX123456 là mã số học viên, 4.0.0 là phiên bản phần mềm).

Hiển thị đường phân cách giữa tiêu đề và nội dung chức năng.

Hiển thị menu cho người dùng chọn theo mẫu ví dụ.
1. Xem danh sách khách hàng
2. Nhập danh sách khách hàng
3. Thêm tài khoản ATM
4. Chuyển tiền
5. Rút tiền
6. Tra cứu lịch sử giao dịch

0. Thoát

1.4 tổng quan chi tiết các chức năng của hệ thống
chương trình thao tác trên nhiều khách hàng.

Chức năng xem danh sách khách hàng sẽ hiển thị ra tất cả các khách hàng có trong ngân hàng bằng cách đọc danh sách khách hàng từ một tệp nhị phân (Ví dụ: customers.dat).

Chức năng nhập danh sách khách hàng sẽ đọc danh sách khách hàng từ tệp text (VD: customers.txt) sau đó kiểm tra các dữ liệu khách hàng trong file có hợp lệ hay không rồi thêm từng khách hàng vào danh sách khách hàng hiện có (lưu trong file customers.dat). Chức năng này giống với các chức năng import dữ liệu từ file vào hệ thống. Học viên có thể lưu dữ liệu khách hàng để import vào dưới dạng dữ liệu con người có thể đọc được ở định dạng bất kỳ (vd: txt, json, csv, …).

Chức năng thêm tài khoản ATM , lưu tài khoản vào mảng thì sẽ lưu các tài khoản vào một tệp nhị phân (Ví dụ: accounts.dat).

Chức năng chuyển tiền, rút tiền sẽ tạo ra các giao dịch thêm tiền và trừ tiền, thay vì lưu vào mảng thì sẽ lưu tất cả các giao dịch vào một tệp nhị phân (Ví dụ: transactions.dat).

Chức năng rút tiền sẽ cập nhật số dư tài khoản và tạo ra một giao dịch rút tiền.

Chức năng chuyển tiền sẽ cập nhật số dư tài khoản và tạo giao dịch rút tiền cho tài khoản gửi và tài khoản nhận

Chức năng tra cứu lịch sử giao dịch sẽ hiển thị tất cả các giao dịch của tất cả các tài khoản của một khách hàng, từ mã số của khách hàng bạn sẽ phải đọc file và lấy ra những tài khoản và giao dịch tương ứng.
