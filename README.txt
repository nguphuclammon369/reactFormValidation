# React Form Validation Redux - FIXED

Bản này sửa lỗi chức năng Sửa/Cập nhật.

Điểm quan trọng:
- Khi bấm Sửa, `editingId` lưu mã của dòng cũ.
- Khi bấm Cập nhật, Redux nhận:
  - `originalId`: mã của dòng cũ
  - `student`: dữ liệu mới
- Reducer dùng `originalId` để tìm đúng dòng rồi thay bằng dữ liệu mới.
- Vì vậy có thể sửa Họ tên, Số điện thoại, Email và cả Mã SV.
- Có kiểm tra không cho đổi sang Mã SV đã tồn tại.

Chức năng:
- Thêm
- Xóa
- Sửa
- Cập nhật
- Validation
- Search bằng filter()
- Redux
- componentDidUpdate()

Chạy:
1. Giải nén.
2. Mở thư mục bằng VS Code.
3. Mở `index.html`.
4. Chuột phải -> Open with Live Server.
