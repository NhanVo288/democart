# Hướng Dẫn Thiết Lập Môi Trường và Chạy Kịch Bản Selenium với Edge
Giới Thiệu
Tệp hướng dẫn này mô tả cách thiết lập môi trường để chạy các kịch bản kiểm thử tự động hóa bằng Selenium và Microsoft Edge, sử dụng pytest làm framework kiểm thử. Bạn sẽ học cách cài đặt các công cụ cần thiết, cấu hình WebDriver cho trình duyệt Edge, và cách chạy các bài kiểm tra.

Yêu Cầu Hệ Thống
Trước khi bắt đầu, đảm bảo rằng bạn có các công cụ sau:

Python 3.7+: Bạn có thể tải Python tại python.org.
Microsoft Edge: Phiên bản mới nhất của trình duyệt Edge.
Edge WebDriver: WebDriver để điều khiển trình duyệt Edge, bạn có thể tải nó từ trang WebDriver của Edge.
pip: Công cụ quản lý gói của Python (thường được cài sẵn với Python).
Bước 1: Cài đặt Python và pip
Kiểm tra xem Python và pip đã được cài đặt chưa bằng cách chạy các lệnh sau trong terminal:

bash

Copy
python --version
pip --version
Nếu Python chưa được cài đặt, tải và cài đặt Python từ python.org.

Bước 2: Cài đặt các thư viện cần thiết
Sử dụng pip để cài đặt các thư viện cần thiết cho dự án, bao gồm Selenium và pytest.

bash

Copy
pip install selenium pytest
Bước 3: Tải về và cấu hình Edge WebDriver
Tải về Edge WebDriver: Truy cập trang WebDriver của Edge và tải về phiên bản tương ứng với trình duyệt Edge của bạn.
Cấu hình Edge WebDriver:
Giải nén tệp tải về và lưu nó vào một thư mục mà bạn có thể truy cập dễ dàng.
Thêm đường dẫn đến thư mục chứa Edge WebDriver vào biến môi trường PATH của hệ thống.
Ví dụ trên Windows:
Kích chuột phải vào This PC -> Properties -> Advanced system settings -> Environment Variables.
Trong phần System variables, chọn Path và nhấn Edit.
Thêm đường dẫn đến thư mục chứa Edge WebDriver của bạn.
