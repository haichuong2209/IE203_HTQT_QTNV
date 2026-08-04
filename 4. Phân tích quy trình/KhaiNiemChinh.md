# Mục 4 – Các khái niệm chính của phân tích quy trình

Mỗi quy trình được phân tích qua **4 nhóm khái niệm**, đi từ định tính đến định lượng.

| # | Khái niệm | Mục đích |
|---|---|---|
| 1 | Phân tích giá trị gia tăng (VA / BVA / NVA) | Phân loại từng bước theo mức độ tạo giá trị |
| 2 | Phân tích lãng phí (Move / Hold / Overdo) | Chỉ ra ba dạng lãng phí trong vận hành |
| 3 | Phân tích các bên liên quan và đăng ký phát hành | Xác định bên liên quan, vấn đề và nguyên nhân gốc rễ |
| 4 | Phân tích định lượng | Đo lường thời gian, nguồn lực, chất lượng, chi phí |

---

## 1. Phân tích giá trị gia tăng (VA / BVA / NVA)

Liệt kê từng bước của quy trình và phân loại theo mức độ tạo giá trị.

| Phân loại | Tên đầy đủ | Ý nghĩa |
|---|---|---|
| **VA** | Value-Adding | Bước trực tiếp tạo ra giá trị cho khách hàng |
| **BVA** | Business Value-Adding | Bước không trực tiếp tạo giá trị cho khách hàng nhưng cần cho vận hành, tuân thủ, kiểm soát nội bộ |
| **NVA** | Non-Value-Adding | Bước không tạo giá trị, nên loại bỏ hoặc tự động hóa |

**Cấu trúc bảng phân loại hoạt động:**

| Cột | Nội dung |
|---|---|
| Liệt kê (bước) | Tên bước trong quy trình |
| Phân loại | VA / BVA / NVA |
| Mô tả | Bước đó làm gì, tạo ra giá trị gì |
| Khắc phục | Hướng cải tiến cho bước đó |

---

## 2. Phân tích lãng phí (Move / Hold / Overdo)

Xác định ba dạng lãng phí trong quy trình, mỗi dạng kèm mô tả và hướng khắc phục.

| Dạng lãng phí | Ý nghĩa |
|---|---|
| **Move** (di chuyển) | Hồ sơ, tài liệu hoặc vật tư bị chuyển qua lại nhiều vòng, nhiều kênh, nhiều điểm dừng |
| **Hold** (chờ đợi) | Công việc bị đình trệ vì phải chờ phản hồi, chờ phê duyệt hoặc chờ nguồn lực |
| **Overdo** (làm thừa) | Nhập liệu trùng lặp, làm lại nhiều phiên bản, hoặc làm chi tiết hơn mức cần thiết |

**Cấu trúc bảng phân tích lãng phí:**

| Cột | Nội dung |
|---|---|
| Liệt kê | Move / Hold / Overdo |
| Mô tả | Biểu hiện cụ thể của lãng phí trong quy trình |
| Khắc phục | Giải pháp giảm/loại bỏ lãng phí |

---

## 3. Phân tích các bên liên quan và đăng ký phát hành

Gồm **4 thành phần**.

### 3.1. Phân tích các bên liên quan (Stakeholder Analysis)

Xác định ai chịu ảnh hưởng bởi quy trình và họ mất gì nếu quy trình vận hành kém.

| Cột | Nội dung |
|---|---|
| Bên liên quan | Vai trò / bộ phận |
| Mối quan tâm chính | Điều họ kỳ vọng ở quy trình |
| Rủi ro tiềm ẩn nếu quy trình không hiệu quả | Hậu quả với riêng bên liên quan đó |

### 3.2. Biểu đồ Pareto

Biểu đồ xếp hạng các nguyên nhân gây vấn đề theo mức độ ảnh hưởng giảm dần, giúp nhận diện nhóm nguyên nhân chiếm phần lớn tác động để ưu tiên xử lý trước.

### 3.3. Bảng đăng ký phát hành (Issue Register)

Danh mục các vấn đề phát hiện được trong quy trình.

| Cột | Nội dung |
|---|---|
| Tên vấn đề | Tên gọi ngắn gọn của vấn đề |
| Giả định | Bối cảnh/nguyên nhân được giả định dẫn tới vấn đề |
| Tác động định tính | Ảnh hưởng mô tả bằng lời |
| Tác động định lượng | Ảnh hưởng quy ra số liệu (tỷ lệ, thời gian, chi phí) |
| Cải tiến | Đề xuất khắc phục |

### 3.4. Phân tích nguyên nhân gốc rễ (Root-Cause / Why-Why)

Với **mỗi vấn đề** trong Issue Register, truy ngược nguyên nhân theo chuỗi câu hỏi "Vì sao" gồm **2 cấp**:

```
- Vì: <nguyên nhân cấp 1>
    - Vì: <nguyên nhân cấp 2>
    - Vì: <nguyên nhân cấp 2>
- Vì: <nguyên nhân cấp 1 khác>
    - Vì: <nguyên nhân cấp 2>
```

Mỗi vấn đề thường có **2 nhánh nguyên nhân cấp 1**, mỗi nhánh dẫn tới 1–2 nguyên nhân cấp 2.

---

## 4. Phân tích định lượng

Gồm **4 thành phần**.

### 4.1. Các bước và thời gian xử lý

Bảng liệt kê thời gian của từng bước (đơn vị: phút, giờ công hoặc ngày tùy quy trình).

| Cột | Nội dung |
|---|---|
| STT | Số thứ tự bước |
| Bước | Tên bước |
| Thời gian | Thời gian xử lý của bước |

**Các công thức áp dụng:**

| Chỉ số | Công thức |
|---|---|
| Tổng thời gian xử lý cơ bản | Tổng thời gian các bước, áp dụng cho **90% trường hợp** |
| Tổng thời gian khi có phát sinh | Thời gian cơ bản **+** thời gian các bước phát sinh, áp dụng cho **10% trường hợp** |
| Thời gian xử lý trung bình | `(90% × Thời gian cơ bản) + (10% × Thời gian khi có phát sinh)` |
| Hiệu suất thời gian của quy trình | `(Thời gian kế hoạch / Thời gian thực tế) × 100%` |

> Hiệu suất **> 100%** nghĩa là quy trình chạy nhanh hơn kế hoạch; **< 100%** nghĩa là chậm hơn kế hoạch.

### 4.2. Bảng phân bổ nguồn lực

Ai tham gia vào giai đoạn nào của quy trình.

| Cột | Nội dung |
|---|---|
| Giai đoạn | Nhóm bước trong quy trình |
| Nhân sự tham gia | Vai trò cụ thể |
| Bộ phận | Phòng ban chủ quản |

### 4.3. Bảng phân tích định lượng (Thời gian – Chất lượng – Chi phí)

Các chỉ số đo hiệu quả quy trình trên ba khía cạnh: **thời gian**, **chất lượng** và **chi phí**.

| Cột | Nội dung |
|---|---|
| Giải thích | Tên chỉ số đo lường |
| Giá trị ước lượng | Giá trị hiện tại (dạng khoảng ước lượng) |
| Gợi ý cải thiện | Hướng nâng chỉ số đó |

### 4.4. Kết luận

Đoạn tổng kết cho mỗi quy trình, nêu: thời gian xử lý trung bình, hiệu suất thời gian so với kế hoạch, các điểm rủi ro còn tồn tại, và đề xuất ưu tiên cải tiến.
