# Các sơ đồ quy trình cần được mô hình hình hóa và phân tích
## Nhóm quy trình quản lý (Management)
### Quy trình quản lý chất lượng (Quality Management Process)
- Sau khi lập kế hoạch, quy trình tách song song (AND-split) thành 2 nhánh audit thực tế và rà soát tài liệu, hội tụ lại (AND-join) trước khi đánh giá NC. Nếu có NC, quy trình phân tích nguyên nhân gốc rễ, lập CAPA và theo dõi tiến độ, có vòng lặp khi CAPA trễ hạn nhưng chưa vượt số lần gia hạn cho phép. Nếu không có NC, quy trình còn kiểm tra thêm tình trạng hạn chứng nhận CMMI/ISO để quyết định có cần chuẩn bị tái chứng nhận hay không.
![](Sơ%20đồ%20quy%20trình/01_Quality_Management_Process.png)
- Mô tả độ phức tạp của quy trình

| Tiêu chí             | Giá trị                                                                                                         |
| -------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Số lượng task**    | 11                                                                                                              |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                               |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join tường minh (tách audit thực tế // rà soát tài liệu, hội tụ trước khi đánh giá NC) |
| **Vòng lặp**         | Có — 2 vòng lặp (phân tích lại root cause khi chưa rõ; gia hạn CAPA khi trễ hạn nhưng chưa vượt giới hạn)       |
| **Mức độ phức tạp**  | Cao — 8 cổng điều kiện (đạt mốc >7 điểm tối đa), kết hợp cả XOR và AND, đúng chuẩn BPMN                         |
### Quản lý danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)
- Khi thiếu hụt nguồn lực, quy trình còn phân biệt mức độ khẩn cấp để quyết định tuyển gấp hay đưa vào hàng đợi bình thường. Khi đủ nguồn lực, quy trình tách song song (AND-split) việc ưu tiên hóa danh mục và đánh giá rủi ro từng dự án, hội tụ (AND-join) trước khi phân bổ. Khi có xung đột nguồn lực, quy trình phân biệt xung đột giải quyết được bằng đổi ưu tiên nội bộ hay cần đàm phán lại tiến độ với khách hàng (có thể phải escalate lên BOD nếu đàm phán thất bại).
![](Sơ%20đồ%20quy%20trình/02_Project_Portfolio_Resource_Allocation.png)
- Mô tả độ phức tạp của quy trình

| **Tiêu chí**         | Giá trị                                                                                                           |
| ---------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Số lượng task**    | 12                                                                                                                |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                                 |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join (tách ưu tiên hóa danh mục // đánh giá rủi ro, hội tụ trước khi phân bổ nhân sự)    |
| **Vòng lặp**         | Có — 2 vòng lặp (điều chỉnh ưu tiên rồi phân bổ lại; đàm phán tiến độ thành công rồi phân bổ lại)                 |
| **Mức độ phức tạp**  | Cao — 8 cổng điều kiện (đạt mốc >7 điểm tối đa), phản ánh tính chất điều phối đa chiều của quản lý danh mục dự án |
## Nhóm quy trình cốt lõi (Core)
### Quy trình quản lý Bán hàng (Sales Management Process)
- Quy trình bổ sung bước rà soát pháp lý hợp đồng (với vòng lặp chỉnh sửa điều khoản nếu chưa đạt) và tách song song (AND-split) hai công việc khởi động dự án khi hợp đồng đã ký: kick-off dự án và thiết lập hồ sơ thanh toán, hội tụ (AND-join) trước khi thu tiền. Ở giai đoạn báo giá, nếu khách hàng chưa chấp nhận, quy trình còn phân biệt khách hàng có còn quan tâm điều chỉnh đề xuất hay đã từ bỏ đàm phán.
![](Sơ%20đồ%20quy%20trình/04_Sales_Management_Process.png)
- Mô tả độ phức tạp của quy trình


| **Tiêu chí**         | Giá trị                                                                                                                                                    |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Số lượng task**    | 13                                                                                                                                                         |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                                                                          |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join (tách kick-off dự án // thiết lập hồ sơ thanh toán sau khi ký hợp đồng)                                                      |
| **Vòng lặp**         | Có — 2 vòng lặp (điều chỉnh đề xuất/báo giá khi khách hàng chưa đồng ý; chỉnh sửa hợp đồng khi rà soát pháp lý chưa đạt)                                   |
| **Mức độ phức tạp**  | Cao nhất trong 6 quy trình — 8 cổng điều kiện, nhiều actor phối hợp (Sales, Legal, Tech, Finance, PM), phản ánh đúng một quy trình bán hàng B2B nhiều bước |
### Quy trình quản lý dự án (Agile Scrum) (Project Management Process)
- Sau Sprint Planning, quy trình tách song song (AND-split) phát triển deliverables và viết test case, hội tụ (AND-join) trước khi kiểm thử — đúng thực hành phát triển song song với kiểm thử (test-driven). Quy trình còn kiểm tra định kỳ khả năng khách hàng dừng dự án, và khi sprint chưa đạt Definition of Done, phân biệt rõ nguyên nhân là thiếu thời gian (carry-over sang sprint sau) hay do thay đổi yêu cầu (cập nhật lại Product Backlog rồi lập kế hoạch lại từ đầu).
![](Sơ%20đồ%20quy%20trình/05_Project_Management_Process_Scrum.png)
- Mô tả độ phức tạp của quy trình

| **Tiêu chí**         | Giá trị                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Số lượng task**    | 12                                                                                                                                  |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                                                   |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join (tách phát triển // viết test case, hội tụ trước khi kiểm thử)                                        |
| **Vòng lặp**         | Có — 3 vòng lặp lồng nhau (fix bug rồi kiểm thử lại; carry-over quay lại phát triển; còn sprint tiếp theo quay lại Sprint Planning) |
| **Mức độ phức tạp**  | Cao — 8 cổng điều kiện, vòng lặp lồng nhau thể hiện đúng bản chất iterative của Scrum                                               |
## Nhóm quy trình hỗ trợ (Support)
### Quy trình tuyển dụng nhân sự (HR Recruitment Process)
- Sau phỏng vấn sơ bộ đạt yêu cầu, quy trình tách song song (AND-split) kiểm tra kỹ thuật và kiểm tra thư giới thiệu, hội tụ (AND-join) trước khi đánh giá tổng thể. Ở giai đoạn thỏa thuận lương, nếu chưa thành công, quy trình còn phân biệt ứng viên có còn linh hoạt để đàm phán lại hay không trước khi kết luận offer bị từ chối.
![](Sơ%20đồ%20quy%20trình/07_HR_Recruitment_Process.png)
- Mô tả độ phức tạp của quy trình

| **Tiêu chí**         | Giá trị                                                                                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Số lượng task**    | 11                                                                                                                                                      |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                                                                       |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join (tách kiểm tra kỹ thuật // kiểm tra thư giới thiệu, hội tụ trước khi đánh giá tổng thể)                                   |
| **Vòng lặp**         | Có — 4 vòng lặp khác nhau đều quay về bước "Sàng lọc CV" hoặc "Gửi offer" (thiếu ứng viên, không đạt phỏng vấn, không đạt đánh giá, đàm phán lương lại) |
| **Mức độ phức tạp**  | Cao — 8 cổng điều kiện, nhiều vòng lặp hội tụ, thể hiện tính bất định cao của quy trình tuyển dụng                                                      |
### Quy trình quản lý & kiểm soát tài sản (Assets Control Management)
- Khi thiết bị hỏng, quy trình phân biệt rõ còn bảo hành hay không để chọn sửa qua nhà cung cấp hay sửa nội bộ. Nếu không sửa được, quy trình phân nhánh tiếp giữa việc chỉ cần thanh lý hay cần xin duyệt ngân sách mua mới (có vòng lặp chờ nếu ngân sách chưa được duyệt). Khi thanh lý, quy trình tách song song (AND-split) xóa dữ liệu và xử lý vật lý thiết bị, hội tụ (AND-join) trước khi lưu hồ sơ.
![](Sơ%20đồ%20quy%20trình/08_Assets_Control_Management.png)
- Mô tả độ phức tạp của quy trình

| **Tiêu chí**         | Giá trị                                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Số lượng task**    | 13                                                                                                                 |
| **Số lượng gateway** | 8 (6 XOR + 2 AND)                                                                                                  |
| **Split & Join**     | Có — 1 cặp AND-split/AND-join (tách xóa dữ liệu // xử lý vật lý thiết bị khi thanh lý, hội tụ trước khi lưu hồ sơ) |
| **Vòng lặp**         | Có — 2 vòng lặp (sửa xong quay lại bàn giao sử dụng; chờ ngân sách mua mới)                                        |
| **Mức độ phức tạp**  | Cao — 8 cổng điều kiện, thể hiện đầy đủ vòng đời tài sản từ tiếp nhận đến thanh lý                                 |



