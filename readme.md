# Blog CRUD

Dự án **Blog CRUD** là một ứng dụng web đơn giản cho phép người dùng thực hiện các thao tác cơ bản trên bài viết như tạo, đọc, cập nhật và xóa (CRUD). Ứng dụng được xây dựng bằng **Node.js**, **Express**, **MongoDB**, và sử dụng **EJS** để render giao diện.

## Tính năng chính

- Hiển thị danh sách các bài viết.
- Thêm bài viết mới.
- Chỉnh sửa bài viết hiện có.
- Xóa bài viết.

## Công nghệ sử dụng

- **Node.js**: Nền tảng JavaScript phía server, giúp xây dựng ứng dụng nhanh chóng và hiệu quả.
- **Express**: Framework web mạnh mẽ để xử lý routing và xây dựng API.
- **MongoDB**: Cơ sở dữ liệu NoSQL để lưu trữ dữ liệu bài viết.
- **Mongoose**: Thư viện ODM giúp tương tác dễ dàng với MongoDB.
- **EJS**: Template engine để render giao diện động.
- **AdminLTE**: Giao diện quản trị hiện đại và thân thiện.

## Hướng dẫn cài đặt và chạy dự án

1. **Cài đặt các phụ thuộc**:
   ``` npm install ```
2. **Cấu hình cơ sở dữ liệu**:

    Đảm bảo bạn đã cài đặt và chạy MongoDB trên máy.
    Tạo file .env và thêm thông tin kết nối MongoDB:

    ```MONGO_URI=mongodb://localhost:27017/blog-crud ```

3. **Chạy ứng dụng:**:
```npm start```

4. **Truy cập ứng dụng:**:
    Mở trình duyệt và truy cập: http://localhost:3000