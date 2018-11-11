### Danh sách sinh viên trong nhóm
- Ngô Quang Hòa
- Đào Công Hoàng
- Bùi Đức Hiếu
- Đỗ Minh Hải
### Unit Test

- Khái niệm Một Unit là một thành phần PM nhỏ nhất mà ta có thể kiểm tra được như các hàm (Function), thủ tục (Procedure), lớp (Class), hoặc các phương thức (Method).
</br> Unit được chọn để kiểm tra thường có kích thước nhỏ và chức năng hoạt động đơn giản
=> dễ dàng trong việc tổ chức, kiểm tra, ghi nhận và phân tích kết quả kiểm tra nên việc  phát hiện lỗi sẽ dễ dàng xác định nguyên nhân và khắc phục cũng tương đối dễ dàng vì chỉ khoanh vùng trong một Unit đang kiểm tra.
 
- Thiết kế: Mỗi UT sẽ gửi đi một thông điệp và kiểm tra câu trả lời nhận được đúng hay không, bao gồm:
  - Các kết quả trả về mong muốn
  - Các lỗi ngoại lệ mong muốn
<br/> Các đoạn mã UT hoạt động liên tục hoặc định kỳ để thăm dò và phát hiện các lỗi kỹ thuật trong suốt quá trình phát triển, do đó UT còn được gọi là kỹ thuật kiểm nghiệm tự động.
- UT có các đặc điểm sau:
  - Đóng vai trò như những người sử dụng đầu tiên của hệ thống.
  - Chỉ có giá trị khi chúng có thể phát hiện các vấn đề tiềm ẩn hoặc lỗi kỹ thuật.
### Acceptance Test
- Khái niệm: Là một kỹ thuật kiểm thử được thực hiện để xác định hệ thống phần mềm có đạt được những yêu cầu kỹ thuật hay không.
 
- Mục đích: để đánh giá hệ thống với những yêu cầu của doanh nghiệp và xác nhận nếu hệ thống đáp ứng được những tiêu chí yêu cầu để chuyển đến người dùng cuối.
 
- Kiểm thử chấp nhận có nhiều dạng như sau:
  - Kiểm thử chấp nhận người dùng
  - Kiểm thử chấp nhận doanh nghiệp
  - Kiểm thử Alpha
  - Kiểm thử Beta
### Stability Test
- Khái niệm: Stability testing là khả năng duy trì hoạt động của sản phẩm xuyên suốt thời hạn sử dụng của nó, mà không hỏng hoặc xảy ra lỗi. 
</br> Đây là một kỹ thuật non-functional, với mục đích đòi hỏi khả năng chịu tải của phần mềm tới mức tối đa. Trong quá trình xác định nó hoạt động tốt thế nào dưới tải ở mức chấp nhận được, mức đỉnh, các tải được tạo ra đột ngột, với số lượng dữ liệu lớn được xử lý… 
- Mục đích: Stability testing được thực hiện để kiểm tra hiệu quả của một sản phẩm được phát triển vượt qua mức hoạt động bình thường, hay tới một điểm dừng. Có ý nghĩa quan trọng hơn là trong việc xử lý lỗi, độ tin cậy của phần mềm, khả năng chịu tải và khả năng mở rộng của một sản phẩm dưới tải lớn chứ không phải là kiểm tra cách hoạt động của hệ thống trong các hoàn cảnh bình thường.
<br/> Stability testing còn được gọi là Load hoặc endurance testing.

### Automatic test

- Khái niệm: automatic test la việc sử dụng các công cụ dể thực hiện qua trình test một cách tự dộng . Automatic test là một phần cốt lõi trong cd ci pipeline
- Mục đích : 
   - Tự động công việc, giảm các thao tác test lặp di lặp lại. Đảm bẻo không chạy thiếu, lỗi test case
   - Khả năng tái sư dụng giảm thieu chi phi thời gian nhân lực.
   - Thực hiện các test khó, đặc biệt mà bình thường test thủ không làm dược (vd test hiệu nang)
- Phương pháp:
</br>Các phần mềm chạy ra automatic test thường dựa vào 2 phuơng pháp sau:
   - Graphical user interface testing: Tool sẽ biểu hiện ra ra các user interface events, tức các việc go phím click chuột, thường dùng để test dến các user case người dùng cuối
   - API driven testing: sử dụm programming interface, tester có thể dùng cả cho test về functionality, reliability, performance, và security cho các class, thư viện, module.
   </br> Khảo sát về tỉ lệ dùng các các level trên trong automatic test dùng tại các công ty:
</br>![](https://github.com/ngohoa211/theory_of_project_management/blob/master/test/image/layer.png)
- Lĩnh vực cần dùng dến automatic test
</br>![](https://github.com/ngohoa211/theory_of_project_management/blob/master/test/image/area.png)
</br>(theo các khảo sát tại https://www.logigear.com/magazine/survey/survey-results-test-automation/)
