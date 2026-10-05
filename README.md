# 🛡️ PHẦN MỀM MÃ HOÁ & GIẢI MÃ BẢO MẬT AES-256
**Tác giả:** Dương Tấn Chánh  
**Phiên bản định dạng:** DTC_ENC_01  

---

## 🌟 GIỚI THIỆU
Đây là công cụ **bảo vệ thông tin cá nhân và tài liệu mật** trực tiếp trên trình duyệt của bạn (máy tính hoặc điện thoại). 

Bạn có thể dùng phần mềm để:
* **Khoá tin nhắn/nội dung quan trọng** thành một chuỗi ký tự bí mật để gửi qua Zalo, Messenger, Telegram, Email mà không sợ bị đọc trộm.
* **Khoá các tập tin nhạy cảm** (ảnh chụp căn cước, tài liệu công việc, hợp đồng, video, file Word, Excel, PDF...) thành một tập tin bảo mật đuôi `.enc`. Chỉ người có đúng mật mã mới có thể mở và xem lại file gốc.

---

## 💎 ĐIỂM ĐẶC BIỆT CỦA PHẦN MỀM
1. **Hoạt động 100% Offline (Không qua máy chủ):** Dữ liệu của bạn được xử lý trực tiếp trên máy của bạn. Bạn hoàn toàn có thể **tắt Wifi / 4G** trước khi dùng. Không một ai (kể cả tác giả hay máy chủ web) có thể tiếp cận được thông tin của bạn.
2. **Không cần cài đặt:** Ứng dụng chỉ gồm **1 file duy nhất (`index.html`)**, lưu trên máy tính, điện thoại hoặc USB, nhấp đúp là mở ra dùng ngay.
3. **Bảo mật chuẩn quân sự:** Ứng dụng thuật toán mã hoá cao cấp nhất thế giới hiện nay (**AES-256-GCM**) kết hợp **600.000 vòng bảo vệ mật mã**. Siêu máy tính cũng không thể bẻ khoá nếu mật mã của bạn đủ mạnh.
4. **Chia sẻ riêng tư tuyệt đối (Zero-Knowledge):** Khi gửi liên kết mã hoá, dữ liệu được giữ kín trên trình duyệt của bạn, hoàn toàn không bị lưu lại trong nhật ký của các nhà mạng hay máy chủ mạng.

---

### 📝 1. CÁCH MÃ HOÁ & GIẢI MÃ VĂN BẢN (TIN NHẮN, MẬT KHẨU...)

#### A. Khi bạn muốn Mã hoá (Khoá chữ lại):
1. Tại tab **"Văn Bản"**, nhập hoặc dán nội dung bí mật vào ô lớn phía trên.
2. Nhập một **Mật mã bảo vệ** vào ô mật mã bên dưới (Bạn có thể bấm nút **"Chép mật mã"** để lưu lại mật mã vào bộ nhớ tạm).
3. Bấm nút màu xanh **"🔒 Mã hoá"**.
4. Kết quả xuất hiện bên dưới dạng một chuỗi ký tự mã hoá:
   * Bấm **"📋 Sao chép kết quả"** để gửi đoạn chữ bí mật cho người nhận.
   * Hoặc bấm **"🔗 Chia sẻ (Hash)"** để tạo liên kết tự động gửi qua tin nhắn.

#### B. Khi bạn nhận được tin nhắn mã hoá (Mở khoá ra xem):
1. Dán chuỗi ký tự bí mật vào ô lớn phía trên (hệ thống sẽ tự nhận diện).
2. Nhập chính xác **Mật mã** mà người gửi đã cung cấp.
3. Bấm nút màu tím **"🔓 Giải mã"**.
4. Nội dung ban đầu sẽ hiện ra đầy đủ và rõ ràng.

---

### 📁 2. CÁCH MÃ HOÁ & GIẢI MÃ TẬP TIN (ẢNH, WORD, EXCEL, PDF...)

#### A. Khi bạn muốn Mã hoá tập tin:
1. Chuyển sang tab **"Tập Tin"**.
2. Chọn tập tin cần bảo vệ bằng 1 trong 3 cách:
   * **Bấm vào khung nét đứt** để chọn file từ máy.
   * **Kéo file từ máy tính** thả vào khung.
   * **Dán file (Ctrl+V)** nếu bạn vừa copy một file.
3. Nhập **Mật mã bảo vệ**.
4. Bấm nút **"🔒 Mã hoá Tập tin"**.
5. Sau khi thanh tiến trình chạy xong, bấm nút **"📥 Tải xuống tập tin"**. Bạn sẽ nhận được file mới có đuôi mở rộng `.enc` (ví dụ: `Hoso_canhan.pdf.enc`).

#### B. Khi bạn muốn Giải mã tập tin `.enc`:
1. Chuyển sang tab **"Tập Tin"**.
2. Chọn hoặc kéo thả tập tin đuôi `.enc` vào khung.
3. Nhập chính xác **Mật mã bảo vệ**.
4. Bấm nút **"🔓 Giải mã Tập tin"**.
5. Bấm **"📥 Tải xuống tập tin"**. Tập tin gốc với đúng tên và định dạng ban đầu sẽ được phục hồi hoàn toàn nguyên vẹn!

---

## ⚠️ NHỮNG NGUYÊN TẮC BẢO MẬT BẮT BUỘC PHẢI NHỚ

1. **Mất mật mã là MẤT DỮ LIỆU VĨNH VIỄN:**
   * Vì phần mềm bảo mật tuyệt đối và không có máy chủ lưu lại thông tin, **hoàn toàn KHÔNG CÓ nút "Quên mật khẩu" hay "Khôi phục mật khẩu"**. 
   * Nếu bạn quên mật mã, không một ai trên thế giới có thể lấy lại dữ liệu cho bạn. Hãy ghi nhớ hoặc lưu mật mã ở nơi an toàn!
2. **Tránh đặt mật mã dễ đoán:**
   * Hệ thống có bộ lọc thông minh tự động cảnh báo: Tuyệt đối không đặt mật mã như `123456`, `password`, `matkhau`, `admin` hoặc dãy số tăng dần.
   * Nên đặt mật mã có từ 12 ký tự trở lên, kết hợp chữ hoa, chữ thường, số và ký tự đặc biệt (ví dụ: `Khaosat#2024!BaoMat`).
3. **Giới hạn dung lượng tập tin:**
   * Để đảm bảo trình duyệt chạy nhanh và không làm đơ điện thoại/máy tính, phần mềm quy định dung lượng tập tin tối đa là **300 MB** cho mỗi lần xử lý.
4. **Bảo mật chống nhìn trộm:**
   * Khi bạn thu nhỏ trình duyệt, chuyển qua ứng dụng khác hoặc rời khỏi trang web, phần mềm sẽ **tự động xoá mật mã** đang hiển thị trên màn hình để bảo vệ bạn trước những người xung quanh.

---

## ❓ CÂU HỎI THƯỜNG GẶP (FAQ)

* **Hỏi: Người nhận có cần cài đặt phần mềm này không?**
  * *Trả lời:* Không. Bạn chỉ cần gửi file web `index.html` này cho người nhận, họ mở lên bằng trình duyệt và nhập đúng mật mã là giải mã được ngay.
* **Hỏi: Phần mềm có lấy cắp dữ liệu của tôi gửi lên mạng không?**
  * *Trả lời:* Hoàn toàn không. Bạn có thể rút dây mạng hoặc ngắt kết nối Wifi/4G rồi bấm mã hoá/giải mã, ứng dụng vẫn hoạt động bình thường. Toàn bộ mã nguồn chạy bằng JavaScript nội bộ trên máy bạn.
* **Hỏi: File `.enc` có an toàn khi gửi qua Google Drive, Zalo hay Email không?**
  * *Trả lời:* Cực kỳ an toàn. Tập tin `.enc` đã được khoá bằng thuật toán mã hoá mạnh nhất thế giới. Kể cả tin tặc hay nhà cung cấp dịch vụ mạng cũng chỉ thấy một khối dữ liệu vô nghĩa nếu không có mật mã của bạn.

---
*Chúc bạn có những trải nghiệm bảo mật thông tin an toàn và tiện lợi nhất!*
