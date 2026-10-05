# 🛡️ Công Cụ Mã Hoá & Bảo Vệ Dữ Liệu An Toàn (AES-256)

Chào mừng bạn đến với công cụ mã hoá dữ liệu cá nhân của **Dương Tấn Chánh**. 

Đây là một trang web đơn giản nhưng cực kỳ mạnh mẽ, giúp bạn **"khoá"** các đoạn văn bản nhạy cảm hoặc tập tin quan trọng bằng một mật khẩu do bạn tự đặt. Chỉ những ai có mật khẩu chính xác mới có thể mở và xem được nội dung bên trong.

---

## 🌟 Điểm nổi bật (Tại sao bạn nên dùng?)

* **Bảo mật tuyệt đối (Chuẩn quân đội):** Sử dụng thuật toán mã hoá AES-256 tiên tiến nhất hiện nay.
* **Riêng tư 100% (Không sợ lộ dữ liệu):** Toàn bộ quá trình mã hoá và giải mã diễn ra **ngay trên máy tính / điện thoại của bạn**. Dữ liệu **KHÔNG BAO GIỜ** gửi lên bất kỳ máy chủ (server) hay mạng Internet nào. Thậm chí bạn có thể ngắt mạng (tắt Wi-Fi/4G) mà trang web vẫn chạy bình thường.
* **Tự động nén gọn dữ liệu:** Giúp giảm dung lượng tập tin và văn bản trước khi mã hoá, giúp việc gửi qua Zalo, Messenger, Gmail nhanh hơn.
* **Không làm đơ máy:** Sử dụng công nghệ xử lý ngầm đa luồng mượt mà.

---

## 📖 Hướng Dẫn Sử Dụng Chi Tiết

### 1. Dành cho Văn Bản (Tin nhắn, Ghi chú, Tài khoản/Mật khẩu)

#### 🔒 Cách Mã Hoá (Khoá tin nhắn):
1. Chọn thẻ **"Văn Bản"**.
2. Nhập hoặc dán nội dung bạn muốn bảo vệ vào ô trống lớn phía trên.
3. Nhập mật khẩu bạn muốn đặt vào ô **"Mật mã bảo vệ"** *(Hãy chú ý thang đo màu sắc để biết mật khẩu của bạn đã đủ mạnh chưa)*.
4. Bấm nút **"Mã hoá"** màu xanh dương.
5. Kết quả thu được là một chuỗi ký tự lạ mắt (bản mã):
   * Bấm **"Sao chép kết quả"** để gửi đoạn mã này cho người khác.
   * Hoặc bấm **"Chia sẻ"** để lấy đường link gửi nhanh qua Zalo, SMS, Messenger...

#### 🔓 Cách Giải Mã (Mở tin nhắn):
1. Dán chuỗi ký tự lạ (bản mã) vào ô trống. *(Nếu bạn bấm vào link chia sẻ, ô này sẽ tự điền sẵn)*.
2. Nhập đúng mật khẩu đã dùng lúc mã hoá vào ô **"Mật mã bảo vệ"**.
3. Bấm nút **"Giải mã"** màu tím.
4. Nội dung gốc ban đầu sẽ xuất hiện ngay bên dưới.

---

### 2. Dành cho Tập Tin (Hình ảnh, Video, Tài liệu Word, Excel, PDF...)

#### 🔒 Cách Mã Hoá (Khoá tập tin):
1. Chọn thẻ **"Tập Tin"**.
2. Nhấp vào khung nét đứt để chọn file từ máy, hoặc **kéo thả file** trực tiếp vào khung *(hỗ trợ cả dán file bằng phím `Ctrl + V`)*.
3. Đặt mật khẩu bảo vệ vào ô **"Mật mã bảo vệ"**.
4. Bấm nút **"Mã hoá Tập tin"**.
5. Đợi thanh tiến trình chạy đến 100%, bấm nút **"Tải xuống tập tin"** để lưu file đã khoá về máy (file sẽ có đuôi dạng `.enc`, ví dụ: `hinh_anh.jpg.enc`).

#### 🔓 Cách Giải Mã (Mở lại tập tin gốc):
1. Chọn/Kéo thả file có đuôi `.enc` đã mã hoá vào khung.
2. Nhập chính xác mật khẩu bảo vệ.
3. Bấm nút **"Giải mã Tập tin"**.
4. Bấm **"Tải xuống tập tin"** để nhận lại file gốc ban đầu với đầy đủ tên gọi và chất lượng như lúc chưa khoá.

---

## ⚠️ Lưu Ý CỰC KỲ QUAN TRỌNG

> 🔴 **1. Không có tính năng "Quên mật khẩu":**
> Do cơ chế bảo mật tuyệt đối không lưu dữ liệu, **nếu bạn quên mật khẩu, KHÔNG MỘT AI (kể cả tác giả) có thể giúp bạn lấy lại dữ liệu.** Hãy ghi nhớ thật kỹ hoặc lưu mật khẩu ở nơi an toàn!
>
> 🔴 **2. Giới hạn dung lượng tập tin khuyên dùng:**
> Vì chương trình chạy trực tiếp bằng bộ nhớ RAM của trình duyệt web, để máy hoạt động trơn tru nhất và không bị văng trình duyệt, **bạn nên xử lý các tập tin có dung lượng dưới 200MB - 300MB**.
>
> 🔴 **3. Tự động bảo mật khi rời màn hình:**
> Khi bạn chuyển qua ứng dụng khác hoặc ẩn trình duyệt, mật khẩu đang gõ trên màn hình sẽ **tự động xoá** để tránh người bên cạnh nhìn lén.

---

## ❓ Câu Hỏi Thường Gặp (FAQ)

* **Hỏi: Người tạo ra trang web này có đọc được file hay tin nhắn của tôi không?**  
  *Đáp:* **Hoàn toàn không!** Trang web này hoạt động 100% độc lập trên trình duyệt của máy bạn (Client-Side). Không có bất kỳ gói tin nào được gửi ra ngoài Internet.
* **Hỏi: Tôi gửi file đã mã hoá qua Gmail/Zalo thì người khác có xem được không?**  
  *Đáp:* Không. Kể cả tin tặc hay người nhận tải được file về, nếu không có mật khẩu của bạn thì file đó chỉ là một đống dữ liệu vô nghĩa không thể đọc được.
* **Hỏi: Tôi có cần cài thêm phần mềm nào không?**  
  *Đáp:* Không cần. Chỉ cần một trình duyệt web hiện đại (Google Chrome, Cốc Cốc, Safari, Edge, Firefox trên điện thoại hoặc máy tính) là sử dụng được ngay.

---
**Tác giả:** Dương Tấn Chánh  
*Bảo mật — Riêng tư — Đơn giản — Tiện lợi*
