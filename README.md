# KHDL

I. Ý nghĩa các lệnh

1. Xem 5 dòng đầu tiên - df.head().

2.  Tạo biểu đồ tròn - plt.pie().

3.  Vòng lặp while dừng khi xuất hiện false.

4.  Hàm pivot dùng để chuyển dữ liệu từ dọc sang ngang.

5.  Hàm range (x) lấy số từ 0 đến n ( n là số ngay trước x ).

6. -  How = inner chỉ giữ cái nào chung của cả 2
   
   -  How = outer là giữ thông tin cả 2, cái nào thiếu thông tin thì còn lại fill NaN
  
   -  How = Left/Right là giữ của bên trái hoặc bên phải. Cái còn lại không khớp khóa sẽ điền NaN

7. Hàm fit() trong Scikit - learn dùng để huấn luyện mô hình dữ liệu train.

   * Trong thư viện khác dùng để khớp các hàm/ kích cỡ.

8. Matplotlib, đặt nhãn cho trục x thì nhập set_xlabel().

9. Cấu trúc cắt mảng - arr[start:stop:step]

10. Cấu trúc ghi dataframe ra file JSON - df.to_JSON()

    - Đọc dữ liệu thì là df.read

11. khi ghép 2 mảng muốn đặt một cái là khóa thì dùng Df.merge_right= true hoặc _left = true.

12. Dưới khớp ( underfitting ) - học dốt nên chưa học gì.

    - Quá khớp ( overfitting ) - Học vẹt nên học tất.

13. Muốn đọc tất cả sheet trong một file excel thì dùng xfile = pd.excelfile ("file.xlxs")

    - Prase dùng để mở file ngay lập tức mà không cần tốn thời gian.
   
14. Hàm plot dùng để vẽ biểu đồ.

    - Plot.bar thay cho plot.barh(horizontal) dùng khi có nhiều danh mục với tên dài.

15. Boxplot ( hộp và râu ) dùng để phát hiện giá trị ngoại lai.

16. read_csv() cho phép đặt lại cột names.

17. đọc n dòng đầu tiên dùng nrows=n.

18. One hot encoding là mỗi giá trị cho 1 cột ( chuyển chữ thành số ).

19. Lệnh grouphy dùng để gom những giá trị giống nhau. - df.grouphy()

20. Hàm means dùng để tính giá trị trung bình.

21. sort.values dùng để xếp giá trị tăng dần.

    - nếu muốn xếp nhỏ dần thêm hàm ascending ( tăng dần ) = false => khi đó auto xếp ngược lại là giảm dần.

22. Toán tử is để check xem có cùng vị trí không

23.  Toán tử == check xem có cùng giá trị hay không


II. ý nghĩa và công việc các bước/ thuật toán.

1. Làm sạch dữ liệu:
   - Xử lý dữ liệu bị thiếu hoặc trùng lặp.

2. KNN (K-Nearest Neighbors) là tìm hàng xóm gần nhất mà giống với cái cần tìm => rất chậm

3. Phân tích dữ liệu giúp cung cấp thông tin sơ bộ (insight) định hình cho hướng đi đúng của dự án.

4. Triển khai mô hình gồm đưa mô hình vào môi trường thực tế và phục vụ nghiệp vụ.

5. Phân biệt các bài toán:

   - Phân loại: khi cần dự đoán một nhãn dán, danh mục.
  
   - Hồi quy: khi cần tính toán giá trị cụ thể, liên tục
  
   - Phân cụm: khi dữ liệu ban đầu không có nhãn và phải phân dl thành các cụm
  
   - Học củng cố: cho tự học, đạt thì thưởng (reward), không đạt thì phạt (penalty).

6
III. NOTE.

1. Trong python việc đánh số luôn bắt đầu từ 0.

2. Khi đọc dữ liệu mà không có thì ô đó auto hiện NaN

3. 
