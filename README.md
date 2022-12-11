# Project 6 - Cloud Computing
Tên đề tài: Tìm hiểu về Apache Hive và Xây dựng Data Warehouse đơn giản. 
# Thành viên tham gia Project
* Đinh Tấn Phúc Huy - 20110129 - 20110129@student.hcmute.edu.vn  
* Đỗ Trung Đức - 20110459 - 20110459@student.hcmute.edu.vn  
* Nguyễn Văn Giang - 20110463 - 20110463@student.hcmute.edu.vn
# Nội dung chính
* Tìm hiểu về Apache Hive
* Xây dựng data warehouse trên EMR
# Công nghệ, phần mềm và dịch vụ được sử dụng
* Apache Hive
* Apache Hadoop
* Apache Sqoop
* MySQL
* Amaxon RDS
* Amazon EMR
* Amazon S3
# Những gì nhóm đã làm được
* Tìm hiểu về cơ sở lý thuyết của hive
* Khởi tạo, cấu hình và sử dụng hive trên EMR cluster  
* Truyền tải dữ liệu theo phương pháp Full load:
  * Xây dựng đường truyền dữ liệu từ Amazon RDS/MySQL lên s3 bucket (database -> data lake)
  * Xây dựng đường truyền dữ liệu từ S3 bucket vào bảng hive table (data lake -> data warehouse)
* Truyền tải dữ liệu theo phương pháp Incremental load:
  * Xây dựng đường truyền dữ liệu từ Amazon RDS/MySQL vào bảng hive table
* Sử dụng HUE để thực hiện các truy vấn HiveQL
# Video báo cáo của nhóm
* Lần 1: https://drive.google.com/file/d/1b3XJmsguE0D9BPvcuIM1O1zRCFP6xSgd/view?usp=sharing
* Lần 2:
# Mục tiêu và hướng phát triển
* Áp dụng các phương pháp tải vào các bản cập nhật mới hơn của Amazon EMR.
* Xây dưng được pháp pháp tải Incrememtal load tốt hơn (Amazon RDS/MySQL -> S3 bucket -> Hive)
* Tính toán được chi phí sử dụng
# Link tham khảo: 
* Migrate RDBMS or On-Premise data to EMR Hive, S3 using EMR – Sqoop: https://aws.amazon.com/vi/blogs/big-data/migrate-rdbms-or-on-premise-data-to-emr-hive-s3-and-amazon-redshift-using-emr-sqoop/
* Transfer MySQL RDS data to S3 & Import S3 Data to Hive using SQOOP.
https://www.youtube.com/watch?v=zqyOOyOlcAk&t=796s
