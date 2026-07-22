---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---



### Mục tiêu tuần 9:

* Kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|---|---|---|---|---|
| 1 | - Tìm hiểu Amazon API Gateway (WebSocket).<br>  + Connection.<br>  + Route.<br>  + Integration.<br>- Xây dựng kết nối WebSocket đơn giản. | 28/06/2026 | 28/06/2026 | https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html |
| 2 | - Tìm hiểu Amazon DynamoDB.<br>  + Table.<br>  + Partition Key.<br>  + Query.<br>- Thực hành lưu Connection ID của WebSocket. | 28/06/2026 | 28/06/2026 | AWS DynamoDB Documentation |
| 3 | - Tìm hiểu AWS Secrets Manager.<br>- Lưu trữ Secret và truy xuất Secret từ Lambda Function. | 29/06/2026 | 29/06/2026 | AWS Secrets Manager Documentation |
| 4 | - Tìm hiểu Amazon SES.<br>  + Xác minh Email.<br>  + Gửi Email bằng Lambda.<br>- Thực hành gửi Email thông báo. | 29/06/2026 | 29/06/2026 | AWS SES Documentation |
| 5 | - Xây dựng luồng Notification mẫu: Lambda → DynamoDB → WebSocket → SES.<br>- Kiểm thử gửi thông báo thời gian thực và Email. | 30/06/2026 | 30/06/2026 | AWS Documentation |

### Kết quả đạt được tuần 9:

* Hiểu AWS là gì và nắm được các nhóm dịch vụ cơ bản: 
  * Compute
  * Storage
  * Networking 
  * Database
  * ...

* Đã tạo và cấu hình AWS Free Tier account thành công.

* Làm quen với AWS Management Console và biết cách tìm, truy cập, sử dụng dịch vụ từ giao diện web.

* Cài đặt và cấu hình AWS CLI trên máy tính bao gồm:
  * Access Key
  * Secret Key
  * Region mặc định
  * ...

* Sử dụng AWS CLI để thực hiện các thao tác cơ bản như:

  * Kiểm tra thông tin tài khoản & cấu hình
  * Lấy danh sách region
  * Xem dịch vụ EC2
  * Tạo và quản lý key pair
  * Kiểm tra thông tin dịch vụ đang chạy
  * ...

* Có khả năng kết nối giữa giao diện web và CLI để quản lý tài nguyên AWS song song.
* ...


