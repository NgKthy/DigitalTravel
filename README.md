# 🌍 Digital Travel

> Hệ thống dành cho các công ty lữ hành, quản lý toàn bộ quy trình từ tour mẫu, đặt chỗ, thanh toán, vận hành đến quyết toán tài chính.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?logo=php)](https://php.net)
[![Laravel Version](https://img.shields.io/badge/Laravel-11.x-FF2D20?logo=laravel)](https://laravel.com)
[![MySQL Version](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql)](https://mysql.com)
[![React Version](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)](https://reactjs.org)
[![JWT Auth](https://img.shields.io/badge/Auth-JWT-000000?logo=jsonwebtokens)](https://jwt.io)

---

## 🏗️ Tổng quan

**Digital Travel ERP** là một hệ thống quản trị toàn diện dành cho các doanh nghiệp lữ hành, cung cấp các công cụ để quản lý:

- Quy trình tạo và vận hành tour du lịch
- Đặt chỗ và thanh toán trực tuyến
- Quản lý khách hàng, nhân viên và vai trò
- Theo dõi chi phí và quyết toán tour
- Đánh giá và khiếu nại sau chuyến đi

**Dự án này là phiên bản chuyển đổi hoàn chỉnh từ hệ thống gốc (Java Spring Boot + Oracle), được tái thiết kế với công nghệ hiện đại hơn, đảm bảo bảo toàn 100% nghiệp vụ và dữ liệu.** Frontend React được giữ nguyên, chỉ thay đổi backend và cơ sở dữ liệu.

---

## 🧬 Công nghệ sử dụng (Tech Stack)

| Thành phần | Công nghệ |
|------------|-----------|
| **Frontend** | React |
| **Backend** | PHP Laravel |
| **Database** | MySQL |
| **Authentication** | JWT (HS256) |

---

## 🧩 Chức năng chính

Hệ thống được phân chia thành các module nghiệp vụ dựa trên vai trò người dùng:

### 👑 Quản trị 
- Toàn quyền quản lý hệ thống
- Quản lý tài khoản và phân quyền
- Giám sát nhật ký hệ thống
- Cấu hình tham số hệ thống

### 🏷️ Sản phẩm 
- Quản lý **tour mẫu**: thêm, sửa, xóa, sao chép tour
- Quản lý **lịch trình**
- Quản lý **dịch vụ bổ sung**
- Quản lý **hành động xanh** để tích điểm

### 💼 Kinh doanh 
- Xử lý **đơn đặt tour**: xác nhận, hủy, hoàn tiền
- Quản lý **voucher** và chương trình khuyến mãi
- Xử lý **khiếu nại & yêu cầu hỗ trợ**
- Quản lý danh sách khách hàng

### 🚌 Điều hành 
- Quản lý **tour thực tế**: khởi tạo đợt tour từ tour mẫu
- Quản lý **nhân viên** và năng lực 
- **Phân công** hướng dẫn viên cho tour
- **Điểm danh** hành khách và người đi cùng
- Ghi nhận **sự cố** trong tour

### 👤 Khách hàng
- Đăng ký / Đăng nhập
- Xem danh sách tour công khai
- Đặt tour, thanh toán 
- Xem lịch sử đặt tour và tích điểm "Hành động xanh"
- Đánh giá tour sau khi kết thúc 
- Sử dụng voucher

### 📊 Kế toán 
- Theo dõi **giao dịch**
- Quản lý **chi phí thực tế**
- Xử lý **quyết toán tour**

---

## 🗺️ Sơ đồ luồng nghiệp vụ tổng quan
