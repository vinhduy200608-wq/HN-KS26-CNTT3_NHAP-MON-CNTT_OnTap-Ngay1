# BÀI LÀM – ÔN TẬP NGÀY 1

-   **Họ tên:**Nguyễn Công Vinh

-   **Lớp:**Cntt3

-   **Link repository:**https://github.com/vinhduy200608-wq/HN-KS26-CNTT3_NHAP-MON-CNTT_OnTap-Ngay1.git

-   **Hệ điều hành (Windows/macOS):**macos

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```
 pwd
ls -la
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..
```

### Kết quả B1 (pwd)

```
  /Users/ten_user/Desktop/trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```
.:
.
..
.env
archive
data
docs
logs
bai_lam_ngay1.md
anh_lop_hoc.jpg
logo_trung_tam.png
lich_hoc.txt

./archive:
.
..
logo_trung_tam.png
anh_lop_hoc.jpg

./data:
.
..
hoc_vien_khoa_3.xlsx

./docs:
.
..
lich_hoc.txt
anh_lop_hoc.jpg

./logs:
.
..
access.log
```

## Tự chấm (điền sau khi có đáp án)

-   **Điểm tự chấm:**  ..../100

-   **Lỗi mình đã mắc và cách sửa:**