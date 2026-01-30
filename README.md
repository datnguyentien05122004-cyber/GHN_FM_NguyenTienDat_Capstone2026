## GHN_FM_NguyenTienDat_Capstone2026

Portfolio web giới thiệu hành trình Future Maker tại GHN, tập trung vào việc ứng dụng AI và tự động hóa (Gemini, n8n, Google Sheets, Telegram…) để giải quyết bài toán vận hành NVXL/OTL.

### 1. Công nghệ sử dụng
- **HTML + TailwindCSS CDN**: Xây dựng giao diện responsive, hiện đại.
- **Font Awesome**: Icon cho các phần nội dung.
- **Google Fonts (Inter)**: Font chữ chính.
- **Tài nguyên tĩnh** (trong thư mục `assert`): hình ảnh chân dung, workflow, chứng chỉ, thông báo, video demo.

### 2. Cấu trúc dự án
- **`index.html`**: File web chính, gồm các section:
  - **Header**: Thanh điều hướng cố định.
  - **Profile** (`#profile`): Giới thiệu cá nhân, lộ trình phát triển.
  - **Knowledge Hub** (`#knowledge`): Các công cụ/kiến thức được sử dụng (Vibe Coding, Github, n8n, Gemini, Telegram…).
  - **The Workflow** (`#workflow`): Mô tả vấn đề – giải pháp, workflow n8n, video demo và link trải nghiệm.
  - **Certification** (`#cert`): Chứng nhận Google Gemini Student.
  - **Footer**: Thông tin liên hệ & tagline dự án.
- **`assert/`**: Chứa hình ảnh, video minh họa.

### 3. Cách chạy dự án
- **Cách 1 – Mở trực tiếp**  
  - Mở file `index.html` bằng trình duyệt (Chrome/Edge/Firefox).  
  - Đảm bảo thư mục `assert` nằm cùng cấp với `index.html` để hình ảnh/video hiển thị đúng.

- **Cách 2 – Chạy qua server tĩnh (khuyến nghị)**  
  Dùng một trong các cách sau để tránh lỗi tải tài nguyên khi deploy:
  - Dùng **VSCode Live Server** hoặc tiện ích tương tự.
  - Hoặc dùng Python:
    ```bash
    cd D:\download\GHN_FM_NguyenTienDat_Capstone2026
    python -m http.server 8000
    ```
    Sau đó truy cập `http://localhost:8000` và mở `index.html`.

### 4. Deploy lên Github Pages (gợi ý)
- Đưa toàn bộ thư mục lên một repository GitHub.
- Trong phần **Settings → Pages**, chọn source là branch `main` (hoặc `master`) và root là `/` (không cần build).
- Sau khi GitHub tạo link, bạn có thể dùng đường dẫn này làm portfolio online.

### 5. Ghi chú thêm
- Các link ngoài như workflow n8n, video demo (`assert/demo.mp4`) được nhúng trực tiếp từ project.
- Nếu đổi tên thư mục hoặc file, cần cập nhật lại đường dẫn trong `index.html`.



