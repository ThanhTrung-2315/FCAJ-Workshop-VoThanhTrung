---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Hiểu vai trò của Amazon CloudWatch trong việc giám sát tài nguyên AWS.
* Thu thập và phân tích các chỉ số hoạt động của hệ thống.
* Thiết lập cảnh báo để theo dõi và xử lý các sự cố kịp thời.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu tổng quan về Amazon CloudWatch và các thành phần chính.<br>- Nghiên cứu Metrics, Logs, Events và Dashboards.<br>- Tìm hiểu cách CloudWatch thu thập dữ liệu từ các dịch vụ AWS. | 18/05/2026 | 18/05/2026 | https://docs.aws.amazon.com/cloudwatch/ <br> https://000007.awsstudygroup.com/ |
| 3 | - Theo dõi các chỉ số hoạt động của Amazon EC2 và Amazon RDS.<br>- Phân tích CPU Utilization, Memory, Network In/Out và Disk Read/Write.<br>- Tùy chỉnh giao diện CloudWatch Dashboard để hiển thị các thông số quan trọng. | 19/05/2026 | 19/05/2026 | https://docs.aws.amazon.com/cloudwatch/ |
| 4 | - Cấu hình CloudWatch Logs để thu thập nhật ký từ EC2.<br>- Tạo Log Group và Log Stream.<br>- Kiểm tra khả năng ghi nhận và truy xuất log trên CloudWatch. | 20/05/2026 | 20/05/2026 | https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/ |
| 5 | - Thiết lập CloudWatch Alarm dựa trên ngưỡng CPU Utilization.<br>- Cấu hình Amazon SNS để gửi thông báo khi hệ thống vượt ngưỡng cảnh báo.<br>- Kiểm thử cơ chế cảnh báo bằng cách tạo tải cho EC2 Instance. | 21/05/2026 | 21/05/2026 | https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/ |
| 6 | - Đánh giá dữ liệu giám sát thu thập được trong tuần.<br>- Kiểm tra lịch sử cảnh báo và nhật ký hệ thống.<br>- Tổng hợp kết quả thực hành và tối ưu cấu hình CloudWatch cho hệ thống. | 22/05/2026 | 22/05/2026 | https://docs.aws.amazon.com/cloudwatch/ |

### Kết quả đạt được tuần 5:

* Hiểu được chức năng của Amazon CloudWatch trong việc giám sát tài nguyên và dịch vụ AWS.
* Theo dõi được các chỉ số hoạt động quan trọng của Amazon EC2 và Amazon RDS.
* Xây dựng Dashboard để trực quan hóa tình trạng hoạt động của hệ thống.
* Thu thập và quản lý nhật ký hệ thống bằng CloudWatch Logs.
* Thiết lập thành công CloudWatch Alarm kết hợp Amazon SNS để gửi cảnh báo tự động.
* Có khả năng giám sát, phát hiện và phản ứng kịp thời với các sự cố phát sinh trong môi trường AWS.