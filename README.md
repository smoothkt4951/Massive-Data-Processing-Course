# Xử Lý Dữ Liệu Lớn
## Giới thiệu
  Bài viết này được tạo ra với mục đích chính là phục vụ quá trình học tập, nghiên cứu về Xử Lý Dữ Liệu Lớn của mình, qua đó tổng hợp lại các kiến thức từ tổng quan đến chi tiết những gì mình học tập, nghiên cứu và thực hành được. Trong mỗi phần mình trình bày về lý thuyết sẽ có các phần minh họa cụ thể, phần minh họa này được code bằng Python, lưu file với đuôi là .ipynb hoặc có thể là đường link đến Google Colab của mình. 
  Dưới đây là toàn bộ nội dung mình đã học tập, nghiên cứu được và đi kèm với đó là các ứng dụng như
  - Đếm số lượng từ trong văn bản: [Word Counting](https://colab.research.google.com/drive/1ooNYc_wXl-0V3JwhQ8F62oXW6ab-986v)
  - Khai thác Association Rules sử dụng thuật toán A-priori trên môi trường PySpark: [Association Rule](https://colab.research.google.com/drive/1WTDOtKL3DR66tBmM_AtKvi_vtJWtCb--)
  - Tìm kiếm văn bản tương tự trong tập văn bản [không sử dụng PySpark](https://colab.research.google.com/drive/1al-1mblo6cCYbNAlHqMY36LNqNOHOC2E) và có [sử dụng PySpark](https://colab.research.google.com/drive/13yTs0VT0wYDV9YzDB9YMIEwu-SKZv-yl).
  - Crawl dữ liệu từ các đầu báo ở Việt Nam: [crawling_news](https://github.com/smoothkt4951/crawling-VietNam-News)
  - Machine Learning trên môi trường PySpark: [bank_datasets](https://colab.research.google.com/drive/1llG_cU6rhy6f1Ly15V--qy4ZNftFJZHV), [echocardiogram_datasets](https://colab.research.google.com/drive/16EMIPcADoxkFqR3f9QHrGNJ5biM-HhjR)
  - Hệ thống khuyến nghị sách

## Nội dung
- [0. Apache Spark và Mapreduce](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/0.%20Introduction%20MapReduce%20%20and%20Apache%20Spark)
  - I. Tổng quan về Apache Spark
    - 1. Giới thiệu
    - 2. Các thành phần của Apache Spark
    - 3. Những tính năng nổi bật
    - 4. Quản lý bộ nhớ của Apache Spark
  - II. Tổng quan về Mapreduce
    - 1. Hadoop và Mapreduce
    - 2. Mapreduce và các thủ tục chính
    - 3. Hàm Map và Reduce
    - 4. Nguyên tắc hoạt động
    - 5. Các bước hoạt động của MapReduce
    - 6. Luồng dữ liệu nền tảng của Mapreduce
    - 7. Ứng dụng của Mapreduce
  - III. Ví dụ minh họa
- [1. Spark Properties, Spark RDDs và Spark Dataframes](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/1.%20Spark%20properties%20and%20RDDs%20DataFrames)
  - I. Spark properties
    - 1. Tổng quan
    - 2. Tải động đối với các thuộc tính của Spark
    - 3. Tổng hợp và phân loại các thuộc tính trong Spark
  - II. Spark RDD
     - 1. Tổng quan
     - 2. Cài đặt Spark
     - 3. Khởi tạo Spark
     - 4. Resilient Distributed Datasets (RDDs)
   - III. Spark DataFrames
     - 1. Tổng quan
     - 2. Sử dụng DataFrames bổ sung cho RDD trong Spark
     - 3. Tính năng chính của DataFrames
     - 4. Khởi tạo DataFrames
     - 5. Làm việc với DataFrames
- [2. Association Rule với thuật toán A-priori](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/2.%20Association%20Rules)
   - I. Tổng quan
     - 1. Các khái niệm cơ bản
   - II. Bài toán Association Rules với store datasets
     - 1. Quy trình khai thác luật kết hợp
     - 2. Ứng dụng minh họa với store datasets
- [3. Locality Sensitive Hashing và bài toán Finding Similar Documents với dữ liện lớn](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/3.%20Locality-Sensitive%20Hashing)
  - I. Tổng quan
    - 1. Bài toán tìm kiếm các văn bản tương tự trong tập văn bản
    - 2. Jaccard Similarity
  - II. Phương pháp Shingling
  - III. Phương pháp Minhashing
  - IV. Phương pháp Locality Sensitive Hashing
     - 1. Phương pháp LSH trong tập tài liệu văn bản
     - 2. Phương pháp LSH cho Minhash Signatures
     - 3. Phân tích phương pháp LSH
  - V. Crawling data từ các đầu báo Việt Nam
  - VI. Bài toán Finding Similar Documents
- [4. Machine Learning trên môi trường PySpark ](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/4.%20Machine%20Learning%20in%20PySpark)
- [5. Recommender Systems](https://github.com/smoothkt4951/Massive-Data-Processing-Course/tree/main/5.%20Recommender%20Systems)

