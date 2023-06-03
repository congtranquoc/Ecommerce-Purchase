# Ecommerce-Purchase
## Mô tả 
Thư mục này chứa một chương trình demo để phân tích một tập dữ liệu và tìm ra các mối quan hệ và mẫu liên quan đến chức danh công việc, tổng số tiền mua hàng, trình duyệt internet, địa điểm và nhà cung cấp thẻ tín dụng. Tập dữ liệu cung cấp thông tin về các giao dịch mua hàng của các cá nhân khác nhau.
## Dataset
Tập dữ liệu được sử dụng cho phân tích này bao gồm các bản ghi mua hàng, bao gồm thông tin như chức danh công việc, tổng số tiền mua hàng, trình duyệt internet, địa điểm (tỉnh/thành phố), nhà cung cấp thẻ tín dụng và thời gian mua hàng (sáng hoặc chiều). Tập dữ liệu được lưu trữ trong tệp có tên là Ecommerce_Purchases.csv.

## Yêu cầu
Để chạy chương trình demo thành công, bạn cần đáp ứng các yêu cầu sau:

1. Python 3.x
2. Thư viện Pandas (phiên bản 1.2.0 trở lên)
3. Thư viện NumPy (phiên bản 1.20.0 trở lên)
4. Thư viện Matplotlib (phiên bản 3.3.0 trở lên)

## Task
Chương trình demo thực hiện các nhiệm vụ phân tích sau trên tập dữ liệu:
1. Tìm mối quan hệ giữa 5 chức danh công việc hàng đầu và tổng số tiền mua hàng: Phân tích này xác định 5 chức danh công việc hàng đầu và số tiền mua hàng tương ứng.
2. Tìm mối quan hệ giữa chức danh công việc và giá trị trung bình của tổng số tiền mua hàng: Phân tích này xác định giá trị trung bình của tổng số tiền mua hàng cho mỗi chức danh công việc
3. Giá trị mua hàng phụ thuộc vào trình duyệt internet được sử dụng và chức danh (nghề nghiệp) của người mua hàng như thế nào?
4. Có mẫu nào xuất hiện trong các giao dịch mua hàng dựa trên địa điểm (tỉnh/thành phố) và thời gian mua hàng (AM hoặc PM) không?
5. Mua hàng phụ thuộc vào nhà cung cấp thẻ tín dụng (CC) và thời gian mua hàng (AM hoặc PM) như thế nào?
6. Những địa điểm nào là 5 địa điểm hàng đầu cho các giao dịch mua hàng?
