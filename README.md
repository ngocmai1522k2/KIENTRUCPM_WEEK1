# KIENTRUC & TKPM_WEEK1
 Lớp học phần: DHKTPM16A
 Giảng viên hướng dẫn: Võ Văn Hải & Nguyễn Văn Thắng
 Sinh viên thực hiện: Lê Thị Ngọc Mai
 MSSV: 20005501

## Nội dung thực hành week1
![image](https://github.com/ngocmai1522k2/KIENTRUCPM_WEEK1/assets/144517477/86876336-3d96-47d4-820c-742edee5db5b)

## 1. Yêu cầu đặc tả:
- Phần mềm được thiết kế để điều khiển 1 máy rút tiền tự động (ATM gồm đầu đọc thẻ, bàn phím, màn hình, khe gửi phong bì, máy rút tiền mặt, máy in biên lai, công tắc vận hành bằng phím cho phép người vận hành khởi động hoặc dừng máy).
- ATM sẽ phục vụ tại 1 thời điểm. Khách hàng đưa thẻ vào khe đọc thẻ, nhập mã PIN, sau đó thông tin sẽ được gửi đến ngân hàng để xác thực trước khi thực hiện giao dịch. Khách hàng có thể thực hiện 1 hoặc nhiều giao dịch. Thẻ sẽ được trả lại khi khách hàng xác nhận không giao dịch nữa.
- ATM phải cung cấp các dịch vụ:
   + Khách hàng phải có khả năng rút tiền mặt từ bất kỳ tài khoản phù hợp nào được liên kết với thẻ, theo bội số của $20,00. Phải có sự chấp thuận của ngân hàng trước khi rút tiền mặt.
   + Khách hàng phải có khả năng gửi tiền vào bất kỳ tài khoản nào được liên kết với thẻ, bao gồm tiền mặt và/hoặc séc trong phong bì. Khách hàng sẽ nhập số tiền gửi, và xác nhận thủ công khi phong bì được lấy ra của ngân hàng.
   + Khách hàng phải có khả năng thực hiện chuyển tiền giữa hai tài khoản bất kỳ được liên kết vào thẻ.
   + Khách hàng phải có khả năng truy vấn số dư của bất kỳ tài khoản nào được liên kết với thẻ.
   + Khách hàng phải có khả năng hủy giao dịch đang diễn ra bằng cách nhấn phím Hủy.
   + ATM sẽ liên lạc từng giao dịch với ngân hàng và xác minh rằng nó đã được thực hiện.
   + Nếu giao dịch không thành công vì bất kỳ lý do nào khác ngoài mã PIN không hợp lệ, ATM sẽ hiển thị lời giải thích và sau đó sẽ hỏi khách hàng xem họ có muốn làm một việc khác không.
   + ATM sẽ cung cấp cho khách hàng bản in hóa đơn cho mỗi giao dịch thành công, hiển thị ngày, giờ, vị trí máy, loại giao dịch, (các) tài khoản, số tiền và kết thúc và (các) số dư khả dụng của tài khoản bị ảnh hưởng (tài khoản "đến" để chuyển khoản).
   + ATM sẽ có một công tắc vận hành bằng chìa khóa cho phép người vận hành khởi động và dừng hoạt động.
   + ATM cũng sẽ duy trì nhật ký giao dịch nội bộ

  CÁC USE CASES:
  ![image](https://github.com/ngocmai1522k2/KIENTRUCPM_WEEK1/assets/144517477/886719ea-11dd-458d-acfd-60c040e7c651)

  

## Tài liệu liên quan

- [Java EE Documentation](https://javaee.github.io/javaee-spec/)
- [Java Database Connectivity (JDBC) Documentation](https://docs.oracle.com/en/java/javase/16/docs/api/java.sql/java/sql/package-summary.html)
- [Apache Tomcat Documentation](https://tomcat.apache.org/tomcat-9.0-doc/index.html)
- [Git Version Control](https://git-scm.com/book/en/v2)


## Đóng góp

Nếu bạn muốn đóng góp vào dự án hoặc báo cáo lỗi, vui lòng tạo issue hoặc gửi pull request vào repository GitHub của dự án.

- GitHub Repository: [www_lab_week1](https://github.com/ngocmai1522k2/KIENTRUCPM_WEEK1)
- Tạo issue mới: [Tạo issue](https://github.com/ngocmai1522k2/KIENTRUCPM_WEEK1/issues/new)
- Gửi pull request: [Gửi pull request](https://github.com/ngocmai1522k2/KIENTRUCPM_WEEK1/compare)

Chúng tôi rất hoan nghênh mọi đóng góp từ cộng đồng!

---
