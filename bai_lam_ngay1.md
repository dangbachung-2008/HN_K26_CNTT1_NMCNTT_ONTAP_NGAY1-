# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:**đặng bá chung 
- **Lớp:**cntt1 
- **Link repository:**
- **Hệ điều hành (Windows/macOS):**windowns 

## Phần A. Tổ chức thư mục bằng GUI
  Đổi tên thư mục gốc:
Đổi tên thư mục Trung Tam Tieng Anh FINAL thành trung-tam-tieng-anh.
  Tạo 5 thư mục con bên trong trung-tam-tieng-anh:
docs
media
• data
• logs
• archive
Đổi tên 5 file theo dạng snake_case:
• Logo Trung Tam.PNG ➔ logo_trung_tam.png (hoặc .PNG)
• Anh Lop Hoc.JPG ➔ anh_lop_hoc.jpg (hoặc .JPG)
• Lich Hoc.txt ➔ lich_hoc.txt
• Hoc Vien Khoa 3.xlsx ➔ hoc_vien_khoa_3.xlsx
• Access.log ➔ access.log
 Di chuyển bằng GUI:
• Kéo thả / di chuyển file hoc_vien_khoa_3.xlsx vào thư mục data/.
• Kéo thả / di chuyển file access.log vào thư mục logs/.
 Chuẩn bị file bài làm:
• Sao chép file bai_lam_ngay1.md từ starter-kit/ vào thẳng thư mục gốc trung-tam-tieng-anh/.
• Giữ nguyên file .env tại thư mục gốc trung-tam-tieng-anh/ (không xóa, không upload lên GitHub)


## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

### Các lệnh đã thực hiện (B1 - B7)

- **B1**: `pwd`
- **B2**: `ls -Force`
- **B3**: 
  `mv lich_hoc.txt docs/`
  `mv logo_trung_tam.png media/`
  `mv anh_lop_hoc.jpg media/`
- **B4**: `cp media/logo_trung_tam.png archive/`
- **B5**: 
  `rm temp_201.tmp`
  `rm temp_202.tmp`
- **B6**: 
  `cd logs`
  `ls`
  `cd ..`
- **B7**: 
  `cd docs`
  `cp ../media/anh_lop_hoc.jpg ../archive/`
  `cd ..`

### Kết quả câu B1 (Đường dẫn tuyệt đối)
```text
C:\Users\Admin\Desktop\trung-tam-tieng-anh

Kết quả câu B8 (Liệt kê toàn bộ dự án)
Lệnh sử dụng: Get-ChildItem -Recurse -Force

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        20/10/2026   20:00                archive
d-----        20/10/2026   20:00                data
d-----        20/10/2026   20:00                docs
d-----        20/10/2026   20:00                logs
d-----        20/10/2026   20:00                media
-a-h--        20/10/2026   19:00             32 .env
-a----        20/10/2026   20:30           1200 bai_lam_ngay1.md

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        20/10/2026   20:10          15000 anh_lop_hoc.jpg
-a----        20/10/2026   20:05          25000 logo_trung_tam.png

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        20/10/2026   19:30          12500 hoc_vien_khoa_3.xlsx

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        20/10/2026   19:30            500 lich_hoc.txt

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        20/10/2026   19:30           3400 access.log

    Directory: C:\Users\Admin\Desktop\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        20/10/2026   19:30          15000 anh_lop_hoc.jpg
-a----        20/10/2026   19:30          25000 logo_trung_tam.png
