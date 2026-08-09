**Quy trình Quản lý Chất lượng (Quality management Process)**

## **4\. Phân tích quy trình** 

### **4.1. Phân tích Định tính (Qualitative Analysis)**

#### **a) Phân tích Giá trị Gia tăng (Value-Added Analysis)**

| Bảng Phân tích Giá trị Gia tăng | Tên bước / Hoạt động trong quy trình | Phân loại (VA / VBA / NVA) | Mô tả chi tiết | Đề xuất khắc phục / Cải tiến |
| :---- | :---- | :---- | :---- | :---- |
| **1** | Lập kế hoạch audit & Rà soát tài liệu | **VBA** *(Business Value-Added)* | Đáp ứng yêu cầu quản lý và tuân thủ chuẩn ISO/CMMI của doanh nghiệp. | Tự động hóa lịch audit qua phần mềm quản lý. |
| **2** | Audit thực tế & Ghi nhận NC | **VA** *(Value-Added)* | Tạo giá trị trực tiếp cho sản phẩm/dịch vụ bằng cách phát hiện lỗi chất lượng. | Chuẩn hóa checklist audit dạng số hóa trên mobile/web. |
| **3** | Phân tích nguyên nhân gốc rễ & Lập CAPA | **VA** *(Value-Added)* | Giúp loại bỏ rễ nhánh sự cố, cải thiện chất lượng lâu dài. | Áp dụng khung 5 Why / Fishbone chuẩn hóa trong biểu mẫu. |
| **4** | Lặp lại phân tích nguyên nhân (do làm chưa rõ) | **NVA** *(Non-Value-Added)* | Hoạt động lãng phí do kỹ năng phân tích kém, không tạo ra giá trị. | Đào tạo kỹ năng root-cause analysis cho Project Manager. |
| **5** | Cho phép gia hạn CAPA khi trễ hạn | **NVA** *(Non-Value-Added)* | Thời gian chờ đợi và xử lý thủ tục gia hạn làm kéo dài tồn đọng lỗi. | Cấu hình tự động cảnh báo trước 2 ngày, giới hạn khắt khe số lần gia hạn. |
| **6** | Theo dõi & Đóng NC / Báo cáo BOD | **VBA** *(Business Value-Added)* | Giúp lãnh đạo nắm bức tranh chất lượng và duy trì chứng nhận tổ chức. | Tự động tổng hợp Dashboard báo cáo BOD |

#### **b) Phân tích Sự lãng phí (Waste Analysis / 7 Wastes)**

| Bảng Phân tích Lãng phí | Dạng lãng phí | Mô tả chi tiết trong Quy trình QA | Phương án khắc phục |
| :---- | :---- | :---- | :---- |
| **1** | **Move (Di chuyển / Luân chuyển)** | Luân chuyển báo cáo, hồ sơ NC qua lại nhiều lần giữa QA, PM và BOD bằng Email/Giấy. | Tích hợp hệ thống Workflow/BPMN Tool tập trung. |
| **2** | **Hold (Chờ đợi / Tồn đọng)** | Thời gian chờ PM phân tích nguyên nhân và chờ xác nhận gia hạn khi CAPA bị trễ hạn. | Đặt SLA rõ ràng cho từng bước; tự động Escalate lên cấp quản lý nếu quá hạn. |
| **3** | **Overdo (Làm thừa / Gia công quá mức)** | Rà soát tài liệu thủ công lặp đi lặp lại hoặc làm lại phân tích root cause nhiều lần. | Sử dụng Template phân tích chuẩn và tự động hóa khâu kiểm tra định dạng tài liệu. |

#### **c) Phân tích Nguyên nhân \- Kết quả (Fishbone Diagram / Cause-Effect Analysis)**

*Vấn đề phân tích:* **Thời gian xử lý và đóng NC/CAPA bị kéo dài trễ hạn.**

* **Con người (People):** PM thiếu kỹ năng phân tích nguyên nhân gốc rễ (Root cause); Đội ngũ dự án ưu tiên làm Task khách hàng hơn làm CAPA.  
* **Quy trình (Process):** Vòng lặp gia hạn chưa chặt chẽ; thủ tục phê duyệt gia hạn phức tạp.  
* **Công cụ (Tool):** Theo dõi thủ công bằng Excel/Email dẫn đến trôi thông tin, thiếu cảnh báo tự động.  
* **Môi trường / Văn hóa (Environment):** Chưa coi trọng đúng mức công tác QA, xem QA là "bắt lỗi" thay vì đồng hành.

### **4.2. Phân tích Định lượng (Quantitative Analysis)**

| Bảng Phân tích Định lượng | Chỉ số (KPIs) | Công thức / Giá trị ước tính hiện tại | Đánh giá & Bằng chứng quy trình | Giải pháp khắc phục |
| :---- | :---- | :---- | :---- | :---- |
| **Thời gian (Time)** | **Cycle Time (Thời gian chu trình)** | **15 \- 25 ngày** (Từ khi phát hiện NC đến khi đóng NC hoàn toàn). | Thời gian chết nằm nhiều ở bước chờ lập CAPA và vòng lặp gia hạn khi trễ hạn. | Rút ngắn SLA phân tích CAPA xuống tối đa 3 ngày; bỏ vòng lặp gia hạn lần 2\. |
| **Chất lượng (Quality)** | **First-Time-Through (FTT Rate)** | **\~ 65%** (Tỷ lệ NC được giải quyết dứt điểm ngay lần phân tích & sửa đầu tiên). | Có tới 35% trường hợp phải chạy vòng lặp phân tích lại root cause do làm sơ sài. | Bắt buộc đính kèm bằng chứng khắc phục (Evidence) trước khi chuyển trạng thái Đóng NC. |
| **Chi phí (Cost)** | **Resource Effort Cost** | **20 \- 30 giờ công / đợt audit** (Bao gồm giờ làm việc của QA, PM và BOD). | Tốn chi phí nhân sự cho các hoạt động NVA (nhắc nhở, họp phân tích lại, duyệt gia hạn). | Tự động hóa báo cáo và nhắc việc qua hệ thống để giảm 40% giờ công QA. |
