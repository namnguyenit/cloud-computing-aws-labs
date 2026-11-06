# ☁️ AWS Cloud Computing Labs: Clickstream Data Pipeline & Cloud9 IDE

Kho lưu trữ tài liệu và mã nguồn thực hành môn **Điện toán đám mây (Cloud Computing with AWS)**.

## 🚀 Nội dung chính

### 1. Kiến trúc Clickstream Data Pipeline trên AWS
- **Mục tiêu**: Xây dựng pipeline dữ liệu hoàn chỉnh để thu thập, chuyển đổi và phân tích nhật ký click chuột (clickstream access logs) của website AnyCompany Café.
- **Sơ đồ kiến trúc**:
  - `Clickstream Pipeline.drawio.png` (Ảnh sơ đồ trực quan)
  - `Clickstream Pipeline.xml` (File nguồn draw.io để chỉnh sửa)
- **Thành phần AWS sử dụng**:
  - **EC2 Web Server**: Host ứng dụng web PHP và Apache HTTPD.
  - **Amazon CloudWatch Agent**: Thu thập log thời gian thực và đẩy lên CloudWatch Logs.
  - **CloudWatch Logs Insights**: Truy vấn dữ liệu log theo toạ độ địa lý, tạo widget biểu đồ (Pie chart, Bar chart).
  - **Amazon S3**: Lưu trữ dữ liệu log lâu dài phục vụ Data Lake / Analytics.
- **Tài liệu hướng dẫn chi tiết**: Xem file [`AWS_CLICKSTREAM_LAB_GUIDE.md`](./AWS_CLICKSTREAM_LAB_GUIDE.md).

### 2. Môi trường phát triển AWS Cloud9
- Thư mục `Cloud9-Lab-IDE/` và file nén `Cloud9-Lab-IDE.zip`: Chứa cấu hình môi trường phát triển trên nền tảng AWS Cloud9 IDE.

## 👨‍💻 Tác giả
- [Cao Đức Trung (@namnguyenit)](https://github.com/namnguyenit)
