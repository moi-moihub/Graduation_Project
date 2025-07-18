Xây dựng hệ thống SOC-as-a-Service hỗ trợ doanh nghiệp vừa và nhỏ (SMEs)
Sinh viên thực hiện: Tư Mã Ý
Ngành: An toàn thông tin
Thời gian thực hiện: 12 tháng

1. Mục tiêu
Xây dựng một hệ thống SOC-as-a-Service (Security Operation Center dưới dạng dịch vụ) với mã nguồn mở, chi phí thấp, dễ triển khai và phù hợp với nhu cầu giám sát an ninh mạng cho các doanh nghiệp vừa và nhỏ (SMEs).

2. Nội dung chính
Thu thập log hệ thống: từ Linux, Windows, ứng dụng web và thiết bị mạng thông qua Syslog/Agent.

Xử lý & lưu trữ log: Sử dụng các công cụ như Elastic Stack (hoặc SQLite nhẹ).

Giám sát và cảnh báo: Thiết lập rule phát hiện hành vi bất thường (VD: brute force, đăng nhập lạ).

Phân tích AI/ML đơn giản: Áp dụng scikit-learn để phân loại log đáng ngờ và dự đoán sự cố bảo mật.

Dashboard giám sát: Giao diện web hiển thị log, cảnh báo, phân tích thống kê.

Khảo sát thị trường: Phân tích nhu cầu bảo mật thực tế từ SMEs qua biểu mẫu khảo sát.

3. Kết quả kỳ vọng
Hệ thống hoạt động cơ bản (MVP), có thể triển khai thử nghiệm cho SMEs.

Toàn bộ mã nguồn, tài liệu hướng dẫn, mô hình ML được public trên GitHub.

Tài liệu đồ án đầy đủ: báo cáo chi tiết, video demo, slide trình bày.

Có kết quả khảo sát từ 5–10 doanh nghiệp vừa và nhỏ về nhu cầu giám sát bảo mật.

4. Công nghệ sử dụng
Ngôn ngữ: Python, Bash

ML Framework: Scikit-learn

Frontend: Streamlit hoặc Flask + Bootstrap

Log system: Syslog, Logstash hoặc Fluentd

Deploy: Docker, Ubuntu Server

Survey: Google Form hoặc LimeSurvey

5. Ý nghĩa thực tiễn
Hệ thống SOC truyền thống thường tốn kém và phức tạp. Đồ án hướng tới một giải pháp dễ dùng, có thể mở rộng thành sản phẩm startup nhằm hỗ trợ SMEs phòng chống các mối đe dọa mạng ngày càng tinh vi với chi phí hợp lý.
