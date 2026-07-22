---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Hiểu khái niệm Infrastructure as Code (IaC) trên AWS.
* Sử dụng AWS CloudFormation để tự động triển khai hạ tầng.
* Quản lý và cập nhật tài nguyên AWS thông qua CloudFormation Stack.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu khái niệm Infrastructure as Code (IaC).<br>- Nghiên cứu kiến trúc và quy trình hoạt động của AWS CloudFormation.<br>- Tìm hiểu cấu trúc của CloudFormation Template gồm Resources, Parameters, Outputs và Mappings. | 25/05/2026 | 25/05/2026 | https://docs.aws.amazon.com/cloudformation/ <br> https://000008.awsstudygroup.com/ |
| 3 | - Viết CloudFormation Template bằng định dạng YAML.<br>- Khai báo các tài nguyên cơ bản như Amazon S3 Bucket và Security Group.<br>- Kiểm tra cú pháp và xác thực Template trước khi triển khai. | 26/05/2026 | 26/05/2026 | https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-guide.html |
| 4 | - Tạo CloudFormation Stack từ Template đã xây dựng.<br>- Theo dõi quá trình tạo Stack và kiểm tra các tài nguyên được khởi tạo.<br>- Phân tích các sự kiện (Events) và xử lý lỗi nếu có. | 27/05/2026 | 27/05/2026 | https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/stacks.html |
| 5 | - Cập nhật CloudFormation Stack để bổ sung hoặc chỉnh sửa tài nguyên.<br>- Quan sát cơ chế Update Stack và Change Set.<br>- Thực hành xóa Stack và kiểm tra việc tự động giải phóng tài nguyên AWS. | 28/05/2026 | 28/05/2026 | https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks.html |
| 6 | - Đánh giá lợi ích của CloudFormation trong quản lý hạ tầng AWS.<br>- Tổng hợp Template và tài liệu thực hành.<br>- Chuẩn bị các Template sẽ sử dụng cho các tuần tiếp theo của dự án. | 29/05/2026 | 29/05/2026 | https://docs.aws.amazon.com/cloudformation/ |

### Kết quả đạt được tuần 6:

* Hiểu được nguyên lý Infrastructure as Code và vai trò của AWS CloudFormation trong tự động hóa hạ tầng.
* Xây dựng được CloudFormation Template bằng định dạng YAML.
* Triển khai thành công CloudFormation Stack để tạo tài nguyên AWS tự động.
* Thực hiện cập nhật và quản lý tài nguyên thông qua Stack mà không cần thao tác thủ công trên AWS Console.
* Hiểu quy trình theo dõi trạng thái Stack, phân tích Events và xử lý lỗi khi triển khai.
* Có khả năng tái sử dụng CloudFormation Template để triển khai hạ tầng một cách nhất quán và tiết kiệm thời gian.