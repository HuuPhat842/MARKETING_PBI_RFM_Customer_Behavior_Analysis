# PBI_RFM_ANALYSIS
## I. Giới thiệu
### 1. Câu hỏi doanh nghiệp
Mỗi khách hàng là một cá thể độc lập với hành vi và cá tính khác nhau, do đó họ sẽ có những phản ứng khác nhau với cùng loại chương trình ưu đãi, gói dịch vụ, hoặc sản phẩm. Xu hướng bán hàng và tiếp cận khách hàng trong thời đại hiện nay dần chuyển sang cá nhân hóa cho từng đối tượng để tăng khả năng thành công và tiết kiệm chi phí cho doanh nghiệp.
Hành vi của khách hàng (Customer Behaviour) không mô tả ai (who) đang mua sắm tại cửa hàng của bạn mà mô tả cách họ mua sắm (how) tại cửa hàng của bạn. Nó xem xét các yếu tố như tần suất mua sắm, sở thích sản phẩm và cách cảm nhận về hoạt động tiếp thị, bán hàng và cung cấp dịch vụ của bạn. Hiểu những chi tiết này giúp doanh nghiệp giao tiếp với khách hàng một cách hiệu quả và thú vị.
Song song với đó, để hiểu được hành vi của khách hàng, chúng ta cũng cần phân loại khách hàng thành các nhóm riêng biệt có cùng một xu hướng hành động, hoặc đặc điểm chung nào đó (Customer Segmentation). Ví dụ phân loại theo nhân khẩu học dựa vào tuổi, giới tính, thu nhập, trình độ giáo dục, trạng thái hôn nhân; hoặc phân loại theo địa lý dựa vào châu lục, đất nước, khu vực, thành phố, thị trấn; hoặc phân loại theo tâm lý học dựa vào tính cách, thái độ, thế giới quan, sự quan tâm.

**Hãy ứng dụng dữ liệu giao dịch của khách hàng vào thực hiện phân tích RFM.**
-  **Trình bày được rõ ràng các phân khúc khách hàng trong doanh nghiệp, sự thể hiện của từng phân khúc.**
-  **Đưa ra các gợi ý duy trì / phát triển / giữ chân / thu hút phù hợp cho từng phân khúc khách hàng.**
### 2. Dataset
- Dataset: adventureworks2019 (Google BigQuery dataset)
- Từ điển Dataset: https://dataedo.com/samples/html/AdventureWorks/doc/AdventureWorks_2/home.html
- Dataset Schema:  https://i0.wp.com/improveandrepeat.com/wp-content/uploads/2018/12/AdvWorksOLTPSchemaVisio.png?ssl=1</p>
Dataset access:
- Đăng nhập vào tài khoản Google Cloud Platform và tạo dự án mới.
- Chuyển đến bảng điều khiển BigQuery và chọn dự án mới tạo.
- Trong bảng điều hướng, chọn "Add Data" rồi chọn "Start a project by name"
## II. Ứng dụng design-thinking mindset
### 1. Nhìn rộng (Empathize)
![image](https://github.com/user-attachments/assets/e2a110f6-f241-44cc-92cf-a4d65d8226b7)
![image](https://github.com/user-attachments/assets/88f8496b-9dfd-4e2a-9202-38f82d9647e1)
### 2. Nhìn sâu (Define point of view)
![image](https://github.com/user-attachments/assets/53a19eba-a9df-419b-b9dc-68694223d120)
### 3. Ý tưởng (Ideate)
![image](https://github.com/user-attachments/assets/f7764756-4171-42ef-ae2b-fc4888b46e77)
## III. Quy trình chính
### 1. Kết nối dữ liệu đến PBI và tiến hành modeling
![image](https://github.com/user-attachments/assets/81cf1b71-aa0f-4ae9-8ed7-e81b7916bc3b)
### 2. Xây dựng Dashboard
![image](https://github.com/user-attachments/assets/aca974cf-f795-4650-83fe-88f95c4bcc0c)
![image](https://github.com/user-attachments/assets/bb20f683-ef3d-455c-85e1-441775a015b4)
## IV. Insights từ Dashboard:
![image](https://github.com/user-attachments/assets/954cbf02-3479-44f3-9715-baa670cfd6e5)
![image](https://github.com/user-attachments/assets/cbe9535a-6258-4b8f-8a0d-049820e2832f)
![image](https://github.com/user-attachments/assets/b432a731-aec7-4596-8890-254d74d61e35)
![image](https://github.com/user-attachments/assets/77a32053-43a8-4224-802f-25be000c0a1b)
![image](https://github.com/user-attachments/assets/621f38a8-1632-466a-9cd8-f813d71b9f95)
![image](https://github.com/user-attachments/assets/6a4a1b56-5a75-4079-b3cb-97d5d5637ff0)
## V. Đề xuất bước đi tiếp theo cho doanh nghiệp:

**Các tệp KH doanh nghiệp cần ưu tiên hướng đến:**
- Champions: Triển khai các chiến dịch trao thưởng cho khách hàng 
chi tiêu nhiều, chi tiêu gần đây. Đồng thời chăm sóc họ bằng các 
kênh marketing trực tiếp, họ có thể sớm chấp nhận sản phẩm/dịch 
vụ mới -> Họ là kênh giới thiệu rất tốt
- Cant lose them: Đối thủ cạnh tranh sẽ giành lấy tệp KH này nếu 
doanh nghiệp không chủ động giành lại họ. Chăm sóc họ bằng các 
chương trình khuyến mãi theo hướng marketing cá nhân hóa.
- At risk: Tương tự như tệp Cant lose them.
- Loyal customers: Đưa ra các chiến lược khuyến mãi, upsell thúc 
đẩy chi tiêu đồng thời seeding reviews từ tệp KH này.




