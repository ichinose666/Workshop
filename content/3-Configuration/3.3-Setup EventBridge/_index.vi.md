---
title: "Thiết lập EventBridge"
weight: 3
chapter: false
pre: "<b>3.3 </b>"
---

## Thiết lập EventBridge để nhận thông báo sự kiện từ AWS Config

EventBridge giúp bạn tạo các luồng sự kiện tự động khi có thay đổi cấu hình hoặc vi phạm quy tắc.

1. Trong AWS Management Console, vào **Amazon EventBridge**.
2. Chọn **Rules** → **Create rule**.
3. Nhập tên rule (ví dụ: `config-rule-violation`).
4. Ở phần **Event source**, chọn:
   - **AWS services** → **AWS Config**.
5. Ở phần **Event pattern**, chọn:
   - Loại sự kiện: **Config Rules Compliance Change** hoặc **Configuration Item Change**.
6. Ở phần **Target**, chọn:
   - SNS Topic, Lambda function hoặc Step Functions để xử lý sự kiện.
7. Nhấn **Create**.

![Setup EventBridge](/images/3.3/030.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/031.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/032.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/033.png?featherlight=false&width=90pc)

![Setup EventBridge](/images/3.3/034.png?featherlight=false&width=90pc)

