# Thực hành SASS Variables & Mixins

Ví dụ này tách stylesheet thành các partial để quản lý biến và tái sử dụng
kiểu dáng bằng mixins.

## Cấu trúc

- `scss/abstracts/_variables.scss`: màu sắc, cỡ chữ, khoảng cách và đổ bóng.
- `scss/abstracts/_mixins.scss`: mixins cho nút bấm và thẻ nội dung.
- `scss/base/_typography.scss`: kiểu chữ cho trang và các tiêu đề.
- `scss/components/_buttons.scss`: áp dụng mixin cho nút bấm.
- `scss/components/_cards.scss`: áp dụng mixin cho thẻ nội dung.
- `scss/main.scss`: entry point kết hợp các partial.
- `css/style.css`: stylesheet đã biên dịch để trang HTML sử dụng.

## Chạy thử

Cần cài Node.js. Chạy các lệnh sau ở thư mục dự án:

```sh
npm install
npm run build
```

Mở `index.html` trong trình duyệt để xem kết quả. Khi chỉnh sửa SCSS,
dùng `npm run watch` để tự động biên dịch CSS.
