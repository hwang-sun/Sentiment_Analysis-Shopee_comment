### 1. Dữ liệu được tiền xử lý (xử lý ký hiệu, viết tắt, n-gram,...) ở file notebook "Data_preprocessing". 
Output của quá trình xử lý là file dữ liệu được lưu với tên "final_df.csv"

### 2. Dữ liệu "final_df.csv" sau đó được đọc vào file "Sklearn_Modeling.ipynb" và xử lý với các thao tác sau
  - EDA 
  - Data cleaning
  - Feature engineering and output encoding
  - TF-IDF
  - Handle imbalanced classes
  - Sklearn modeling
  - Model evaluating
  - Parameter Tunning 
  - Save model - "SentimentAnalysis_LR.pkl"

### 3. Dữ liệu "final_df.csv" cũng được đọc và xử lý với pyspark trong file "Pyspark_Model.ipynb" với các thao tác
  - Data cleaning
  - TF-IDF
  - Modeling
  - Model evaluating
  - Save model - "multinomial_nb_model"
