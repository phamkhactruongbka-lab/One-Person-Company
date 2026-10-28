# 🏢 CineTech AI Corp — Dự Án Phòng Ban Ảo 3D (Hologram Command Center)

Dự án độc lập sử dụng toàn bộ nội dung và giao diện **Không gian 3D Hologram Command Center** của hệ thống phòng ban ảo **CineTech AI**.

---

## 📂 Cấu trúc thư mục dự án (`phong-ban-ao`)

```text
phong-ban-ao/
├── index.html          # Trang chủ chính: Sàn 3D Hologram 7 Phòng Ban & Trung Tâm Điều Hành
├── company.html        # Trang tương thích đường dẫn trực tiếp (bản sao đồng bộ với index.html)
├── style.css           # Bộ giao diện Dark Mode Điện Ảnh & Hiệu ứng 3D Hologram
├── assets/             # Bộ hình ảnh Robot 3D làm việc, Robot CEO tuần tra & Poster
│   ├── robot-ceo-3d.png
│   ├── robot-worker.png
│   ├── robot-rnd.png
│   ├── robot-editor.png
│   ├── robot-qa.png
│   ├── robot-ui.png
│   └── robot-biz.png
├── data/               # Dữ liệu JSON đồng bộ trực tiếp lên các màn hình Hologram
│   ├── published.json  # Dữ liệu tin điện ảnh đã duyệt
│   ├── products.json   # Dữ liệu thiết bị giải trí xác minh
│   ├── cashflow.json   # Dữ liệu tiến độ dòng tiền & quỹ mục tiêu 550.000 VNĐ
│   └── ui_themes.json  # Dữ liệu chủ đề giao diện tự động
└── docs/               # Bản đóng gói sẵn sàng cho GitHub Pages (nếu đẩy lên repo riêng)
```

---

## ✨ Các tính năng chính trong giao diện

1. **Sàn 3D Hologram 7 Phòng Ban (`#holoViewport`)**:
   - **P.101 · Săn Tin & R&D (`research.py`)**: Robot `"Radar-503"` quét RSS tự động.
   - **P.102 · Ban Biên Tập (`editor.py`)**: Robot `"Neuro-Editor"` biên tập & gắn mã SHA-256.
   - **P.103 · Pháp Chế & QA (`validate.py`)**: Robot `"Shield-QA"` kiểm toán dữ liệu & chống XSS.
   - **P.201 · DevOps & CI/CD (`autopilot.py`)**: Robot `"Chronos-Ops"` vận hành tự động 24/7.
   - **P.202 · Góc Thiết Bị (`products.json`)**: Robot `"Gear-Spec"` tra cứu thông số nhà sản xuất.
   - **P.203 · Kế Toán & Dòng Tiền (`cashflow.json`)**: Robot `"Fin-Zero"` kiểm soát ngân sách 0đ & mục tiêu 550k.
   - **P.204 · Giao Diện UI (`ui_designer.py`)**: Robot `"Astro-Cinema"` tự động nhận diện nội dung phim để đổi giao diện.

2. **Robot 3D Tổng Biên Tập & CEO Đi Tuần Tra**:
   - Tự động di chuyển kiểm tra từng phòng ban mỗi 3.6 giây hoặc **click trực tiếp vào bất kỳ phòng ban nào** để điều Robot CEO tới kiểm tra ngay lập tức.
   - Hỗ trợ **kéo chuột 360°** để xoay góc nhìn 3D và chuyển đổi ánh sáng theo 4 ca làm việc trong ngày (Sáng sớm, Ca chiều, Hoàng hôn, Ca đêm).

3. **Trung Tâm Giám Sát Tiến Độ & Kho 20 Shop Mục Tiêu (`#exec-dashboard`)**:
   - Lộ trình 6 mốc tiến độ thực chiến & Chu trình tự động hóa 8 bước.
   - Kho kịch bản tiếp cận **20 Shop mục tiêu** chia làm 4 đợt với nút **📋 Chép tin mẫu** chỉ bằng 1 cú click.
   - **Bàn điều khiển mô phỏng dòng tiền 550.000 VNĐ** phản hồi trực tiếp theo thời gian thực.

---

## 🚀 Cách mở và chạy dự án

### Cách 1: Mở trực tiếp trên trình duyệt
Nhấp đúp vào file:
- `D:\Codex\cinetech-ai-for-codex\phong-ban-ao\index.html`

### Cách 2: Chạy qua máy chủ nội bộ (Local HTTP Server)
```powershell
cd D:\Codex\cinetech-ai-for-codex\phong-ban-ao
python -m http.server 8080
```
Sau đó mở trình duyệt tại địa chỉ: `http://localhost:8080`

