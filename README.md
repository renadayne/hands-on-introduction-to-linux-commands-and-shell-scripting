# Linux and Shell Scripting

# Final Project

Tình huống: Hãy tưởng tượng bạn là một nhà phát triển Linux chủ chốt tại công ty công nghệ hàng đầu ABC International Inc. ABC hiện đang gặp phải một vấn đề lớn: mỗi ngày, các thực tập sinh phải truy cập vào các tệp mật khẩu đã mã hóa trên các máy chủ chính và sao lưu bất kỳ tệp nào đã được cập nhật trong vòng 24 giờ qua. Quá trình này dễ gây ra sai sót của con người, làm giảm bảo mật và tốn nhiều công sức không cần thiết.

Là một trong những nhà phát triển Linux đáng tin cậy nhất của ABC, bạn được giao nhiệm vụ tạo ra một script có tên backup.sh, chạy hàng ngày và tự động sao lưu bất kỳ tệp mật khẩu đã mã hóa nào đã được cập nhật trong vòng 24 giờ qua.

Mục tiêu học tập: Hoàn thành dự án cuối kỳ này, bạn sẽ:

Chứng minh kỹ năng shell scripting nâng cao trong một tình huống thực tế.
Áp dụng kiến thức đã học để đánh giá và chấm điểm bài làm của các bạn học cùng.
Tổng quan về bài lab: Script Sao lưu Đã Lên Lịch
Trong phần lab này, bạn sẽ tạo ra một script sao lưu có lịch trình.

Hướng dẫn: Ngay sau khi đọc bài này, bạn sẽ hoàn thành phần lab thực hành của dự án cuối kỳ, nơi bạn sẽ tạo ra một script sao lưu có lịch trình.

Các yêu cầu nộp bài: Bạn cần nộp các tài liệu sau để được đánh giá bởi các bạn cùng lớp:

Các screenshot hiển thị mã code và kết quả cho từng tác vụ.
Tệp script hoàn thành của bạn (backup.sh).
Các chi tiết đầy đủ cho từng tác vụ trong bài lab.
Tiêu chí chấm điểm: Có tổng cộng 20 điểm cho 17 tác vụ trong dự án cuối kỳ này. Điểm của bạn sẽ được chấm dựa trên các tác vụ trong bài lab:

[Tác vụ 1-13]: Nộp screenshot của các phần trong script backup.sh hiển thị mã đúng (13 điểm: 1 điểm cho mỗi tác vụ).
[Tác vụ 14]: Nộp tệp script backup.sh hoàn thành (1 điểm).
[Tác vụ 15]: Nộp screenshot hiển thị quyền thực thi cho script (2 điểm).
[Tác vụ 16]: Nộp screenshot hiển thị tệp có tên backup-[TIMESTAMP].tar.gz (2 điểm).
[Tác vụ 17]: Nộp screenshot hiển thị lịch trình crontab chạy mỗi ngày một lần (2 điểm).