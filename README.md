# QBK Chứng khoán (app)

Web app (PWA) xem kết quả của 9 AI agent phân tích cổ phiếu Việt Nam. Repo này **chỉ chứa giao diện** và file dữ liệu
đã mã hóa `data.enc.json`. File dữ liệu do repo private `QBK-CK-engine` cập nhật mỗi giờ (giống QBK-app / QBK-Company).

- **Bản tin**: VN-Index, bản tin sáng, tin tức đã được AI phân loại và chấm tâm lý
- **Tiềm năng**: kết quả phễu lọc của Stock Scout, có nút phân tích sâu
- **Phân tích**: gửi lệnh cho đội agent, đọc báo cáo (4 chuyên viên, tranh luận Bull/Bear, rủi ro, quyết định)
- **Theo dõi**: watchlist, cảnh báo Telegram
- **Lịch sử**: các khuyến nghị đã đưa ra, các lần Scout chạy, chi phí API

Dữ liệu được mã hóa AES-256-GCM (khóa sinh bằng PBKDF2-SHA256) và giải mã ngay trên trình duyệt bằng mật khẩu app.
Hướng dẫn cài đặt nằm trong README của `QBK-CK-engine`.
