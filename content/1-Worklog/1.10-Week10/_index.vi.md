---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Đánh giá hiệu năng của hệ thống dưới nhiều mức tải khác nhau.
* Kiểm tra và tăng cường cấu hình bảo mật cho các dịch vụ AWS.
* Xác nhận hệ thống đáp ứng các yêu cầu về tính ổn định và an toàn trước khi hoàn thiện dự án.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Đánh giá hiệu năng tổng thể của hệ thống sau các giai đoạn triển khai và tối ưu.<br>- Xác định các chỉ số cần theo dõi như CPU Utilization, Memory Usage, Response Time và Throughput.<br>- Xây dựng kế hoạch kiểm thử hiệu năng. | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/ <br> https://000012.awsstudygroup.com/ |
| 3 | - Thực hiện kiểm thử tải đối với ứng dụng để đánh giá khả năng xử lý đồng thời.<br>- Theo dõi các chỉ số của Amazon EC2, Amazon ECS và Amazon RDS thông qua Amazon CloudWatch.<br>- Phân tích các điểm nghẽn ảnh hưởng đến hiệu năng của hệ thống. | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/cloudwatch/ |
| 4 | - Rà soát cấu hình IAM, Security Group và Network ACL.<br>- Kiểm tra quyền truy cập của người dùng và các dịch vụ AWS.<br>- Đánh giá việc áp dụng nguyên tắc Least Privilege trong hệ thống. | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/ |
| 5 | - Kiểm tra cấu hình mã hóa dữ liệu trên Amazon S3 và Amazon RDS.<br>- Đánh giá các cơ chế sao lưu và khôi phục dữ liệu.<br>- Kiểm tra khả năng ghi nhận và theo dõi sự kiện bảo mật thông qua AWS CloudTrail. | 25/06/2026 | 25/06/2026 | https://docs.aws.amazon.com/awscloudtrail/ |
| 6 | - Tổng hợp kết quả đánh giá hiệu năng và bảo mật.<br>- Đề xuất các cải tiến nhằm nâng cao tính ổn định và an toàn của hệ thống.<br>- Hoàn thiện tài liệu đánh giá phục vụ giai đoạn tổng kết dự án. | 26/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/wellarchitected/ |

### Kết quả đạt được tuần 10:

* Đánh giá được hiệu năng tổng thể của hệ thống thông qua các chỉ số vận hành và kết quả kiểm thử tải.
* Phát hiện và phân tích các điểm có thể ảnh hưởng đến hiệu suất của ứng dụng.
* Rà soát và cải thiện cấu hình bảo mật đối với IAM, Security Group và Network ACL.
* Kiểm tra việc áp dụng các cơ chế mã hóa, sao lưu và ghi nhận sự kiện bảo mật trên AWS.
* Xác nhận hệ thống đáp ứng các yêu cầu cơ bản về hiệu năng và bảo mật trước khi hoàn thiện dự án.
* Hoàn thiện báo cáo đánh giá, làm cơ sở cho giai đoạn tổng kết và bàn giao hệ thống.