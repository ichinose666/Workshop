---
title: "Tạo IAM User"
weight: 1
chapter: false
pre: "<b>2.1 </b>"
---

## Tạo IAM User để cấu hình AWS Config

AWS Config cần một IAM User với quyền phù hợp để cấu hình và quản lý các tài nguyên AWS.

1. **Vào** dịch vụ **IAM** trong AWS Management Console.
2. Chọn **Users** → **Add users**.
3. Nhập tên user (ví dụ: `UserADMIN`).
4. Ở **AWS access type**, chọn:
   - **Access key - Programmatic access** nếu bạn muốn dùng CLI/SDK.
   - **Password - AWS Management Console access** nếu cần đăng nhập Console.
5. Nhấn **Next** để gán quyền:
   - Chọn **Attach existing policies directly**.
   - Gắn quyền **AdministratorAccess** (hoặc quyền tối thiểu theo nguyên tắc least privilege, như `AWSConfigUserAccess`).
6. Nhấn **Next**, bỏ qua tag nếu không cần.
7. Chọn **Create user**.
8. Lưu lại **Access key** và **Secret access key** (nếu tạo quyền programmatic access).

![Create IAM User](/images/2.1/001.png?featherlight=false&width=90pc)

![Create IAM User](/images/2.1/002.png?featherlight=false&width=90pc)

![Create IAM User](/images/2.1/003.png?featherlight=false&width=90pc)


