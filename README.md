### DAP304x_Assignment1
# Lastname_firstname_grade_the_exams
## Giới Thiệu

Dự án này được thiết kế để chấm điểm các bài kiểm tra trắc nghiệm dựa trên một bảng đáp án được cung cấp. Nó nhận vào một tệp chứa câu trả lời của học sinh, đánh giá chúng so với bảng đáp án, và tạo ra một báo cáo về hiệu suất của học sinh. Hệ thống chấm điểm xem xét các câu trả lời đúng, các câu hỏi bị bỏ qua và các câu trả lời sai.

## Tải Dữ Liệu

Dữ liệu "Data_files" cho dự án có thể được tải xuống từ [đường link này](https://drive.google.com/file/d/1OP35rvIGoKp-pboeA5m0jIfSw2GdlY5h/view)

## Yêu Cầu

Để chạy dự án này, đảm bảo bạn đã cài đặt Anaconda trên hệ thống của mình. Bạn có thể tải Anaconda (Python phiên bản 3.9) từ [trang web chính thức](https://www.anaconda.com/products/distribution).

## Cài Đặt

Sau khi tải thành công, bạn sẽ mở Anaconda chọn (Lauch) Jupyter Notebook. 

## Sử dụng

1. Upload các **"class_file"** và file notebook chứa code dự án **"lastname_firstname_grade_the_exams.py"** lên Home page của Jupyter notebook.

2. Mở file notebook tên **"lastname_firstname_grade_the_exams.py"**.

3. Chạy các dòng code trong dự án sau đó input tên từng **"class_file"** để kiểm tra và chấm điểm theo yêu cầu.

## Tính năng của các hàm được sử dụng trong dự án

**read_file**: Đọc một tệp CSV chứa câu trả lời của học sinh.

**check_valid**: Kiểm tra các dòng dữ liệu hợp lệ và không hợp lệ theo các tiêu chí cụ thể.

**grading**: Đánh giá các câu trả lời của học sinh so với một bảng đáp án, xem xét các câu trả lời đúng, các câu hỏi bị bỏ qua và các câu trả lời sai.

**statistics_grades**: Cung cấp các số liệu thống kê về hiệu suất của học sinh, bao gồm điểm trung bình, điểm cao nhất, điểm thấp nhất, phạm vi điểm, điểm trung vị, câu hỏi được bỏ qua nhiều nhất và câu hỏi được trả lời sai nhiều nhất.

**write_result**: Xuất kết quả ra một tệp mới.

## Ghi Chú
Dự án này được tham khảo từ bài code mẫu của Tutor Tuấn Bùi.


