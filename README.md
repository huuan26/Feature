# Alpha Factors Research

> **Một nghiên cứu hệ thống về các nhân tố Alpha cho Quant Trading**

Dự án này được xây dựng như một **phòng thí nghiệm học tập** để đào tạo kỹ năng **Quant Research**, tập trung vào việc xây dựng và triển khai các nhóm nhân tố Alpha trong giao dịch định lượng.

---

## 📌 Tổng quan

Dự án phân loại và triển khai **7 nhóm nhân tố Alpha** chính trong giao dịch:

| Nhóm | Mô tả | Ví dụ |
|------|-------|-------|
| **1. Giá / Mẫu hình** | Phân tích hành động giá và cấu trúc nến | Log Return, Heikin-Ashi, Marubozu, Takuri |
| **2. Động lượng** | Đo lường sức mạnh và tốc độ xu hướng | Fisher Transform, Schaff Trend Cycle (STC), QQE |
| **3. Overlap (Làm mượt)** | Lọc nhiễu, giảm độ trễ | ALMA, HMA, Super Smoother Filter |
| **4. Thống kê** | Phân phối & rủi ro đuôi | Shannon Entropy, Rolling Skewness, Kurtosis |
| **5. Xu hướng** | Nhận diện xu hướng và trạng thái thị trường | Choppiness Index, Vortex, CTI |
| **6. Biến động** | Quản trị rủi ro và đo lường Volatility | Ulcer Index, Mass Index, NATR |
| **7. Khối lượng** | Phân tích dòng tiền và áp lực giao dịch | Ease of Movement, Elder's Force Index, PVR |

---

## 🛠️ Thư viện sử dụng

- **Backtrader** — Framework backtesting
- **Python 3.x** — Ngôn ngữ chính
- **NumPy** — Tính toán số học
- **Math** — Các phép toán cơ bản

---

## 📖 Nội dung nghiên cứu

Mỗi indicator đều được trình bày theo cấu trúc 4 phần:

1. **Cơ sở lý thuyết** — Giải thích ý tưởng và triết lý đằng sau chỉ báo
2. **Công thức Toán học** — Công thức bằng LaTeX để dễ hiểu
3. **Template Code** — Code mẫu trên Backtrader
4. **Ý nghĩa & Cách dùng** — Ứng dụng thực tế và tín hiệu giao dịch

---

## 🎯 Mục đích

- Học tập và nghiên cứu về **Alpha Factors**
- Xây dựng nền tảng kiến thức về **Quant Research**
- Phát triển kỹ năng code **Backtrader Indicators**
- Tạo thư viện các nhân tố để sử dụng trong chiến lược giao dịch thực tế

---

## 📌 Lưu ý học tập

> **Quan trọng:** Các chỉ báo thống kê (Skewness, Kurtosis, Entropy) được tính toán trên chuỗi **Log Returns** — không phải giá OHLCV — vì chuỗi giá là **chuỗi không dừng** (non-stationary), việc tính toán trực tiếp sẽ cho kết quả vô nghĩa về mặt toán học.

---

## 👤 Tác giả

**huuan26**

---

## 📄 License

MIT — Tự do sử dụng cho mục đích học tập và nghiên cứu.
