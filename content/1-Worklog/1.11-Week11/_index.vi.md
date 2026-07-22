---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
|---|---|---|---|---|
| 1 | - Khởi tạo dự án WebFood.<br>- Thiết kế cấu trúc Backend theo mô hình Serverless.<br>- Xây dựng các API cơ bản bằng Amazon API Gateway và AWS Lambda (Đăng nhập, Đăng ký, Danh mục món ăn). | 02/07/2026 | 02/07/2026 | AWS Lambda Documentation<br>API Gateway Documentation |
| 2 | - Kết nối Backend với MongoDB Atlas.<br>- Xây dựng các API CRUD cho món ăn, nhà hàng và đơn hàng.<br>- Lưu thông tin cấu hình bằng AWS Secrets Manager. | 02/07/2026 | 02/07/2026 | MongoDB Atlas Documentation<br>AWS Secrets Manager Documentation |
| 3 | - Tích hợp Amazon S3 để lưu trữ hình ảnh món ăn.<br>- Cấu hình CloudFront để phân phối nội dung và tối ưu tốc độ truy cập.<br>- Thiết lập AWS WAF bảo vệ API và CloudFront. | 03/07/2026 | 03/07/2026 | MoMo Developer Documentation (TBD) |
| 4 | - Tích hợp thanh toán MoMo.<br>- Xây dựng API tạo giao dịch thanh toán.<br>- Xử lý Callback/IPN và cập nhật trạng thái đơn hàng. | 03/07/2026 | 03/07/2026 | MoMo Developer Documentation |
| 5 | - Tích hợp EventBridge, SQS và Amazon SES.<br>- Gửi Email xác nhận đơn hàng sau khi thanh toán thành công.<br>- Kiểm thử toàn bộ luồng xử lý đơn hàng. | 04/07/2026 | 06/07/2026 | AWS EventBridge Documentation<br>Amazon SQS Documentation<br>Amazon SES Documentation |

### Kết quả đạt được tuần 11:

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


