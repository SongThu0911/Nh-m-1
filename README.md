# Nhom1
Tính chất của lập trình hướng đối tượng
1.Tính đóng gói (Encapsulation)
Gom dữ liệu và các phương thức xử lý dữ liệu vào cùng một đối tượng.
Che giấu dữ liệu bên trong, chỉ cho phép truy cập thông qua các phương thức cần thiết.
Ví dụ: thuộc tính soDu của tài khoản ngân hàng được đặt private, muốn thay đổi phải thông qua phương thức napTien().
2.Tính kế thừa (Inheritance)
Một lớp có thể kế thừa thuộc tính và phương thức từ lớp khác.
Giúp tái sử dụng code và tạo mối quan hệ giữa các lớp.
Ví dụ: lớp SinhVien có thể kế thừa từ lớp Nguoi.
3.Tính đa hình (Polymorphism)
Cùng một phương thức nhưng có thể có cách thực hiện khác nhau tùy đối tượng.
Thường thể hiện qua ghi đè (override) và nạp chồng (overload).
Ví dụ: cho.keu() phát ra "Gâu gâu", còn meo.keu() phát ra "Meo meo".
Tính trừu tượng (Abstraction)
Chỉ thể hiện những đặc điểm cần thiết và ẩn đi chi tiết cài đặt không quan trọng.
Giúp chương trình dễ sử dụng và dễ quản lý.
Ví dụ: khi gọi xe.khoiDong(), người dùng không cần biết chi tiết động cơ hoạt động bên trong như thế nào.
