<div align="center">

  <!-- Banner / Logo dự án -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=11,18,22&height=180&section=header&text=VOC%20Web%20AI%20Portfolio&fontSize=42&fontColor=ffffff&animation=fadeIn" alt="VOC Web AI Banner" width="100%" />

  <p align="center">
    <strong>Dự án xây dựng Portfolio cá nhân hiện đại & các bài thực hành thiết kế Web chuẩn SEO, Responsive và Design System CSS Variables.</strong>
  </p>

  <!-- Badges từ Shields.io -->
  <p align="center">
    <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=github" alt="Status" />
    <img src="https://img.shields.io/badge/Language-HTML5%20%7C%20CSS3%20%7C%20JS-blue?style=for-the-badge&logo=javascript" alt="Languages" />
    <img src="https://img.shields.io/badge/Layout-CSS%20Grid%20%26%20Flexbox-8b5cf6?style=for-the-badge&logo=css3" alt="Layout" />
    <img src="https://img.shields.io/badge/Responsive-Mobile%20%26%20Desktop-orange?style=for-the-badge&logo=responsive" alt="Responsive" />
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
  </p>

  <p align="center">
    <a href="#-giới-thiệu-dự-án">Giới thiệu</a> •
    <a href="#-tính-năng-nổi-bật">Tính năng</a> •
    <a href="#-công-nghệ-sử-dụng">Công nghệ</a> •
    <a href="#-cấu-trúc-thư-mục">Cấu trúc thư mục</a> •
    <a href="#-hướng-dẫn-cài-đặt--khởi-chạy">Cài đặt & Chạy</a> •
    <a href="#-lộ-trình-phát-triển">Lộ trình</a> •
    <a href="#-tác-giả">Tác giả</a>
  </p>

</div>

---

## 📖 Giới Thiệu Dự Án (About The Project)

**VOC Web AI** là repository lưu trữ các bài tập lớn, đồ án thực hành và mã nguồn dự án môn **Thiết Kế Web (Web Design & AI)**. Trọng tâm của dự án là việc áp dụng các nguyên lý UI/UX hiện đại, xây dựng hệ thống biến toàn cục (**CSS Variables Design Tokens**), làm chủ kỹ thuật bố cục nâng cao (**CSS Grid & Flexbox**), và tối ưu hóa hiển thị đa thiết bị thông qua **Media Queries**.

### 🌟 Điểm nhấn tiêu biểu trong dự án:
- **Hoạt động 1 (`Hoạt động1.html`)**: Kỹ thuật căn giữa tuyệt đối với Flexbox, xử lý hiệu ứng tương tác Hover, chuyển màu viền/nền và hiệu ứng nảy (CSS Animation Pulse).
- **Hoạt động 2 (`Hoạt động2.html`)**: Website Portfolio cá nhân hoàn chỉnh:
  - Bố cục 2 cột (Sidebar cố định & Main Content).
  - Hệ thống **CSS Variables tại `:root`** trích xuất 100% mã màu và thang khoảng cách (`margin`/`padding`/`gap` từ `0` đến `32px`).
  - Tối ưu **Media Queries (< 768px)**: Tự động chuyển Grid 2 cột sang 1 cột duy nhất, đưa sidebar lên đầu trang thành thanh điều hướng gọn gàng.
  - Lưới **Dịch vụ (`.services-container`)**: Hiển thị 4 cột trên màn hình lớn (> 1024px), 2 cột trên tablet (768px - 1024px) và 1 cột trên mobile (< 768px) với `gap: 20px`.

---

## ✨ Tính Năng Nổi Bật (Key Features)

- [x] 🎨 **Design System chuẩn chỉnh**: Toàn bộ màu sắc và khoảng cách được quản lý tập trung tại `:root` bằng các biến CSS (`var(--...)`), dễ dàng chuyển đổi theme.
- [x] 📐 **Bố cục CSS Grid & Flexbox**: Kết hợp linh hoạt giữa Grid cho layout khung lớn và Flexbox cho căn chỉnh thanh menu, thẻ icon, card.
- [x] 📱 **Responsive Design toàn diện**:
  - Desktop (> 1024px): Bố cục 2 cột sidebar/content rộng rãi, lưới dịch vụ 4 cột.
  - Tablet (768px - 1024px): Lưới dịch vụ chuyển sang 2 cột cân đối.
  - Mobile (< 768px): Bố cục chuyển thành 1 cột duy nhất, thanh điều hướng dạng horizontal bar tiện thao tác cảm ứng.
- [x] 💎 **Hiệu ứng Glassmorphism**: Nền thẻ mờ cao cấp với `backdrop-filter: blur()`.
- [x] ⚡ **Code sạch & chuẩn SEO**: Sử dụng đúng các thẻ ngữ nghĩa Semantic HTML (`<aside>`, `<main>`, `<section>`, `<nav>`, `<footer>`).

---

## 🛠 Công Nghệ Sử Dụng (Tech Stack)

| Hạng mục | Công nghệ / Kỹ thuật áp dụng |
| :--- | :--- |
| **Ngôn ngữ cốt lõi** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Kỹ thuật bố cục** | CSS Grid Layout, CSS Flexbox, CSS Variables (`:root`), Responsive Media Queries |
| **UI/UX & Design** | Glassmorphism, Gradient Accents, Hover Transitions, Box-shadow Systems |
| **Công cụ hỗ trợ** | ![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=flat-square&logo=visual%20studio%20code&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) |

---

## 📁 Cấu Trúc Thư Mục (Folder Structure)

```text
voc-web-ai/
│
├── Hoạt động1.html         # Bài tập 1: Demo căn giữa Flexbox & hiệu ứng Hover
├── hoatdong1-style.css     # CSS stylesheet cho Hoạt động 1
│
├── Hoạt động2.html         # Bài tập 2: Trang Portfolio cá nhân hoàn chỉnh
├── hoatdong2-style.css     # CSS Stylesheet chính (CSS Variables, Grid, Responsive)
│
├── Website.html            # Trang web mẫu dự án
├── index.html              # Bài tập cấu trúc Semantic HTML tuần 1
├── index3.html             # Bài tập cấu trúc bổ trợ tuần 3
├── hđ1.html                # Phiên bản dự phòng Hoạt động 1
├── hđ1.css                 # CSS stylesheet dự phòng Hoạt động 1
│
└── README.md               # Tài liệu hướng dẫn dự án chuẩn GitHub
```

---

## 🚀 Hướng Dẫn Cài Đặt & Khởi Chạy (Getting Started)

Để xem và chạy dự án trực tiếp trên máy tính của bạn:

### 1. Sao chép (Clone) Repository

```bash
git clone https://github.com/CaoXuanThanh/voc-web-ai.git
cd voc-web-ai
```

### 2. Khởi chạy trên trình duyệt

Bạn có thể chạy dự án bằng một trong các cách sau:

- **Cách 1 (Đơn giản nhất)**: Nhấp đúp trực tiếp vào file `Hoạt động2.html` để mở trên trình duyệt (Chrome, Edge, Firefox...).
- **Cách 2 (Sử dụng Live Server trên VS Code)**:
  1. Cài đặt tiện ích mở rộng **Live Server** trên Visual Studio Code.
  2. Chuột phải vào file `Hoạt động2.html` $\rightarrow$ chọn **"Open with Live Server"**.
  3. Trang web sẽ tự động chạy tại địa chỉ `http://127.0.0.1:5500/Hoạt động2.html`.

---

## 🗺 Lộ Trình Phát Triển (Roadmap)

- [x] Xây dựng cấu trúc Semantic HTML5 chuẩn SEO.
- [x] Xây dựng bố cục 2 cột với CSS Grid & Flexbox.
- [x] Thiết lập hệ thống CSS Variables tại `:root` (2 màu chủ đạo, 3 mức xám text, màu nền).
- [x] Tối ưu hóa Media Queries cho Tablet & Mobile (< 768px).
- [x] Thiết kế lưới dịch vụ đa màn hình `.services-container` (4 cột / 2 cột / 1 cột, `gap: 20px`).
- [x] Trích xuất 100% mã màu và khoảng cách vào hệ thống biến `var()`.
- [ ] Tích hợp tính năng chuyển đổi giao diện Sáng / Tối (Dark / Light Mode Toggle).
- [ ] Xử lý gửi biểu mẫu liên hệ với JavaScript & Formspree API.
- [ ] Triển khai hosting trực tiếp qua GitHub Pages.

---

## 🤝 Đóng Góp (Contributing)

Mọi ý kiến đóng góp nhằm cải thiện giao diện và tối ưu code đều được hoan nghênh:

1. **Fork** repository này.
2. Tạo nhánh tính năng (`git checkout -b feature/AmazingFeature`).
3. Commit các thay đổi (`git commit -m 'feat: Add some AmazingFeature'`).
4. Push lên nhánh của bạn (`git push origin feature/AmazingFeature`).
5. Tạo một **Pull Request** mới.

---

## 📄 Giấy Phép (License)

Dự án này được cấp phép theo giấy phép **MIT License** - xem file [LICENSE](LICENSE) để biết thêm chi tiết.

---

## 👤 Thông Tin Tác Giả (Author)

**Đào Nhựt Quang Minh (QMinh)**
- 🎓 Sinh viên ngành Công Nghệ Thông Tin - Đại Học Lạc Hồng (LHU)
- 🆔 Mã số sinh viên: **125000125**
- 📧 Email: [125000125@lachong.edu.vn](mailto:125000125@lachong.edu.vn)
- 🐙 GitHub: [@CaoXuanThanh](https://github.com/CaoXuanThanh) / [QMinh](https://github.com/CaoXuanThanh/voc-web-ai)

---

<div align="center">
  <sub>Được xây dựng với sự tâm huyết bởi <b>Đào Nhựt Quang Minh</b> © 2026. Hãy bấm ⭐️ Star nếu bạn thấy dự án hữu ích!</sub>
</div>
