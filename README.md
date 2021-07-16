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
### Waterfall : Trong mô hình Waterfall, các giai đoạn của dự án được thực hiện lần lượt và nối tiếp nhau. Giai đoạn mới chỉ được bắt đầu khi giai đoạn trước nó đã được hoàn thành.
### V : Trong mô hình V, các hoạt động phát triển và đảm bảo chất lượng được thực hiện đồng thời. Không có pha rời rạc được gọi là kiểm thử, thay vào đó kiểm thử được bắt đầu ngay từ giai đoạn lấy yêu cầu. Các hoạt động xác minh và xác nhận đi liền với nhau.
### Mô hình lặp :
- Xây dựng nhanh ứng dụng con đáp ứng một phần yêu cầu
- Ứng dụng con cũng được kiểm tra, đánh giá và hiệu chỉnh
- Trong mỗi bước lặp, mở rộng ứng dụng con lớn dần cho đến khi đáp ứng tất cả yêu cầu
- Có thể có nhiều vòng lặp tại một thời điểm và ứng dụng lớn có thể được chia thành nhiều hiện thực con (build)
### Mô hình xoắn ốc : Mô hình xoắn ốc (Spiral-Model) là mô hình có sự kết hợp giữa mô hình thác nước (Waterfall-Model) và mô hình tiếp cận lặp (Iterative-Model) và nó có nhiều điểm giống nhau với mô hình gia tăng (Incremental-Model).
### Mô hình RAD : Mô hình RAD (Phát triển ứng dụng nhanh) dựa trên nguyên mẫu và phát triển lặp mà không có kế hoạch cụ thể liên quan
## b. Agile là gì? Các nguyên tắc chính của Agile? 
Agile là một phương pháp phát triển phần mềm linh hoạt để làm sao đưa sản phẩm đến tay người dùng càng nhanh càng tốt càng sớm càng tốt.
Tuyên ngôn Agile :
- **Cá nhân và sự tương tác** hơn là quy trình và công cụ;
- **Phần mềm chạy tốt hơn** là tài liệu đầy đủ;
- **Cộng tác với khách hàng hơn** là đàm phán hợp đồng;
- **Phản hồi với các thay đổi hơn** là bám sát kế hoạch.
## c. So sánh Agile và Waterfall 
|Waterfall          |Agile        |
|-------------------|-------------|
|Tách SDLC thành các sprint lặp đi lặp lại|Tách SDLC thành các giai đoạn rõ ràng|
|Tiếp cận tăng trưởng|Tiếp cận tuần tự|
|Linh hoạt với sự thay đổi|Kém linh hoạt, cững nhắc, bám sát kế hoạch|
|Là một tập hợp nhiều dự án nhỏ kết hợp|Được phát triển như một dự án duy nhất|
|Kiểm thử trong mỗi sprint|Kiểm thử trong giai đoạn kiểm thử|
|Thích hợp với các dự án có yêu cầu không rõ ràng, có sự thay đổi về yêu cầu và phạm vi|Thích hợp với những dự án yêu cầu rõ ràng, không có sự thay đổi yêu cầu và phạm vi|
## d. Scrum và Extreme Programming: là gì? so sánh 2 phương pháp 
Scrum là một quy trình phát triển phần mềm theo phương pháp Agile. Chính vì thế, Scrum tuân thủ các nguyên tắc của Agile Manifesto.
XP (Extreme Programming) là một phương pháp phát triển phần mềm hướng đến việc nâng cao chất lượng phần mềm và khả năng đáp ứng với thay đổi yêu cầu người dùng. XP là một trong các phương pháp thuộc họ Agile, nó chủ trương đưa ra các bản phát hành thường xuyên thông qua các chu trình phát triển ngắn.

Cả 2 framework đều phát triển dựa trên các sprint, mỗi sprint có độ dài cố định, có sprint backlog, sprint goal & bao gồm các hoạt động Agile như daily meeting, sprint planning, sprint retro, sprint review.

Khác biệt :
|Scrum|XP|
|-----|--|
|Sprint kéo dài từ 1-4 tuần|Sprint kéo dài từ 1 - 2 tuần, chú trọng release sớm|
|hạn chế thay đổi sprint backlog sau khi các kế hoạch của sprint được đề ra|có thể thay đổi backlog miễn là có độ lớn tương ứng backlog cũ|
|Có thể tự quyết định thứ tự thực hiện đáp ứng các User Story|Thứ tự thực hiện phải đúng với thứ tự ưu tiên đề ra|
|Không yêu cầu tuân thử chặt chẽ programming practices|Yêu cầu tuân thủ programming practices để đảm bảo CD|
# 7. Thiết kế hướng cấu trúc (SOD) và thiết kế hướng đối tượng (OOD) là gì? So sánh 2 phương pháp. 
SOD : Là một cách tiếp cận có hệ thống, sử dụng các công cụ đồ họa để phân tích và tinh chỉnh các mục tiêu của một hệ thống hiện có
OOD : Nắm bắt cấu trúc và hành vi của các hệ thống thông tin thành các mô-đun nhỏ kết hợp cả dữ liệu và quy trình
# 8. Mô hình hóa dữ liệu 
## a. ERD (là gì? Mục đích? Thành phần? Các bước xây dựng) 
 ERD là một sơ đồ, thể hiện các thực thể có trong database, và mối quan hệ giữa chúng với nhau.
Thành phần :
- Thực thể
- Thuộc tính
- Mối quan hệ
Cách vẽ
- B1: Nhận biết thực thể, đặc tính, quan hệ
- B2: Nhận biết khoá chính
- B3: Phác thảo mô hình ERD
- B4: Nhận biết bậc của quan hệ và các ràng buộc
thành viên khi cập nhật phác thảo bên trên với
các giá trị của nó
- B5: Phân tích các đặc tính đa giá trị vào các đặc
tính có thể phân biệt được hoặc tạo thêm một
thực thể
- B6: Vẽ lại mô hình ERD với giá trị bổ sung từ
bước 5
## b. Dữ liệu quan hệ (là gì? Mục đích? Thành phần? Các bước xây dựng) 
Mô hình dữ liệu quan hệ được xây dựng dựa trên đối tượng cơ bản là các quan hệ (bảng), các thuộc tính và các ràng buộc –> dùng để thể hiện mô hình dữ liệu hiện thực.
Cấu trúc :
- Dữ liệu được thể hiện trong các bảng, mỗi bảng thể hiện thông tin về một chủ thể (hàng, cột)
- Mỗi hàng biểu thị cho một cá thể, gồm một bộ các giá trị tương ứng các cột
- Các cột biểu thị các thuộc tính của chủ thể, tên cột là tên của thuộc tính.
Các bước xây dựng :
- Xây dựng ERD tương ứng
- Chuyển đổi ERD sang mô hình dữ liệu quan hệ
## c. Chuyển đổi từ ERD sang mô hình dữ liệu quan hệ 
- Chuyển các mối kết hợp 1-1 gom 2 thực thể thành một thực thể
- Các mối kết hợp 1-N lấy khóa bên thực thể nhiều chuyển thành khóa ngoại
- Các mối quan hệ N-N hình thành một loại quan hệ mới
- kiểm tra lại dạng chuẩn của các mối quan hệ.
# 9. UML và OOAD 
## a. Lịch sử, ý nghĩa, thành phần của UML 
UML để :
- Trực quan hóa
- Cụ thể hóa
- Sinh mã ở dạng nguyên mẫu
- Lập và cung cấp tài liệu
Thành phần : 
- View (góc nhìn)
- Diagram (bản vẽ)
- Notations (ký hiệu)
- Mechanisms (qui tắc, cơ chế)
## b. Các sơ đồ trong UML: use case, sơ đồ tuần tự, hoạt động và sơ đồ lớp 
Use case : đưa ra cách nhìn bao quát (từ trên xuống) cách sử dụng của hệ thống cũng như cách nhìn hệ thống từ bên ngoài.
Tuần tự : mô tả sự tương tác của các lớp trong trình tự về thời gian. Những mô hình này được liên kết với phương pháp case (tình huống).
Hoạt động : mô tả tiến trình xử lý và trình tự những hành động trong tiến trình xử lý, Trông nó giống như biểu đồ tiến trình (flowchart) bởi vì nó mô tả dòng làm việc từ hoạt động sang hoạt động và từ hoạt động sang trạng thái.
Lớp : Class diagram là xương sống của hầu như tất cả các phương pháp hướng đối tượng, bao gồm cả UML. Chúng mô tả các cấu trúc tĩnh của hệ thống.
## c. Các bước trong phân tích và thiết kế hướng đối tượng, nội dung từng bước 
### Phân tích hướng đối tượng
- Xác định các yêu cầu, xây dựng mô hình ca sử dụng
- Xác định các lớp và mối quan hệ của chúng với các lớp khác trong phạm vi liên quan
### Thiết kế hướng đối tượng
- Thiết kế và tinh chỉnh các lớp, thuộc tính, phương thức và cấu trúc, giao diện người dùng và truy cập dữ liệu
- Xác định và định nghĩa các lớp hoặc đối tượng bổ sung hỗ trợ thực hiện yêu cầuHoạt động phát triển hệ thống hướng đối tượng
### Tạo mẫu
- Giúp hiểu đầy đủ việc thực hiện một số tính năng
- Cung cấp cho người dùng một cơ hội để nhận xét về tính khả dụng và hữu ích của thiết kế
- Có thể làm rõ rang hơn cho use case và giúp việc mô hình hóa các use case dễ dàng hơn
### Thực hiện: sử dụng pp Component-Based Development (CBD) hoặc Rapid Application Development (RAD)
### Kiểm tra tăng dần
- Kiểm thử được lặp đi lặp lại
- Sản phẩm được thử nghiệm trong các giai đoạn phát triển khác nhau
# 10. 3 Mô hình tier và 3 layer 
## a. Giới thiệu, thành phần, ý nghĩa của từng mô hình? 
## b. So sánh 3 tier và 3 layer
# 11.Trình bày một mô hình mà bạn quan tâm (khác với seminar của nhóm), trình bày các hiểu biết của bạn về mô hình đó.
# 12.Nắm rõ chủ đề seminar của nhóm.

