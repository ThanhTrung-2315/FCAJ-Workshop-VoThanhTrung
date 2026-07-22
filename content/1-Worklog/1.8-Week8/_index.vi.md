---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Hiểu quy trình Continuous Integration và Continuous Delivery (CI/CD).
* Xây dựng Pipeline để tự động hóa việc build và triển khai ứng dụng.
* Tích hợp các dịch vụ AWS phục vụ quy trình phát triển và phát hành phần mềm.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu mô hình CI/CD và các giai đoạn Build, Test và Deploy.<br>- Tìm hiểu vai trò của AWS CodeCommit, CodeBuild, CodeDeploy và CodePipeline.<br>- Thiết kế quy trình triển khai phù hợp với kiến trúc của dự án. | 08/06/2026 | 08/06/2026 | https://docs.aws.amazon.com/codepipeline/ <br> https://000010.awsstudygroup.com/ |
| 3 | - Tạo kho mã nguồn trên AWS CodeCommit hoặc kết nối kho GitHub hiện có.<br>- Thiết lập quyền truy cập và đồng bộ mã nguồn.<br>- Kiểm tra quá trình cập nhật mã nguồn từ môi trường phát triển. | 09/06/2026 | 09/06/2026 | https://docs.aws.amazon.com/codecommit/ |
| 4 | - Cấu hình AWS CodeBuild để tự động build ứng dụng.<br>- Tạo tệp buildspec.yml và thiết lập các bước build.<br>- Kiểm tra kết quả build và xử lý lỗi nếu phát sinh. | 10/06/2026 | 10/06/2026 | https://docs.aws.amazon.com/codebuild/ |
| 5 | - Thiết lập AWS CodePipeline để kết nối Source, Build và Deploy.<br>- Cấu hình triển khai ứng dụng lên Amazon ECS sau khi build thành công.<br>- Thực hiện cập nhật mã nguồn và theo dõi Pipeline tự động chạy. | 11/06/2026 | 11/06/2026 | https://docs.aws.amazon.com/codepipeline/ |
| 6 | - Kiểm tra toàn bộ quy trình CI/CD từ khi thay đổi mã nguồn đến khi ứng dụng được cập nhật trên Amazon ECS.<br>- Đánh giá hiệu quả của Pipeline và tối ưu thời gian triển khai.<br>- Hoàn thiện tài liệu và dọn dẹp các tài nguyên thử nghiệm. | 12/06/2026 | 12/06/2026 | https://docs.aws.amazon.com/devops-guru/latest/userguide/welcome.html |

### Kết quả đạt được tuần 8:

* Hiểu quy trình Continuous Integration và Continuous Delivery trong phát triển phần mềm.
* Thiết lập thành công kho mã nguồn phục vụ Pipeline triển khai.
* Cấu hình AWS CodeBuild để tự động build ứng dụng sau mỗi lần cập nhật mã nguồn.
* Xây dựng Pipeline tự động bằng AWS CodePipeline kết nối các giai đoạn Source, Build và Deploy.
* Triển khai thành công phiên bản mới của ứng dụng lên Amazon ECS thông qua quy trình CI/CD.
* Có khả năng áp dụng quy trình CI/CD nhằm rút ngắn thời gian triển khai và giảm thao tác thủ công trong quá trình phát triển phần mềm.