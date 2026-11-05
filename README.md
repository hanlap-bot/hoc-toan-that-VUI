# 🦊 Phòng Thí Nghiệm Toán Tư Duy Lớp 2

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-brightgreen?style=for-the-badge)

**Phòng Thí Nghiệm Toán Tư Duy Lớp 2** là một ứng dụng web tương tác (Web App) được thiết kế dành riêng cho các bé học sinh lớp 2. Ứng dụng chuyển hóa các bài toán trừu tượng trong sách giáo khoa (Toán cân Robecvan, Toán đong nước, Toán có lời văn) thành những trải nghiệm thực tế, trực quan và sinh động.

👉 **Trải nghiệm ứng dụng tại đây:** [https://hanlap-bot.github.io/hoc-toan-that-VUI/](https://hanlap-bot.github.io/hoc-toan-that-VUI/)

---

## ✨ Tính Năng Nổi Bật

Ứng dụng bao gồm **9 dạng bài tập** được chia thành 3 nhóm chính, bám sát chương trình Toán lớp 2:

### ⚖️ Nhóm 1: Toán Cân Robecvan (Tư duy logic)
- **Bài 1:** Bao 5kg & Quả cân 2kg → Lấy 1kg.
- **Bài 2:** Bao 8kg (Không có quả cân) → Lấy 2kg.
- **Bài 3:** Bao 9kg & Quả cân 2kg → Lấy 4kg.
- *Đặc điểm:* Bé trực tiếp kéo thả quả cân và bao gạo, quan sát đòn cân nghiêng và kim chỉ vạch số 0 thực tế.

### 💧 Nhóm 2: Toán Đong Nước (Thực nghiệm vật lý)
- **Bài 4:** Can 5 lít & Can 3 lít → Đong đúng 4 lít.
- **Bài 5:** Can 5 lít & Can 2 lít → Đong đúng 1 lít.
- *Đặc điểm:* Mô phỏng dòng nước chảy trực quan, bé học được cách chuyển đổi dung tích qua lại giữa các can.

### 📚 Nhóm 3: Toán Có Lời Văn (Phân tích & Tính toán)
- **Bài 6 & 7:** Bài toán bán gạo (Tìm ngày 2, Tìm cả 2 ngày).
- **Bài 8:** Bài toán trồng cây của 2 lớp 2A10 và 2A13.
- **Bài 9:** Bài toán thay đổi tổng (Tăng số hạng).
- *Đặc điểm:* Có tính năng **Tóm tắt bằng sơ đồ đoạn thẳng** chuẩn sư phạm, giúp bé hình dung được bài toán và điền phép tính (cộng/trừ) chính xác.

### 🛠️ Tính Năng Dành Cho Phụ Huynh
- **⚙️ Tạo đề mới:** Tự tạo ra vô số bài toán mới với số liệu tùy chỉnh (Cân nặng, Dung tích, hoặc Số liệu bài toán có lời văn).
- **🔊 Âm thanh & Giọng đọc:** Phản hồi âm thanh vui nhộn khi thao tác đúng/sai.
- **📱 Hỗ trợ PWA (Progressive Web App):** Có thể cài đặt như một ứng dụng thật trên iPad, iPhone, Android và Máy tính. Chơi được hoàn toàn **Offline** mà không cần mạng.

---

## 🛠 Công Nghệ Sử Dụng

Dự án được xây dựng với triết lý **"Single-File Architecture"** (Kiến trúc đơn tệp) giúp tối ưu hóa hiệu năng và dễ dàng triển khai:

- **Giao diện:** HTML5 Semantic, Tailwind CSS (CDN).
- **Đồ họa:** SVG nguyên bản vẽ hoàn toàn bằng code (Cân, quả cân, bao gạo, can nước) - không cần tải hình ảnh, giúp tải trang cực nhanh.
- **Logic:** Vanilla JavaScript (ES6+), mô hình State-driven UI.
- **Âm thanh:** Web Audio API tổng hợp âm thanh trực tiếp từ trình duyệt (không dùng file mp3 nặng).
- **PWA:** Service Worker (`sw.js`) giúp lưu trữ offline, `manifest.json` giúp cài đặt màn hình chính.

---

## 🚀 Hướng Dẫn Cài Đặt Lên Điện Thoại / iPad

Để bé chơi toàn màn hình giống hệt một ứng dụng tải từ App Store:

**Trên iPad / iPhone (Bắt buộc dùng Safari):**
1. Mở link web bằng trình duyệt **Safari**.
2. Bấm nút **Chia sẻ** (hình vuông có mũi tên trỏ lên) trên thanh công cụ.
3. Cuộn xuống chọn **"Thêm vào MH chính"** (Add to Home Screen).
4. Bấm **"Thêm"**. Biểu tượng Cáo 🦊 sẽ xuất hiện trên màn hình chính.

**Trên Android (Dùng Chrome):**
1. Mở link bằng **Chrome**.
2. Bấm dấu **3 chấm** ở góc trên bên phải.
3. Chọn **"Cài đặt ứng dụng"** hoặc **"Thêm vào MH chính"**.

---

## 💻 Chạy Dưới Máy Cục Bộ (Local)

Nếu bạn là lập trình viên và muốn phát triển thêm:
1. Clone dự án này về máy.
2. Do dự án dùng Service Worker, bạn cần chạy qua Local Server (không mở trực tiếp file HTML được). Có thể dùng Python:
   ```bash
   python -m http.server 8000
