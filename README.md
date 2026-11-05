# Phân tích dữ liệu hành khách Titanic

Dự án phân tích dữ liệu sử dụng bộ dữ liệu **Titanic** trên Kaggle tìm hiểu các yếu tố **có liên hệ với tỷ lệ sống sót** của hành khách.

## 1\. Mục tiêu và nội dung

* **Giai đoạn 1 – Thu thập và đánh giá dữ liệu:** Đọc dữ liệu, kiểm tra cấu trúc, kiểu dữ liệu, giá trị thiếu và trùng lặp.
* **Giai đoạn 2 – Làm sạch dữ liệu:** Xử lý giá trị thiếu, loại bản ghi trùng, tạo nhóm tuổi/nhóm gia đình và phát hiện giá vé bất thường bằng IQR.
* **Giai đoạn 3 – Phân tích và trực quan hóa:** Tỷ lệ sống sót chung; so sánh theo giới tính, hạng vé, kết hợp giới tính–hạng vé, nhóm tuổi, đi một mình và số người thân đi cùng; kiểm định Chi-square giữa giới tính và tình trạng sống sót.
* **Giai đoạn 4 – Kết luận:** Tổng hợp phát hiện, giới hạn dữ liệu và đề xuất hướng phân tích tiếp theo.

## 2\. Nguồn dữ liệu

* **Nguồn dữ liệu:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data).

## 3\. Cấu trúc dự án

```text
Titanic/
├── README.md
├── Vũ\_Hồng\_Nhung.ipynb
├── titanic.pdf
└── data/
  ├── train.csv
  ├── test.csv
  └── gender\_submission.csv
```

## 4\. Cài đặt môi trường và chạy trên Google Colab

**Bước 1.** Mở `Vũ_Hồng_Nhung.ipynb` bằng Google Collab .

**Bước 2.** Chọn **Runtime → Run all** để chạy các ô phân tích theo thứ tự.



## 

