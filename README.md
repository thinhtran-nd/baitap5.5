# baitap5.5
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI TẬP 5.5: HỆ THỐNG QUẢN LÝ QUY TRÌNH XUẤT - NHẬP KHO NGUYÊN VẬT LIỆU (INVENTORY MANAGEMENT)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="969" height="696" alt="GD" src="https://github.com/user-attachments/assets/3160da1c-1612-4cb5-8a43-8dc263c24911" />


- Giao diện phần quản lí/cảnh báo tồn kho
<img width="965" height="692" alt="CN1" src="https://github.com/user-attachments/assets/eefe142a-a739-49cb-bdd1-f4c8a5f467f1" />


- Lỗi khi nhập dữ liệu kho khi chưa có mặt hàng nào
<img width="968" height="695" alt="CN2" src="https://github.com/user-attachments/assets/1a26a36f-9e45-4ad1-a0b7-4e3b60d78856" />


- Thêm các mặt hàng vào phiếu
<img width="973" height="690" alt="CN3" src="https://github.com/user-attachments/assets/25cee432-1618-4df9-858d-f2957ebb7458" />


- Xác nhận lưu trữ mặt hàng vào phiếu
<img width="964" height="689" alt="KQ" src="https://github.com/user-attachments/assets/862d3b74-a6f7-4256-8575-cc2ba60d451a" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `InventoryDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
