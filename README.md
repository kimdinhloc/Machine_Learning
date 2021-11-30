# Machine_Learning
### Đồ án vấn đáp môn Học máy - Phân lớp ảnh chữ số viết tay bằng SVM    
Bộ dữ liệu được sử dụng là bộ MNIST (http://yann.lecun.com/exdb/mnist/). Mỗi mẫu (example) trong bộ MNIST gồm: input là ảnh chữ số viết tay grayscale có kích thước 28×28 (như vậy, véc-tơ input sẽ có số chiều là 28×28=784), “correct ouput” ∈ {0, 1, ..., 9} cho biết chữ số tương ứng của ảnh (như vậy, sẽ có tất cả 10 lớp).  
Chọn hàm dự đoán có độ lỗi nhỏ nhất trên tập validation là hàm dự đoán cuối cùng.

Thành viên nhóm:  
KIM ĐÌNH LỘC 1712568  
NGUYỄN HỮU THẮNG - 1712756  

Sau khi train model linear SVM với C=0.1 thì ta đạt được 94.63% cao hơn yêu cầu là 92%.  
Còn đối với model RBF kennel với C = 10, Gamma = 0.1 thì ta đạt max tận 98.2% cao hơn yêu cầu là 96.4%.  
