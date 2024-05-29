# Kiểm Thử Postman
## Giới thiệu
Postman là một công cụ mạnh mẽ được sử dụng để kiểm thử và phát triển API. Nó cung cấp nhiều tính năng giúp bạn dễ dàng tạo, gửi và kiểm tra các yêu cầu HTTP, cũng như quản lý các bộ sưu tập API và môi trường.
## API được chọn
API được chọn là HTTP Cats, là một API cung cấp các hình ảnh mèo
## Phân tích tài liệu API
- Điểm cuối chính: https://http.cat
- Phương thức: GET
- Tham số bắt buộc: id (hình ảnh)
## Các trường hợp kiểm thử
### I. Truy vấn hợp lệ
![Cat API 101](https://github.com/TDCSon21011629/DanhGia-KiemDinhChatLuongPhanMem/assets/97428357/a41d2592-d466-417a-88f4-890656604972)
### II. Truy vấn không hợp lệ
![Cat API Not Found](https://github.com/TDCSon21011629/DanhGia-KiemDinhChatLuongPhanMem/assets/97428357/2d8c443b-6136-4f35-9919-21776b7957ac)
## Báo cáo kiểm thử chi tiết
### Mục tiêu kiểm thử:
- Xác định và xác thực các phản hồi của Cats API dựa trên các truy vấn khác nhau.
### Phạm vi kiểm thử:
- Các điểm cuối liên quan đến việc lấy dữ liệu.
### Kết quả kiểm thử:
- Tất cả các trường hợp kiểm thử được thực hiện đều có kết quả đúng với mong đợi.
- API hoạt động đúng với hình hợp lệ tương ứng và xử lí các lỗi một cách thích hợp khi cung cấp dữ liệu không hợp lệ.
