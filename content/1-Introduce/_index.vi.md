---
title : "Giới thiệu"
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
**Tuân thủ cấu hình với AWS Config và khắc phục** Chủ đề của chúng tôi tập trung vào việc xây dựng và triển khai nền tảng quản lý tuân thủ cấu hình (Configuration Compliance) trên AWS bằng cách sử dụng AWS Config, Config Rules, và Automated Remediation. Mục tiêu là đảm bảo hệ thống luôn duy trì trạng thái cấu hình đúng theo chuẩn đã định, phát hiện nhanh chóng các sai lệch (drift), và tự động khắc phục khi vi phạm xảy ra.

Quá trình triển khai bao gồm:

Kích hoạt AWS Config và thiết lập S3 bucket, SNS topic để ghi nhận và thông báo về các thay đổi cấu hình.

Tạo các Config Rules (AWS managed hoặc custom) để giám sát các tài nguyên như S3, EC2, IAM, RDS…

Thiết lập automated remediation giúp tự động sửa các cấu hình sai, giảm thiểu rủi ro bảo mật và lỗi vận hành.

Tích hợp Amazon EventBridge và CloudWatch để cảnh báo ngay lập tức khi phát hiện drift hoặc vi phạm.

Lưu trữ log drift và compliance trên S3 phục vụ mục đích audit và báo cáo.

Xây dựng compliance dashboard và báo cáo tự động giúp quản trị viên dễ dàng theo dõi tình trạng tuân thủ.

![Introduce](/images/1/000.png?featherlight=false&width=90pc)