# MEDICAL COST ANALYSIS PROJECT

## 📋 Giới thiệu
Dự án phân tích và trực quan hóa dữ liệu chi phí bảo hiểm y tế (Medical Cost Personal Datasets). 
Mục tiêu: Áp dụng các kỹ thuật thống kê (EDA, Phân phối xác suất, Kiểm định giả thuyết, Phân tích tương quan) và mô hình Hồi quy đa biến để dự đoán chi phí y tế.

## 🗂️ Cấu trúc thư mục
- `data/`: Chứa file dữ liệu thô `insurance.csv` và dữ liệu đã làm sạch `data_sach.csv`.
- `1_EDA_Hien.ipynb`: Code Khám phá dữ liệu và Tiền xử lý (Diệu Hiền).
- `2_PhanPhoi_Loi.ipynb`: Code Phân tích phân phối xác suất (Kim Lợi).
- `3_KiemDinh_Phuong.ipynb`: Code Kiểm định giả thuyết T-test, ANOVA (Đức Phương).
- `4_HoiQuy_Van.ipynb`: Code Phân tích tương quan và Mô hình Hồi quy đa biến (Thùy Vân).

## 🚀 Hướng dẫn làm việc nhóm (Quy trình Git)
1. **Giai đoạn 1 (Chờ Diệu Hiền):** Hiền code file `1_EDA_Hien.ipynb`, xử lý missing/outliers. Quan trọng nhất: Xuất ra file `data/data_sach.csv` và Push lên Repo.
2. **Giai đoạn 2 (Đồng bộ):** Vân, Lợi, Phương thực hiện lệnh `git pull` để cập nhật file `data_sach.csv` về máy mình.
3. **Giai đoạn 3 (Code Song song):** Mọi người mở file Notebook mang tên mình lên để code. Do code trên 4 file khác nhau nên có thể Commit và Push bất cứ lúc nào, không sợ bị Conflict.
4. **Giai đoạn 4 (Đóng gói):** Vân gộp 4 file Notebook thành 1 file báo cáo cuối cùng.
