LAB 3: LÀM SẠCH DỮ LIỆU CƠ BẢN (Basic Data Cleaning)
📌 Giới thiệu (Introduction)
  Bài thực hành này tập trung vào kỹ năng xử lý và làm sạch dữ liệu y khoa (cụ thể là dữ liệu về huyết áp và nhịp tim của bệnh nhân).
Mục tiêu chính: Sinh viên nắm vững cách sử dụng thư viện Pandas trong Python để phát hiện và xử lý các vấn đề thường gặp trong dữ liệu thô.
Dữ liệu được cung cấp dưới định dạng .csv với quy mô nhỏ để người học dễ dàng nắm bắt toàn bộ cấu trúc.

Đối tượng: Các cá nhân khác nhau.
Các trường thông tin (Columns):
  Age (Tuổi)
  
  Weight (Cân nặng)
  
  Sex (Giới tính)
  
  Heart Rates (Nhịp tim đo tại các khoảng thời gian khác nhau)

🛠 Yêu cầu kỹ thuật (Prerequisites)
    Ngôn ngữ: Python
    Thư viện: Pandas, NumPy
✅ Các vấn đề cần xử lý (Task List)
Trong bài Lab này, chúng ta sẽ lần lượt giải quyết 8 vấn đề phổ biến của dữ liệu thô:

[ ] Thiếu dòng tiêu đề (Missing header): File csv không có hàng tên cột.

[ ] Nhiều biến lưu ở một cột: Dữ liệu chưa được chuẩn hóa (tidy data).

[ ] Đơn vị không nhất quán: Dữ liệu trong cùng một cột chứa các đơn vị đo lường khác nhau.

[ ] Dòng trống: Dữ liệu chứa các hàng hoàn toàn rỗng.

[ ] Dòng trùng lặp: Các bản ghi bị lặp lại nhiều lần.

[ ] Ký tự không phải ASCII: Lỗi mã hóa văn bản (encoding).

[ ] Giá trị bị mất (Missing values): Xử lý NaN hoặc null.

[ ] Tiêu đề cột là giá trị: Tên cột thực chất là một giá trị của biến chứ không phải tên biến.
