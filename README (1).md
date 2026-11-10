# Phân tích dữ liệu hành khách Titanic

Dự án phân tích dữ liệu sử dụng bộ dữ liệu **Titanic** trên Kaggle nhằm tìm hiểu các yếu tố **có liên hệ với tỷ lệ sống sót** của hành khách.

## 1\. Mục tiêu và nội dung

* **Giai đoạn 1 – Thu thập và đánh giá dữ liệu:** Đọc dữ liệu, kiểm tra cấu trúc, kiểu dữ liệu, giá trị thiếu và trùng lặp.
* **Giai đoạn 2 – Làm sạch dữ liệu:** Xử lý giá trị thiếu, kiểm tra bản ghi trùng, tạo nhóm tuổi/nhóm gia đình và phát hiện giá vé bất thường bằng IQR.
* **Giai đoạn 3 – Thống kê, trực quan hóa và kiểm định:** Phân tích tỷ lệ sống sót theo giới tính, hạng vé, tuổi, gia đình, giá vé, danh xưng và cảng lên tàu; phân tích kết hợp nhiều yếu tố; kiểm định Chi-square và tính khoảng tin cậy 95%. Xây dựng bốn mô hình **Logistic Regression, Decision Tree, Random Forest và XGBoost**; so sánh bằng Stratified Cross-Validation, tối ưu tham số với RandomizedSearchCV, đánh giá trên tập validation, giải thích mô hình và dự đoán `test.csv` để xuất `submission.csv`.
* **Kết luận:** Tổng hợp các phát hiện, so sánh hiệu quả mô hình, nêu giới hạn dữ liệu và đề xuất hướng mở rộng (không tách thành một giai đoạn riêng).

## 2\. Nguồn dữ liệu

* **Nguồn dữ liệu:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data). 

## 3\. Cấu trúc dự án

```text
Titanic/

├── README.md
├── titanic.ipynb
├── titanic.pdf
└── data/
    ├── train.csv
    ├── test.csv
    └── gender_submission.csv
```

## 4\. Cài đặt môi trường và chạy trên Google Colab hoặc VS Code

**Bước 1.** Mở `titanic.ipynb` bằng Google Collab .

**Bước 2.** Chọn **Runtime → Run all** để chạy các ô phân tích theo thứ tự.

