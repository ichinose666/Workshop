---
title: "Thêm Config Rules"
weight: 2
chapter: false
pre: "<b>3.2 </b>"
---

## Thêm Config Rules để giám sát cấu hình

Config Rules cho phép bạn xác định các tiêu chuẩn cấu hình và kiểm tra tài nguyên AWS có tuân thủ hay không.

1. Trong AWS Management Console, vào **AWS Config** → **Rules** → **Add rule**.
2. Chọn **AWS Managed Rules** (có sẵn) hoặc **Custom Rule** (do bạn tạo).
3. Ví dụ: Tìm và chọn rule **required-tags** để bắt buộc tài nguyên phải có thẻ.
4. Cấu hình tham số cho rule (nếu có).
5. Chọn **Trigger**:
   - **Configuration changes** (kích hoạt khi tài nguyên thay đổi).
   - **Periodic** (kiểm tra định kỳ).
6. Nhấn **Next** và **Add rule**.

![Add Config Rule](/images/3.2/026.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/027.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/028.png?featherlight=false&width=90pc)

![Add Config Rule](/images/3.2/029.png?featherlight=false&width=90pc)

