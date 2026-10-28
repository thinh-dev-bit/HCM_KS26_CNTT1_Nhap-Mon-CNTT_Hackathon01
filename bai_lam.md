# BÀI LÀM – HACKATHON 01

- **Mã đề:** 13
- **Họ tên: Trinh Phu Thinh** 
- **Lớp:HCM_KS26_CNTT1** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Window** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
mv thoi_khoa_bieu.txt docs/
mv logo_trung_tam_ngoai_ngu.png media/
cp media/logo_trung_tam_ngoai_ngu.png backup/
rm temp_213.tmp
cd ./logs
ls -Force

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           1117 course.log


PS C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\logs> cd ..
PS C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website> Get-ChildItem -Recurse -Force


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   8:25 AM                backup
d-----        10/28/2026   8:05 AM                data
d-----        10/28/2026   8:23 AM                docs
d-----        10/28/2026   8:07 AM                logs
d-----        10/28/2026   8:24 AM                media
------        10/27/2026   1:31 AM             68 .env
-a----        10/27/2026   1:31 AM           2227 bai_lam.md


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           4365 logo_trung_tam_ngoai_ngu.png


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           6109 dang_ky_hoc_thang_3.xlsx


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM             67 thoi_khoa_bieu.txt


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           1117 course.log


    Directory: C:\Users\thien\Downloads\starter-kit\starter-kit\ngoai-ngu-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           4365 logo_trung_tam_ngoai_ngu.png

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
Get-Content logs/course.log |Select-String "ERROR"

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-03-28 08:24:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:30:28 [ERROR] Het thoi gian cho (timeout)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dang_ky_hoc_thang_3.xlsx`, không cần ghi vào đây.
