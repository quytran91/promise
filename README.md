# Quy Luật và Lời Hứa — trang đọc tiếng Việt

Trang đọc phong cách *The Power (Sức Mạnh)*: nền tối, hình động SVG, emoji Apple, tối ưu cho iPhone.

## Cấu trúc thư mục

```
├── index.html              # Mục lục sách: danh sách chương, thanh tiến độ, nút "Đọc tiếp"
├── chuong-01.html          # Chương 1 · Quy Luật: Tưởng Tượng Tạo Ra Hiện Thực
├── chuong-02.html          # Chương 2 · Hãy Sống Trong Đó
├── chuong-03.html          # Chương 3 · Quay Ngược Bánh Xe Thời Gian
├── chuong-04.html          # Chương 4 · Không Có Gì Là Hư Cấu
├── images/                 # Ảnh bìa từng chương: chuong-01.jpg, chuong-02.jpg, …
├── icons/                  # Icon app (192, 512, apple-touch, favicon)
├── manifest.webmanifest    # "Thêm vào Màn hình chính" như một app
├── 404.html                # Link sai sẽ tự quay về mục lục
└── .nojekyll               # Để GitHub Pages phục vụ file nguyên trạng
```

Mỗi trang chương là một file tự chứa (CSS, JS, emoji, hình động nằm sẵn bên trong);
chỉ ảnh bìa và icon nằm ngoài.

## Đưa lên GitHub Pages (GitHub Desktop)

1. Copy toàn bộ nội dung thư mục này vào một repo (hoặc một thư mục con trong repo đã bật Pages).
2. GitHub Desktop: **Commit to main** → **Push origin**.
3. Repo mới: *Settings → Pages* → *Deploy from a branch* → `main` / `(root)` → Save.
4. Vài phút sau trang có ở https://quytran91.github.io/promise/

## Cập nhật

Khi có chương mới hoặc ảnh bìa mới, chỉ cần thay cả thư mục bằng bản mới rồi commit/push lại.
Vị trí đọc, chữ đã tô bút và cỡ chữ được lưu riêng trên từng máy (trình duyệt), không mất khi cập nhật.
