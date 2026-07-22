---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Hiểu kiến trúc mạng của Amazon VPC.
* Thiết kế và triển khai hạ tầng mạng riêng trên AWS.
* Áp dụng các cơ chế bảo mật để kiểm soát lưu lượng truy cập giữa các tài nguyên.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu kiến trúc Amazon VPC.<br>- Tìm hiểu CIDR Block, Public Subnet, Private Subnet và Route Table.<br>- Phân tích mô hình mạng sử dụng trong các ứng dụng triển khai trên AWS. | 04/05/2026 | 04/05/2026 | https://docs.aws.amazon.com/vpc/ <br> https://000003.awsstudygroup.com/ |
| 3 | - Thiết kế và tạo Virtual Private Cloud (VPC).<br>- Cấu hình Public Subnet và Private Subnet.<br>- Thiết lập Route Table và Internet Gateway để kết nối Internet cho Public Subnet. | 05/05/2026 | 05/05/2026 | https://docs.aws.amazon.com/vpc/ |
| 4 | - Tìm hiểu các cơ chế bảo mật trên AWS.<br>- Cấu hình Security Group và Network ACL cho VPC.<br>- So sánh phạm vi hoạt động và cách sử dụng của Security Group và Network ACL. | 06/05/2026 | 06/05/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security.html |
| 5 | - Thực hành triển khai EC2 trong Public Subnet và Private Subnet.<br>- Kiểm tra khả năng truy cập giữa các máy chủ thông qua Security Group.<br>- Đánh giá kết quả bằng các công cụ SSH và Ping (trong phạm vi cho phép). | 07/05/2026 | 07/05/2026 | https://docs.aws.amazon.com/ec2/ |
| 6 | - Rà soát toàn bộ kiến trúc mạng đã triển khai.<br>- Kiểm thử các quy tắc định tuyến và bảo mật.<br>- Xóa các tài nguyên không còn sử dụng và hoàn thiện tài liệu ghi chú. | 08/05/2026 | 08/05/2026 | https://docs.aws.amazon.com/ |

### Kết quả đạt được tuần 3:

* Hiểu được vai trò của Amazon VPC trong việc xây dựng hạ tầng mạng trên AWS.
* Thiết kế và triển khai thành công một Virtual Private Cloud với Public Subnet và Private Subnet.
* Cấu hình được Internet Gateway và Route Table để điều hướng lưu lượng mạng.
* Hiểu sự khác biệt giữa Security Group và Network ACL, đồng thời áp dụng phù hợp cho từng trường hợp.
* Kiểm tra thành công khả năng kết nối giữa các tài nguyên trong VPC theo các chính sách bảo mật đã thiết lập.
* Có khả năng xây dựng một kiến trúc mạng AWS cơ bản đáp ứng yêu cầu về kết nối và bảo mật.