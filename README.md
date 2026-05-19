# KHDL

I. Ý nghĩa các lệnh

1. Xem 5 dòng đầu tiên - df.head().

2.  Tạo biểu đồ tròn - plt.pie().

3.  Vòng lặp while dừng khi xuất hiện false.

   - mệnh đề else trong câu lệnh for thực hiện khi vòng lặp kết thúc bình thường, không bị break.

5.  Hàm pivot dùng để chuyển dữ liệu từ dọc sang ngang.

   - melt chuyển từ rộng sang dài.

6.  Hàm range (x) lấy số từ 0 đến n ( n là số ngay trước x ).

7. -  How = inner chỉ giữ cái nào chung của cả 2
   
   -  How = outer là giữ thông tin cả 2, cái nào thiếu thông tin thì còn lại fill NaN
  
   -  How = Left/Right là giữ của bên trái hoặc bên phải. Cái còn lại không khớp khóa sẽ điền NaN

8. Hàm fit() trong Scikit - learn dùng để huấn luyện mô hình dữ liệu train.

   * Trong thư viện khác dùng để khớp các hàm/ kích cỡ.

9. Matplotlib, đặt nhãn cho trục x thì nhập set_xlabel().

10. Cấu trúc cắt mảng - arr[start:stop:step]

11. Cấu trúc ghi dataframe ra file JSON - df.to_JSON()

    - Đọc dữ liệu thì là df.read

12. khi ghép 2 mảng muốn đặt một cái là khóa thì dùng Df.merge_right= true hoặc _left = true.

13. Dưới khớp ( underfitting ) - học dốt nên chưa học gì.

    - Quá khớp ( overfitting ) - Học vẹt nên học tất.

14. Muốn đọc tất cả sheet trong một file excel thì dùng xfile = pd.excelfile ("file.xlxs")

    - Prase dùng để mở file ngay lập tức mà không cần tốn thời gian.
   
15. Hàm plot dùng để vẽ biểu đồ.

    - Plot.bar thay cho plot.barh(horizontal) dùng khi có nhiều danh mục với tên dài.

16. Boxplot ( hộp và râu ) dùng để phát hiện giá trị ngoại lai.

17. read_csv() cho phép đặt lại cột names.

18. đọc n dòng đầu tiên dùng nrows=n.

19. One hot encoding là mỗi giá trị cho 1 cột ( chuyển chữ thành số ). => dùng phân loại biến không có thứ 

20. Lệnh grouphy dùng để gom những giá trị giống nhau. - df.grouphy()

21. Hàm means dùng để tính giá trị trung bình.

    - var tính phương sai
   
    - median số trung vị
   
    - độ lệch chuẩn 

23. sort.values dùng để xếp giá trị tăng dần.

    - nếu muốn xếp nhỏ dần thêm hàm ascending ( tăng dần ) = false => khi đó auto xếp ngược lại là giảm dần.

24. Toán tử is để check xem có cùng vị trí không

25.  Toán tử == check xem có cùng giá trị hay không

26. Phân biệt loc và iLoc

    - iloc dựa vào vị trí vật lý hoàn toàn.
   
    - loc dựa vào tên/nhãn ( nên phải có label)

27. Phân biệt khi nào nên sử dụng biểu đồ nào

    - Line: theo dõi xu hướng
   
    - Bar: theo dói cơ cấu
   
    - heatmap: thống kê mức độ hoạt động
   
    - dot: sự phân bố.

28. tạo một series từ thư viện dùng pd.series(dicta)

29. s.index.name dùng để đặt tên cho một series.

30. obj.index để xác định tối ưu của chuỗi

31. Sum() và mean() có axis=1 dùng để tính toán theo chiều ngang ( từng hàng )

32. lệnh kiểm tra dữ liệu biến x là type.(x)

33. xem 5 dòng đầu tiên dùng df.head(). => sau khi sắp xếp xong lấy 5 dòng đầu df.head(5)

34.  pop = trả về cột chỉ định + xóa

35.  đặt một cái gì đó = set.()

36. Không dùng linear registration cho nhị phân (0/1) vì chỉ có giá trị 0 và 1. không có ý nghĩa xác xuất

37. id.var() => định danh

    - value.var() => chuyển thành cột dữ 
   
38. Biến tất cả đầu cột thành chữ hoa df.collums = df.collums.str.upper()

39. thêm dữ liệu vào cuối list append()

40. viết comment bằng #comment

41. 
II. ý nghĩa và công việc các bước/ thuật toán.

1. Làm sạch dữ liệu:
   - Xử lý dữ liệu bị thiếu hoặc trùng lặp.

2. KNN (K-Nearest Neighbors) là tìm hàng xóm gần nhất mà giống với cái cần tìm => rất chậm

   - tính means = giá trị trung bình cộng của K

4. Phân tích dữ liệu giúp cung cấp thông tin sơ bộ (insight) định hình cho hướng đi đúng của dự án.

5. Triển khai mô hình gồm đưa mô hình vào môi trường thực tế và phục vụ nghiệp vụ.

6. Phân biệt các bài toán:

   - Phân loại: khi cần dự đoán một nhãn dán, danh mục.
  
   - Hồi quy: khi cần tính toán giá trị cụ thể, liên tục
  
   - Phân cụm: khi dữ liệu ban đầu không có nhãn và phải phân dl thành các cụm
  
   - Học củng cố: cho tự học, đạt thì thưởng (reward), không đạt thì phạt (penalty).

6. Các yếu tố trong một bài toán phân loại (classicfication) accuracy, precission, recall, f1-score.

7. hiển thị biểu đồ trực tiếp trong notebook jupyter %matplotlib inline

8. tạo thêm một subplot vào trong figure add_subplot()

9. Pandas:

   - series: 1 chiều (vd: list,..)
  
   - dataframe: 2 chiều (vd: exvel,..)
  
   - panel: 3 chiều
  
   - index: hệ thống dán nhãn định 
III. NOTE.

1. Trong python việc đánh số luôn bắt đầu từ 0.

2. Khi đọc dữ liệu mà không có thì ô đó auto hiện NaN

3. MSE hiếm khi bằng 0 do thực tế dữ liệu luôn có nhiễu và không bao giờ nằm bảng tuyệt đối.

4. nếu không có tiêu đề thì header = none.

5. linear regression nhạy cảm với dữ liệu ngoại lại do dùng bình phương sai số (mse) => dl sai phóng đại cấp số nhân.

6. set trong python không cho phần tử trùng

7. 3 cấp chỉ số: [0;1;2]

8. Mục tiêu chính của phân loại(category) là chuyển dữ liệu chữ sang số.

9. xủ lý giá trị thiếu ( data imputation ) kiểm tra tỷ lệ phân bố giá trị thiếu => hiệu quả hơn khi phát hiện giá trị ngoại 

10. chia nhánh nhằm tọa ra nhóm con tinh khiết (pure)

11. chỉ số phân cấp cho phép nhiều nhãn trên một cột ( hierarchical indexing )

12. f1 - score quyết định nên tin tưởng cái nào hơn.

13. set thì không lấy phần bị lặp lại.
