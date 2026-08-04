## Sơ đồ quy trình: Purchasing Process (Quy trình mua hàng)

**Các thành phần trong sơ đồ:**
- **Purchasing Department** (Phòng mua hàng)
- **Warehouse Department** (Phòng kho)
- **Vendor** (Nhà cung cấp) — nhận Purchasing Order, gửi lại Goods + Shipment Notice
- **Accounts Payable Department** (Phòng kế toán công nợ) — thực hiện Payment cho Vendor
- **Purchasing Database** (Cơ sở dữ liệu mua hàng) — lưu trữ, trao đổi dữ liệu với Purchasing Department và Accounts Payable Department
- **120 People** — số lượng nhân sự liên quan đến Accounts Payable Department

**Luồng dữ liệu chính:**
1. Purchasing Department gửi **Purchasing Order** đến Vendor
2. Vendor gửi **Goods + Shipment Notice** đến Warehouse Department
3. Warehouse Department trao đổi dữ liệu với Purchasing Database
4. Purchasing Department cũng trao đổi dữ liệu với Purchasing Database
5. Accounts Payable Department lấy dữ liệu từ Purchasing Database và thực hiện **Payment** cho Vendor

---

## Câu hỏi và trả lời

### 1. Who are the actors in this process? (Ai là các tác nhân trong quy trình này?)

Các tác nhân (actors) tham gia trực tiếp vào quy trình bao gồm:
- **Purchasing Department** — lập và gửi đơn đặt hàng
- **Warehouse Department** — nhận hàng hóa và thông báo giao hàng
- **Accounts Payable Department** — xử lý thanh toán
- **Vendor** — nhà cung cấp hàng hóa, nhận đơn hàng và thanh toán

*(Purchasing Database là một đối tượng dữ liệu/hệ thống lưu trữ, không phải là actor.)*

### 2. Which actors can be considered as customers in this process? (Tác nhân nào có thể được xem là khách hàng trong quy trình này?)

Trong quy trình này, **Vendor (Nhà cung cấp)** đóng vai trò là **khách hàng** của quy trình mua hàng — vì:
- Vendor là bên nhận **Purchasing Order** (đầu ra trực tiếp mà quy trình tạo ra để gửi cho một bên bên ngoài)
- Vendor cũng là bên nhận **Payment** — kết quả cuối cùng mà quy trình cung cấp giá trị cho họ (thanh toán đúng hạn, đúng số tiền)

Xét theo góc nhìn nội bộ, các phòng ban (Purchasing, Warehouse, Accounts Payable) là **khách hàng nội bộ** của nhau (internal customers), vì họ nhận đầu ra công việc từ nhau (ví dụ: Warehouse là "khách hàng nội bộ" của Vendor khi nhận Goods + Shipment Notice).

### 3. What value does the process deliver to its customers? (Quy trình này tạo ra giá trị gì cho khách hàng?)

- Đối với **Vendor**: quy trình đảm bảo đơn hàng được đặt rõ ràng, chính xác (Purchasing Order) và được **thanh toán đúng hạn, đầy đủ** (Payment) — đây chính là giá trị mà quy trình mang lại cho nhà cung cấp.
- Đối với **doanh nghiệp** (nhìn từ góc độ tổ chức thực hiện quy trình): quy trình đảm bảo hàng hóa/vật tư cần thiết được **mua đúng, nhận đúng, và được ghi nhận/thanh toán chính xác** thông qua Purchasing Database — hỗ trợ hoạt động sản xuất/kinh doanh liên tục.

### 4. What are the possible outcomes of this process? (Các kết quả có thể xảy ra của quy trình là gì?)

- **Kết quả tích cực (positive outcome):**
  - Đơn hàng được xử lý thành công: Vendor giao đúng hàng hóa, Warehouse nhận và xác nhận hàng, Accounts Payable thực hiện thanh toán đúng hạn cho Vendor → hoàn tất chu trình mua hàng.

- **Kết quả tiêu cực / ngoại lệ (negative outcome):**
  - Hàng hóa giao không đúng/không đủ so với Purchasing Order (sai lệch giữa Goods nhận được và đơn đặt hàng)
  - Sai lệch giữa hóa đơn/thông tin thanh toán với đơn hàng gốc (invoice mismatch), dẫn đến việc thanh toán bị trì hoãn hoặc bị chặn lại để kiểm tra
  - Vendor giao hàng trễ hoặc không giao hàng

---
