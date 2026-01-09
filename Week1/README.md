# WEEK 1
I.Mục tiêu:
  1. Tìm hiểu nghiệp vụ dữ liệu
  2. Nhập liệu bằng công cụ từ file excel
  3. Xác định dữ liệu định tính và định lượng
  4. Hiệu chỉnh các thang đo phù hợp và kiểu giá trị dữ liệu cho từng biến số
  5. Hiệu chỉnh dữ liệu và xử lý dữ liệu thiếu
  6. Chuyển đổi (transformation) dữ liệu theo khoảng cho trước
  7. Tạo biến số phụ thuộc theo biến độc lập
  8. Tạo biến định tính phân loại
II.Sử dụng Pandas để thực hiện các yêu cầu
  1. Xác định và phân loại dữ liệu định tính và định lượng
  2. Định nghĩa các thang đo phù hợp cho từng biến số
  3. Sử dụng Python để tải dữ liệu lên chương trình và in ra màn hình 10 dòng đầu tiên và 10
     dòng cuối cùng
III. Ứng dụng pandas
  1. Pandas cho phép bạn làm mọi thứ bạn làm trên Excel (và hơn thế nữa) nhưng thông qua các dòng code, giúp xử lý lượng dữ liệu cực lớn mà Excel không thể tải nổi.
  2. Những việc cụ thể Pandas làm được:
     * Đọc và Ghi dữ liệu: Pandas có thể đọc dữ liệu từ rất nhiều nguồn khác nhau như file CSV, Excel, JSON, SQL Database, HTML,... và chuyển đổi chúng thành DataFrame để xử          lý.
     * Làm sạch dữ liệu (Data Cleaning):
     * Xử lý các dữ liệu bị thiếu (missing data/NaN).
     * Xóa hoặc thay thế các dòng dữ liệu trùng lặp.
     * Đổi định dạng dữ liệu (ví dụ: chuyển chuỗi ký tự sang ngày tháng).
     * Thao tác và Biến đổi dữ liệu:
     * Cắt, lọc, chọn lọc dữ liệu theo điều kiện (ví dụ: "Lấy tất cả khách hàng mua hàng trên 1 triệu").
     * Gộp (Merge/Join) nhiều bảng dữ liệu lại với nhau (tương tự SQL JOINS).
     * Xoay bảng (Pivot tables) và thay đổi hình dạng dữ liệu (Reshaping).
     * Phân tích và Thống kê.
     * Tính toán nhanh các chỉ số thống kê: Trung bình, trung vị, min, max, độ lệch chuẩn.
     * Nhóm dữ liệu (groupby) để tính toán tổng hợp (ví dụ: "Doanh thu tổng theo từng tháng").
  3. Tại sao Pandas lại quan trọng?
    * Hiệu suất: Pandas được xây dựng trên nền tảng NumPy (viết bằng C), nên tốc độ xử lý nhanh hơn nhiều so với Python thuần túy.
    * Nền tảng của Data Science: Hầu hết các thư viện Machine Learning và AI (như Scikit-learn, TensorFlow) đều hoạt động tốt nhất khi dữ liệu đầu vào đã được xử lý qua Pandas.
    * Cộng đồng lớn: Tài liệu phong phú, giải quyết lỗi dễ dàng.
