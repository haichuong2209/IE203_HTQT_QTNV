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

***Bảng đăng ký phát hành (Issue Register)***

***Bảng 25 – Đăng ký phát hành: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Tên vấn đề | Giả định | Tác động định tính | Tác động định lượng | Cải tiến |
| ----- | ----- | ----- | ----- | ----- |
| Sprint không đạt DoD | Ước lượng story point chưa sát \+ scope creep | Giảm uy tín với khách hàng, dồn việc sang sprint sau | 25–30% sprint không đạt DoD đúng hạn | Refine backlog kỹ \+ cam kết backlog rõ ràng |
| Thay đổi yêu cầu giữa sprint | Product Owner chưa chốt yêu cầu trước Sprint Planning | Team phải làm lại, ảnh hưởng velocity | 20% sprint bị ảnh hưởng bởi scope creep | Backlog refinement session trước mỗi sprint |
| Ước lượng story point sai | Thiếu dữ liệu lịch sử velocity để tham chiếu | Kế hoạch sprint không thực tế | Sai lệch ước lượng trung bình 15–20% | Theo dõi velocity 3–5 sprint gần nhất làm chuẩn tham chiếu |
| Thiếu tài nguyên test song song | Tester kiêm nhiệm nhiều việc, chưa tách vai trò rõ ràng | Bug phát hiện trễ, phải rework nhiều | 20–30 giờ công rework/tháng do bug phát hiện muộn | Tự động hóa test (CI/CD), tách vai trò tester rõ ràng |
| Retrospective thiếu theo dõi | Hành động cải tiến sau retro không được theo dõi thực hiện | Vấn đề lặp lại nhiều sprint liên tiếp | Chỉ 40–50% hành động retro được thực hiện đầy đủ | Gắn action item retro vào backlog, theo dõi ở sprint sau |

***Phân tích nguyên nhân gốc rễ (Root-Cause / Why-Why) cho từng vấn đề***

***1\. Sprint không đạt Definition of Done***

• Vì: Ước lượng story point chưa sát thực tế

> ➤ Vì: Thiếu dữ liệu lịch sử velocity để tham chiếu

> ➤ Vì: Chưa refine backlog kỹ trước khi Sprint Planning

• Vì: Yêu cầu thay đổi giữa sprint (scope creep)

> ➤ Vì: Product Owner chưa chốt được yêu cầu trước Sprint Planning

> ➤ Vì: Khách hàng thay đổi ưu tiên đột xuất giữa sprint

***2\. Thay đổi yêu cầu giữa sprint***

• Vì: Product Owner chưa chốt yêu cầu trước khi Sprint Planning

> ➤ Vì: Thiếu backlog refinement session định kỳ

• Vì: Khách hàng thay đổi ưu tiên đột xuất

> ➤ Vì: Chưa có cam kết rõ ràng về việc 'khóa' scope trong sprint

***3\. Ước lượng story point sai***

• Vì: Thiếu dữ liệu lịch sử velocity để tham chiếu

> ➤ Vì: Chưa lưu trữ có hệ thống velocity qua các sprint

• Vì: Backlog chưa được refine kỹ trước khi estimate

> ➤ Vì: Áp lực thời gian khiến team bỏ qua bước làm rõ chi tiết

***4\. Thiếu tài nguyên test song song***

• Vì: Tester kiêm nhiệm nhiều việc trong team

> ➤ Vì: Chưa tuyển đủ nhân sự QA/tester chuyên trách

• Vì: Thiếu tự động hóa kiểm thử (CI/CD)

> ➤ Vì: Đầu tư công cụ test tự động chưa được ưu tiên

***5\. Retrospective thiếu theo dõi***

• Vì: Hành động cải tiến không được gắn vào công việc cụ thể

> ➤ Vì: Chưa có cơ chế theo dõi action item retro trong backlog

• Vì: Retro thường bị rút ngắn do áp lực thời gian

> ➤ Vì: Lịch retro xếp cuối ngày làm việc, team đã mệt

**d) Phân tích định lượng**

***Các bước và thời gian xử lý***

***Bảng 26 – Các bước và thời gian xử lý: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process) (đơn vị: ngày)***

| STT | Bước | Thời gian (ngày) |
| ----- | ----- | ----- |
| 1 | Sprint Planning | 0.5 |
| 2 | Development | 7 |
| 3 | Testing song song (tập trung) | 1.5 |
| 4 | Sprint Review | 0.5 |
| 5 | Retrospective | 0.5 |

*Tổng thời gian xử lý cơ bản (90% trường hợp) \= 0.5 \+ 7 \+ 1.5 \+ 0.5 \+ 0.5 \= 10 ngày.*

*Trường hợp phát sinh (10% trường hợp): thêm Fix bug/carry-over sang đầu sprint sau: 2 ngày → Tổng thời gian xử lý khi có phát sinh \= 12 ngày.*

*Thời gian xử lý trung bình \= (90% × 10\) \+ (10% × 12\) \= 10.2 ngày.*

***Hiệu suất thời gian của quy trình \= (Thời gian kế hoạch / Thời gian thực tế) × 100% \= (10 / 10.2) × 100% \= 98%.***

***Bảng phân bổ nguồn lực***

***Bảng 27 – Phân bổ nguồn lực: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Giai đoạn | Nhân sự tham gia | Bộ phận |
| ----- | ----- | ----- |
| Sprint Planning | Scrum Master, PO, Dev team | Phòng Phát triển |
| Development | Dev team | Phòng Phát triển |
| Testing | Tester (trong Dev team) | Phòng Phát triển |
| Sprint Review | PO, Customer, Dev team | Phòng Phát triển, Khách hàng |
| Retrospective | Scrum Master, Dev team | Phòng Phát triển |

***Bảng phân tích định lượng (Thời gian – Chất lượng – Chi phí)***

***Bảng 28 – Phân tích định lượng: Quy trình Quản lý Dự án (Agile Scrum) (Project Management Process)***

| Giải thích | Giá trị ước lượng | Gợi ý cải thiện |
| ----- | ----- | ----- |
| Velocity trung bình / sprint | 35 – 40 story points | Refine backlog kỹ hơn trước Sprint Planning |
| Tỷ lệ sprint đạt DoD đúng hạn | 70 – 75% | Giảm scope creep bằng cam kết backlog rõ ràng |
| Tỷ lệ story bị carry-over sang sprint sau | 15 – 20% | Chia nhỏ story lớn thành các story nhỏ hơn, dễ ước lượng |
| Chi phí rework do bug phát hiện sau release | Ước tính 20–30 giờ công/tháng | Tăng cường test tự động (CI/CD) |
| Thời gian trung bình 1 sprint | 2 tuần (10 ngày làm việc) | Giữ nguyên độ dài sprint, tăng chất lượng planning |
| Hiệu suất thời gian quy trình (kế hoạch/thực tế) | 98,0% | Duy trì bằng backlog refinement và test tự động |

***Kết luận***

Một sprint tiêu chuẩn (10 ngày làm việc) hiện mất trung bình 10,2 ngày khi tính cả các trường hợp phát sinh (fix bug, carry-over), đạt hiệu suất thời gian 98,0% so với kế hoạch. Tỷ lệ sprint đạt Definition of Done đúng hạn chỉ khoảng 70–75%, chủ yếu do ước lượng story point chưa sát và scope creep giữa sprint. Nhóm đề xuất tăng cường backlog refinement trước Sprint Planning và tự động hóa kiểm thử (CI/CD) để cải thiện tỷ lệ đạt DoD.
