---
title: "Dọn dẹp tài nguyên"
weight: 4
chapter: false
pre: "<b>4 </b>"
---

## Dọn dẹp tài nguyên

Thực hiện các bước sau để xóa toàn bộ tài nguyên AWS được tạo trong workshop. **Cẩn thận** – việc này sẽ xóa vĩnh viễn dữ liệu và cấu hình.

### 4.1 Xóa AWS Config Recorder & Delivery Channel
1. Vào **AWS Config** → **Settings**.
2. Dừng **Configuration Recorder**.
3. Xóa **Delivery Channel**.
4. Xác nhận xóa.

![Clean](/images/4/037.png?featherlight=false&width=90pc)

![Clean](/images/4/038.png?featherlight=false&width=90pc)

### 4.2 Xóa Config Rules
1. Trong **AWS Config**, vào **Rules**.
2. Chọn từng rule đã tạo.
3. Nhấn **Delete** → Xác nhận.

![Clean](/images/4/039.png?featherlight=false&width=90pc)

### 4.3 Xóa S3 Bucket
1. Vào **Amazon S3**.
2. Xóa toàn bộ dữ liệu trong bucket dùng cho log của AWS Config.
3. Chọn bucket → **Delete** → Nhập tên bucket để xác nhận.

![Clean](/images/4/040.png?featherlight=false&width=90pc)

### 4.4 Xóa SNS Topics và Subscriptions
1. Vào **Amazon SNS**.
2. Mở danh sách **Topics** và xóa topic.
3. Vào **Subscriptions** và xóa tất cả subscription liên quan.

![Clean](/images/4/041.png?featherlight=false&width=90pc)

### 4.5 Xóa IAM User
1. Vào **IAM** → **Users**.
2. Chọn user đã tạo cho workshop.
3. Gỡ access keys và policy liên kết.
4. Xóa user.

![Clean](/images/4/042.png?featherlight=false&width=90pc)
