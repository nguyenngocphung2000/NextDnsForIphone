# [Hướng dẫn] Cấu hình nhanh NextDNS để chặn quảng cáo

NextDNS là một dịch vụ DNS thông minh giúp chặn quảng cáo, mã độc và các trang lừa đảo. Dưới đây là hướng dẫn cấu hình nhanh NextDNS để bạn có thể sử dụng dịch vụ này một cách hiệu quả.

## Ưu điểm của NextDNS
- **Có máy chủ ở Việt Nam**: Đảm bảo tốc độ truy cập nhanh chóng.
- **Tích hợp chặn trang mã độc/lừa đảo ở Việt Nam**: Bảo vệ bạn khỏi các trang web độc hại.
- **Mã hoá truy vấn DNS**: Đảm bảo an toàn và bảo mật thông tin.

## Các bước cấu hình

### Bước 1: Tạo tài khoản NextDNS
1. Truy cập [https://nextdns.io](https://nextdns.io).
2. Chọn **my.nextdns.io** ở góc phải phía trên.
3. Ghi nhớ **ID** được tạo.

### Bước 2: Thêm bộ lọc
1. Qua tab **Privacy**.
2. Thêm 2 bộ lọc:
   - **hostsVN**
   - **AdGuard DNS filter**

### Bước 3: Tuỳ chọn nâng cao (không bắt buộc)
- **Cho phép liên kết tiếp thị**: 
  - Bật **Allow Affiliate & Tracking Links** nếu bạn muốn nhấn được vào các đường dẫn quảng cáo trong kết quả tìm kiếm Google hoặc các liên kết tiếp thị như Lazada/Shopee.
  
- **Chặn trang cờ bạc**:
  - Qua tab **Parental Control**.
  - Tại mục **Categories**, thêm **Gambling** nếu bạn muốn chặn các trang có nội dung cờ bạc.

- **Tối ưu tốc độ mạng**:
  - Nếu sử dụng mạng khác bị chậm, vào tab **Setting** và tắt **Anonymized EDNS Client Subnet**.

- **Cài đặt cho phụ huynh**:
 - Qua tab **Parental Control**
 - Tại mục **Categories**,thêm P*rn để chặn nội dung người lớn
 - Bật tính năng **SafeSearch**
 - Phần **Recreation Time** đặt thời gian cho phép sử dụng
### Bước 4: Cài đặt
1. Trở về tab **Setup**.
2. Cài đặt theo hướng dẫn ở **Setup Guide**.
3. Nếu iphone thì nhấn vào [Đây](https://apple.nextdns.io/) để tạo cấu hình cài đặt.
## Thông tin thêm
- **Hướng dẫn đầy đủ**: [https://github.com/bigdargon/hostsVN/wiki/NextDNS](https://github.com/bigdargon/hostsVN/wiki/NextDNS)
- **Tài khoản miễn phí**: 300k truy vấn/tháng, đủ sử dụng cho cá nhân 1-2 thiết bị.

Chúc mọi người thành công! #NextDNS #hostsVN
