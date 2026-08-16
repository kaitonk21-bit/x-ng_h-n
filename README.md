# Xưởng Hàn Thép

Website giới thiệu dịch vụ gia công và hàn kết cấu thép, được xây dựng bằng React và Vite. Giao diện tiếng Việt, responsive trên desktop/mobile, có portfolio công trình, bộ lọc dự án, lightbox, form tính báo giá nhanh và form liên hệ.

## Chạy local

```bash
pnpm install
PORT=5173 BASE_PATH=/ pnpm --filter @workspace/xuong-han-thep run dev
```

Mở `http://localhost:5173`.

## Build production

```bash
PORT=5173 BASE_PATH=/ pnpm --filter @workspace/xuong-han-thep run build
```

File build nằm trong `artifacts/xuong-han-thep/dist/public`.

## Tuỳ chỉnh nội dung

- Nội dung và tương tác chính: `artifacts/xuong-han-thep/src/App.tsx`
- Màu sắc, font và responsive styles: `artifacts/xuong-han-thep/src/index.css`
- Ảnh dự án: `artifacts/xuong-han-thep/attached_assets/`
- Favicon và robots: `artifacts/xuong-han-thep/public/`

Các thông tin mẫu như tên xưởng, số điện thoại, địa chỉ và nội dung dự án có thể thay trực tiếp trong `App.tsx` trước khi đẩy lên GitHub.