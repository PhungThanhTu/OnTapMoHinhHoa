# 1. Mô hình hóa là gì? Ý nghĩa mô hình hóa?
Mô hình hoá là **hướng nền tảng** và **định lượng** để **hiểu các hệ thống phức tạp** và các hiện tượng (tự nhiên, trong cuộc sống…)<br>
Mô hình hoá là sự **bổ sung** tới các **phương pháp nghiên cứu cổ điển** về **lý thuyết** và **thực nghiệm**
Mô hình hoá là quá trình sản sinh ra các **mô hình trừu tượng** và **khái niệm.**

Mô hình hoá sẽ tạo các kỹ năng và kỹ thuật nhằm tạo ra các kết quả **sâu sắc, đáng tin cậy**, và **dễ sử dụng**

# 2. Mô hình hướng dịch vụ (SOA) là gì? Kiến trúc và lợi ích của SOA?
SOA là một **cách tiếp cận** để **tổ chức** **các tài nguyên  công nghệ thông tin** mà ở đó **dữ liệu, logic và nguồn  lực hạ tầng** được **truy cập** thông qua các **giao diện  (interface)** và **thông điệp (Message)**
<div style="text-align:center"><img src="https://user-images.githubusercontent.com/67744403/125777347-4335bea2-bf9a-445c-9a08-f9c47f886262.PNG" /></div>
 Lợi ích : <br>
 
 - **Hướng sự tập trung** vào **xây dựng** các **tính năng nghiệp vụ** (trong quá trình phát triển phần mềm) <br>
 - Tính **tái sử dụng** cao, **không đòi hỏi phải thay đổi** 
 toàn bộ quy trình<br>
 - **Giảm thiể**u yêu cầu về **đào tạo và kỹ năng**<br>
 - **Giảm thiểu **chi phí**, chi phí bảo trì thấp<br>
 - Chu trình phát triển phần mềm **nhanh chóng** hơn<br>
 - Các bên không cần khai báo **tường minh** về công 
 nghệ, nền tảng hệ thống, vị trí hoặc môi trường<br>

# 3. Web service (WS) là gì? Các thành phần của WS? 
Web service là một **công nghệ triệu gọi từ xa** có tính **khả chuyển** cao: mang tính **độc lập nền**, độc lập **ngôn ngữ**

Thành phần :
- Nhóm các chuẩn dựa trên XML
- Ngôn ngữ định danh dịch vụ Web (Web Services Definition Language – WSDL) có nhiệm vụ cung cấp một cách thức cơ bản để mô tả các thành phần của phần mềm
- Giao thức truy cập đối tượng đơn giản (Simple Object Access Protocol – SOAP)
- Chuẩn dịch vụ Tích hợp, Khám phá và Mô tả thống nhất (Universal Description, Discovery, and Integration – UDDI)

# 4. SDLC là gì? Các giai đoạn trong SDLC? Trình bày mục đích của từng giai đoạn?
SDLC là một **quy trình** được sử dụng bởi ngành **công nghiệp phần mềm** để **thiết kế**.

Mục đích từng giai đoạn :
- Lập kế hoạch : báo cáo tính khả thi chứa đựng định nghĩa một vấn đề và tổng quát hoá mục tiêu, phạm vi và các rủi ro liên quan
- Xác định yêu cầu : thu được tài liệu SRS (Đặc tả yêu cầu phần mềm-Software Requirements Specification) bao gồm tất cả các yêu cầu sản phẩm được thiết kế và phát triển trong vòng đời dự án
- Phân tích : Mô hình hệ thống mà tổng quát ,cung cấp giá thành/lợi ích trong quá trình chọn lựa và đưa ra những đề nghị sẽ làm gì trong mô hình
- Thiết kế : Thiết kế bên trong của tất cả các mô-đun của hệ thống (Design Document Specification-DDS)
- Xây dựng hệ thống : Viết mã hiện thực hóa các module được đặc tả trong DDS
- Thử nghiệm và bảo trì hệ thống : Hoàn thiện hệ thống để sẵn sàng đưa vào triển khai
- Vận hành và đánh giá hệ thống : Cung cấp các bản vá lỗi và các bản cập nhật thích hợp cho hệ thống
# 5. Có những cách tiếp cận nào trong hiện thực SDLC? Nêu ưu/nhược điểm của từng cách và cho ví dụ về phương pháp trong từng cách tiếp cận. 
### Phương pháp tiếp cận tuyến tính ( Linear )
Ưu điểm :
 + Đơn giản dễ áp dụng
 + Dễ quản lí 
 + Tiêu chí đầu vào rõ ràng, kiểm tra chất lượng dễ dàng
 + Hoạt động hiệu quả trong các dự án nhỏ với yêu cầu rõ ràng
 + Cung cấp nhiều tài liệu cho khách hàng
Nhược điểm :
 + Không hiệu quả trong các dự án lớn
 + Không hiệu quả khi yêu cầu không rõ ràng
 + Khó thích ứng với sự thay đổi yêu cầu, kế hoạch, phạm vi dự án
 + Khách hàng chỉ thấy và sử dụng sản phẩm ở cuối chu trình
### Phương pháp tiếp cận tăng trường ( Incremental )
Ưu điểm :
 + Thực hiện nhanh một số chức năng
 + Thực hiện song song các chức năng
 + Chi phí thấp nếu yêu cầu/phạm vi thay đổi
 + Phù hợp với các dự án lớn và cấp bách
Nhược điểm :
 + Cần nhiều tài nguyên
 + Công tác quản lý không dễ dàng
 + Phác thảo và thiết kế liên tục
 + Cần nhiều kinh nghiệm khi tiến hành
# 6. SDLC 
## a. Các mô hình: Waterfall, mô hình chữ V, lặp, xoắn ốc, RAD, Agile 
## b. Agile là gì? Các nguyên tắc chính của Agile? 
## c. So sánh Agile và Waterfall 
## d. Scrum và Extreme Programming: là gì? so sánh 2 phương pháp 
# 7. Thiết kế hướng cấu trúc (SOD) và thiết kế hướng đối tượng (OOD) là gì? So sánh 2 phương pháp. 
# 8. Mô hình hóa dữ liệu 
## a. ERD (là gì? Mục đích? Thành phần? Các bước xây dựng) 
## b. Dữ liệu quan hệ (là gì? Mục đích? Thành phần? Các bước xây dựng) 
## c. Chuyển đổi từ ERD sang mô hình dữ liệu quan hệ 
# 9. UML và OOAD 
## a. Lịch sử, ý nghĩa, thành phần của UML 
## b. Các sơ đồ trong UML: use case, sơ đồ tuần tự, hoạt động và sơ đồ lớp 
## c. Các bước trong phân tích và thiết kế hướng đối tượng, nội dung từng bước 
# 10. 3 Mô hình tier và 3 layer 
## a. Giới thiệu, thành phần, ý nghĩa của từng mô hình? 
## b. So sánh 3 tier và 3 layer
# 11.Trình bày một mô hình mà bạn quan tâm (khác với seminar của nhóm), trình bày các hiểu biết của bạn về mô hình đó.
# 12.Nắm rõ chủ đề seminar của nhóm.

