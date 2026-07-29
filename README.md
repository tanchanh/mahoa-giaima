# Phần Mềm Mã Hoá & Giải Mã Bảo Mật (AES-256)

**Tác giả:** Dương Tấn Chánh  
**Hình thức:** Ứng dụng Web đơn trang (Hoạt động 100% Offline trên trình duyệt)

---

## 💡 Giới Thiệu
Ứng dụng giúp bạn **bảo vệ an toàn nội dung tin nhắn, tài liệu và tập tin (file)** bằng mật mã cá nhân trước khi gửi qua Zalo, Messenger, Email hay lưu trữ riêng tư.

Mọi thao tác mã hoá và giải mã đều được xử lý trực tiếp trên thiết bị của bạn (máy tính hoặc điện thoại) thông qua Web Crypto API tiêu chuẩn. Dữ liệu của bạn **không bao giờ bị gửi lên mạng hay bất kỳ máy chủ nào**, đảm bảo riêng tư và an toàn tuyệt đối.

---

## ⭐ Các Tính Năng Nổi Bật

### 🛡️ Bảo Mật An Toàn & Chuẩn Thuật Toán
* **Mã hoá AES-GCM 256-bit:** Chuẩn mã hoá bảo mật cao với khoá PBKDF2 (600.000 vòng lặp) và muối ngẫu nhiên (Salt/IV).
* **Hoạt động 100% Offline:** Không cần kết nối Internet, dữ liệu thuộc quyền kiểm soát hoàn toàn của bạn.

### 🔗 Chia Sẻ Liên Kết Nhanh Cho Tin Nhắn (Zalo, Messenger...)
* **Tạo link chia sẻ 1-chạm:** Mã hoá xong có thể bấm "Chia sẻ" để gửi ngay liên kết chứa sẵn dữ liệu mã hoá.
* **Kiểm soát độ dài an toàn (< 1.900 ký tự):** Đảm bảo liên kết không bị ứng dụng nhắn tin (như Zalo có giới hạn 2.000 ký tự) cắt xén làm hỏng dữ liệu.
* **Tự động điền dữ liệu khi mở link:** Người nhận chỉ cần nhấp vào liên kết, ứng dụng tự động tải dữ liệu vào ô nhập và tập trung con trỏ vào ô Mật mã để giải mã ngay.

### ⚡ Nén Gọn Dung Lượng Tự Động
* **Tự động nén dữ liệu:** Sử dụng thuật toán CompressionStream (Deflate/Gzip) giúp thu gọn kích thước văn bản và file trước khi mã hoá.
* **Báo tỷ lệ nén:** Hiển thị rõ số % dung lượng đã nén gọn sau khi mã hoá.

### ⏱️ Tự Động Bảo Vệ Tránh Lộ Mật Mã & Dữ Liệu
* **Nút Sao chép & Chia sẻ tiện lợi:** Nhấp nút "Sao chép kết quả" hoặc "Chia sẻ" để gửi nhanh bản mã qua Zalo, Messenger.
* **Tự động xoá mật mã khi rời ứng dụng:** Khi chuyển tab hoặc ẩn trình duyệt, mật mã bảo vệ sẽ tự động được xoá để chống nhìn lén.
* **Tự động nhận diện bản mã:** Khi dán chuỗi Base64 vào ô nhập, hệ thống tự động phát hiện và sẵn sàng giải mã.

### 📁 Mã Hoá & Khôi Phục Tập Tin (File) Đầy Đủ
* **Hỗ trợ mọi định dạng:** Hình ảnh, tài liệu Word, Excel, PDF, video, tệp nén...
* **Giữ nguyên tên tệp gốc:** Khi giải mã, tập tin được khôi phục chính xác tên và định dạng ban đầu.

---

## 📖 Hướng Dẫn Sử Dụng

### 1. Xử Lý Văn Bản / Tin Nhắn
* **Mã Hoá Văn Bản:**
  1. Mở tab **"Xử lý Văn bản"**.
  2. Nhập hoặc dán nội dung cần bảo vệ vào ô nhập liệu.
  3. Nhập mật mã bảo vệ do bạn tự đặt.
  4. Bấm **"Mã hoá (có nén)"**.
  5. Bản mã hiển thị bên dưới, bạn bấm **"Sao chép kết quả"** hoặc bấm **"Chia sẻ"** để gửi link trực tiếp qua Zalo/Messenger.

* **Giải Mã Văn Bản:**
  1. Nhấp vào liên kết chia sẻ nhận được (hoặc dán đoạn mã vào ô nhập).
  2. Nhập đúng mật mã người gửi cung cấp.
  3. Bấm **"Giải mã & Giải nén"** để xem nội dung ban đầu.

---

### 2. Xử Lý Tập Tin (File)
* **Mã Hoá File:**
  1. Mở tab **"Xử lý Tập tin"**.
  2. Kéo thả hoặc bấm chọn tập tin cần bảo vệ.
  3. Nhập mật mã bảo vệ.
  4. Bấm **"Mã hoá Tập tin (có nén)"**. Tệp có đuôi `.enc` sẽ tự động tải về máy.

* **Giải Mã File:**
  1. Chọn tệp `.enc` cần mở.
  2. Nhập đúng mật mã.
  3. Bấm **"Giải mã & Khôi phục Tập tin"** để tải về tập tin gốc ban đầu.

---

## 📌 Tóm Tắt Ưu Điểm
* 🛡️ **Bảo mật AES-256:** An toàn tuyệt đối, mã hoá & giải mã ngay trên thiết bị.
* 🔗 **Chia sẻ thông minh:** Tự động điền dữ liệu qua URL, tương thích hoàn hảo với Zalo, Messenger.
* ⚡ **Nén dữ liệu:** Giúp tiết kiệm dung lượng khi truyền gửi.
* 📡 **Offline 100%:** Không tải dữ liệu lên máy chủ, đảm bảo riêng tư tuyệt đối.
