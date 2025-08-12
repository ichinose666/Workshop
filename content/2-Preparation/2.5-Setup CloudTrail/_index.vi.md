---
title: "Cấu hình AWS CloudTrail"
weight: 5
chapter: false
pre: "<b>2.5 </b>"
---

## Bật CloudTrail cho AWS Config

AWS Config dựa vào AWS CloudTrail để ghi lại các lệnh API thay đổi tài nguyên. Chúng ta sẽ bật CloudTrail.

1. **Vào** dịch vụ **CloudTrail** trong AWS Management Console.
2. Nếu chưa có trail, chọn **Create trail**.
3. Đặt tên (ví dụ: `config-trail`).
4. Chọn **Create new S3 bucket** hoặc bucket có sẵn để lưu log.
5. Bật **Log file validation** để đảm bảo tính toàn vẹn của log.
6. Nhấn **Create trail**.

![Setup CloudTrail](/images/2.5/016.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/017.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/018.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/019.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/020.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/021.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/022.png?featherlight=false&width=90pc)

![Setup CloudTrail](/images/2.5/023.png?featherlight=false&width=90pc)

