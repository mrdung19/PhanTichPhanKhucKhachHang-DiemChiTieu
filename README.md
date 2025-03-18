🚀 1. Giới thiệu
Dự án này phân tích dữ liệu khách hàng bằng mô hình RFM và dự đoán điểm chi tiêu (M_Score) bằng hồi quy tuyến tính.
🔹 Mục tiêu: Nhóm khách hàng, dự đoán chi tiêu, hỗ trợ chiến lược marketing.
👥 2. Thành viên nhóm
✅ Nguyễn Đức Duy
✅ Nguyễn Minh Đức
✅ Nguyễn Tất Toàn
✅ Nguyễn Tiến Dũng
🛠 3. Công nghệ sử dụng
🔹 Ngôn ngữ: R
🔹 Xử lý dữ liệu: Spark, R (tùy chọn Hadoop)
🔹 Thư viện: tidyverse, ggplot2, caret, Metrics, sparklyr
🔄 4. Quy trình thực hiện
✔ Bước 1: Tiền xử lý dữ liệu (lọc lỗi, tính toán TotalPrice).
✔ Bước 2: Phân tích RFM (Recency, Frequency, Monetary).
✔ Bước 3: Xây dựng mô hình hồi quy dự đoán M_Score.
✔ Bước 4: Đánh giá mô hình bằng RMSE, MAE, R².
✔ Bước 5: Trực quan hóa dữ liệu (biểu đồ doanh thu, sản phẩm bán chạy).
🎯 5. Kết quả đạt được
📌 Phân loại khách hàng theo RFM: VIP, trung thành, tiềm năng...
📌 Mô hình dự đoán điểm chi tiêu với độ chính xác:

RMSE: 1.094, MAE: 0.934, R²: 0.414
📌 Biểu đồ trực quan giúp dễ dàng phân tích dữ liệu.
🏁 6. Cách chạy chương trình
🔹 Chạy trên R Studio
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("caret")
library(tidyverse)
library(ggplot2)
source("main_script.R")

🔹 Chạy với Spark (tùy chọn Hadoop)
sc <- spark_connect(master = "local")
df_spark <- spark_read_csv(sc, path = "hdfs:///data/RFM_Segmentation.csv")
📚 Tài liệu tham khảo
Kaggle: https://www.kaggle.com
Apache Spark: https://spark.apache.org/
Tidyverse: https://www.tidyverse.org/
📧 Liên hệ
Email: dunggay2k4@gmail.com
Link: https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin
