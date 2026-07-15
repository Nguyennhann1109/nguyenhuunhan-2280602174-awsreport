---
title : "Tuần 9"
date : "`r Sys.Date()`"
weight : 9
chapter : false
pre : "<b>1.9</b>"
---

# Phát triển Chức năng Giao tiếp Thời gian thực

## Mục tiêu

- Xây dựng các chức năng giao tiếp thời gian thực cho hệ thống.
- Triển khai cơ chế quản lý trạng thái người dùng (Presence).
- Đồng bộ dữ liệu giữa các Backend Realtime thông qua Redis Pub/Sub.

## Thời gian thực hiện

**Từ ngày 12/06/2026 đến ngày 18/06/2026**

## Nội dung thực hiện

| Thứ | Nội dung thực hiện | Tài liệu tham khảo |
|:---:|--------------------|--------------------|
| **6** | Xây dựng **Presence Service** để quản lý trạng thái Online/Offline của người dùng.<br><br>Xử lý các sự kiện khi người dùng kết nối hoặc ngắt kết nối khỏi hệ thống. | Socket.IO Documentation<br>Redis Documentation |
| **7** | Triển khai **Redis Pub/Sub** để đồng bộ dữ liệu giữa nhiều Backend Realtime Instance.<br><br>Kiểm tra việc truyền và nhận sự kiện giữa các Redis Channels. | Redis Pub/Sub Documentation |
| **2** | Xây dựng **Chat Handler** để tiếp nhận, xử lý và phát sự kiện tin nhắn theo thời gian thực.<br><br>Kiểm tra quá trình gửi và nhận tin nhắn giữa nhiều người dùng. | Socket.IO Documentation |
| **3** | Xây dựng **Cache Service** sử dụng Redis để lưu trữ thông tin người dùng đang trực tuyến và dữ liệu tạm thời.<br><br>Tối ưu tốc độ truy xuất dữ liệu Realtime. | Redis Documentation |
| **4** | Kiểm thử các chức năng Realtime đã triển khai.<br><br>Đánh giá khả năng đồng bộ dữ liệu và xử lý nhiều kết nối đồng thời của hệ thống. | Ghi chú cá nhân |

## Kết quả đạt được

Sau khi hoàn thành tuần thứ chín, em đã đạt được các kết quả sau:

- Xây dựng thành công chức năng quản lý trạng thái Online/Offline của người dùng.
- Triển khai Redis Pub/Sub để đồng bộ dữ liệu giữa các Backend Realtime.
- Hoàn thành chức năng xử lý và truyền tải tin nhắn theo thời gian thực.
- Áp dụng Redis Cache nhằm nâng cao hiệu năng truy xuất dữ liệu.
- Đảm bảo các chức năng Realtime hoạt động ổn định trong môi trường phát triển.

