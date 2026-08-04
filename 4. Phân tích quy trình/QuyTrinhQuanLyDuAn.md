## **B. Nhóm Cốt lõi (Core)**

### **4\. Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)**

**a) Phân tích giá trị gia tăng (VA / BVA / NVA)**

***Bảng – Phân loại hoạt động: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Liệt kê (bước) | Phân loại | Mô tả | Khắc phục |
| ----- | ----- | ----- | ----- |
| Sprint Planning (estimate) | BVA | Lập kế hoạch công việc rõ ràng cho sprint | Dùng dữ liệu velocity lịch sử để estimate chính xác hơn |
| Daily Standup | BVA | Đồng bộ tiến độ, phát hiện sớm impediment | Giới hạn thời lượng nghiêm ngặt 15 phút, tránh lan man |
| Phát triển deliverables (coding) | VA | Trực tiếp tạo ra sản phẩm cho khách hàng | Code review đồng thời để giảm rework sau này |
| Viết test case // kiểm thử song song | VA | Đảm bảo chất lượng sản phẩm trước khi release | Tự động hóa test (CI/CD) để tăng tốc độ kiểm thử |
| Sprint Review (demo cho customer) | VA | Khách hàng thấy được giá trị thực tế mỗi sprint | Chuẩn bị kịch bản demo rõ ràng, tập trung vào giá trị |
| Retrospective | BVA | Cải tiến liên tục cách làm việc của team | Theo dõi hành động cải tiến ở sprint kế tiếp, tránh làm hình thức |
| Cập nhật tài liệu cuối Closing | NVA | Thường làm hình thức, ít được tham chiếu lại | Chỉ giữ tài liệu thiết yếu, tự động sinh từ công cụ quản lý |

**b) Phân tích lãng phí (Move / Hold / Overdo)**

***Bảng – Phân tích lãng phí: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Liệt kê | Mô tả | Khắc phục |
| ----- | ----- | ----- |
| Move | Yêu cầu/thông tin trao đổi qua nhiều kênh (email, chat, họp) khiến ngữ cảnh bị thất lạc. | Một kênh trao đổi chính thức duy nhất theo từng sprint (VD: Jira/Slack). |
| Hold | Team phải chờ Product Owner làm rõ yêu cầu, gây đình trệ (blocking) giữa sprint. | Product Owner dành thời gian cố định hàng ngày để giải đáp nhanh. |
| Overdo | Viết tài liệu đặc tả quá chi tiết cho những task đơn giản, không cần thiết. | Áp dụng nguyên tắc 'vừa đủ' (just enough documentation) theo độ phức tạp task. |

**c) Phân tích các bên liên quan và đăng ký phát hành**

***Phân tích các bên liên quan (Stakeholder Analysis)***

***Bảng – Phân tích các bên liên quan: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Bên liên quan | Mối quan tâm chính | Rủi ro tiềm ẩn nếu quy trình không hiệu quả |
| ----- | ----- | ----- |
| Product Owner | Backlog phản ánh đúng giá trị kinh doanh | Mất uy tín với khách hàng nếu sprint không đạt DoD |
| Scrum Master/PM | Team làm việc hiệu quả, gỡ impediment kịp thời | Khó kiểm soát nếu yêu cầu thay đổi liên tục |
| Dev/Scrum Team | Yêu cầu rõ ràng, đủ thời gian hoàn thành | Áp lực deadline khi ước lượng sai |
| Customer | Thấy giá trị tăng dần mỗi sprint | Mất niềm tin nếu nhiều sprint liên tiếp không đạt DoD |
