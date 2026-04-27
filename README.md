# 👨‍💻 Portfolio Cá Nhân | Nguyễn Tuấn Anh

Đây là mã nguồn trang web Portfolio cá nhân của tôi, được xây dựng để giới thiệu về bản thân, lộ trình phát triển kỹ năng (đặc biệt là Fullstack Web Development), các dự án tiêu biểu và các chứng chỉ chuyên môn trực tuyến.

Trang web đang được vận hành trực tiếp và miễn phí thông qua dịch vụ **GitHub Pages**.

## 🚀 Link truy cập trực tiếp
👉 [https://Waitforngnl.github.io](https://Waitforngnl.github.io)

## 🛠 Công nghệ sử dụng
* **HTML5:** Cấu trúc phân mảng toàn bộ nội dung trang (Giới thiệu, Dự án, Chứng chỉ, Liên hệ).
* **CSS3:** Tùy biến giao diện Dark Mode (chủ đề tối) tối giản, sử dụng các thuộc tính hiện đại như Flexbox và CSS Grid để chia bố cục hiển thị tốt trên cả máy tính và thiết bị di động.

---

## 📖 Hướng dẫn triển khai (Deploy) trang web bằng GitHub Pages

Quá trình đưa trang web tĩnh từ mã nguồn (local) lên môi trường mạng Internet thông qua GitHub Pages được thực hiện theo các bước sau:

### Bước 1: Khởi tạo và đẩy mã nguồn lên Repository
1. Đăng nhập vào tài khoản GitHub.
2. Tạo một Repository mới. 
   * *Lưu ý quan trọng:* Để tạo trang cá nhân mặc định của tài khoản, tên Repository phải được đặt theo cú pháp `<username>.github.io` (Ví dụ: `Waitforngnl.github.io`).
3. Khởi tạo Git tại máy cá nhân, sau đó commit và push file `index.html` (cùng các tài nguyên khác nếu có) lên nhánh `main` của Repository vừa tạo.

### Bước 2: Kích hoạt tính năng GitHub Pages
1. Truy cập vào giao diện Repository trên trình duyệt.
2. Nhấn vào tab **Settings** (Cài đặt) ở thanh công cụ phía trên.
3. Ở thanh menu bên trái, cuộn xuống mục *Code and automation* và chọn **Pages**.
4. Tại phần thiết lập **Build and deployment**:
   * Ở mục *Source*, giữ nguyên tùy chọn **Deploy from a branch**.
   * Ở mục *Branch*, nhấn vào menu thả xuống đang báo *None*, chọn nhánh chứa mã nguồn (thường là **main** hoặc **master**).
   * Giữ nguyên thư mục gốc là `/(root)`.
   * Nhấn nút **Save**.

### Bước 3: Chờ quá trình Build hoàn tất
* Ngay sau khi lưu, GitHub Actions sẽ tự động kích hoạt tiến trình biên dịch (build process). Quá trình này thường mất khoảng 1 đến 3 phút.
* Tải lại (F5) trang cấu hình Pages. Khi màn hình xuất hiện thông báo báo xanh *"Your site is live at..."* kèm theo một đường dẫn URL, trang web đã chính thức được public và có thể truy cập từ bất kỳ đâu.

