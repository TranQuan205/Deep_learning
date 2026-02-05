# LAB 4: BÀI THỰC HÀNH CHUẨN BỊ DỮ LIỆU (DATA PREPARATION)


---

## 📖 Giới thiệu (Overview)

Bài thực hành (Lab 4) tập trung vào quy trình **Chuẩn bị dữ liệu (Data Preparation)** - một bước cực kỳ quan trọng trong quy trình Khoa học dữ liệu. Mục tiêu cuối cùng là xử lý dữ liệu thô từ sự kiện lịch sử tàu Titanic để phục vụ cho bài toán xây dựng mô hình dự báo khả năng sống sót của hành khách.

## 🎯 Mục tiêu học tập (Objectives)

Sau khi hoàn thành bài thực hành này, sinh viên sẽ nắm được các kiến thức và kỹ thuật sau:
1.  **Data Cleansing:** Kỹ thuật làm sạch dữ liệu (xử lý missing value, nhiễu, outliers...).
2.  **Exploratory Data Analysis (EDA):** Phân tích khám phá dữ liệu để hiểu cấu trúc và mối quan hệ giữa các biến.
3.  **Function Chaining:** Sử dụng kỹ thuật chuỗi hàm trong Pandas với phương thức `pipe()`.
4.  **Feature Engineering:** Kỹ thuật tạo đặc trưng mới từ dữ liệu có sẵn để cải thiện hiệu suất mô hình.
5.  **Data Wrangling:** Kỹ thuật chuyển đổi và ánh xạ dữ liệu thô sang định dạng phù hợp.

## 🛳️ Mô tả dữ liệu (Dataset Description)

Dữ liệu được sử dụng là **Titanic Dataset**.
Sự kiện chìm tàu Titanic là một trong những vụ đắm tàu nổi tiếng nhất lịch sử. Vào ngày 15/4/1912, trong chuyến đi đầu tiên, tàu RMS Titanic đã chìm sau khi va phải băng trôi. Thật không may, không có đủ xuồng cứu sinh cho tất cả mọi người, dẫn đến cái chết của 1502 trên tổng số 2224 hành khách và thủy thủ đoàn.

Mặc dù có yếu tố may mắn, nhưng một số nhóm người có khả năng sống sót cao hơn những nhóm khác.

### Từ điển dữ liệu (Data Dictionary)

| Biến (Variable) | Định nghĩa (Definition) | Giải thích/Key (Key) |
| :--- | :--- | :--- |
| **PassengerId** | Mã định danh hành khách | Identifier |
| **Survived** | Trạng thái sống sót | 0 = No (Không), 1 = Yes (Có) |
| **Pclass** | Hạng vé (Ticket class) | 1 = 1st (Hạng 1), 2 = 2nd (Hạng 2), 3 = 3rd (Hạng 3) |
| **Name** | Tên hành khách | |
| **Sex** | Giới tính | |
| **Age** | Tuổi | Tính theo năm |
| **SibSp** | Số lượng anh chị em/vợ chồng đi cùng | # of siblings / spouses aboard the Titanic |
| **Parch** | Số lượng cha mẹ/con cái đi cùng | # of parents / children aboard the Titanic |
| **Ticket** | Số vé | Ticket number |
| **Fare** | Giá vé | Passenger fare |
| **Cabin** | Số hiệu cabin | Cabin number |
| **Embarked** | Cổng lên tàu (Port of Embarkation) | C = Cherbourg, Q = Queenstown, S = Southampton |

## 🚀 Yêu cầu bài toán

**Nhiệm vụ:** Hãy chuẩn bị dữ liệu phục vụ cho bài toán:
> *"Xây dựng mô hình dự báo nhóm hành khách có khả năng sống sót với các thông số đầu vào là các đặc trưng của hành khách (tên, tuổi, giới tính, tầng lớp kinh tế - xã hội...), trong sự kiện Titanic lịch sử."*

**Phần thực hiện chính:**
* **PHẦN 1:** DATA CLEANSING & FEATURE ENGINEERING

## 🛠️ Công cụ & Thư viện sử dụng

* **Ngôn ngữ:** Python 3.x
* **Môi trường:** Jupyter Notebook / Google Colab
* **Thư viện chính:**
    * `pandas`: Xử lý và phân tích dữ liệu bảng (DataFrames, pipe).
    * `numpy`: Tính toán số học.
    * `seaborn` & `matplotlib`: Trực quan hóa dữ liệu (tham khảo: seaborn statistical data visualization).

## 📚 Tài liệu tham khảo

* [Seaborn Documentation](https://seaborn.pydata.org/)
* Pandas Documentation: `pipe()` method.

---

