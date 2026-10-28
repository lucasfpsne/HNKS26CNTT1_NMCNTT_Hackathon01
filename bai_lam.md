# BÀI LÀM – HACKATHON 01

- **Mã đề:** 18
- **Họ tên:Nguyễn Đặng Hoàng Minh** 
- **Lớp:HNKS26-CNTT1** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Windows** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
pwd
get-childitem -recurse -force
mv .\Kich_Thuoc.txt .\docs\
mv .\Logo_Noi_That.PNG .\media\
cp .\media\Logo_Noi_That.PNG .\backup\
rm .\temp_267.pmt
cd .\logs
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
 Directory: D:\Rikkei Lms Connect\starter-kit\starter-kit\noi-that-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   8:07 AM                backup
d-----        10/28/2026   8:15 AM                data
d-----        10/28/2026   8:07 AM                docs
d-----        10/28/2026   8:15 AM                logs
d-----        10/28/2026   8:07 AM                media
------        10/27/2026   1:32 AM             68 .env
-a----        10/27/2026   1:32 AM             53 Kich_Thuoc.txt
-a----        10/27/2026   1:32 AM           4403 Logo_Noi_That.PNG
------        10/27/2026   1:32 AM             22 temp_267.tmp


    Directory: D:\Rikkei Lms Connect\starter-kit\starter-kit\noi-that-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6121 Don_Noi_That_Quy_1.xlsx


    Directory: D:\Rikkei Lms Connect\starter-kit\starter-kit\noi-that-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1028 Furniture.log

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
Get-Content .\Furniture.log | select-string "ERROR" >daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-01-28 07:35:33 [ERROR] Dat coc bi tu choi
2026-01-28 07:47:33 [ERROR] Dat coc bi tu choi
```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
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

> Phần Excel được chấm trực tiếp trên file `data/don_noi_that_quy_1.xlsx`, không cần ghi vào đây.
