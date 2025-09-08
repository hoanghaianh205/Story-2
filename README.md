# Story-2
# Module 2 – Building Web Applications with Laravel

## 1. Routing (Định tuyến)
- Quản lý URL và ánh xạ đến Controller hoặc Closure.
- Khai báo route trong `routes/web.php`.
- Các phương thức: GET, POST, PUT, DELETE.
- Route Parameters & Route Model Binding.

## 2. Controllers (Bộ điều khiển)
- Điều phối logic giữa Model và View.
- Tạo controller: `php artisan make:controller`.
- RESTful controllers: `index`, `show`, `create`, `store`, `edit`, `update`, `destroy`.

## 3. Views (Giao diện hiển thị)
- View đặt trong thư mục `resources/views`.
- Blade template engine (`{{ }}`, `@directive`).
- Layouts và Template inheritance: `@extends`, `@section`, `@yield`.

## 4. Migrations (Quản lý CSDL)
- Quản lý schema bằng migration.
- Tạo migration: `php artisan make:migration`.
- Các kiểu cột: `string`, `integer`, `boolean`, `timestamps`.
- Chạy & rollback:
- `php artisan migrate`
- `php artisan migrate:rollback`

## 5. Eloquent ORM (Làm việc với dữ liệu)
- ActiveRecord cho PHP, ánh xạ Model ↔ Bảng.
- CRUD cơ bản:
- `Model::all()`
- `Model::find(id)`
- `Model::create([...])`
- `$model->update([...])`
- `$model->delete()`
- Quan hệ: One-to-One, One-to-Many, Many-to-Many.

## 6. Middleware
- Lọc request trước khi vào Controller.
- Ứng dụng: xác thực đăng nhập, kiểm tra quyền hạn, logging.
- Tạo middleware: `php artisan make:middleware`.
- Đăng ký trong `app/Http/Kernel.php`.

## 7. Authentication (Xác thực)
- Cấu hình login, register với Laravel.
- Sử dụng `Auth` facade, middleware `auth`.
- Quản lý session, bảo vệ route yêu cầu login.

---
