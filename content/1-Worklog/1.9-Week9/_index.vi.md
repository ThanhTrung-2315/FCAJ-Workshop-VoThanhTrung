---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Đánh giá hiệu năng của API và cơ sở dữ liệu.
* Tối ưu truy vấn dữ liệu nhằm cải thiện tốc độ phản hồi của ứng dụng.
* Kiểm tra tính ổn định của hệ thống sau khi thực hiện các thay đổi.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Đánh giá kiến trúc API hiện tại và xác định các điểm có thể tối ưu.<br>- Phân tích thời gian phản hồi của các API thông qua quá trình kiểm thử.<br>- Xác định các truy vấn cơ sở dữ liệu có thời gian xử lý cao. | 15/06/2026 | 15/06/2026 | https://docs.aws.amazon.com/ <br> https://000011.awsstudygroup.com/ |
| 3 | - Rà soát cấu trúc bảng dữ liệu và các mối quan hệ trong Amazon RDS.<br>- Tối ưu các câu lệnh SQL và bổ sung chỉ mục (Index) cho các trường thường xuyên truy vấn.<br>- Kiểm tra sự thay đổi về hiệu năng sau khi tối ưu. | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/ |
| 4 | - Cải thiện xử lý dữ liệu trong các API bằng cách giảm truy vấn dư thừa.<br>- Kiểm tra cơ chế phân trang, lọc và sắp xếp dữ liệu.<br>- Thực hiện kiểm thử chức năng sau khi tối ưu mã nguồn. | 17/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/ |
| 5 | - Thực hiện kiểm thử tải để đánh giá khả năng xử lý của API.<br>- Theo dõi CPU, bộ nhớ và kết nối cơ sở dữ liệu thông qua Amazon CloudWatch.<br>- Ghi nhận các chỉ số hiệu năng trước và sau khi tối ưu. | 18/06/2026 | 18/06/2026 | https://docs.aws.amazon.com/cloudwatch/ |
| 6 | - Tổng hợp kết quả tối ưu API và cơ sở dữ liệu.<br>- Đánh giá mức độ cải thiện của hệ thống dựa trên các chỉ số thu thập được.<br>- Cập nhật tài liệu kỹ thuật và chuẩn bị cho giai đoạn kiểm thử tổng thể của dự án. | 19/06/2026 | 19/06/2026 | https://docs.aws.amazon.com/ |

### Kết quả đạt được tuần 9:

* Đánh giá được hiệu năng của các API và cơ sở dữ liệu trong hệ thống.
* Tối ưu các truy vấn SQL và cải thiện tốc độ truy xuất dữ liệu.
* Cải thiện thời gian phản hồi của API thông qua việc giảm các thao tác xử lý không cần thiết.
* Theo dõi và phân tích các chỉ số hiệu năng bằng Amazon CloudWatch.
* Kiểm chứng hệ thống hoạt động ổn định sau khi thực hiện các thay đổi.
* Hoàn thiện tài liệu về quá trình tối ưu nhằm phục vụ cho việc vận hành và bảo trì hệ thống.