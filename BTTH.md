Phần A:

- S1 đúng , vì:  
+ Independent: Có thể triển khai chức năng chấm sao tương đối độc lập  
+ Negotiable: Mô tả nhu cầu, không áp đặt cách hệ thống phải triển khai  
+ Valuable: Mang lại giá trị cho khách hàng và dữ liệu đánh giá cho sản phẩm  
+ Estimable: Có thể ước lượng công sức thực hiện  
+ Small: Phạm vi tương đối nhỏ, có thể thực hiện trong một Sprint  
+ Testable: Có thể kiểm thử quy tắc chấm từ 1 đến 5 sao  
- S2 có vấn đề ở cấp độ và phạm vi, không phải chỉ do câu chữ:  
+ vi phạm nguyên tắc phân cấp: có quá nhiều chức năng cho 1 user story  
+ vi phạm INVEST:   
* Independent: Các chức năng trong S2 có quan hệ và phụ thuộc khác nhau  
* Estimable: Phạm vi quá rộng nên khó ước lượng chính xác  
* Small: Không đủ nhỏ để xem như một User Story thông thường  
* Testable: Có quá nhiều hành vi khác nhau cần kiểm thử trong cùng một Story  
- Không nên đưa S2 vào Sprint ở trạng thái hiện tại vì:   
+ Không biết chính xác Sprint phải hoàn thành những phần nào  
+ Khó ước lượng Story Point  
+ Khó kiểm thử và xác định thế nào là "Done"  
+ Nếu một phần hoàn thành nhưng phần khác chưa hoàn thành thì rất khó đánh giá S2 đã hoàn thành hay chưa

	\=\> Cần tách S2 thành các User Story nhỏ hơn, mỗi Story tập trung vào một nhu cầu có giá trị và có thể ước lượng, phát triển, kiểm thử riêng

Phần B: 

- Đặt tên Feature phù hợp cho F2: Xem đánh giá sản phẩm   
- User Story hợp lệ: “Là một khách hàng, tôi muốn gửi đánh giá sau khi đã chấm sao và viết nhận xét, để đánh giá của tôi được hệ thống tiếp nhận”  
- Viết lại S2:

+ ### S2.1 – Viết bình luận và đính kèm ảnh: “Là một khách hàng, tôi muốn viết bình luận và đính kèm ảnh khi đánh giá sản phẩm, để tôi có thể chia sẻ nhận xét chi tiết và hình ảnh thực tế về sản phẩm”

+ ### S2.2 – Gửi đánh giá: “Là một khách hàng, tôi muốn gửi đánh giá sau khi hoàn tất nội dung đánh giá, để đánh giá của tôi được hệ thống tiếp nhận”

+ ### S2.3 – Kiểm duyệt đánh giá: “Là một quản trị viên, tôi muốn kiểm duyệt nội dung đánh giá trước khi hiển thị công khai, để các đánh giá không phù hợp không xuất hiện trên trang sản phẩm”


Backlog hoàn thiện:

#### **F1 – Viết đánh giá sản phẩm**

+ **S1:** Là một khách hàng, tôi muốn chấm sao từ 1–5 cho sản phẩm đã mua, so that tôi chia sẻ mức độ hài lòng của mình  
+ **S2.1:** Là một khách hàng, tôi muốn viết bình luận và đính kèm ảnh khi đánh giá sản phẩm, so that tôi có thể chia sẻ nhận xét chi tiết và hình ảnh thực tế về sản phẩm  
+ **S2.2:** Là một khách hàng, tôi muốn gửi đánh giá sau khi hoàn tất nội dung đánh giá, so that đánh giá của tôi được hệ thống tiếp nhận  
+ **S2.3:** Là một quản trị viên, tôi muốn kiểm duyệt nội dung đánh giá trước khi hiển thị công khai, so that các đánh giá không phù hợp không xuất hiện trên trang sản phẩm

#### **F2 – Xem đánh giá sản phẩm**

+ **S3:** Là một khách hàng, tôi muốn xem điểm đánh giá trung bình và đọc các đánh giá của những khách hàng khác, so that tôi có thêm thông tin trước khi quyết định mua sản phẩm

