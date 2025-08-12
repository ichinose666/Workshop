---
title: "Thiết lập AWS Config"
weight: 1
chapter: false
pre: "<b>3.1 </b>"
---

## Bật và cấu hình AWS Config

AWS Config cho phép bạn **đánh giá, kiểm tra và giám sát** cấu hình của các tài nguyên AWS, đồng thời lưu trữ lịch sử thay đổi để phục vụ kiểm toán và tuân thủ.

### Các bước thực hiện

1. **Mở** AWS Management Console và truy cập **AWS Config**.
2. Nếu đây là lần đầu thiết lập, chọn **Get started**.
3. Ở mục **Settings**:
   - **Resource types**: Chọn **All resources** (theo dõi toàn bộ tài nguyên) hoặc chỉ định các loại tài nguyên cần giám sát.
   - **Delivery method**:
     - **S3 bucket**: Chọn bucket đã tạo trước đó để lưu file cấu hình.
     - **SNS Topic**: Chọn SNS Topic đã tạo ở bước 2.4 để nhận thông báo thay đổi.
4. Ở mục **AWS Config role**:
   - Chọn **Create AWS Config service-linked role** nếu chưa có role này.
5. Nhấn **Next** → Kiểm tra lại cấu hình.
6. Nhấn **Confirm** để bật AWS Config.

### Kiểm tra hoạt động

- Sau khi bật, AWS Config sẽ bắt đầu ghi nhận trạng thái cấu hình hiện tại và cập nhật khi có thay đổi.
- Để thử nghiệm:
  1. Chỉnh sửa một tài nguyên mà AWS Config đang theo dõi (ví dụ: thay đổi quyền truy cập của S3 bucket).
  2. Quay lại **AWS Config** → **Resources** → tìm tài nguyên đó.
  3. Kiểm tra **Configuration timeline** để xem lịch sử thay đổi.

⚠ **Lưu ý:** Một số thay đổi nhỏ (như metadata không quan trọng) có thể không kích hoạt ghi nhận ngay. Thời gian đồng bộ có thể mất vài phút tùy dịch vụ.

---

![AWS Config Setup](/images/3.1/024.png?featherlight=false&width=90pc)

![AWS Config Setup](/images/3.1/025.png?featherlight=false&width=90pc)

![AWS Config Change Detection](/images/3.1/035.png?featherlight=false&width=90pc)

![AWS Config Timeline](/images/3.1/036.png?featherlight=false&width=90pc)
