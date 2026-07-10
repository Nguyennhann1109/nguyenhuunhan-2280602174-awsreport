---
title : "Tuần 8"
date : "`r Sys.Date()`"
weight : 8
chapter : false
pre : "<b>1.8</b>"
---

# Xây dựng Nền tảng Backend Realtime

## Mục tiêu

- Khởi tạo dịch vụ Backend Realtime cho hệ thống.
- Xây dựng nền tảng giao tiếp thời gian thực bằng Socket.IO.
- Thiết lập môi trường phát triển, Redis và cơ chế xác thực người dùng qua JWT.

## Thời gian thực hiện

**Từ ngày 05/06/2026 đến ngày 11/06/2026**

## Nội dung thực hiện

| Thứ | Nội dung thực hiện | Tài liệu tham khảo |
|:---:|--------------------|--------------------|
| **6** | Khởi tạo project **Backend Realtime** sử dụng Node.js và Express.<br><br>Cài đặt các thư viện cần thiết như Socket.IO, Redis, PostgreSQL và JWT. | Socket.IO Documentation<br>Express.js Documentation |
| **7** | Xây dựng kiến trúc project theo từng module gồm Config, Services, Handlers, Sockets và Middlewares.<br><br>Cấu hình môi trường phát triển và các biến môi trường (.env). | Node.js Documentation |
| **2** | Thiết lập kết nối PostgreSQL và Redis.<br><br>Khởi tạo Redis Client phục vụ cho việc lưu trạng thái và đồng bộ dữ liệu giữa các service. | Redis Documentation<br>PostgreSQL Documentation |
| **3** | Xây dựng cơ chế xác thực Socket bằng JWT thông qua Socket Middleware.<br><br>Kiểm tra và xác thực người dùng trước khi thiết lập kết nối WebSocket. | JWT Documentation<br>Socket.IO Middleware |
| **4** | Thiết lập Socket Connection và xử lý quá trình người dùng kết nối hoặc ngắt kết nối khỏi hệ thống.<br><br>Kiểm tra hoạt động của Backend Realtime trong môi trường phát triển. | Socket.IO Documentation |

## Kết quả đạt được

Sau khi hoàn thành tuần thứ tám, em đã đạt được các kết quả sau:

- Khởi tạo thành công dự án Backend Realtime bằng Node.js và Express.
- Thiết lập được môi trường phát triển cho hệ thống WebSocket.
- Kết nối thành công Redis và PostgreSQL phục vụ cho Backend Realtime.
- Xây dựng cơ chế xác thực người dùng thông qua JWT trước khi kết nối Socket.
- Hoàn thành nền tảng ban đầu cho các chức năng Realtime sẽ được phát triển trong các tuần tiếp theo.
