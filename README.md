# MEDICAL COST ANALYSIS PROJECT

## 📋 Giới thiệu
Dự án phân tích và trực quan hóa dữ liệu chi phí bảo hiểm y tế (Medical Cost Personal Datasets). 
Mục tiêu: Áp dụng các kỹ thuật thống kê cơ bản và học máy để giải mã các yếu tố ảnh hưởng đến chi phí y tế, từ đó xây dựng mô hình dự đoán. Đồ án cuối kỳ môn Phân tích và Trực quan hóa dữ liệu.

## 🗂️ Cấu trúc thư mục
- `data/`: Chứa file dữ liệu thô `insurance.csv` và dữ liệu đã làm sạch `data_sach.csv`.
- `CODE.ipynb`: Mã nguồn Python tổng hợp toàn bộ các bước phân tích (EDA, Phân phối xác suất, Kiểm định giả thuyết, Phân tích tương quan và Hồi quy đa biến).

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
