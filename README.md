# TIẾNG TRUNG MIA — Gói hoàn chỉnh

## Bản chạy để upload hosting

Các tệp ở thư mục gốc của gói (`index.html`, `assets/`, `mia-logo.png` và các tài nguyên đi kèm) là bản production đã build.

Để triển khai, tải toàn bộ nội dung ở thư mục gốc lên thư mục website của hosting, giữ nguyên cấu trúc thư mục.

## Mã nguồn

Thư mục `source-code/` chứa mã React/Vite đầy đủ.

Chạy local:

```bash
npm install
npm run dev
```

Tạo lại bản production:

```bash
npm run build
```

Kết quả build nằm trong thư mục `dist/`.
