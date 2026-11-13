# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.8: HỆ THỐNG QUẢN LÝ BÀN BIDA & DỊCH VỤ GIẢI TRÍ
(BILLIARDS CLUB MANAGEMENT SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1003" height="640" alt="Screenshot 2026-11-13 184010" src="https://github.com/user-attachments/assets/bda8a9dc-6897-4d4d-8a04-f7c84abe3178" />

- Giao diện khi bắt đầu mở bàn
<img width="1010" height="648" alt="Screenshot 2026-11-13 184027" src="https://github.com/user-attachments/assets/93ed2740-ab98-4e9b-80a4-cbfe05081636" />

- Thêm món của bàn đang mở
<img width="1002" height="646" alt="Screenshot 2026-11-13 184036" src="https://github.com/user-attachments/assets/163f305c-e601-4af0-aea7-566de8208ad2" />

- Thanh toán thành công
<img width="1004" height="642" alt="Screenshot 2026-11-13 184043" src="https://github.com/user-attachments/assets/96694d92-7770-426a-a255-e509e2d04092" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `BillardsDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
