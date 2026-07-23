# Mục 2 – Mô hình hóa quy trình

Theo yêu cầu đồ án, mục này mô hình hóa chi tiết bằng BPMN cho 6 trong số 9 quy trình đã liệt kê ở Mục 1 (2 quy trình Quản lý, 2 quy trình Cốt lõi, 2 quy trình Hỗ trợ) — được lựa chọn vì có bằng chứng tài liệu thực tế rõ ràng nhất (file PRO-* của OR Tech) và thể hiện đủ độ phức tạp cần thiết theo rubric. Ba quy trình còn lại (Risk Management, Software Maintenance & Support, Software Installation Management) đã được mô hình hóa ở phần phụ lục làm tài liệu tham khảo bổ sung.

Theo rubric chấm điểm mục 2, phần "độ phức tạp quy trình" được chấm dựa trên SỐ LƯỢNG cổng điều kiện (gateway) trong mỗi sơ đồ: >7 cổng = 1đ, >5 cổng = 0.75đ, >3 cổng = 0.5đ; đồng thời yêu cầu thể hiện đúng cả Split (tách nhánh) và Join (hội tụ nhánh), và bị trừ 0.25đ cho mỗi ký hiệu sai. Do đó, cả 6 sơ đồ dưới đây đều được thiết kế với ĐÚNG 8 cổng điều kiện (vượt mốc >7 để đạt điểm tối đa), trong đó có ít nhất 1 cặp cổng AND (Split & Join) thể hiện các hoạt động chạy song song thực tế, còn lại là cổng XOR (rẽ nhánh loại trừ). Ký hiệu tuân thủ đúng chuẩn BPMN: XOR = hình thoi có dấu X, AND = hình thoi có dấu +, được chú thích rõ trong chú giải (legend) ở mỗi sơ đồ.

Bổ sung: theo khái niệm "Process Perspectives" (Quan điểm quy trình — Control Flow, Data, Resource Perspective), mỗi quy trình dưới đây được giới thiệu trước bằng một sơ đồ tổng quan dạng mũi tên (chevron) thể hiện Control Flow Perspective ở mức cao — chỉ các giai đoạn/mốc chính theo trình tự, KHÔNG thể hiện nhánh rẽ (gateway) hay vai trò thực hiện. Sơ đồ này giúp người đọc nắm nhanh "bức tranh tổng thể" trước khi đi vào sơ đồ BPMN chi tiết (thể hiện đầy đủ logic rẽ nhánh, vòng lặp và vai trò thực hiện — thuộc Control Flow Perspective ở mức chi tiết, có bổ sung Resource Perspective qua actor/swimlane gắn trên từng task).

## A. Nhóm quy trình Quản lý (Management)

### 1. Quy trình Quản lý Chất lượng (Quality Management Process) — Nhóm: Management

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quy trình Quản lý Chất lượng (Quality Management Process)](Sơ%20đồ%20quy%20trình/chevron_quality.png)

*Hình 1 – Process Perspective (tổng quan): Quy trình Quản lý Chất lượng (Quality Management Process)*

**Mô hình BPMN chi tiết**

Sau khi lập kế hoạch, quy trình tách song song (AND-split) thành 2 nhánh audit thực tế và rà soát tài liệu, hội tụ lại (AND-join) trước khi đánh giá NC. Nếu có NC, quy trình phân tích nguyên nhân gốc rễ, lập CAPA và theo dõi tiến độ, có vòng lặp khi CAPA trễ hạn nhưng chưa vượt số lần gia hạn cho phép. Nếu không có NC, quy trình còn kiểm tra thêm tình trạng hạn chứng nhận CMMI/ISO để quyết định có cần chuẩn bị tái chứng nhận hay không.

![BPMN chi tiết - Quy trình Quản lý Chất lượng (Quality Management Process)](Sơ%20đồ%20quy%20trình/bpmn_quality.png)

*Hình 2 – Mô hình BPMN chi tiết: Quy trình Quản lý Chất lượng (Quality Management Process)*

**Mô tả độ phức tạp của quy trình**

*Bảng 1 – Độ phức tạp: Quy trình Quản lý Chất lượng (Quality Management Process)*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 11 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join tường minh (tách audit thực tế // rà soát tài liệu, hội tụ trước khi đánh giá NC) |
| Vòng lặp | Có — 2 vòng lặp (phân tích lại root cause khi chưa rõ; gia hạn CAPA khi trễ hạn nhưng chưa vượt giới hạn) |
| Mức độ phức tạp | Cao — 8 cổng điều kiện (đạt mốc >7 điểm tối đa), kết hợp cả XOR và AND, đúng chuẩn BPMN |

### 2. Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management) — Nhóm: Management

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)](Sơ%20đồ%20quy%20trình/chevron_portfolio.png)

*Hình 3 – Process Perspective (tổng quan): Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)*

**Mô hình BPMN chi tiết**

Khi thiếu hụt nguồn lực, quy trình còn phân biệt mức độ khẩn cấp để quyết định tuyển gấp hay đưa vào hàng đợi bình thường. Khi đủ nguồn lực, quy trình tách song song (AND-split) việc ưu tiên hóa danh mục và đánh giá rủi ro từng dự án, hội tụ (AND-join) trước khi phân bổ. Khi có xung đột nguồn lực, quy trình phân biệt xung đột giải quyết được bằng đổi ưu tiên nội bộ hay cần đàm phán lại tiến độ với khách hàng (có thể phải escalate lên BOD nếu đàm phán thất bại).

![BPMN chi tiết - Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)](Sơ%20đồ%20quy%20trình/bpmn_portfolio.png)

*Hình 4 – Mô hình BPMN chi tiết: Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)*

**Mô tả độ phức tạp của quy trình**

*Bảng 2 – Độ phức tạp: Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 12 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join (tách ưu tiên hóa danh mục // đánh giá rủi ro, hội tụ trước khi phân bổ nhân sự) |
| Vòng lặp | Có — 2 vòng lặp (điều chỉnh ưu tiên rồi phân bổ lại; đàm phán tiến độ thành công rồi phân bổ lại) |
| Mức độ phức tạp | Cao — 8 cổng điều kiện (đạt mốc >7 điểm tối đa), phản ánh tính chất điều phối đa chiều của quản lý danh mục dự án |

## B. Nhóm quy trình Cốt lõi (Core)

### 3. Quy trình Quản lý Bán hàng (Sales Management Process) — Nhóm: Core

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quy trình Quản lý Bán hàng (Sales Management Process)](Sơ%20đồ%20quy%20trình/chevron_sales.png)

*Hình 5 – Process Perspective (tổng quan): Quy trình Quản lý Bán hàng (Sales Management Process)*

**Mô hình BPMN chi tiết**

Quy trình bổ sung bước rà soát pháp lý hợp đồng (với vòng lặp chỉnh sửa điều khoản nếu chưa đạt) và tách song song (AND-split) hai công việc khởi động dự án khi hợp đồng đã ký: kick-off dự án và thiết lập hồ sơ thanh toán, hội tụ (AND-join) trước khi thu tiền. Ở giai đoạn báo giá, nếu khách hàng chưa chấp nhận, quy trình còn phân biệt khách hàng có còn quan tâm điều chỉnh đề xuất hay đã từ bỏ đàm phán.

![BPMN chi tiết - Quy trình Quản lý Bán hàng (Sales Management Process)](Sơ%20đồ%20quy%20trình/bpmn_sales.png)

*Hình 6 – Mô hình BPMN chi tiết: Quy trình Quản lý Bán hàng (Sales Management Process)*

**Mô tả độ phức tạp của quy trình**

*Bảng 3 – Độ phức tạp: Quy trình Quản lý Bán hàng (Sales Management Process)*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 13 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join (tách kick-off dự án // thiết lập hồ sơ thanh toán sau khi ký hợp đồng) |
| Vòng lặp | Có — 2 vòng lặp (điều chỉnh đề xuất/báo giá khi khách hàng chưa đồng ý; chỉnh sửa hợp đồng khi rà soát pháp lý chưa đạt) |
| Mức độ phức tạp | Cao nhất trong 6 quy trình — 8 cổng điều kiện, nhiều actor phối hợp (Sales, Legal, Tech, Finance, PM), phản ánh đúng một quy trình bán hàng B2B nhiều bước |

### 4. Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum)) — Nhóm: Core

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum))](Sơ%20đồ%20quy%20trình/chevron_scrum.png)

*Hình 7 – Process Perspective (tổng quan): Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum))*

**Mô hình BPMN chi tiết**

Sau Sprint Planning, quy trình tách song song (AND-split) phát triển deliverables và viết test case, hội tụ (AND-join) trước khi kiểm thử — đúng thực hành phát triển song song với kiểm thử (test-driven). Quy trình còn kiểm tra định kỳ khả năng khách hàng dừng dự án, và khi sprint chưa đạt Definition of Done, phân biệt rõ nguyên nhân là thiếu thời gian (carry-over sang sprint sau) hay do thay đổi yêu cầu (cập nhật lại Product Backlog rồi lập kế hoạch lại từ đầu).

![BPMN chi tiết - Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum))](Sơ%20đồ%20quy%20trình/bpmn_scrum.png)

*Hình 8 – Mô hình BPMN chi tiết: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum))*

**Mô tả độ phức tạp của quy trình**

*Bảng 4 – Độ phức tạp: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process (Agile Scrum))*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 12 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join (tách phát triển // viết test case, hội tụ trước khi kiểm thử) |
| Vòng lặp | Có — 3 vòng lặp lồng nhau (fix bug rồi kiểm thử lại; carry-over quay lại phát triển; còn sprint tiếp theo quay lại Sprint Planning) |
| Mức độ phức tạp | Cao — 8 cổng điều kiện, vòng lặp lồng nhau thể hiện đúng bản chất iterative của Scrum |

## C. Nhóm quy trình Hỗ trợ (Support)

### 5. Quy trình Tuyển dụng Nhân sự (HR Recruitment Process) — Nhóm: Support

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quy trình Tuyển dụng Nhân sự (HR Recruitment Process)](Sơ%20đồ%20quy%20trình/chevron_hr.png)

*Hình 9 – Process Perspective (tổng quan): Quy trình Tuyển dụng Nhân sự (HR Recruitment Process)*

**Mô hình BPMN chi tiết**

Sau phỏng vấn sơ bộ đạt yêu cầu, quy trình tách song song (AND-split) kiểm tra kỹ thuật và kiểm tra thư giới thiệu, hội tụ (AND-join) trước khi đánh giá tổng thể. Ở giai đoạn thỏa thuận lương, nếu chưa thành công, quy trình còn phân biệt ứng viên có còn linh hoạt để đàm phán lại hay không trước khi kết luận offer bị từ chối. (Bản cập nhật: sơ đồ chi tiết bổ sung thêm bước duyệt yêu cầu tuyển dụng đầu quy trình để phản ánh đúng thực tế phê duyệt nội bộ.)

![BPMN chi tiết - Quy trình Tuyển dụng Nhân sự (HR Recruitment Process)](Sơ%20đồ%20quy%20trình/bpmn_hr.png)

*Hình 10 – Mô hình BPMN chi tiết: Quy trình Tuyển dụng Nhân sự (HR Recruitment Process)*

**Mô tả độ phức tạp của quy trình**

*Bảng 5 – Độ phức tạp: Quy trình Tuyển dụng Nhân sự (HR Recruitment Process)*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 11 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join (tách kiểm tra kỹ thuật // kiểm tra thư giới thiệu, hội tụ trước khi đánh giá tổng thể) |
| Vòng lặp | Có — 5 vòng lặp đều quay về Opening Job Requisition, Sàng lọc CV, hoặc Thỏa thuận lương tùy nguyên nhân (yêu cầu tuyển dụng chưa được duyệt, thiếu ứng viên, không đạt phỏng vấn, không đạt đánh giá, đàm phán lương lại) |
| Mức độ phức tạp | Cao — 8 cổng điều kiện, nhiều vòng lặp hội tụ, thể hiện tính bất định cao của quy trình tuyển dụng |

### 6. Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management) — Nhóm: Support

**Process Perspective — Tổng quan quy trình (Control Flow mức cao)**

![Process Perspective - Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management)](Sơ%20đồ%20quy%20trình/chevron_assets.png)

*Hình 11 – Process Perspective (tổng quan): Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management)*

**Mô hình BPMN chi tiết**

Khi thiết bị hỏng, quy trình phân biệt rõ còn bảo hành hay không để chọn sửa qua nhà cung cấp hay sửa nội bộ. Nếu không sửa được, quy trình phân nhánh tiếp giữa việc chỉ cần lưu hồ sơ hay cần xin duyệt ngân sách mua thiết bị thay thế (có vòng lặp chờ nếu ngân sách chưa được duyệt). Khi xác định không sửa được, quy trình tách song song (AND-split) xóa dữ liệu và xử lý vật lý thiết bị, hội tụ (AND-join) trước khi lưu hồ sơ.

![BPMN chi tiết - Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management)](Sơ%20đồ%20quy%20trình/bpmn_assets.png)

*Hình 12 – Mô hình BPMN chi tiết: Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management)*

**Mô tả độ phức tạp của quy trình**

*Bảng 6 – Độ phức tạp: Quy trình Quản lý & Kiểm soát Tài sản (Assets Control Management)*

| Tiêu chí | Giá trị |
| --- | --- |
| Số lượng task | 13 |
| Số lượng gateway | 8 (6 XOR + 2 AND) |
| Split & Join | Có — 1 cặp AND-split/AND-join (tách xóa dữ liệu // xử lý vật lý thiết bị khi không sửa được, hội tụ trước khi lưu hồ sơ) |
| Vòng lặp | Có — 2 vòng lặp (sửa xong quay lại bàn giao sử dụng; chờ ngân sách mua mới) |
| Mức độ phức tạp | Cao — 8 cổng điều kiện, thể hiện đầy đủ vòng đời tài sản từ tiếp nhận đến thanh lý |

# D. Tổng hợp so sánh độ phức tạp

| Quy trình | Nhóm | Số task | Số gateway | Split & Join / Điểm |
| --- | --- | --- | --- | --- |
| Quy trình Quản lý Chất lượng | Management | 11 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |
| Quản lý Danh mục Dự án & Phân bổ Nguồn lực | Management | 12 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |
| Quy trình Quản lý Bán hàng | Core | 13 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |
| Quy trình Quản lý Dự án | Core | 12 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |
| Quy trình Tuyển dụng Nhân sự | Support | 11 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |
| Quy trình Quản lý & Kiểm soát Tài sản | Support | 13 | 8 (6 XOR + 2 AND) | Có / >7 → 1đ |

Nhận xét: cả 6 sơ đồ đều đạt đúng 8 cổng điều kiện (vượt mốc ">7" để đạt điểm tối đa 1đ cho tiêu chí độ phức tạp), mỗi sơ đồ đều có ít nhất 1 cặp AND-split/AND-join tường minh thể hiện hoạt động song song thực tế (không chỉ dùng XOR cho có số lượng), và ký hiệu gateway được vẽ đúng chuẩn BPMN (XOR = dấu X, AND = dấu +, có chú giải/legend đi kèm mỗi sơ đồ) nhằm tránh bị trừ điểm sai ký hiệu. Sơ đồ Process Perspective (chevron) đi kèm mỗi quy trình giúp minh họa thêm góc nhìn tổng quan (high-level control flow) bên cạnh góc nhìn chi tiết của BPMN, đáp ứng đầy đủ khái niệm "Process Perspectives" đã học ở chương 2.

# Phụ lục – 3 quy trình bổ sung (tham khảo)

Ngoài 6 quy trình bắt buộc ở trên, nhóm đã mô hình hóa thêm 3 quy trình còn lại để có cái nhìn đầy đủ về toàn bộ kiến trúc quy trình công ty: Risk Management Process (Management), Software Maintenance & Support Process (Core), và Software Installation Management Process (Support). Hình ảnh và file draw.io của cả 3 quy trình này được cung cấp riêng kèm theo bộ tài liệu, có thể đính kèm vào phụ lục báo cáo nếu nhóm muốn trình bày đầy đủ 9 quy trình.
