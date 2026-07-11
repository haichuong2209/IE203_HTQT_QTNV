# Danh sách 10 quy trình
## Quy trình quản lý (Management)
- Qualiti Management Process (Quy trình quản lý chất lượng).
- Project Portfolio & Resource Allocation Management (Quy trình quản lý dự án & Phân bỏ nguồn lực).
- Risk Management Process (Quy trình quản lý rủi ro).
## Quy trình cốt lõi (Core)
- Sales Management Process - Quy trình quản lý bán hàng.
- Project Management Process - Quy trình quản lý dự án Agile Scrum.
- Software Maintenance & Support Process - Quy trình bảo trì & hỗ trợ phần mềm
## Quy trình hỗ trợ (Support)
- HR Recruitment Process - Quy trình tuyển dụng nhân sự.
- Asset Control Management - Quy trình quản lý & kiểm soát tài sản.
- Software Installation Management Process - Quy trình quản lý cài đặt phần mềm.
- Purchasing Management Process - Quy trình mua hàng.

## Kiến trúc quy trình (Process Architecture)
## ![](sources/orient_process_architecture.png)
# Nội dung
## Nhóm quy trình quản lý (Management Process)
### Quy trình quản lý chất lượng (Quality Management Process)
#### Actor / Tác nhân:
- QA Manager
- Nhóm QA/QC
- Project Manager (chủ sở hữu quy trình được audit)
- Ban Giám đốc (BOD)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Xây dựng/ cập nhật tiêu chuẩn chất lượng nội bộ theo khung CMMI/ISO mà công ty áp dụng.
    - Lập kế hoạch kiểm toán (audit) định kỳ cho các dự án/phòng ban.
    - Thực hiện audit quy trình thực tế so với tài liệu quy trình (PRO-*) đã ban hành.
    - Ghi nhận các điểm không phù hợp (Non-conformance – NC) nếu có.
    - Yêu cầu bộ phận liên quan lập kế hoạch khắc phục (CAPA – Corrective and Preventive Action).
    - Theo dõi tiến độ khắc phục và đóng NC khi đã xác minh.
    - Báo cáo tổng hợp chất lượng cho BOD theo quý.
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo sản phẩm/dịch vụ phần mềm bàn giao cho khách hàng đạt chuẩn chất lượng đã cam kết trong hợp đồng/SLA, duy trì chứng nhận CMMI/ISO – yếu tố cạnh tranh quan trọng để khách hàng quốc tế tin tưởng lựa chọn dịch vụ outsourcing.
- Nhiệm vụ chính (Key tasks): Lập kế hoạch audit; thực hiện audit; ghi nhận & phân loại NC; theo dõi CAPA; báo cáo chất lượng định kỳ.
#### Khách hàng / Customer:
- Khách hàng nội bộ: BOD, Process Owner, Project Manager. Khách hàng gián tiếp: khách hàng thuê ngoài (được đảm bảo chất lượng sản phẩm).
#### Khả năng kết quả / Possible outcomes:
- Quy trình/dự án đạt chuẩn (Compliant) – không có NC.
- Phát hiện điểm không phù hợp, phát hành CAR và yêu cầu khắc phục (Non-conformance issued).
- Duy trì chứng nhận CMMI/ISO (Certification maintained) hoặc chứng nhận bị treo/cảnh báo (At risk) nếu không khắc phục kịp thời.

### Quy trình quản lý danh mục dự án & phân bổ nguồn lực (Project Portfolio & Resource Allocation Management)
#### Actor / Tác nhân:
- COO/BOD
- PMO/ Resource Manager
- Head of Development
- Project Manager của từng dự án
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Thu thập nhu cầu nguồn lực từ tất cả các dự án đang/sắp triển khai (định kỳ hoặc khi có dự án mới ký).
    - Đánh giá năng lực & tình trạng sẵn sàng của đội ngũ hiện có (kỹ năng, %  bận việc).
    - Ưu tiên hóa danh mục dự án theo giá trị hợp đồng, mức độ rủi ro, hạn chót khách hàng.
    - Phân bổ nhân sự cụ thể cho từng dự án, xử lý các trường hợp một nhân sự tham gia nhiều dự án song song.
    - Theo dõi mức độ sử dụng nguồn lực (utilization rate) hàng tuần/tháng.
    - Điều chỉnh phân bổ khi có xung đột nguồn lực hoặc dự án mới phát sinh gấp.
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo mỗi dự án của khách hàng luôn có đội ngũ đủ số lượng và đúng kỹ năng để thực hiện đúng tiến độ cam kết, tránh tình trạng dự án bị chậm vì thiếu người.
- Nhiệm vụ chính (Key tasks): Thu thập nhu cầu nguồn lực; đánh giá năng lực hiện có; ưu tiên hóa danh mục; phân bổ nhân sự; theo dõi utilization; điều chỉnh xung đột.
#### Khách hàng / Customer:
- Khách hàng nội bộ: Project Manager, BOD. Khách hàng gián tiếp: khách hàng thuê dự án (đảm bảo dự án đủ người, đúng tiến độ).
#### Khả năng kết quả / Possible outcomes:
- Phân bổ nguồn lực thành công, dự án có đủ đội ngũ đúng kế hoạch.
- Phát hiện thiếu hụt nguồn lực – cần tuyển thêm hoặc thuê ngoài gấp (liên kết với quy trình HR Recruitment).
- Xung đột nguồn lực giữa các dự án – phải điều chỉnh lại thứ tự ưu tiên hoặc đàm phán lại tiến độ với khách hàng.

### Quy trình quản lý rủi ro (Risk Management Process)
#### Actor / Tác nhân:
- Risk Owner (thường là PM hoặc COO)
- BOD
- Trưởng các phòng ban liên quan
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Nhận diện rủi ro tiềm ẩn: rủi ro dự án (trễ tiến độ, thiếu nhân sự), rủi ro bảo mật thông tin khách hàng, rủi ro vận hành, rủi ro nhân sự (nghỉ việc đột xuất).
    - Đánh giá xác suất xảy ra và mức độ tác động của từng rủi ro.
    - Xếp hạng rủi ro theo ma trận xác suất – tác động, cập nhật Risk Register.
    - Lập kế hoạch ứng phó: giảm thiểu (mitigate), chuyển giao (transfer – ví dụ bảo hiểm), chấp nhận (accept) tuỳ mức độ.
    - Theo dõi định kỳ tình trạng các rủi ro đã ghi nhận.
    - Báo cáo rủi ro trọng yếu cho BOD; kích hoạt kế hoạch ứng phó khi rủi ro xảy ra thực tế.
- Giá trị mang lại cho khách hàng (Value to customer): Giảm thiểu khả năng gián đoạn dịch vụ hoặc rò rỉ thông tin cho khách hàng, duy trì cam kết SLA và uy tín của công ty outsourcing đối với đối tác quốc tế.
- Nhiệm vụ chính (Key tasks): Nhận diện rủi ro; đánh giá xác suất/tác động; cập nhật Risk Register; lập kế hoạch ứng phó; theo dõi & báo cáo.
#### Khách hàng / Customer:
- Khách hàng nội bộ: BOD, Project Manager, các phòng ban. Khách hàng gián tiếp: khách hàng thuê dự án (đảm bảo tính liên tục dịch vụ).
#### Khả năng kết quả / Possible outcomes:
- Rủi ro được kiểm soát trong ngưỡng chấp nhận được (Risk controlled).
- Rủi ro leo thang mức nghiêm trọng, cần hành động khẩn cấp (Risk escalated).
- Rủi ro xảy ra thực tế (Risk materialized) – kích hoạt kế hoạch ứng phó/khắc phục sự cố.

## Nhóm quy trình cốt lõi (Core Process)
### Quy trình quản lý bán hàng (Sales Management Process)
#### Actor / Tác nhân:
- Sales Executive/Representative
- Head of Development
- Tech team (ước lượng)
- Finance/Accountant
- Branch Director
- BOD
- Legal Consultant
- CEO
- Khách hàng (Client)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Tạo nguồn khách hàng tiềm năng (Create Lead Pool) qua LinkedIn, Crunchbase, MKT list.
    - Theo dõi & chăm sóc lead tiềm năng (Follow up Potential Leads) qua email/gọi điện.
    - Tổ chức buổi gặp khách hàng (Conduct Client Meeting) để thu thập yêu cầu.
    - Lập đề xuất (Make Proposal) dựa trên breakdown công việc & ước lượng từ Tech team.
    - Lập báo giá (Make Quotation) và trình duyệt.
    - Soạn hợp đồng thương mại (Make Commercial Contract), rà soát pháp lý.
    - Ký hợp đồng (Sign Contract) và chuyển sang quy trình triển khai dự án (Production).
    - Hậu mãi: thu tiền (Revenue Collection), chăm sóc khách hàng định kỳ, khảo sát hài lòng khách hàng, đánh giá post-mortem sau khi kết thúc deal.
- Giá trị mang lại cho khách hàng (Value to customer): Mang lại cho khách hàng một giải pháp phát triển phần mềm phù hợp với ngân sách và yêu cầu kỹ thuật, thông qua quy trình tư vấn minh bạch, báo giá rõ ràng và hợp đồng chặt chẽ, giảm rủi ro khi thuê ngoài (outsourcing) cho bên thứ ba.
- Nhiệm vụ chính (Key tasks): Tìm kiếm & sàng lọc lead; gặp khách hàng; lập đề xuất/báo giá; soạn & ký hợp đồng; thu tiền; chăm sóc khách hàng sau bán.
#### Khách hàng / Customer:
- Khách hàng doanh nghiệp có nhu cầu thuê ngoài phát triển phần mềm (potential clients và existing clients) tại các thị trường như Úc, Mỹ, Châu Âu.
#### Khả năng kết quả / Possible outcomes:
- Ký được hợp đồng – deal thành công (Deal won), chuyển sang triển khai dự án.
- Khách hàng từ chối – deal thất bại (Deal lost).
- Khách hàng yêu cầu điều chỉnh đề xuất/báo giá (Proposal/Quotation revision requested).
- Thanh toán trễ hạn (Late payment) cần Sales phối hợp Finance xử lý.

### Quy trình quản lý dự án Agile Scrum (Project Management Process (Agile Scrum))
#### Actor / Tác nhân:
- Project Sponsor
- Product Owner
- Scrum Master/Project Manager
- Scrum Team (Developer, Tester)
- Khách hàng (Customer)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Initiate – Sprint Zero: xác định Project/Product Vision, lập Project Charter, thành lập Scrum Team, xây dựng Product Backlog, họp Kick-off.
    - Plan and Estimate – Sprint Planning: tạo User Story, ước lượng, cam kết backlog cho sprint, tạo Sprint Backlog.
    - Implement – Development Sprints: phát triển deliverables, họp Daily Standup, cập nhật Product Backlog.
    - Review & Retrospect: demo sản phẩm cho khách hàng, đánh giá Done/Not-Done, họp rút kinh nghiệm (retrospective).
    - Monitoring & Controlling (song song xuyên suốt): theo dõi rủi ro, cập nhật kế hoạch, đo lường hiệu suất.
    - Release: bàn giao sản phẩm/sprint, thu thập phản hồi khách hàng.
    - Closing: cập nhật tài liệu dự án, nghiệm thu sản phẩm, tổng kết bài học kinh nghiệm, giải phóng nguồn lực.
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo sản phẩm phần mềm được xây dựng đúng phạm vi (scope), đúng tiến độ theo từng sprint, và khách hàng có thể theo dõi/tham gia đánh giá tiến độ minh bạch qua các buổi sprint review/demo.
- Nhiệm vụ chính (Key tasks): Lập kế hoạch sprint; phát triển deliverables; daily standup; sprint review & retrospective; release; đóng dự án.
#### Khách hàng / Customer:
- Khách hàng đã ký hợp đồng thuê ngoài phát triển phần mềm (chủ sở hữu sản phẩm/Product Owner phía khách hàng).
#### Khả năng kết quả / Possible outcomes:
- Sprint/dự án hoàn thành đúng Definition of Done, khách hàng nghiệm thu (Product accepted).
- Sprint chưa hoàn thành, các hạng mục dời sang sprint kế tiếp (Carried-over items).
- Dự án đóng thành công, bàn giao đầy đủ tài liệu (Project closed successfully).
- Dự án bị tạm dừng/hủy giữa chừng do thay đổi từ phía khách hàng (Project suspended/cancelled).

### Quy trình bảo trì & hỗ trợ phần mềm (Software Maintenance & Support Process)
#### Actor / Tác nhân:
- Đội Bảo trì/Support (Maintenance team)
- Account Manager
- Project Manager
- Khách hàng (Customer)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Tiếp nhận yêu cầu hỗ trợ/báo lỗi (ticket) qua help desk/email từ khách hàng.
    - Phân loại mức độ ưu tiên theo SLA đã cam kết (Critical/High/Medium/Low).
    - Điều tra nguyên nhân lỗi hoặc yêu cầu nâng cấp nhỏ.
    - Khắc phục lỗi/thực hiện thay đổi, viết bản vá (patch/hotfix).
    - Kiểm thử bản vá trước khi triển khai.
    - Triển khai bản vá lên môi trường production của khách hàng.
    - Xác nhận với khách hàng và đóng ticket; báo cáo tuân thủ SLA định kỳ.
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo hệ thống phần mềm của khách hàng vận hành ổn định sau khi đã bàn giao, xử lý sự cố/khắc phục lỗi đúng cam kết thời gian phản hồi và xử lý (SLA), duy trì mối quan hệ hợp tác lâu dài.
- Nhiệm vụ chính (Key tasks): Tiếp nhận & phân loại ticket; điều tra; khắc phục/vá lỗi; kiểm thử; triển khai; xác nhận & báo cáo SLA.
#### Khách hàng / Customer:
- Khách hàng đã đưa sản phẩm vào vận hành thực tế (giai đoạn hậu dự án/hợp đồng bảo trì).
#### Khả năng kết quả / Possible outcomes:
- Sự cố được khắc phục trong thời hạn SLA (SLA met).
- Vi phạm SLA do sự cố phức tạp (SLA breach) – có thể phát sinh phạt hợp đồng.
- Yêu cầu hỗ trợ chuyển thành một dự án nâng cấp/mở rộng mới (Change request → new project, quay lại quy trình Sales/Project Management).
- Khách hàng gia hạn hợp đồng bảo trì (Maintenance contract renewed).

## Nhóm quy trình hỗ trợ (Support Process)
### Quy trình tuyển dụng nhân sự (HR Recruitment Process)
#### Actor / Tác nhân:
- Requester (Leader/Manager/Sales)
- TA Lead/TA member
- HR Manager
- BOD/COO
- Ứng viên (Candidate)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Opening Job Requisition: Requester điền Job Requisition Form, gửi TA Lead; BOD/COO phê duyệt nhu cầu tuyển dụng.
    - Recruitment Preparation: TA Lead/member xây dựng/cập nhật Job Description, đăng tuyển, tìm nguồn ứng viên tiềm năng.
    - Screening Applicants: sàng lọc CV theo tiêu chí, phỏng vấn sơ bộ qua điện thoại, thu hẹp danh sách ứng viên.
    - Evaluating Candidates: phỏng vấn chính thức (HR & kỹ thuật), đánh giá theo Interview Report.
    - Making an Offer Letter: chuẩn bị và gửi thư mời làm việc cho ứng viên trúng tuyển.
    - Pre-On-Board: chuẩn bị hồ sơ, hợp đồng lao động, NDA, chỗ ngồi... trước ngày ứng viên nhận việc.
- Giá trị mang lại cho khách hàng (Value to customer): Cung cấp nguồn nhân lực IT chất lượng, đúng thời điểm cho các phòng ban/dự án, gián tiếp đảm bảo công ty luôn đủ năng lực đáp ứng các hợp đồng đã ký với khách hàng.
- Nhiệm vụ chính (Key tasks): Mở yêu cầu tuyển dụng; chuẩn bị JD & đăng tuyển; sàng lọc CV & phỏng vấn sơ bộ; phỏng vấn đánh giá; gửi offer; chuẩn bị onboarding.
#### Khách hàng / Customer:
- Khách hàng nội bộ: Requester (Leader/Manager/PM/Sales) cần bổ sung nhân sự cho dự án/phòng ban.
#### Khả năng kết quả / Possible outcomes:
- Tuyển được ứng viên phù hợp, ứng viên chấp nhận offer (Offer accepted).
- Ứng viên từ chối offer (Offer declined) – phải quay lại bước tìm ứng viên khác.
- Vị trí tuyển dụng bị hủy do nhu cầu thay đổi (Requisition cancelled).
- Không tìm được ứng viên phù hợp trong thời gian dự kiến, kéo dài thời gian tuyển dụng (Recruitment delayed).

### Quy trình quản lý & kiểm soát tài sản (Assets Control Management)
#### Actor / Tác nhân:
- IT/Admin (ICS Department)
- HR & Admin Department
- Nhân viên sử dụng tài sản
- FA Department (thanh lý)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Nhận thiết bị mới (Receive New Equipment) từ quy trình Purchasing, kiểm tra tình trạng.
    - Chuẩn bị kiểm kê (Preparation for Inventory) và cập nhật Equipment Control Register.
    - Bàn giao thiết bị & ký nhận (Delivery and Sign-off) cho nhân viên.
    - Bảo trì thiết bị định kỳ (Maintenance of Equipment) theo kế hoạch.
    - Sửa chữa/bảo hành khi thiết bị hỏng (Fixing Equipment/Warranty Services).
    - Kiểm soát tài sản ra/vào công ty (Property In/Out) khi nhân viên mang thiết bị đi công tác hoặc mượn dùng.
    - Thanh lý tài sản hết khấu hao/hỏng không sửa được (Equipment Disposal/Liquid Assets).
    - Lưu hồ sơ, biên bản kiểm kê/bàn giao/thanh lý (Records Control).
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo toàn bộ nhân viên (bao gồm các kỹ sư đang trực tiếp làm dự án cho khách hàng) luôn có đầy đủ thiết bị làm việc hoạt động tốt, giảm thiểu gián đoạn công việc do sự cố thiết bị – gián tiếp bảo vệ tiến độ dự án khách hàng.
- Nhiệm vụ chính (Key tasks): Nhận & kiểm tra thiết bị mới; bàn giao & ký nhận; bảo trì định kỳ; sửa chữa/bảo hành; kiểm soát ra/vào; thanh lý tài sản.
#### Khách hàng / Customer:
- Khách hàng nội bộ: toàn bộ nhân viên và các phòng ban sử dụng trang thiết bị.
#### Khả năng kết quả / Possible outcomes:
- Thiết bị được bàn giao đầy đủ, hoạt động tốt (Equipment delivered & operational).
- Thiết bị hỏng cần sửa chữa/bảo hành (Equipment under repair/warranty).
- Thiết bị được thanh lý theo đúng quy định (Equipment disposed).
- Phát hiện thất thoát tài sản cần xử lý, quy trách nhiệm (Asset loss – investigation required).

### Quy trình quản lý cài đặt phần mềm (Software Installation Management Process)
#### Actor / Tác nhân:
- IT member
- Head of Department/Project Manager (Requester)
- HR
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Đăng ký phần mềm cần cài đặt (Register the Software Application) qua ticket gửi IT.
    - IT kiểm tra & phê duyệt tính hợp lệ của license phần mềm đề nghị cài đặt.
    - Cài đặt phần mềm lên máy tính nhân viên/dự án theo yêu cầu đã duyệt.
    - Audit định kỳ việc cài đặt phần mềm trên toàn công ty (Software Installation Audit) để phát hiện vi phạm.
    - Gỡ bỏ/thu hồi license phần mềm vi phạm hoặc hết hạn (Revoke license).
    - Cập nhật Software Register List và IT Software Control List sau mỗi thay đổi.
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo các công cụ phát triển phần mềm (IDE, phần mềm bản quyền) luôn sẵn sàng và hợp lệ cho đội ngũ kỹ sư triển khai dự án, đồng thời tuân thủ pháp lý về bản quyền phần mềm – giảm rủi ro pháp lý/uy tín cho công ty khi làm việc với khách hàng quốc tế.
- Nhiệm vụ chính (Key tasks): Đăng ký phần mềm; kiểm tra & phê duyệt license; cài đặt; audit định kỳ; gỡ bỏ vi phạm; cập nhật danh sách kiểm soát.
#### Khách hàng / Customer:
- Khách hàng nội bộ: nhân viên/dự án cần công cụ phần mềm để triển khai công việc.
#### Khả năng kết quả / Possible outcomes:
- Phần mềm được cài đặt hợp lệ, đúng license (Software installed – compliant).
- Phát hiện vi phạm license trong quá trình audit, phải gỡ bỏ (Non-compliant software revoked).
- Danh sách kiểm soát phần mềm được cập nhật đầy đủ (Software Control List updated).

### Quy trình mua hàng (Purchasing Management Process)
#### Actor / Tác nhân:
- Requester (nhân viên/phòng ban có nhu cầu)
- Admin/Procurement staff
- BOD/COO (phê duyệt ngân sách)
- Finance/Accountant
- Nhà cung cấp (Vendor)
#### Mô tả quy trình / Process Description:
- Các bước thực hiện (Steps):
    - Requester tạo Yêu cầu mua hàng (Purchase Requisition) nêu rõ nhu cầu thiết bị/dịch vụ/phần mềm.
    - Admin/Procurement kiểm tra ngân sách và tính cần thiết của yêu cầu.
    - Trình BOD/COO phê duyệt yêu cầu mua sắm.
    - So sánh báo giá & lựa chọn nhà cung cấp phù hợp (giá cả, chất lượng, uy tín).
    - Phát hành Đơn đặt hàng (Purchase Order – PO) gửi nhà cung cấp.
    - Nhận hàng/dịch vụ, đối chiếu với PO để xác nhận đúng số lượng & chất lượng.
    - Chuyển hồ sơ cho Phòng Tài chính để thanh toán cho nhà cung cấp.
    - Bàn giao thiết bị/tài sản mới nhận cho quy trình Assets Control Management để tiếp tục quản lý (Receive New Equipment).
    - Lưu trữ hồ sơ mua sắm (PO, hóa đơn, biên bản nhận hàng).
- Giá trị mang lại cho khách hàng (Value to customer): Đảm bảo công ty mua được đúng thiết bị, phần mềm, dịch vụ cần thiết với chi phí hợp lý, từ nhà cung cấp uy tín và đúng thời điểm, phục vụ hoạt động vận hành nội bộ cũng như tiến độ các dự án đang triển khai cho khách hàng.
- Nhiệm vụ chính (Key tasks): Tạo yêu cầu mua hàng; kiểm tra ngân sách; phê duyệt; so sánh báo giá & chọn NCC; phát hành PO; nhận hàng & đối chiếu; thanh toán; lưu hồ sơ.
#### Khách hàng / Customer:
- Khách hàng nội bộ: nhân viên/phòng ban/dự án có nhu cầu mua sắm thiết bị, phần mềm hoặc dịch vụ.
#### Khả năng kết quả / Possible outcomes:
- Đơn mua hàng hoàn tất, hàng/dịch vụ được nhận đúng yêu cầu (Purchase completed & goods received).
- Yêu cầu bị từ chối do vượt ngân sách hoặc không cần thiết (Requisition rejected).
- Nhà cung cấp không đáp ứng được yêu cầu, phải tìm nhà cung cấp thay thế (Vendor re-selection).
- Hàng nhận không đúng yêu cầu/PO, phải trả lại hoặc đổi hàng (Goods returned/replaced).

