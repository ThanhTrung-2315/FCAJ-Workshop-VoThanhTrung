---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Hiểu nguyên lý hoạt động của Elastic Load Balancing (ELB).
* Triển khai Auto Scaling để tự động mở rộng và thu hẹp hệ thống.
* Đánh giá khả năng cân bằng tải và tính sẵn sàng của ứng dụng trên AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu kiến trúc Elastic Load Balancing (ELB).<br>- Phân biệt các loại Load Balancer trên AWS.<br>- Tìm hiểu cơ chế phân phối lưu lượng truy cập giữa nhiều EC2 Instances. | 11/05/2026 | 11/05/2026 | https://docs.aws.amazon.com/elasticloadbalancing/ <br> https://000006.awsstudygroup.com/ |
| 3 | - Chuẩn bị môi trường triển khai gồm VPC, Subnet và các EC2 Instances.<br>- Tạo Target Group và đăng ký các EC2 Instances.<br>- Cấu hình Application Load Balancer (ALB) để cân bằng tải cho hệ thống. | 12/05/2026 | 12/05/2026 | https://docs.aws.amazon.com/elasticloadbalancing/ |
| 4 | - Nghiên cứu Amazon EC2 Auto Scaling.<br>- Tạo Launch Template và Auto Scaling Group.<br>- Thiết lập số lượng Instance tối thiểu, tối đa và mong muốn của hệ thống. | 13/05/2026 | 13/05/2026 | https://docs.aws.amazon.com/autoscaling/ |
| 5 | - Thiết lập Scaling Policy dựa trên chỉ số CPU Utilization.<br>- Thực hiện kiểm thử bằng cách tạo tải cho hệ thống.<br>- Theo dõi quá trình tự động mở rộng và thu hẹp của EC2 Instances. | 14/05/2026 | 14/05/2026 | https://docs.aws.amazon.com/autoscaling/ |
| 6 | - Đánh giá hiệu quả của Load Balancer và Auto Scaling.<br>- Kiểm tra Health Check của Target Group.<br>- Dọn dẹp toàn bộ tài nguyên đã sử dụng và cập nhật tài liệu thực hành. | 15/05/2026 | 15/05/2026 | https://docs.aws.amazon.com/ |

### Kết quả đạt được tuần 4:

* Hiểu cách Elastic Load Balancing phân phối lưu lượng truy cập đến nhiều máy chủ.
* Triển khai thành công Application Load Balancer kết nối với nhiều EC2 Instances.
* Xây dựng Auto Scaling Group dựa trên Launch Template.
* Thiết lập được các chính sách Auto Scaling theo mức sử dụng tài nguyên của hệ thống.
* Kiểm chứng khả năng tự động mở rộng và thu hẹp số lượng EC2 Instances khi tải thay đổi.
* Hiểu cách kết hợp ELB và Auto Scaling để nâng cao tính sẵn sàng và khả năng mở rộng của ứng dụng trên AWS.