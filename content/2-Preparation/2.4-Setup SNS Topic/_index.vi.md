---
title: "Tạo SNS Topic"
weight: 4
chapter: false
pre: "<b>2.4 </b>"
---

## Tạo SNS Topic để nhận thông báo từ AWS Config

SNS Topic sẽ gửi thông báo khi có sự thay đổi hoặc sự kiện liên quan đến AWS Config.

1. **Vào** dịch vụ **SNS** trong AWS Management Console.
2. Chọn **Topics** → **Create topic**.
3. Chọn **Standard** và nhập tên topic (ví dụ: `config-alerts-23`).
4. Giữ nguyên các tùy chọn khác hoặc tùy chỉnh nếu cần.
5. Nhấn **Create topic**.
6. Sau khi tạo xong, chọn **Create subscription**:
   - Chọn **Protocol**: Email (hoặc HTTPS, Lambda, SQS... tùy yêu cầu).
   - Nhập **Endpoint** (ví dụ: địa chỉ email nhận thông báo).
   - Nhấn **Create subscription**.
7. Xác nhận email để kích hoạt nhận thông báo.

![Setup SNS Topic](/images/2.4/009.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/010.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/011.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/012.png?featherlight=false&width=90pc)

![Setup SNS Topic](/images/2.4/013.png?featherlight=false&width=90pc)


