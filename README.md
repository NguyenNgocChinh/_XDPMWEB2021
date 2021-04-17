# BÁO CÁO MÔN HỌC XÂY DỰNG PHẦN MỀM WEB

## Thành Viên Nhóm:

| Tên Thành Viên | MSSV  | Lớp  |
| :-----: | :-: | :-: |
| Nguyễn Ngọc Chinh | DH51703173 | D17_TH07 |
| Nguyễn Văn Mạnh | DH51703733 | D17_TH07 |
| Phạm Minh Hùng | DH51703468 | D17_TH07 |
| Trần Thị Ngọc Nhật | DH51705101 | D17_TH07 |
| Nguyễn Thị Bích Nhụy | DH51703915 | D17_TH07 |

## Source code 
1. Front End 
2. Back End
## Database
1. sunhouse.sql
## BÁO CÁO
1. Project Chính + API
2. SEO
  * File Word
  * GOOGLE DOCS: [LINK DẪN TỚI GOOGLE DOCS](https://docs.google.com/document/d/1wYaI5LnkpAqkTpg3qPL-PMgFXS5ZgAs4-fX5B6J7kcM/edit?usp=sharing)
 
 ## Hướng dẫn chạy Project Back End (API)
 #### Yêu cầu 
  * `GD Extension` trong php.ini
  * `Composer` được cài đặt
  
 #### Các bước khởi tạo
 1. `composer install` để cài đặt các packages cần thiết
 2. Thay đổi `Tên database` trong file `.env`
 3. Chạy file database hoặc dùng `php artisan migrate --seed` để tạo các bảng và tạo dữ liệu ảo cho các bảng
 4. Sau khi mọi thứ hoàn tất chạy `php artisan serve` để khởi chạy project.


 ## Hướng dẫn chạy Project Front End
 #### Yêu cầu
 * Có cài đặt `NodeJS`
 
 #### Các bước khởi tạo
 1. `npm install` để cài các packages
 2. `npm run dev` để start project
