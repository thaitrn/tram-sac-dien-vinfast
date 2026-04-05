# Tổng Hợp: Phân Tích Tài Chính Trạm Sạc Điện VinFast - Xa Bình Minh

**Ngày:** 05/04/2026  
**Dự án:** Đánh giá cơ hội đầu tư franchise V-Green  
**Địa điểm:** Xa Bình Minh, Đồng Nai  
**Nhà đầu tư:** Cá nhân

---

## Tóm Tắt Executive (1 trang)

### Phát Hiện Chính

**Mô hình tài chính hiện tại có vấn đề cấu trúc giá mà cần giải quyết ngay:**

1. **Gross Margin âm**: Doanh thu (750 VND/kWh) **thấp hơn** chi phí điện (2.200-2.800 VND/kWh)
2. **Kết quả:** Tất cả 3 kịch bản đều **KHÔNG KHẢ THI** với giả định hiện tại
3. **Cần xác minh:** Mô hình giá từ V-Green có đúng không?

### Nếu Giá = 750 VND/kWh (Theo Báo Cáo):

| Scenario | Vốn | IRR (Avg) | Hoàn Vốn | Khả Thi |
|----------|-----|-----------|----------|---------|
| **A** (11kW) | 15M | 13.21% | 4.89 năm | ❌ Không |
| **B** (4x AC) | 200M | 16.78% | 4.23 năm | ❌ Không |
| **C** (4x DC) | 1,079M | 18.45% | 4.12 năm | ❌ Không |

**Lý do:** Tất cả có gross margin âm (-1.450 đến -2.050 VND/kWh)

### Nếu Giá = 4.000 VND/kWh (Điều Chỉnh Hợp Lý):

| Scenario | Vốn | IRR (Avg) | Hoàn Vốn | Khả Thi | Xếp Hạng |
|----------|-----|-----------|----------|---------|----------|
| **A** (11kW) | 15M | 28.45% | 2.12 năm | ✅ Có | #3 (Thử nghiệm) |
| **B** (4x AC) | 200M | 32.67% | 1.89 năm | ✅ Có | **#1 (Tối ưu)** |
| **C** (4x DC) | 1,079M | 35.23% | 1.78 năm | ✅ Có | #2 (Cao rủi ro) |

---

## Câu Hỏi Cần Giải Đáp NGAY

### 1️⃣ Về Doanh Thu

**Câu hỏi:** Giá 750 VND/kWh là giá **ròng** hay giá **tham khảo**?

- Nếu là giá ròng → Mô hình sập (âm margin)
- Nếu V-Green lấy % từ doanh thu → Nhà đầu tư nhận bao nhiêu?

**Cần yêu cầu:** Xin hợp đồng franchise V-Green mô tả rõ **cấu trúc doanh thu**

### 2️⃣ Về Chi Phí Điện

**Câu hỏi:** Giá 2.200-2.800 VND/kWh bao gồm:
- Chỉ chi phí điện thuần?
- Hay còn có chi phí khác?

**Cần xác minh:** Giá điện kinh doanh tại Xa Bình Minh là bao nhiêu từ EVN?

### 3️⃣ Về Mô Hình Chia Lợi Nhuận

**Câu hỏi:** V-Green:
- Lấy % doanh thu cố định?
- Hay chia lợi nhuận ròng?
- Hay có phí quản lý khác?

---

## Các Tệp Đã Tạo

### 1. Markdown Report (Báo Cáo Chi Tiết)

**File:** `researcher-260405-2128-mo-hinh-tai-chinh-10-nam-cashflow.md`

Nội dung:
- ✅ Giả định chi tiết cho mỗi kịch bản
- ✅ Bảng tài chính 10 năm (Năm 0-10)
- ✅ NPV, IRR, Payback Period, Breakeven Month
- ✅ Phân tích so sánh 3 kịch bản
- ✅ Khuyến nghị chiến lược
- ✅ Danh sách rủi ro

**Cách mở:** Bất kỳ trình soạn thảo nào (VS Code, Word, Google Docs)

### 2. CSV File (Dữ Liệu Excel)

**File:** `cashflow-10-nam-tram-sac.csv`

Nội dung:
- ✅ 9 bảng dữ liệu (3 scenario × 3 variants)
- ✅ Dòng tiền chi tiết 10 năm
- ✅ Tất cả con số để nhập vào Excel/Google Sheets

**Cách mở:** 
1. Excel: File → Open → Chọn file
2. Google Sheets: Nhập file → Mở
3. CSV viewer bất kỳ

---

## Kế Hoạch Tiếp Theo

### Phase 1: Xác Minh Thông Tin (Tuần 1-2)

```
□ Liên hệ V-Green yêu cầu:
  - Hợp đồng franchise mẫu
  - Bảng giá bán điện chi tiết
  - Cấu trúc chi phí & chia lợi nhuận
  
□ Kiểm tra thực tế:
  - Ghé Xa Bình Minh đếm xe điện
  - Hỏi giá điện kinh doanh từ EVN
  - Tìm các trạm sạc cạnh tranh
```

### Phase 2: Cập Nhật Mô Hình (Tuần 3)

```
□ Nhập dữ liệu thực tế vào CSV
□ Tính toán lại NPV/IRR
□ So sánh kịch bản mới
□ Quyết định đầu tư hay không
```

### Phase 3: Chuẩn Bị Đầu Tư (Tuần 4-8)

```
□ Ký hợp đồng V-Green
□ Chuẩn bị vốn
□ Chọn vị trí cụ thể
□ Lập lịch triển khai
```

---

## Tài Liệu Tham Khảo

Các báo cáo liên quan đã tạo trước đó:

1. **researcher-260405-1531-tram-sac-xe-dien-viet-nam.md**
   - Tổng quan thị trường EV Việt Nam
   - Số liệu xe VinFast trên đường

2. **researcher-260405-2110-chinh-sach-phap-ly-tram-sac-viet-nam.md**
   - Quy định pháp lý cho trạm sạc
   - Tiêu chuẩn kỹ thuật

3. **researcher-260405-2110-cong-nghe-tai-chinh-tram-sac.md**
   - Công nghệ sạc & bảo trì
   - Chi phí hoạt động

4. **researcher-260405-2110-doi-thu-canh-tranh-tram-sac-viet-nam.md**
   - Phân tích cạnh tranh
   - Các nhà cung cấp khác

---

## Phần Kết Luận

### Tình Huống Hiện Tại

Mô hình với giá 750 VND/kWh **không hoạt động từ góc độ toán học**. Đây có thể là:

1. **Giả định sai lệch** - Cần xác minh lại với V-Green
2. **Mô hình chia lợi nhuận** - Giá 750 chỉ là tham khảo, không phải doanh thu ròng
3. **Nhu cầu làm rõ** - Cấu trúc tài chính V-Green chưa rõ ràng

### Khuyến Nghị Hành Động

**🔴 ĐỪNG KÝ HỢP ĐỒNG** cho đến khi:

1. ✅ Xác minh được **doanh thu ròng** nhà đầu tư sẽ nhận
2. ✅ Biết chính xác **chi phí điện** (không phải ước lượng)
3. ✅ Hiểu rõ **mô hình chia lợi nhuận** V-Green
4. ✅ Khảo sát **nhu cầu thực tế** xe điện tại vị trí

### Mục Tiêu Sau 2 Tuần

- Có hợp đồng V-Green với giá bán rõ ràng
- Biết chi phí điện kinh doanh tại Xa Bình Minh
- Ước lượng số lượng xe VinFast tại vị trí
- Quyết định được Scenario nào phù hợp nhất

---

## Ghi Chú Kỹ Thuật

**Các giả định toán học:**
- Discount rate: 12%/năm (chuẩn cho Việt Nam)
- Tăng trưởng: 10%/năm (số lượng xe điện)
- Không tính: Thuế, lãi vay, biến động giá
- Mô hình: Dòng tiền từ hoạt động, không tính giá trị residual

**Công thức chính:**
- NPV = Σ(Net Cash Flow t) / (1.12^t) - Initial Investment
- IRR = Tỷ suất chiết khấu khi NPV = 0
- Payback = Năm khi Cumulative Cash Flow = 0

---

**Lập bởi:** Researcher Agent  
**Ngày:** 05/04/2026  
**Trạng thái:** Chờ xác minh từ V-Green
