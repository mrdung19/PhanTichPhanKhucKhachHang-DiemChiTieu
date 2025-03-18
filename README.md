## 📊 Phân tích phân khúc khách hàng & Dự đoán điểm chi tiêu
## 🚀 1. Giới thiệu
<br> Dự án này phân tích dữ liệu khách hàng bằng mô hình RFM và dự đoán điểm chi tiêu (M_Score) bằng hồi quy tuyến tính.
<br> 🔹Mục tiêu: Nhóm khách hàng, dự đoán chi tiêu, hỗ trợ chiến lược marketing.
## 👥 2. Thành viên nhóm
<br> ✅ Nguyễn Đức Duy
<br> ✅ Nguyễn Minh Đức
<br> ✅ Nguyễn Tất Toàn
<br> ✅ Nguyễn Tiến Dũng
## 🛠 3. Công nghệ sử dụng
<br>🔹 Ngôn ngữ: R
<br> 🔹 Xử lý dữ liệu: Spark, R (tùy chọn Hadoop)
<br> 🔹 Thư viện: tidyverse, ggplot2, caret, Metrics, sparklyr
## 🔄 4. Quy trình thực hiện
<br> ✔ Bước 1: Tiền xử lý dữ liệu (lọc lỗi, tính toán TotalPrice).
<br> ✔ Bước 2: Phân tích RFM (Recency, Frequency, Monetary).
<br> ✔ Bước 3: Xây dựng mô hình hồi quy dự đoán M_Score.
<br> ✔ Bước 4: Đánh giá mô hình bằng RMSE, MAE, R².
<br> ✔ Bước 5: Trực quan hóa dữ liệu (biểu đồ doanh thu, sản phẩm bán chạy).
## 🎯 5. Kết quả đạt được
<br> 📌 Phân loại khách hàng theo RFM: VIP, trung thành, tiềm năng...
<br> 📌  Mô hình dự đoán điểm chi tiêu với độ chính xác:
<br> -   RMSE: 1.094, MAE: 0.934, R²: 0.414
<br> 📌 Biểu đồ trực quan giúp dễ dàng phân tích dữ liệu.
## 🏁 6. Cách chạy chương trình
<br> 🔹 Chạy trên R Studio
```r
  install.packages(c("tidyverse", "sparklyr", "caret", "ggplot2"))
``` 

## 🔹 Chạy với Spark (tùy chọn Hadoop)
```r
sc <- spark_connect(master = "local")
df_spark <- spark_read_csv(sc, path = "hdfs:///data/RFM_Segmentation.csv")
``` 
## 📚 7. Tài liệu tham khảo
Kaggle: https://www.kaggle.com
<br> Apache Spark: https://spark.apache.org/
<br>Tidyverse: https://www.tidyverse.org/
## 📧 8. Liên hệ
Email: dunggay2k4@gmail.com
<br> Link: https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin
