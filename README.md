# Car Parking Manager – Đồ Án Tốt Nghiệp 

> Ứng dụng quản lý bãi đỗ xe sử dụng **Java + JavaFX + DAO + SQL**


## 🔧 Tính Năng Chính

- 🚘 Quản lý thông tin xe vào - ra bãi đỗ
- 🕒 Ghi nhận thời gian đỗ xe & tính tiền tự động
- 📋 Danh sách chỗ đỗ xe: đang trống, đang sử dụng
- 📊 Thống kê lịch sử gửi xe
- 💾 Lưu trữ dữ liệu bằng cơ sở dữ liệu SQL
- 🧼 Giao diện dễ sử dụng, bố cục rõ ràng

---

## 💻 Công Nghệ Sử Dụng

| Công Nghệ      | Vai Trò                         |
|----------------|---------------------------------|
| 🟦 Java SE     | Ngôn ngữ lập trình chính        |
| 🎨 JavaFX      | Xây dựng giao diện người dùng   |
| 🛢️ JDBC       | Kết nối với cơ sở dữ liệu       |
| 🗃️ SQL (MySQL/SQLite) | Cơ sở dữ liệu            |
| 📁 DAO Pattern | Tổ chức truy xuất dữ liệu       |

---

## 📂 Cấu Trúc Thư Mục Dự Án

```bash
CarParkingManager/
│
├── src/
│   ├── controllers/       # JavaFX Controllers
│   ├── dao/               # DAO interfaces & implementation
│   ├── models/            # Các lớp đại diện dữ liệu
│   ├── utils/             # Kết nối CSDL, helpers
│   └── Main.java          # Điểm khởi chạy chính
│
├── resources/
│   ├── fxml/              # FXML layout files
│   └── css/               # Style cho UI
│
├── schema.sql             # File tạo CSDL
├── parking.db             # SQLite DB (nếu dùng)
└── README.md
