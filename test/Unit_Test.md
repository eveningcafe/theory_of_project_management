- Khái niệm: Một Unit là một thành phần PM nhỏ nhất mà ta có thể kiểm tra được như các hàm (Function), thủ tục (Procedure), lớp (Class), hoặc các phương thức (Method).
</br> Unit được chọn để kiểm tra thường có kích thước nhỏ và chức năng hoạt động đơn giản
=> dễ dàng trong việc tổ chức, kiểm tra, ghi nhận và phân tích kết quả kiểm tra nên việc  phát hiện lỗi sẽ dễ dàng xác định nguyên nhân và khắc phục cũng tương đối dễ dàng vì chỉ khoanh vùng trong một Unit đang kiểm tra.
 
- Thiết kế: Mỗi UT sẽ gửi đi một thông điệp và kiểm tra câu trả lời nhận được đúng hay không, bao gồm:
  - Các kết quả trả về mong muốn
  - Các lỗi ngoại lệ mong muốn
<br/> Các đoạn mã UT hoạt động liên tục hoặc định kỳ để thăm dò và phát hiện các lỗi kỹ thuật trong suốt quá trình phát triển, do đó UT còn được gọi là kỹ thuật kiểm nghiệm tự động.
- UT có các đặc điểm sau:
  - Đóng vai trò như những người sử dụng đầu tiên của hệ thống.
  - Chỉ có giá trị khi chúng có thể phát hiện các vấn đề tiềm ẩn hoặc lỗi kỹ thuật.
