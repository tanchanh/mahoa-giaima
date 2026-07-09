# 🔑 Ứng Dụng Mã Hoá & Giải Mã AES-256

Ứng dụng web bảo mật cao giúp mã hoá và giải mã **văn bản** hoặc **tập tin** trực tiếp trên trình duyệt sử dụng thuật toán mã hoá mạnh mẽ **AES-GCM 256-bit** được cấp phép bởi tiêu chuẩn Web Crypto API.

---

## ✨ Tính Năng Nổi Bật

* **An toàn tuyệt đối:** Hoạt động hoàn toàn ở chế độ **offline**, không truyền bất kỳ dữ liệu nào lên máy chủ mạng.

* **Mã hoá đa dạng:** Hỗ trợ xử lý song song cả hai phân hệ dữ liệu bao gồm **văn bản thường** và **tập tin đa định dạng**.

* **Hệ thống dẫn xuất khoá cao cấp:** Sử dụng cơ chế băm khoá nguồn **PBKDF2** với 100.000 lượt lặp kết hợp vector muối (Salt) ngẫu nhiên chống tấn công từ điển.

* **Đóng gói thông minh:** Bản mã hoá của tập tin tự động nhúng kèm tên file và định dạng gốc giúp khôi phục nguyên vẹn sau khi giải mã.

---

## 🛠️ Hướng Dẫn Sử Dụng

### 1. Đối Với Phân Hệ Văn Bản

* **Bước 1:** Chọn tab **Văn bản** và nhập nội dung cần mã hoá (hoặc dán chuỗi Base64 nếu cần giải mã).

* **Bước 2:** Nhập mật mã bảo vệ tại ô **Mật mã (Password)**.

* **Bước 3:** Nhấn nút **Mã hoá** hoặc **Giải mã** tùy theo nhu cầu.

* **Bước 4:** Nhấn nút **Sao chép** tại khung kết quả hiển thị bên dưới để lưu lại chuỗi Base64 hoặc văn bản đã khôi phục.

### 2. Đối Với Phân Hệ Tập Tin

* **Bước 1:** Chuyển sang tab **Tập tin**, kéo thả hoặc nhấp chọn file cần xử lý vào vùng **Drop zone**.

* **Bước 2:** Cài đặt mật mã bảo mật riêng cho tập tin.

* **Bước 3:** Nhấp chọn **Mã hoá tập tin** (để xuất ra định dạng đuôi `.enc`) hoặc **Giải mã tập tin** (để khôi phục cấu trúc file gốc).

* **Bước 4:** Hệ thống tự động xử lý thanh tiến trình và kích hoạt trình tải xuống tự động lưu file về thiết bị.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ cốt lõi:** HTML5, CSS3 (Responsive Neon Glassmorphism), Web Crypto API tích hợp sẵn của trình duyệt.
