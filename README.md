Hotel Management Application
Ứng dụng quản lý khách sạn được phát triển bằng Python với giao diện desktop sử dụng Tkinter và MySQL làm cơ sở dữ liệu. Hướng dẫn này sẽ giúp bạn cài đặt XAMPP, import cơ sở dữ liệu MySQL và chạy ứng dụng.

Yêu cầu hệ thống:
Windows 7/8/10/11
Python 3.x
XAMPP (để quản lý MySQL server)
1. Cài đặt XAMPP
Bước 1: Tải XAMPP
Truy cập trang web chính thức của XAMPP: https://www.apachefriends.org/download.html
Tải phiên bản XAMPP phù hợp với hệ điều hành của bạn (Windows).
Bước 2: Cài đặt XAMPP
Sau khi tải về, khởi chạy file cài đặt của XAMPP.
Chọn thành phần MySQL khi cài đặt. Bạn có thể bỏ chọn các thành phần khác nếu không cần thiết.
Bước 3: Chạy MySQL Server
Mở XAMPP Control Panel và nhấn nút Start cho MySQL.
2. Import cơ sở dữ liệu MySQL
Bước 1: Mở phpMyAdmin
Mở trình duyệt và truy cập http://localhost/phpmyadmin.
Trong phpMyAdmin, nhấp vào tab Databases.
Bước 2: Tạo cơ sở dữ liệu mới
Tạo một cơ sở dữ liệu mới với tên (ví dụ: hotel_management_db).
Nhấp vào Create để tạo cơ sở dữ liệu.
Bước 3: Import file SQL
Sau khi tạo cơ sở dữ liệu, chọn cơ sở dữ liệu mới vừa tạo từ danh sách.
Chọn tab Import.
Nhấp vào Choose File, sau đó chọn file SQL đi kèm trong bộ cài đặt ứng dụng (ví dụ: manager_booking_hotel.sql).
Nhấn Go để import cơ sở dữ liệu.
Bước 4: Kiểm tra dữ liệu
Sau khi import thành công, bạn sẽ thấy các bảng xuất hiện trong cơ sở dữ liệu của bạn.
3. Chạy ứng dụng
Bước 1: Cài đặt ứng dụng
Sau khi download bộ cài đặt HotelManagementSetup.exe, mở file đó và làm theo các hướng dẫn để cài đặt ứng dụng lên máy tính của bạn.
Bước 2: Chạy ứng dụng
Sau khi cài đặt hoàn tất, bạn sẽ thấy một shortcut cho ứng dụng trong Start Menu hoặc Desktop với tên Hotel Management.
Nhấn vào shortcut này để mở ứng dụng.
Bước 3: Đăng nhập
Ứng dụng sẽ mở với trang đăng nhập. Bạn có thể đăng nhập bằng tài khoản admin hoặc guest.
Admin: quản lý phòng, báo cáo doanh thu.
Guest: đặt phòng và xem lịch sử đặt phòng.
