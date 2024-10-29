# Hướng Dẫn Thiết Lập Môi Trường và Chạy Kịch Bản Selenium với Edge

## Giới Thiệu

Tệp hướng dẫn này mô tả cách thiết lập môi trường để chạy các kịch bản kiểm thử tự động hóa bằng **Selenium** và **Microsoft Edge**, sử dụng **pytest** làm framework kiểm thử. Bạn sẽ học cách cài đặt các công cụ cần thiết, cấu hình WebDriver cho trình duyệt Edge, và cách chạy các bài kiểm tra.

## Yêu Cầu Hệ Thống

Trước khi bắt đầu, đảm bảo rằng bạn có các công cụ sau:
1. **Python 3.7+**: Bạn có thể tải Python tại [python.org](https://www.python.org/downloads/).
2. **Microsoft Edge**: Phiên bản mới nhất của trình duyệt Edge.
3. **Edge WebDriver**: WebDriver để điều khiển trình duyệt Edge, bạn có thể tải nó từ [trang WebDriver của Edge](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/).
4. **pip**: Công cụ quản lý gói của Python (thường được cài sẵn với Python).

## Bước 1: Cài đặt Python và pip

Kiểm tra xem Python và pip đã được cài đặt chưa bằng cách chạy các lệnh sau trong terminal:

```bash
python --version
pip --version
```
## Bước 2: Cài Đặt Các Thư Viện Cần Thiết

Sử dụng `pip` để cài đặt các thư viện cần thiết cho dự án của bạn. Các thư viện cơ bản bao gồm:

- **Selenium**: Thư viện chính để tự động hóa các trình duyệt web.
- **pytest**: Thư viện để viết và chạy các bài kiểm tra.

Mở terminal hoặc command prompt và chạy lệnh sau:

```bash
pip install selenium pytest
```
