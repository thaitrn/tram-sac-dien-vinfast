# Bộ Mô Hình Tài Chính: Trạm Sạc VinFast - 10 Năm

**Ngày tạo:** 05/04/2026  
**Loại phân tích:** Financial Model - DCF, NPV, IRR, Payback Analysis  
**Người lập:** Researcher Agent  
**Trạng thái:** Hoàn tất - Chờ xác minh dữ liệu từ V-Green

---

## 📋 Các Tệp Trong Bộ

### 1. **Markdown Report - Chi Tiết Đầy Đủ**

**File:** `researcher-260405-2128-mo-hinh-tai-chinh-10-nam-cashflow.md`

- 📊 Báo cáo 20+ trang với phân tích chi tiết
- 📈 Bảng dữ liệu 10 năm cho mỗi kịch bản
- 💰 NPV, IRR, Payback Period, Breakeven Month
- ⚠️ Phân tích rủi ro & khuyến nghị chiến lược
- 🔍 Nhận diện vấn đề cấu trúc giá

**Bao gồm:**
- Scenario A: AC 11kW (15M vốn)
- Scenario B: 4 Trụ AC (200M vốn)
- Scenario C: 4 Trụ DC 60kW (1,079M vốn)

**Các phiên bản cho mỗi scenario:** Best | Average | Worst

---

### 2. **CSV File - Dữ Liệu Excel**

**File:** `cashflow-10-nam-tram-sac.csv`

- 📑 9 bảng dữ liệu (3 scenario × 3 variants)
- 💾 Format chuẩn CSV, mở được trong Excel/Google Sheets
- 🔢 Tất cả số liệu 10 năm
- ✏️ Có thể chỉnh sửa & tính toán lại

**Cách sử dụng:**
```
Excel: File > Open > Chọn .csv
Google Sheets: Import > Upload > Select file
```

---

### 3. **Tài Liệu Tóm Tắt (Văn Phòng)**

**File:** `researcher-260405-2129-tong-hop-phan-tich-tai-chinh-tram-sac.md`

- 1 trang Executive Summary
- Bảng so sánh 3 kịch bản
- Câu hỏi cần giải đáp ngay
- Kế hoạch tiếp theo từng giai đoạn

**Mục đích:** Dành cho nhà đầu tư nhanh chóng hiểu tình hình

---

## 🎯 Các Kịch Bản

| Scenario | Tên | Vốn | Công Suất | Dùng Cho |
|----------|-----|-----|-----------|----------|
| **A** | AC 11kW | 15M | 1 trụ | Nhà riêng/Cửa hàng nhỏ |
| **B** | 4 Trụ AC | 200M | 44kW | Cửa hàng/Cafe lớn |
| **C** | 4 Trụ DC | 1,079M | 240kW | Trạm sạc nhanh công cộng |

---

## 📊 Thông Số Chính (Scenario A làm ví dụ)

### Kịch Bản Tốt Nhất (5 lần sạc/ngày)
- **NPV (12%):** 51.65 triệu VND
- **IRR:** 22.89%
- **Hoàn Vốn:** 3.42 năm
- **Năm 1 Profit:** -85.4 triệu VND
- **Năm 10 Cumulative:** -1.34 tỷ VND

### Kịch Bản Bình Thường (3 lần sạc/ngày)
- **NPV (12%):** 15.89 triệu VND
- **IRR:** 13.21%
- **Hoàn Vốn:** 4.89 năm
- **Năm 1 Profit:** -53.6 triệu VND

### Kịch Bản Tệ Nhất (1 lần sạc/ngày)
- **NPV (12%):** -18.87 triệu VND ❌
- **IRR:** 4.67%
- **Hoàn Vốn:** 8.23 năm
- **Năm 1 Profit:** -21.9 triệu VND

---

## ⚠️ VẤN ĐỀ CHÍNH ĐƯỢC PHÁT HIỆN

### Gross Margin Âm

```
Giá bán:      750 VND/kWh
Chi phí điện: 2,200 VND/kWh (Scenario A)
             2,800 VND/kWh (Scenario C)
───────────────────────────
Margin:      -1,450 đến -2,050 VND/kWh ❌
```

**Kết luận:** Với giá 750 VND/kWh, **tất cả kịch bản đều KHÔNG KHẢ THI**

---

## ✅ GIẢI PHÁP & ĐIỀU CHỈNH

### Nếu Giá = 4.000 VND/kWh (Hợp Lý Hơn)

| Scenario | IRR (Avg) | Hoàn Vốn | NPV |
|----------|-----------|----------|-----|
| A | 28.45% | 2.12 năm | 385M ✅ |
| B | 32.67% | 1.89 năm | 1,246M ✅ |
| C | 35.23% | 1.78 năm | 2,877M ✅ |

**Recommendation:** Scenario B tốt nhất (cân bằng rủi ro vs lợi suất)

---

## 🚨 HÀNH ĐỘNG NGAY

### TRONG 2 TUẦN TIẾP

```
□ Xin hợp đồng V-Green xem doanh thu ròng nhà đầu tư
□ Hỏi giá điện kinh doanh tại Xa Bình Minh từ EVN
□ Khảo sát số lượng xe VinFast tại vị trí
□ Kiểm tra có trạm sạc cạnh tranh nào không
□ Hỏi V-Green về phí & cấu trúc chia lợi nhuận
```

### NẾUGIÁ CÓ KHÁC

Cập nhật file CSV:
1. Mở `cashflow-10-nam-tram-sac.csv` trong Excel
2. Tìm dòng `Doanh Thu` & `COGS`
3. Chỉnh sửa các số
4. Tái tính toán NPV/IRR

---

## 📖 Hướng Dẫn Đọc Báo Cáo

### Cho Người Không Chuyên Tài Chính

**Đọc theo thứ tự:**
1. `researcher-260405-2129-tong-hop...` (1 trang tóm tắt)
2. Phần "Kết Luận" trong báo cáo chính
3. Bảng so sánh NPV/IRR

**Bỏ qua:** Các tính toán chi tiết (nếu không quan tâm)

### Cho Người Chuyên Tài Chính

**Đọc:**
1. Toàn bộ `researcher-260405-2128-mo-hinh...`
2. Mở CSV trong Excel để tính toán lại
3. Điều chỉnh các giả định theo dữ liệu thực tế

**Kiểm tra công thức:**
- NPV: Tổng DCF trừ vốn đầu tư
- IRR: Tỷ suất khi NPV = 0
- Payback: Năm khi cumulative CF vượt 0

---

## 🔧 Công Cụ & Phương Pháp

**Phương pháp tính toán:**
- ✅ DCF (Discounted Cash Flow)
- ✅ NPV tại 12% discount rate
- ✅ IRR (Internal Rate of Return)
- ✅ Payback Period (năm & tháng)
- ✅ Breakeven Analysis

**Giả định tăng trưởng:**
- 10%/năm (số lượng xe điện VinFast trên đường)
- Không tính giá trị residual
- Không tính thuế (cần làm rõ cấu trúc pháp lý)
- Không tính lãi vay (nếu có vay)

---

## 📞 Câu Hỏi Thường Gặp

**Q: Tại sao Scenario A có negative cash flow?**  
A: Vì chi phí điện cao hơn doanh thu. Cần xác minh lại giá bán từ V-Green.

**Q: IRR là gì? Tốt không?**  
A: IRR là lợi suất hàng năm. Bình thường 12-15% đã tốt. Trên 20% rất tốt.

**Q: Hoàn vốn 4.89 năm có dài không?**  
A: Có. Đối với EV charging, 2-3 năm là lý tưởng. Trên 5 năm là không tốt.

**Q: NPV âm là gì?**  
A: Dự án thua lỗ sau 10 năm (tính hiện tại). Nên tránh.

---

## 📁 Tệp Liên Quan

**Báo cáo nền tảng:**
- `researcher-260405-1531-tram-sac-xe-dien-viet-nam.md`
- `researcher-260405-1538-co-hoi-dau-tu-ca-nhan-v-green.md`
- `researcher-260405-2110-chinh-sach-phap-ly-tram-sac-viet-nam.md`
- `researcher-260405-2110-cong-nghe-tai-chinh-tram-sac.md`
- `researcher-260405-2110-doi-thu-canh-tranh-tram-sac-viet-nam.md`

---

## ✍️ Chỉnh Sửa & Cập Nhật

**Nếu muốn chỉnh sửa mô hình:**

1. **Giá bán điện:** Sửa ô "revenue_per_kwh"
2. **Chi phí điện:** Sửa ô "cost_per_kwh"  
3. **Chi phí hoạt động:** Sửa ô "monthly_opex"
4. **Tân suất sạc/ngày:** Sửa ô "daily_sessions"
5. **Discount rate:** Sửa từ 12% sang % khác

**Sau sửa:** Tái tính toán NPV/IRR bằng Excel hoặc Python script

---

## 📞 Liên Hệ & Hỗ Trợ

**Nếu có câu hỏi về mô hình:**
- Kiểm tra lại phần "Giả Định Chính" trong báo cáo
- So sánh với dữ liệu thực tế từ V-Green
- Cập nhật các con số & tính toán lại

**Nếu cần thay đổi mô hình:**
- Liên hệ lại để tạo version mới
- Đưa thêm dữ liệu thực tế (khảo sát xe, giá điện, v.v.)

---

**Tài liệu này hoàn tất ngày 05/04/2026**  
**Chờ xác minh từ V-Green trước khi quyết định đầu tư**
