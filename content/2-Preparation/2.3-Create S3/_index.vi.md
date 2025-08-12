---
title: "Tạo S3 Bucket"
weight: 3
chapter: false
pre: "<b>2.3 </b>"
---

## Tạo S3 Bucket để lưu trữ dữ liệu AWS Config

AWS Config cần một S3 Bucket để lưu trữ lịch sử cấu hình và các file snapshot.

1. **Vào** dịch vụ **S3** trong AWS Management Console.
2. Chọn **Create bucket**.
3. Nhập tên bucket (ví dụ: `config-log-bucket-23`) — tên phải duy nhất trên toàn AWS.
4. Chọn **Region** phù hợp với tài nguyên của bạn.
5. Ở phần **Block Public Access**, giữ nguyên **Enable** để bảo mật.
6. Các thiết lập khác để mặc định hoặc tùy chỉnh theo yêu cầu.
7. Nhấn **Create bucket**.

![Create S3 Bucket](/images/2.3/006.png?featherlight=false&width=90pc)

![Create S3 Bucket](/images/2.3/007.png?featherlight=false&width=90pc)

![Create S3 Bucket](/images/2.3/008.png?featherlight=false&width=90pc)


