---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---



### Mục tiêu tuần 8:

* Kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|---|---|---|---|---|
| 1 | - Tìm hiểu kiến trúc Event-driven Architecture trên AWS.<br>  + Event.<br>  + Producer.<br>  + Consumer.<br>  + Event Bus.<br>- Phân tích các trường hợp ứng dụng trong hệ thống ĐỒ ÁN | 23/06/2026 | 24/06/2026 | https://cloudjourney.awsstudygroup.com/<br>https://docs.aws.amazon.com/eventbridge/ |
| 2 | - Tìm hiểu Amazon EventBridge.<br>  + Event Bus.<br>  + Rule.<br>  + Target.<br>- Thực hành tạo Custom Event và Event Rule | 24/06/2026 | 25/06/2026 | AWS EventBridge Documentation |
| 3 | - Tìm hiểu Amazon SQS.<br>  + Standard Queue.<br>  + Dead Letter Queue (DLQ).<br>  + Visibility Timeout.<br>- So sánh EventBridge và SQS. | 25/06/2026 | 25/06/2026 | AWS SQS Documentation |
| 4 | - Thực hành tích hợp Lambda → EventBridge → SQS.<br>- Gửi và nhận Message giữa các thành phần của hệ thống. | 26/06/2026 | 26/06/2026 | AWS Documentation |
| 5 | - Xây dựng Lambda Worker xử lý Queue.<br>- Kiểm thử luồng xử lý bất đồng bộ và ghi log trên CloudWatch. | 27/06/2026 | 27/06/2026 | AWS Documentation |

### Kết quả đạt được tuần 8:

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


