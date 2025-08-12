---
title: "Tạo EC2 Instance"
weight: 2
chapter: false
pre: "<b>2.2 </b>"
---

## Khởi tạo EC2 Instance để kiểm thử

Chúng ta sẽ tạo một EC2 instance nhỏ để tạo ra các thay đổi cấu hình, giúp AWS Config có dữ liệu để theo dõi.

1. **Vào** dịch vụ **EC2** trong AWS Management Console.
2. Chọn **Launch instance**.
3. Nhập tên instance (ví dụ: `AWS-CONFIG`).
4. Chọn Amazon Machine Image (AMI) như **Amazon Linux 2**.
5. Chọn loại instance nhỏ (ví dụ: `t2.micro`).
6. Ở phần **Key pair**, tạo mới hoặc chọn key pair đã có.
7. Trong **Network settings**, chỉ cho phép inbound rule cần thiết (ví dụ: SSH từ IP của bạn).
8. Nhấn **Launch instance**.

![Create EC2](/images/2.2/004.png?featherlight=false&width=90pc)

![Create EC2](/images/2.2/005.png?featherlight=false&width=90pc)


