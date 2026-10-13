# Dự Án Tối Ưu Hóa CSS Sử Dụng SASS Variables & Mixins

Dự án thực hành chuyển đổi file CSS truyền thống sang SCSS nhằm giảm lặp code và dễ dàng quản lý giao diện thông qua:
- **Variables**: Kiểm soát màu sắc (`$primary-color`, `$text-color`), kích thước font chữ (`$font-large`, `$font-medium`), và hiệu ứng đổ bóng.
- **Mixins**: Tái sử dụng style nút bấm (`@mixin button-style`) và kiểu dáng khung chứa (`@mixin box-style`).
- **Modular Structure**: Tách nhỏ mã nguồn theo cấu trúc thư mục `abstracts`, `base`, `components`.

## Lệnh Biên Dịch SASS

```bash
sass scss/main.scss css/main.css --watch
