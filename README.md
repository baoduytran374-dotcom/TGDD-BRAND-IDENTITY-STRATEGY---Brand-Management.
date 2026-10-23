# Dashboard – Chiến lược trẻ hóa thương hiệu Thế Giới Di Động (Nhóm 1)

Trang dashboard tĩnh (HTML, CSS, JavaScript), không cần cài đặt hay chạy máy chủ.

## Cấu trúc thư mục
```
index.html              Trang chính
.nojekyll               Báo cho GitHub Pages không xử lý bằng Jekyll
assets/css/style.css    Giao diện (kèm khai báo font)
assets/js/app.js        Biểu đồ, hiệu ứng rê chuột, chuyển tab
assets/js/chart.umd.js  Thư viện Chart.js 4.4.1 (giấy phép MIT, xem chart.js-LICENSE.md)
assets/fonts/           Font Be Vietnam Pro (giấy phép SIL OFL)
assets/img/             Ảnh minh họa, key visual, poster
```

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ `tgdd-dashboard`).
2. Tải toàn bộ nội dung thư mục này lên repository, giữ nguyên cấu trúc. `index.html` phải nằm ở thư mục gốc.
3. Vào **Settings → Pages**. Ở mục **Build and deployment**, chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/ (root)`, bấm **Save**.
4. Chờ 1–2 phút, trang sẽ có địa chỉ dạng `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Xem thử trên máy
Bấm đúp `index.html` là xem được. Nếu trình duyệt chặn font hoặc ảnh khi mở trực tiếp, chạy:
`python3 -m http.server 8000` trong thư mục này rồi mở `http://localhost:8000`.

## Lưu ý
- Số liệu và nội dung lấy từ báo cáo Nhóm 1 (khảo sát 124 phản hồi, TP. HCM). Ngân sách 3 tỷ đồng và mức ưu đãi là giả định minh họa, không phải chính sách hay báo giá chính thức của Thế Giới Di Động.
- Poster, logo và key visual thuộc về nhóm thực hiện và thương hiệu liên quan; chỉ dùng cho mục đích học tập.
