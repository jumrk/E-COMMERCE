# 👗 XÂY DỰNG HỆ THỐNG BÁN HÀNG THỜI TRANG VỚI CÔNG NGHỆ REACTJS VÀ NODEJS

> ✅ **Thực tập tốt nghiệp**: XÂY DỰNG HỆ THỐNG BÁN HÀNG THỜI TRANG VỚI CÔNG NGHỆ REACTJS VÀ NODEJS

---

## 📌 Mô tả dự án

Hệ thống bán hàng thời trang được xây dựng với mục tiêu cung cấp một nền tảng **mua sắm tiện lợi – hiện đại**.
---

## 🚀 Tính năng chính

### 🛍️ Dành cho người dùng
- 🔐 Đăng ký / Đăng nhập tài khoản (email, google, facebook)
- 👗 Xem danh sách sản phẩm theo danh mục
- 🔍 Tìm kiếm và lọc sản phẩm
- 🛒 Thêm sản phẩm vào giỏ hàng
- 📦 Đặt hàng, theo dõi đơn hàng
- ⭐ Đánh giá sản phẩm đã mua
- 📰 Xem blog, bài viết thời trang
- 💬 chat với người quản trị

### ⚙️ Dành cho quản trị viên (Admin)
- 🧺 Quản lý sản phẩm, danh mục
- 👥 Quản lý người dùng
- 📑 Quản lý đơn hàng
- 💬 Quản lý đánh giá, bình luận
- 🎟️ Quản lý mã giảm giá
- 📝 Quản lý blog thời trang
- 📬 Quản lý hộp thư liên hệ từ khách hàng

---

## 🛠️ Công nghệ sử dụng

| Layer         | Công nghệ                                         |
|---------------|---------------------------------------------------|
| **Frontend**  | ReactJS, TailwindCSS, Axios, React Router         |
| **Backend**   | Node.js, Express.js, JWT, Multer                  |
| **Database**  | MongoDB (Compass hoặc Atlas)                        |
| **Khác**      | Cloudinary (upload ảnh), dotenv, Mongoose,...     |

---

## 📂 Cấu trúc thư mục


📁 E-COMMERCE 
├── 📁 frontend/ # Giao diện React 
├── 📁 backend/ # Server Node.js + API 
├── 📁 data/ # Dữ liệu mẫu MongoDB (.json) 
├── README.md # File hướng dẫn

```md
---

## ⚙️ HƯỚNG DẪN CÀI ĐẶT DỰ ÁN

### 🔽 1. Clone dự án từ GitHub
```bash
git clone https://github.com/jumrk/THUCTAPTOTNGHIEM.git
cd THUCTAPTOTNGHIEM
```

---

### 🛠️ 2. Cài đặt Backend (Server)
```bash
cd backend
npm install
npm run dev
```

---

### 🎨 3. Cài đặt Frontend (Client)
```bash
cd ../frontend
npm install
npm run dev
```

---

### 🗃️ 4. Cài đặt và kết nối MongoDB

> 📦 Dữ liệu mẫu đã được chuẩn bị sẵn trong thư mục `/data`.

#### Các bước:
1. Tải và cài đặt [MongoDB Compass](https://www.mongodb.com/try/download/compass)
2. Mở Compass và kết nối đến địa chỉ:
```
mongodb://localhost:27017
```
3. Tạo một Database mới tên: `E-COMMERCE`
4. Import các collection (sản phẩm, người dùng, đơn hàng,...) từ thư mục `data/`

---

## 👨‍💻 TÀI KHOẢN DEMO

| Role  | Email                 | Mật khẩu   |
|-------|-----------------------|------------|
| Admin | jumrk03@gmail.com     | 12345678   |
| User  | jumrk03@gmail.com     | 12345678   |

---

## 📑 GIẤY PHÉP

Dự án được xây dựng phục vụ **mục đích học tập, nghiên cứu** trong khuôn khổ đồ án tốt nghiệp.  
⚠️ **Không sử dụng vào mục đích thương mại.**

---

## 💬 LIÊN HỆ

- 👤 Tác giả: **Nguyễn Văn Thuận**  
- 📧 Email: [jumrk03@gmail.com](mailto:jumrk03@gmail.com)  
- 🔗 GitHub: [https://github.com/jumrk](https://github.com/jumrk)

---
```
