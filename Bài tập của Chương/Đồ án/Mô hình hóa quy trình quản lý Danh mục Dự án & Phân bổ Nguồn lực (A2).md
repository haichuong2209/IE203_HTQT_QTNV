## **Mô hình quản lý danh mục dự án & phân bổ nguồn lực (Project Portfolio & Resource Allocation Management)**

**_Process Perspective — Tổng quan quy trình_**

<img width="1121" height="271" alt="chevron_portfolio drawio" src="https://github.com/user-attachments/assets/d5f0c3b9-715f-4b95-9069-f576efce591b" />

----

**_Mô hình BPMN chi tiết_**

Khi thiếu hụt nguồn lực, quy trình còn phân biệt mức độ khẩn cấp để quyết định tuyển gấp hay đưa vào hàng đợi bình thường. Khi đủ nguồn lực, quy trình tách song song (AND-split) việc ưu tiên hóa danh mục và đánh giá rủi ro từng dự án, hội tụ (AND-join) trước khi phân bổ. Khi có xung đột nguồn lực, quy trình phân biệt xung đột giải quyết được bằng đổi ưu tiên nội bộ hay cần đàm phán lại tiến độ với khách hàng (có thể phải escalate lên BOD nếu đàm phán thất bại).

<img width="3186" height="925" alt="bpmn_portfolio drawio" src="https://github.com/user-attachments/assets/39409156-53d3-4161-ad54-1d85ff8f1b71" />

----
**_Độ phức tạp: Quản lý Danh mục Dự án & Phân bổ Nguồn lực (Project Portfolio & Resource Allocation Management)_**

| **Tiêu chí**     | **Giá trị**                                                                                                       |
| ---------------- | ----------------------------------------------------------------------------------------------------------------- |
| Số lượng task    | 12                                                                                                                |
| Số lượng gateway | 8 (6 XOR + 2 AND)                                                                                                 |
| Split & Join     | Có — 1 cặp AND-split/AND-join (tách ưu tiên hóa danh mục // đánh giá rủi ro, hội tụ trước khi phân bổ nhân sự)    |
| Vòng lặp         | Có — 2 vòng lặp (điều chỉnh ưu tiên rồi phân bổ lại; đàm phán tiến độ thành công rồi phân bổ lại)                 |
| Mức độ phức tạp  | Cao — 8 cổng điều kiện (đạt mốc >7 điểm tối đa), phản ánh tính chất điều phối đa chiều của quản lý danh mục dự án |
