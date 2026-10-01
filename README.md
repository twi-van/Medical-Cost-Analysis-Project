# MEDICAL COST ANALYSIS PROJECT

## 📋 Giới thiệu
Dự án phân tích và trực quan hóa dữ liệu chi phí bảo hiểm y tế (Medical Cost Personal Datasets). 
Mục tiêu: Áp dụng các kỹ thuật thống kê cơ bản và học máy để giải mã các yếu tố ảnh hưởng đến chi phí y tế, từ đó xây dựng mô hình dự đoán. Đồ án cuối kỳ môn Phân tích và Trực quan hóa dữ liệu.

## 🗂️ Cấu trúc thư mục
- `data/`: Chứa file dữ liệu thô `insurance.csv` và dữ liệu đã làm sạch `data_sach.csv`.
- `1_EDA_Hien.ipynb`: Khám phá dữ liệu (EDA), Tiền xử lý, xử lý Missing Values và Outliers.
- `2_PhanPhoi_Loi.ipynb`: Phân tích phân phối xác suất (Chuẩn, Lệch phải) bằng biểu đồ Histogram và KDE.
- `3_KiemDinh_Phuong.ipynb`: Kiểm định giả thuyết (T-test, ANOVA) để chứng minh sự khác biệt về mặt thống kê.
- `4_HoiQuy_Van.ipynb`: Phân tích tương quan (Pearson, Spearman) và Xây dựng mô hình Hồi quy tuyến tính đa biến (Multiple Linear Regression).

## 🛠 Thư viện & Công cụ
Để chạy được dự án này, vui lòng cài đặt các thư viện sau (hoặc sử dụng file `requirements.txt`):
- `pandas`, `numpy`: Thao tác và biến đổi dữ liệu.
- `matplotlib`, `seaborn`: Trực quan hóa dữ liệu.
- `scipy`: Chạy các kiểm định thống kê.
- `scikit-learn`: Phân tích học máy (Hồi quy đa biến).

## 🎯 Mục tiêu phân tích
1. Tìm hiểu mối liên hệ giữa việc hút thuốc (Smoker) và chi phí y tế (Charges).
2. Kiểm chứng sự ảnh hưởng của Chỉ số cơ thể (BMI) và Tuổi tác (Age) lên phí bảo hiểm.
3. Dự đoán chi phí y tế dựa trên các đặc trưng cá nhân với độ chính xác cao nhất (đánh giá bằng R-squared).
