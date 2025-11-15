Đây là dự án bài tập lớn môn Machine Learning của hai thành viên: 
1. Nguyễn Hà Phương Uyên
2. Nguyễn Thị Phương Thảo

Trong nghiên cứu này, chúng tôi đề xuất một mô hình gợi ý phim lai (Hybrid Recommendation System) kết hợp giữa Collaborative Filtering (CF) và Content-Based Filtering (CBF) theo hai cơ chế cascade và weighted hybrid nhằm nâng cao độ chính xác của quá trình gợi ý. 
Người dùng được phân cụm bằng thuật toán K-Means, giúp giảm không gian tìm kiếm khi áp dụng KNN-based Collaborative Filtering. Mức độ tương đồng giữa người dùng được tính bằng Adjusted Cosine Similarity, từ đó xác định nhóm người dùng lân cận và dự đoán điểm đánh giá cho các phim chưa xem thông qua Weighted Average Prediction. 
Đồng thời, mô hình Content-Based Filtering được xây dựng dựa trên hồ sơ thể loại (genre profile) của từng người dùng, tính toán điểm nội dung (Content Score) cho mỗi phim bằng cách trung bình hóa điểm thể loại tương ứng. Cuối cùng, hai thành phần CF và CBF được kết hợp bằng phương pháp Weighted Hybrid. 
 
Kết quả thực nghiệm cho thấy mô hình lai này đạt được sự cân bằng giữa khả năng học từ dữ liệu hành vi người dùng và khả năng hiểu ngữ nghĩa nội dung phim, giúp cải thiện chất lượng gợi ý so với các phương pháp đơn lẻ.
