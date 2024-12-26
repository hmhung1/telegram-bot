# Bot Telegram đơn giản bằng Node.js
Đây là một bot Telegram đơn giản được xây dựng bằng Node.js. Bot này hỗ trợ các tính năng cơ bản như:
- Xử lý các lệnh được định nghĩa trong thư mục `./plugins/commands`.
- Xử lý các sự kiện được định nghĩa trong thư mục `./plugins/events`.
## Cách sử dụng
1. **Cài đặt các gói cần thiết:**
   ```bash
   npm install
   ```
Tạo một file .env trong thư mục gốc của dự án và thêm TOKEN của bot Telegram vào đó:
   TOKEN="YOUR_BOT_TOKEN", thêm API key của gemini vào GEMINI_API_KEY="YOUR_API_HERE" nếu cần sử dụng AI (Không bắt buộc)
  
2. **Khởi động bot:**
   ```bash
   npm start
   ```
