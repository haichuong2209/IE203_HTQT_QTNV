# Giải thích các khái niệm trong Mục 4 – Phân tích quy trình

## 1. Phân tích giá trị gia tăng (Value-Added Analysis)

Dùng để phân loại từng **bước/hoạt động** trong quy trình theo mức độ tạo ra giá trị, nhằm biết nên giữ, cải tiến hay loại bỏ hoạt động nào.

* **VA – Value Added (Tạo giá trị trực tiếp)**
  * Hoạt động mà **khách hàng sẵn sàng trả tiền** để có được, tác động trực tiếp đến sản phẩm/dịch vụ họ nhận.
  * Ví dụ: Client Meeting, làm Proposal, coding (phát triển deliverables), phỏng vấn ứng viên.
  * Nguyên tắc: nếu bỏ hoạt động này đi, khách hàng sẽ nhận ra ngay sản phẩm/dịch vụ bị thiếu hụt.

* **BVA – Business Value Added (Tạo giá trị cho doanh nghiệp)**
  * Hoạt động **khách hàng không trực tiếp thấy/trả tiền cho nó**, nhưng doanh nghiệp **bắt buộc phải làm** (tuân thủ pháp luật, kiểm soát rủi ro, quản trị nội bộ).
  * Ví dụ: audit chất lượng, rà soát pháp lý hợp đồng, báo cáo cho BOD, escalation.
  * Nguyên tắc: không thể loại bỏ hoàn toàn, nhưng có thể tối ưu để làm nhanh/gọn hơn.

* **NVA – Non-Value Added (Không tạo giá trị)**
  * Hoạt động **không phục vụ khách hàng lẫn doanh nghiệp**, chỉ tồn tại do quy trình chưa tối ưu (thường là hệ quả của việc thiếu công cụ/tự động hóa).
  * Ví dụ: nhập liệu thủ công 2 lần (double entry), chuyển email qua lại để xin phê duyệt, ghi chép giấy rồi nhập lại Excel.
  * Nguyên tắc: đây là mục tiêu **ưu tiên loại bỏ** khi cải tiến quy trình.

> Cách phân biệt nhanh: hỏi "Khách hàng có trả tiền cho việc này không?" → Có: VA. "Không, nhưng công ty/pháp luật bắt buộc?" → Có: BVA. "Không cái nào cả, chỉ tồn tại vì cách làm cũ?" → NVA.

---

## 2. Phân tích lãng phí (Move / Hold / Overdo)

Đây là 3 dạng lãng phí (waste) rút gọn từ hệ thống 7 lãng phí của Lean, tập trung vào các quy trình nghiệp vụ dạng luồng công việc (workflow) thay vì sản xuất.

* **Move (Di chuyển thừa)**
  * Thông tin, tài liệu, hoặc con người phải **di chuyển qua lại nhiều lần/nhiều nơi** một cách không cần thiết trước khi hoàn tất công việc.
  * Ví dụ: email proposal được chuyển qua lại nhiều vòng giữa Sales – Tech – Legal – Client; hồ sơ ứng viên chuyển qua nhiều phòng ban.

* **Hold (Chờ đợi)**
  * Một bước phải **dừng lại chờ** bước khác hoàn tất mới có thể tiếp tục (bottleneck), gây trễ toàn bộ quy trình.
  * Ví dụ: Proposal chờ estimate từ Tech team; thiết bị hỏng chờ duyệt ngân sách; NC chờ PM phản hồi CAPA.

* **Overdo (Làm quá mức cần thiết)**
  * Làm **nhiều hơn mức cần thiết** để hoàn thành công việc — lặp lại thao tác, làm chi tiết hơn yêu cầu thực tế, hoặc nhập cùng một dữ liệu ở nhiều nơi.
  * Ví dụ: ghi Property In/Out cả trên giấy lẫn Excel; viết tài liệu đặc tả quá chi tiết cho task đơn giản; audit checklist ghi giấy rồi nhập lại.

---

## 3. Phân tích các bên liên quan và đăng ký phát hành

### 3.1. Phân tích các bên liên quan (Stakeholder Analysis)
* Xác định **ai bị ảnh hưởng hoặc có ảnh hưởng** đến quy trình (khách hàng, nhân viên thực hiện, quản lý, đối tác...).
* Với mỗi bên liên quan, làm rõ:
  * **Mối quan tâm chính**: họ mong muốn/kỳ vọng gì ở quy trình.
  * **Rủi ro tiềm ẩn**: điều gì xảy ra với họ nếu quy trình vận hành không tốt.
* Mục đích: đảm bảo khi cải tiến quy trình, không bỏ sót lợi ích/rủi ro của bất kỳ bên nào.

### 3.2. Bảng đăng ký phát hành (Issue Register)
* Một bảng tổng hợp **các vấn đề (issue)** đã phát hiện được trong quy trình (thường lấy từ kết quả biểu đồ Pareto), gồm các cột:
  * **Tên vấn đề**: vấn đề cụ thể là gì.
  * **Giả định**: nguyên nhân/bối cảnh được cho là dẫn đến vấn đề (chưa chắc chắn 100%, cần xác minh thêm).
  * **Tác động định tính**: ảnh hưởng ở góc độ mô tả (uy tín, trải nghiệm, rủi ro...).
  * **Tác động định lượng**: ảnh hưởng có con số cụ thể (%, số lần, số ngày...).
  * **Cải tiến**: đề xuất hướng xử lý.
* Đây là công cụ để **theo dõi và ưu tiên hóa** các vấn đề cần giải quyết, tương tự một "sổ nhật ký vấn đề" của dự án cải tiến quy trình.

---

## 4. Biểu đồ Pareto

* Dựa trên nguyên lý **80/20**: phần lớn hậu quả (80%) thường đến từ một số ít nguyên nhân (20%).
* Cách đọc biểu đồ:
  * **Cột (bar)**: số lần xảy ra của từng nguyên nhân, xếp từ cao đến thấp.
  * **Đường (line)**: phần trăm tích lũy (cumulative %) cộng dồn từ trái sang phải.
* Mục đích: giúp xác định **nên ưu tiên xử lý nguyên nhân nào trước** để đạt hiệu quả cải tiến cao nhất với nguồn lực hạn chế — thường ưu tiên các nguyên nhân nằm trước mốc 80% tích lũy.

---

## 5. Phân tích nguyên nhân gốc rễ (Root-Cause / Why-Why)

* Kỹ thuật đặt câu hỏi **"Vì sao?" lặp lại nhiều lần** (thường 3–5 lần) để đi từ triệu chứng bề mặt đến **nguyên nhân gốc rễ** thực sự.
* Cấu trúc trình bày: bắt đầu từ 1 vấn đề → tìm 1–2 nguyên nhân trực tiếp ("Vì...") → với mỗi nguyên nhân, tiếp tục hỏi "Vì sao lại vậy?" để tìm nguyên nhân sâu hơn ("➤ Vì...").
* Khác với biểu đồ Pareto (cho biết vấn đề nào phổ biến nhất), Root-Cause cho biết **vì sao** vấn đề đó xảy ra — từ đó đề xuất khắc phục đúng gốc rễ thay vì chỉ xử lý triệu chứng.
* Đây là 1 trong 3 công cụ phân tích các bên liên quan mà rubric cho chọn (cùng với Pareto và Fishbone/xương cá); nhóm dùng kết hợp cả Pareto lẫn Root-Cause để phân tích toàn diện hơn.

---

## 6. Phân tích định lượng

### 6.1. Bảng các bước và thời gian xử lý
* Liệt kê từng bước của quy trình kèm thời gian thực hiện, sau đó tính:
  * **Tổng thời gian xử lý cơ bản** (trường hợp thông thường, chiếm ~90% số lần thực hiện).
  * **Tổng thời gian khi có phát sinh** (trường hợp ngoại lệ, cần thêm bước xử lý, chiếm ~10% số lần).
  * **Thời gian xử lý trung bình (weighted average)**:
    ```
    Thời gian trung bình = (90% × Thời gian cơ bản) + (10% × Thời gian phát sinh)
    ```
    → phản ánh thời gian thực tế kỳ vọng, có tính đến rủi ro phát sinh.

### 6.2. Hiệu suất thời gian của quy trình
```
Hiệu suất = (Thời gian kế hoạch / Thời gian thực tế trung bình) × 100%
```
* **> 100%**: quy trình thực hiện **nhanh hơn** kế hoạch đề ra (tốt).
* **< 100%**: quy trình thực hiện **chậm hơn** kế hoạch, cần cải tiến.
* "Thời gian kế hoạch" ở đây là mốc mục tiêu nội bộ (SLA/benchmark) mà nhóm đặt ra để đánh giá quy trình, không phải số đo tuyệt đối duy nhất đúng.

### 6.3. Bảng phân bổ nguồn lực
* Cho biết **giai đoạn nào của quy trình cần nhân sự/bộ phận nào tham gia**, giúp thấy rõ:
  * Giai đoạn nào cần phối hợp liên phòng ban (rủi ro chậm trễ do chờ đợi lẫn nhau).
  * Bộ phận nào đang gánh nhiều đầu việc nhất trong quy trình.

### 6.4. Bảng phân tích định lượng (Giải thích – Giá trị ước lượng – Gợi ý cải thiện)
* Tổng hợp các **chỉ số đo lường** quan trọng của quy trình (thời gian, tỷ lệ lỗi/thất bại, chi phí phát sinh...), mỗi chỉ số gồm:
  * **Giải thích**: chỉ số đó đo lường điều gì.
  * **Giá trị ước lượng**: con số hiện tại (ước tính dựa trên khảo sát/giả định).
  * **Gợi ý cải thiện**: hành động cụ thể để cải thiện chỉ số đó.

### 6.5. Kết luận
* Đoạn tóm tắt cuối mỗi quy trình, liên kết lại các con số quan trọng nhất (thời gian, hiệu suất, chi phí) với đề xuất cải tiến trọng tâm — giúp người đọc nắm nhanh "bức tranh tổng thể" mà không cần đọc lại toàn bộ bảng biểu.
