# ROADMAP ĐỒ ÁN IE203 – Hệ thống Quản trị Quy trình 
### Thành viên nhóm
| STT | Họ tên | MSSV | Công việc |
|---|---|---|---|
| 1 | Nguyễn Văn Trung | 25410325 | ALL – Review & đánh giá, đại diện nhóm nộp |
| 2 | Phạm Tuấn Kiệt | 25410239 | |
| 3 | Phan Chí Hiếu | 25410213 | |
| 4 | Lê Thị Tú Anh | 25410171 | |
| 5 | Vũ Huy Hoàng | 25410220 | |
| 6 | Giang Hải Chương | 25410179 | |
| 7 | Nguyễn Minh Duy | 25410193 | |

---

## 1. Cấu trúc đồ án (5 mục) + Rubric chấm điểm

Đồ án gồm **5 mục, mỗi mục 10 điểm**. Thang rubric mỗi tiêu chí: `>=0.75 → 1đ` | `0.25–0.75 → 0.5đ` | `<0.25 → 0đ`.

### Mục 1 – Liệt kê & Phân tích quy trình (10đ)
- Liệt kê **tối thiểu 10 quy trình** (mỗi quy trình 1đ). *(Nhóm hiện có 9 — cần cân nhắc bổ sung 1 để đủ 10, ví dụ Purchasing hoặc Quality Management đã tách riêng.)*
  - ≥3 quy trình **Quản lý (Management)**
  - ≥3 quy trình **Cốt lõi (Core)**
  - ≥3 quy trình **Hỗ trợ (Support)**
- **Vẽ kiến trúc quy trình** (process architecture – sơ đồ) = 1đ.
- Mỗi quy trình phân tích theo **4 tiêu chí**:
  1. **Actor** – tác nhân.
  2. **Mô tả bằng lời**: các bước chạy · giá trị mang lại cho khách hàng · nhiệm vụ (task).
  3. **Customer** – đối tượng khách hàng.
  4. **Outcomes** – khả năng kết quả của quy trình.

### Mục 2 – Mô hình hóa quy trình (10đ)
- Mô hình hóa **2 Management + 2 Core + 2 Support** (mỗi nhóm 3đ).
- Định dạng: **1 quy trình trên slide, 2 quy trình trong Word**.
- **Độ phức tạp** (điểm theo số cổng điều kiện / gateway):
  - `>7 gateway → 1đ` · `>5 → 0.75đ` · `>3 → 0.5đ`.
  - Yêu cầu: đúng **Split & Join**; **sai ký hiệu bị trừ** (1 → 0.25).

### Mục 3 – Phương pháp thực hiện (10đ)
- **Dựa trên bằng chứng (evidence-based)**: mô tả quy trình hiện có (nếu có) · sơ đồ tổ chức · kế hoạch làm việc · thuật ngữ & sổ tay · biểu mẫu (workshop – biểu mẫu cuộc họp; kịch bản).
- **Phỏng vấn** – liệt kê câu hỏi cho các bên liên quan:
  - **10 câu định tính** (5 có cấu trúc + 5 không cấu trúc).
  - **10 câu định lượng** (5 có cấu trúc + 5 không cấu trúc).
  - Chấm: `<10 câu → 0đ`; `>=20 câu → 0.5đ`.

### Mục 4 – Phân tích quy trình (10đ)
- **Phân tích định tính (2 quy trình):**
  1. **Phân tích giá trị gia tăng** (bảng: Liệt kê – Mô tả – Khắc phục; phân tích trên quy trình):
     - **NVA** – hoạt động **không** tăng giá trị.
     - **BVA/VBA** – hoạt động tăng giá trị **kinh doanh**.
     - **VA** – hoạt động tăng giá trị (cho khách hàng).
  2. **Phân tích lãng phí** (bảng: Liệt kê – Mô tả – Khắc phục):
     - **Move · Hold · Overdo**.
  3. **Phân tích các bên liên quan** – chọn **1 trong 3**: Pareto Chart · Root-Cause (nhân quả) · Fishbone (xương cá).
- **Phân tích định lượng (2 quy trình):** Thời gian · Chất lượng · Chi phí (bảng: Liệt kê – Tính toán – Khắc phục; phân tích trên quy trình).

### Mục 5 – Trình bày & Báo cáo (10đ)
- **Slide & Word**: chính tả; font (size, colour, bullet); index (page, figure, table).
- **Word**: label **hình nằm dưới**, label **bảng nằm trên**; đủ mục lục / mục lục ảnh / mục lục bảng / bảng viết tắt; theo **mẫu KLTN của UIT** (https://httt.uit.edu.vn/cac-bieu-mau/).
- **GitHub**: nộp commit history cho thầy xem — **3 tuần liên tiếp không commit → 0đ**.
- **Trình bày**: bật cam; quá thời gian **5' → trừ 1đ**.
- Tham khảo mẫu: Cellphones, TikiLogistics; Drive: `folders/1u4b5bPnce8csxRjqSwI1JSGyKumg6CT9`.

---

## 2. Kiến trúc 9 quy trình của Orient Software

| # | Quy trình | Nhóm | Có tài liệu gốc? |
|---|---|---|---|
| 1 | Quality Management Process | Management | — |
| 2 | Project Portfolio & Resource Allocation Management | Management | — |
| 3 | Risk Management Process | Management | — |
| 4 | Sales Management Process | Core | ✅ docx (v1.0) |
| 5 | Project Management Process (Agile Scrum) | Core | ✅ pdf (v1.3) |
| 6 | Software Maintenance & Support Process | Core | — |
| 7 | HR Recruitment Process | Support | ✅ pdf (v2.1/3.0) |
| 8 | Assets Control Management | Support | ✅ pdf (v2.1) |
| 9 | Software Installation Management Process | Support | ✅ pdf (v1.0) |

> Kiến trúc quy trình (sơ đồ) tham chiếu ảnh `sources/orient_process_architecture.png` (nêu trong `Danh_sách_9_quy_trình.md`).

---

## 3. Phân tích chi tiết 9 quy trình (nội dung Mục 1 đã viết)

### A. NHÓM QUẢN LÝ (Management)

#### 1. Quality Management Process
- **Actor:** QA Manager · Nhóm QA/QC · PM (được audit) · BOD.
- **Các bước:** xây/cập nhật chuẩn nội bộ (CMMI/ISO) → lập kế hoạch audit → audit thực tế vs tài liệu PRO-* → ghi nhận Non-conformance (NC) → yêu cầu CAPA → theo dõi & đóng NC → báo cáo BOD theo quý.
- **Value:** đảm bảo sản phẩm đạt chuẩn SLA/hợp đồng, duy trì chứng nhận CMMI/ISO.
- **Customer:** nội bộ (BOD, Process Owner, PM) + gián tiếp (khách outsourcing).
- **Outcomes:** Compliant (không NC) · phát hành CAR/NC · duy trì hoặc treo chứng nhận.

#### 2. Project Portfolio & Resource Allocation Management
- **Actor:** COO/BOD · PMO/Resource Manager · Head of Development · PM từng dự án.
- **Các bước:** thu thập nhu cầu nguồn lực → đánh giá năng lực & % bận → ưu tiên hóa danh mục (giá trị HĐ, rủi ro, deadline) → phân bổ nhân sự → theo dõi utilization → điều chỉnh xung đột.
- **Value:** mỗi dự án đủ người đúng kỹ năng, đúng tiến độ.
- **Customer:** nội bộ (PM, BOD) + gián tiếp (khách thuê dự án).
- **Outcomes:** phân bổ thành công · thiếu hụt → tuyển thêm (link HR) · xung đột → điều chỉnh ưu tiên/đàm phán tiến độ.

#### 3. Risk Management Process
- **Actor:** Risk Owner (PM/COO) · BOD · trưởng phòng ban.
- **Các bước:** nhận diện rủi ro → đánh giá xác suất/tác động → xếp hạng theo ma trận, cập nhật **Risk Register** → kế hoạch ứng phó (mitigate/transfer/accept) → theo dõi định kỳ → báo cáo BOD & kích hoạt khi xảy ra.
- **Value:** giảm gián đoạn/rò rỉ thông tin, giữ SLA & uy tín.
- **Customer:** nội bộ (BOD, PM, phòng ban) + gián tiếp (khách).
- **Outcomes:** Risk controlled · Risk escalated · Risk materialized (kích hoạt ứng phó).

### B. NHÓM CỐT LÕI (Core)

#### 4. Sales Management Process
- **Actor:** Sales Executive/Rep · Head of Development · Tech team · Finance/Accountant · Branch Director · BOD · Legal Consultant · CEO · Client.
- **Các bước:** Create Lead Pool (LinkedIn, Crunchbase, MKT) → Follow-up Leads (email/call) → Client Meeting → Make Proposal (breakdown + estimate từ Tech) → Make Quotation → Commercial Contract (rà soát pháp lý) → Sign Contract → chuyển **Production**; hậu mãi: Revenue Collection, chăm sóc, khảo sát hài lòng, post-mortem.
- **Value:** giải pháp phần mềm đúng ngân sách/yêu cầu, tư vấn minh bạch, giảm rủi ro outsourcing.
- **Customer:** doanh nghiệp có nhu cầu thuê ngoài (potential + existing) tại Úc/Mỹ/Châu Âu.
- **Outcomes:** Deal won · Deal lost · yêu cầu revise proposal/quotation · Late payment.
- 👉 Chi tiết đầy đủ ở **§4** (tài liệu gốc Sales).

#### 5. Project Management Process (Agile Scrum)
- **Actor:** Project Sponsor · Product Owner · Scrum Master/PM · Scrum Team (Dev, Tester) · Customer.
- **Các bước (phase):** Initiate (Sprint Zero) → Plan & Estimate (Sprint Planning) → Implement (Development Sprints + Daily Standup) → Review & Retrospect → Monitoring & Controlling (xuyên suốt) → Release → Closing.
- **Value:** sản phẩm đúng scope, đúng tiến độ từng sprint, khách theo dõi minh bạch qua sprint review/demo.
- **Customer:** khách đã ký HĐ (Product Owner phía khách).
- **Outcomes:** Product accepted (Done) · Carried-over items · Project closed · Project suspended/cancelled.
- 👉 Chi tiết đầy đủ ở **§5**.

#### 6. Software Maintenance & Support Process
- **Actor:** Maintenance/Support team · Account Manager · PM · Customer.
- **Các bước:** nhận ticket (helpdesk/email) → phân loại ưu tiên theo SLA (Critical/High/Medium/Low) → điều tra → khắc phục/viết patch → kiểm thử → deploy production → xác nhận & đóng ticket, báo cáo SLA.
- **Value:** hệ thống chạy ổn định sau bàn giao, xử lý sự cố đúng SLA.
- **Customer:** khách đã đưa sản phẩm vào vận hành (hậu dự án/HĐ bảo trì).
- **Outcomes:** SLA met · SLA breach (phạt HĐ) · change request → dự án mới (quay lại Sales/PM) · gia hạn HĐ bảo trì.

### C. NHÓM HỖ TRỢ (Support)

#### 7. HR Recruitment Process
- **Actor:** Requester (Leader/Manager/Sales) · TA Lead/member · HR Manager · BOD/COO · Candidate.
- **Các bước:** Opening Job Requisition → Recruitment Preparation (JD, đăng tuyển, sourcing) → Screening → Evaluating (phỏng vấn HR & kỹ thuật) → Offer Letter → Pre-On-Board.
- **Value:** cung cấp nhân lực IT đúng chất lượng/thời điểm, đảm bảo đủ năng lực đáp ứng HĐ.
- **Customer:** nội bộ (Requester cần bổ sung nhân sự).
- **Outcomes:** Offer accepted · Offer declined · Requisition cancelled · Recruitment delayed.
- 👉 Chi tiết đầy đủ ở **§6**.

#### 8. Assets Control Management
- **Actor:** IT/Admin (ICS) · HR & Admin · nhân viên dùng tài sản · FA Department (thanh lý).
- **Các bước:** Receive New Equipment → Preparation for Inventory (dán nhãn, Equipment Control Register) → Delivery & Sign-off → Maintenance → Fixing/Warranty → Property In/Out → Equipment Disposal → Records Control.
- **Value:** nhân viên (kỹ sư dự án) luôn có thiết bị hoạt động tốt, giảm gián đoạn.
- **Customer:** nội bộ (toàn bộ nhân viên/phòng ban).
- **Outcomes:** delivered & operational · under repair/warranty · disposed · asset loss (điều tra).
- 👉 Chi tiết đầy đủ ở **§7**.

#### 9. Software Installation Management Process
- **Actor:** IT member · Head of Dept/PM (Requester) · HR.
- **Các bước:** Register Software (ticket → IT) → kiểm tra & phê duyệt license → cài đặt → Audit định kỳ (≥6 tháng) → Revoke license vi phạm/hết hạn → cập nhật Software Register List & IT Software Control List.
- **Value:** công cụ dev (IDE, phần mềm bản quyền) sẵn sàng & hợp lệ; tuân thủ pháp lý bản quyền.
- **Customer:** nội bộ (nhân viên/dự án cần công cụ).
- **Outcomes:** installed – compliant · non-compliant → revoke · control list updated.
- 👉 Chi tiết đầy đủ ở **§8**.

---

## 4. Tài liệu gốc: Sales Management Process (docx v1.0)

- **Người tạo:** Thong Lam · Updated: Minh Nguyen · Approved: CEO Nhung Nguyen / CTO Øyvind / COO Dr. Son Nguyen. Classification: Internal Use.
- **Roles:** Global Head of Sales · Sales Representative · Pre-sales support.
- **3 giai đoạn chính (Table 4 – Overview):**
  - **LEADS MANAGEMENT:** Create LEAD pool (Freshworks) → Follow-up Potential Leads (scoring, outbound email, cold call). Target **200 leads/Sales/tháng**; ≥2 task/lead; x% = 3–5% qualified.
  - **SALE EXECUTION:** Conduct Client Meeting → Make Proposal → Review/Approve → Make Quotation → Review/Approve (BOD/Customer) → Make Commercial Contract → Review/Approve (Legal/BOD) → Sign Contract (CEO) → gọi [Production].
  - **POST SALE:** Revenue Collection · Communication Supporting · Customer Satisfaction (khảo sát quý) · Post-mortem review.
- **Chi tiết bước (Main-Process):**
  - *Create Lead Pool:* search Sales channels (LinkedIn/Crunchbase/Twitter/Event) + MKT list → add ≥10 leads/ngày vào Freshworks.
  - *Follow-up:* email → call → follow-up ≥3 lần (task 2 = follow-up sau 3 ngày).
  - *Client Meeting:* giới thiệu OSD → nghe client → đề xuất next step.
  - *Make Proposal* (≤1 tuần sau meeting): Tech breakdown+estimate → viết proposal → gộp → review/approve (Head of Dev, BOD).
  - *Make Quotation:* Accountant estimate theo man-day → Branch Director duyệt → gửi client.
  - *Commercial Contract:* Accountant soạn → BOD duyệt → gửi client.
  - *Sign Contract:* CEO ký → Finance lưu.
  - *Revenue Collection:* Finance làm invoice → thu tiền → báo Sales/BOD nếu trễ → Sales xử lý với client.
- **Tools:** Freshworks, LinkedIn Sales Navigator, Crunchbase, MS Teams/Zoom/Google Meet.
- **RADIO Matrix** (Who Do What): Respond to RFI, form bid team, plan RFP response, estimate, proposal, quotation, bid-loss analysis... (mã D/R/I: Do/Review/Inform).

---

## 5. Tài liệu gốc: Project Management Process – Agile Scrum (pdf v1.3)

- **Approved:** Thong Lam (Oct 15, 2021). Áp dụng Scrum cho Outsourcing Development Dept.
- **Roles:** Project Sponsor · **Product Owner** (1 người, "Voice of Customer", quản lý Product Backlog) · **Scrum Master/PM** (facilitator, gỡ impediment) · Development/Scrum Team.
- **Trụ cột Scrum (Ch.3):** Transparency · Inspection · Adaption.
- **Nguyên tắc (Ch.4):** Self-organization · Collaboration · Value-Based Prioritization · Time-boxing · Iterative Development.
- **6 Phase (Ch.6):**
  1. **Initiate (Sprint Zero):** Project/Product Vision, Project Charter, thành lập team, Product Backlog, Kick-off.
  2. **Plan & Estimate (Sprint Planning):** User Story, estimate, commit backlog → Sprint Backlog.
  3. **Implement (Development Sprints):** phát triển deliverables, Daily Standup, cập nhật backlog.
  4. **Review & Retrospect:** demo, đánh giá Done/Not-Done, retrospective.
  5. **Release:** bàn giao, thu phản hồi.
  6. **Closing:** cập nhật tài liệu, nghiệm thu, bài học, giải phóng nguồn lực.
- **Khái niệm chính:** Product Backlog · Epics · User Stories · Sprint Goal · Sprint Backlog · Increment · Definition of Done (DoD).
- **Templates:** Project Charter, Kick-Off, Management Plan, Risk/Resource Plan, User Story, Change Request, SRS, UAT, Metrics, Customer Satisfaction Survey... (dựa **SCRUM Guide Nov 2020** & **SBOK Guide 3rd**).

---

## 6. Tài liệu gốc: HR Recruitment Process (pdf v2.1/3.0)

- **Approved:** COO Dr. Son Nguyen (Feb 24, 2023). Created by Thao Pham (TA Lead).
- **Roles:** BOD · HR Manager/TA Lead · Head of Departments · Interviewers · HR Team members · IT members.
- **6 bước chi tiết (Section 4):**
  1. **Opening Job Requisition:** Requester điền Job Requisition Form → TA Lead cập nhật Recruitment Needs → BOD/COO duyệt.
  2. **Recruitment Preparation:** tạo/revise JD (TL-HR-Job-Descriptions) → advertise (internal/external) → sourcing.
  3. **Screening Applicants:** tạo shortlist → phone screening.
  4. **Evaluating Candidates:** examination test → interview (HR & kỹ thuật) → salary checking → client interview (optional) → confirm results.
  5. **Making an Offer Letter:** reference check (optional) → C&B tạo Offer Letter → verbal offer.
  6. **Pre-On-Board:** nhập thông tin, phối hợp back-office, HR email toàn team.
- **Forms:** FR-Job-Requisition-Form · TL-HR-Job-Descriptions · Recruitment-Needs · Newcomers-List · Candidate-Review · Interview-Report · Offer-Letter.
- **Guideline:** Sourcing Tip · Phone Screening Tip · Arrange Interview Tip · CL-Onboarding.

---

## 7. Tài liệu gốc: Assets Control Management (pdf v2.1)

- **Approved:** Tai Pham – P&C Manager (Nov 29, 2024). Created by The Nguyen (IT Manager).
- **Mục đích:** quản lý tài sản trong hệ thống QL Chất lượng & An toàn thông tin, tránh thất thoát/lãng phí.
- **8 bước chi tiết (Section 4):**
  1. **Receive New Equipments** – tiếp nhận thiết bị.
  2. **Preparation for Inventory** – lưu kho, dán nhãn (Equipment Control Register).
  3. **Delivery & Sign-Off** – bàn giao & ký nhận.
  4. **Maintenance** – bảo dưỡng, bảo trì định kỳ.
  5. **Fixing/Warranty** – bảo hành, sửa chữa.
  6. **Property In/Out** – kiểm soát tài sản ra/vào công ty.
  7. **Equipment Disposal** – thanh lý & huỷ bỏ (mục 4.7 cập nhật 2024).
  8. **Records Control** – lưu hồ sơ.
- Liên kết đầu vào từ **PRO-OSD-Purchasing-Management-Process**.

---

## 8. Tài liệu gốc: Software Installation Management (pdf v1.0)

- **Approved:** The Nguyen (Dec 07, 2020). Created by Tam Nguyen.
- **Chuẩn tham chiếu:** ISO 27001:2013 A.12.6.2 (Restrictions on Software Installation); POL-OSD-ISMS-IT-Policies.
- **Roles:** Manager/Leader of Dept/Project · IT Department · Branch Director.
- **3 sub-process:**
  1. **Software Register Procedure** – đăng ký phần mềm cần cài.
  2. **Software Audit Procedure** – audit định kỳ (≥6 tháng).
  3. **Revoke Commercial Software** – thu hồi license phần mềm bản quyền vi phạm/hết hạn.
- **Forms:** TL-OSD-Software-Register-List · TL-OSD-IT-Software-Control-List.
- **Định nghĩa:** Commercial software (có license/bán) vs Freeware (miễn phí).

---

## 9. Giáo trình – 8 chương (theo vòng đời BPM)

> Nền tảng: *Fundamentals of Business Process Management* (Dumas, La Rosa, Mendling, Reijers). Slide tiếng Việt.

| Ch | Tên | Nội dung chính |
|---|---|---|
| **1** | Giới thiệu môn học / BPM | Kiến thức quy trình nghiệp vụ, mô hình hóa, kỹ năng xây ứng dụng quản lý điều hành. |
| **2** | Mô hình hóa quy trình kinh doanh | Khái niệm quy trình · phân loại (**Core / Support / Management**) · **BPM Lifecycle** (identification → discovery → analysis → redesign → implementation → monitoring) · vai trò người dùng · thành phần: **Activities, Events, Gateways**. Ký hiệu: BPMN, RAD. |
| **3** | Mô hình hóa với **BPMN** | Business Process Model & Notation: các thành phần (Event, Activity/Task, Gateway XOR/AND/OR, Sequence/Message Flow, Pool/Lane), phương pháp mô hình hóa. |
| **4** | **Khám phá quy trình** (Process Discovery) | Thiết lập discovery · phương pháp khám phá (evidence-based, phỏng vấn, workshop) · mô hình hóa · đảm bảo chất lượng quy trình. → *Cơ sở lý thuyết cho Mục 3 đồ án.* |
| **5** | **Phân tích quy trình** (Process Analysis) | **Định tính**: value-added (VA/BVA/NVA), waste, root-cause, Pareto, Fishbone. **Định lượng**: cycle time, cost, quality (Flow analysis, queuing). → *Cơ sở cho Mục 4 đồ án.* |
| **6** | **Thiết kế lại quy trình** (Process Redesign) | Giới thiệu · **BPR** (tái cấu trúc doanh nghiệp) · phương pháp **Heuristic redesign**. |
| **7** | **Triển khai quy trình** (Process Implementation) | Hệ thống **BPMS** (Business Process Management System) · triển khai quy trình. |
| **8** | **Giám sát quy trình** (Process Monitoring) | Khái niệm · **Dashboard hiệu suất** · **Process Mining** (khai thác quy trình). |

---

## 10. Bài tập Buổi 01 – BuildIT (Equipment Rental Process)

Tình huống kinh điển từ giáo trình: công ty xây dựng **BuildIT** thuê thiết bị từ nhà cung cấp.
Luồng: site engineer điền *Equipment Rental Request* → clerk chọn thiết bị (tra catalogue) → check availability với supplier → works engineer duyệt (approve/reject/replace) → clerk gửi confirmation + **PO** → supplier giao → site engineer inspect (accept/return) → hết hạn supplier pick-up (có thể gia hạn) → supplier gửi invoice → clerk đối chiếu PO → finance thanh toán.

**8 câu hỏi phân tích:** (1) loại quy trình (order-to-cash / procure-to-pay / issue-to-resolution?) · (2) actors & customer · (3) value cho customer · (4) tasks · (5) outcomes · (6) performance measures · (7) issues + thông tin cần thu thập · (8) đề xuất thay đổi & performance measure cải thiện.

> Đây là **procure-to-pay** process — dùng làm mẫu tư duy phân tích cho đồ án.

---

## 11. Chỉ mục file trong project

| File | Loại thật | Nội dung |
|---|---|---|
| `Phân_chia_công_việc_đồ_án.md` | Markdown | Yêu cầu 5 mục + phân công + thành viên |
| `Danh_sách_9_quy_trình.md` | Markdown | 9 quy trình + link ảnh kiến trúc |
| `DoAn_Muc1_LietKeVaPhanTich.docx` | **Text/Markdown** (không phải Word thật) | Bản viết hoàn chỉnh Mục 1 (phân tích 9 quy trình) |
| `PRO-Orient-Sales-Management-Process-1_0.docx` | **Text/Markdown** | Tài liệu gốc quy trình Sales |
| `PROHRRecruitmentProcess2_0.pdf` | **ZIP** (ảnh .jpeg + OCR .txt) | Tài liệu gốc HR Recruitment |
| `PROOSDProjectManagementProcess1_3.pdf` | **ZIP** | Tài liệu gốc Project Management Scrum |
| `PROOSDSoftwareInstallationManagementProcess2_0.pdf` | **ZIP** | Tài liệu gốc Software Installation |
| `PROOrientAssetsControlManagement2_1.pdf` | **ZIP** | Tài liệu gốc Assets Control |
| `Rubik_Đánh_giá_Bài_tập_Đồ_Án.pdf` | **ZIP** | Rubric chấm điểm 5 mục |
| `Buổi_01_Practice111.pdf` | **ZIP** | Bài tập BuildIT + 8 câu hỏi |
| `chap01.pdf` … `chap08.pdf` | **ZIP** | Slide giáo trình 8 chương BPM |

> ⚠️ **Lưu ý kỹ thuật:** các file `.docx` thực chất là text UTF-8, và các file `.pdf` thực chất là **archive ZIP** chứa ảnh trang (`N.jpeg`) + text OCR (`N.txt`). Muốn đọc: `unzip file.pdf '*.txt'` rồi ghép theo thứ tự trang.

---

## 12. Việc cần lưu ý / còn thiếu (checklist)

- [ ] **Cần đủ 10 quy trình** cho Mục 1 (hiện 9) — bổ sung 1 (VD: Purchasing Management, hoặc tách thêm 1 quy trình Support/Core).
- [ ] Vẽ **sơ đồ kiến trúc quy trình** (`orient_process_architecture.png`).
- [ ] Mục 2: mô hình BPMN 6 quy trình (2M+2C+2S) — đảm bảo **>7 gateway** để đạt 1đ độ phức tạp, đúng Split & Join.
- [ ] Mục 3: chuẩn bị **20 câu phỏng vấn** (10 định tính + 10 định lượng, mỗi loại 5 cấu trúc + 5 phi cấu trúc).
- [ ] Mục 4: chọn 2 quy trình cho định tính (VA/NVA/BVA + waste Move/Hold/Overdo + Pareto/Fishbone/Root-cause) và 2 cho định lượng (time/cost/quality).
- [ ] Mục 5: format Word theo mẫu KLTN UIT; duy trì **GitHub commit hàng tuần** (tránh 0đ).
- [ ] Điền cột "Công việc" cho từng thành viên trong file docx Mục 1.
