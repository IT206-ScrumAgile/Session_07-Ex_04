# CHỌN CÁCH DỰ BÁO PHẠM VI CHO SPRINT 6 (RikkeiGo)

**Vai trò:** Vy (Developer), cùng Lan (Scrum Master) chuẩn bị phương án dự báo cho buổi Sprint Planning
**Sprint 6:** 10 ngày | **Planning Capacity:** 186 giờ (Sprint 5: 212 giờ)
**Velocity 5 Sprint gần nhất:** 18, 20, 19, 15, 13 SP

**Số liệu nền:**
- Average Velocity = (18 + 20 + 19 + 15 + 13) / 5 = 85 / 5 = **17 SP**.
- Velocity Range = **13 – 20 SP** (thấp nhất 13, cao nhất 20).
- Capacity giảm: (212 − 186) / 212 ≈ **12,3%**, do Khoa rời đội, Minh mới chỉ dành khoảng một nửa số giờ và Hà nghỉ phép 3 ngày.
- Backlog hiện có: PBI 1 (5 SP), PBI 2 (13 SP, chưa đủ Acceptance Criteria), PBI 3 (3 SP), PBI 4 (5 SP), PBI 5 (2 SP).

---

## Phần 1 – Đề xuất hai cách dự báo

### Cách 1 – Dự báo theo Velocity Range / Average (nhìn về quá khứ)

- **Bản chất:** dùng lịch sử Velocity làm căn cứ chính, lấy PBI theo thứ tự Product Backlog cho tới khi gần đạt mức trung bình.
- **Con số dự báo:** **17 SP** (khoảng 13–20 SP).
- **PBI chọn:** đi theo thứ tự Backlog và loại PBI chưa đủ rõ (PBI 2 thiếu Acceptance Criteria cho trường hợp mất GPS):
  - PBI 1 – Hẹn giờ đặt xe trước (5 SP)
  - PBI 3 – Gửi SMS khi tài xế sắp đến (3 SP)
  - PBI 4 – Chat với tài xế (5 SP)
  - PBI 5 – Giao diện chủ đề Tết (2 SP)
  - **Tổng: 15 SP** (gần mức 17; không thể chạm 17 mà không đưa PBI 2 vào).

### Cách 2 – Dự báo theo Capacity điều chỉnh và Sprint Goal (nhìn vào Sprint tới)

- **Bản chất:** xuất phát từ Sprint Goal và Capacity của Sprint 6; Velocity quá khứ chỉ dùng để đối chiếu mức hợp lý, không phải đích cần lấp đầy.
- **Con số dự báo:** lấy Average Velocity điều chỉnh theo tỉ lệ Capacity, 17 × (186 / 212) ≈ **14,9 ≈ 15 SP** làm **mức trần tham khảo**. Vì Capacity giảm bao nhiêu phần trăm không có nghĩa Velocity giảm đúng bấy nhiêu, Developers rà thêm việc của Minh (đang làm quen dự án) và ngày nghỉ của Hà để chốt, nên dự báo thực tế nằm quanh **13–15 SP**.
- **PBI chọn:** chỉ những PBI phục vụ Sprint Goal "giúp khách chủ động hơn khi chờ tài xế" và đã đủ rõ:
  - PBI 1 – Hẹn giờ đặt xe trước (5 SP)
  - PBI 3 – Gửi SMS khi tài xế sắp đến (3 SP)
  - PBI 4 – Chat với tài xế (5 SP)
  - **Tổng: 13 SP.**

---

## Phần 2 – So sánh hai cách

| Tiêu chí | Cách 1 – Velocity Range / Average | Cách 2 – Capacity điều chỉnh + Sprint Goal |
|----------|-----------------------------------|---------------------------------------------|
| **Phản ánh thay đổi Capacity** | **(–)** Chỉ nhìn Velocity cũ nên gần như bỏ qua việc Capacity giảm khoảng 12% (Minh mới vào, Hà nghỉ, Khoa rời đội); dự báo 17 SP có thể cao hơn khả năng thực của Sprint 6. | **(+)** Điều chỉnh theo Capacity 186 giờ so với 212 giờ và xét riêng Minh, Hà; chỉ dùng tỉ lệ này làm tham khảo, không quy đổi cứng, nên dự báo sát hơn. |
| **Bảo vệ Sprint Goal** | **(–)** Đi theo thứ tự Backlog để cho đủ số SP nên dễ đưa PBI 5 (giao diện Tết, không phục vụ Goal) vào chỉ để lấp chỗ trống; cũng dễ bị kéo PBI 2 (13 SP) khi nhắm 17–18 SP. | **(+)** Chọn từ Sprint Goal trước, số SP chỉ là phép kiểm tra; không lấp đầy bằng việc ngoài Goal và không đưa PBI chưa đủ rõ vào Sprint. |
| **Dễ giải thích với Product Owner** | **(+)** Đơn giản, trực quan: "trung bình 17, dao động 13–20", Đức dễ hiểu ngay. | **(–)** Cần giải thích thêm về Capacity, lý do không lấp đầy và vì sao chỉ cam kết ít SP hơn mức trung bình; mất thêm thời gian trao đổi. |

---

## Phần 3 – Lựa chọn

### 3.1. Cách được chọn: **Cách 2 – Capacity điều chỉnh + Sprint Goal**

**Căn cứ:**
- **Velocity:** Velocity đang giảm (19 → 15 → 13); Sprint 5 chỉ đạt 13 SP với Capacity 212 giờ. Average 17 SP phản ánh quá khứ, không phải mức bắt buộc cho Sprint tới.
- **Capacity:** Sprint 6 chỉ có 186 giờ (giảm ~12%) và Minh mới chỉ làm ở nửa công suất, nên mức 17–20 SP có rủi ro cao.
- **Độ rõ của PBI:** PBI 2 (13 SP) lớn và chưa có Acceptance Criteria cho trường hợp mất GPS nên chưa nên đưa vào Sprint.

### 3.2. Sprint Goal đề xuất

> **"Khách hàng chủ động hơn khi chờ tài xế: hẹn giờ đặt xe trước, biết khi tài xế sắp đến và liên lạc được với tài xế."**

### 3.3. PBI mang vào Sprint Planning

| # | PBI | SP | Lý do |
|---|-----|----|-------|
| 1 | Hẹn giờ đặt xe trước | 5 | Khách chủ động lên lịch, giảm việc phải chờ; Acceptance Criteria đầy đủ. |
| 3 | Gửi SMS khi tài xế sắp đến | 3 | Khách biết khi nào tài xế đến; hợp đồng SMS đã ký nên không còn phụ thuộc bên ngoài. |
| 4 | Chat với tài xế | 5 | Khách liên lạc được với tài xế trong lúc chờ; Acceptance Criteria đầy đủ. |

**Tổng: 5 + 3 + 5 = 13 SP**, nằm trong Velocity Range 13–20 SP, ở mức đáp ứng dự báo 13–15 SP theo Capacity.

**PBI không chọn:**
- **PBI 2 – Theo dõi vị trí tài xế trên bản đồ (13 SP):** quá lớn (gần bằng cả Sprint) và chưa có Acceptance Criteria cho trường hợp mất GPS; cần Refinement cùng Đức, có thể tách nhỏ và ước lượng lại cho Sprint sau.
- **PBI 5 – Giao diện chủ đề Tết (2 SP):** không phục vụ Sprint Goal; không đưa vào chỉ để lấp 2 SP trống.

### 3.4. Phản hồi đề nghị 20 SP của quản lý

"Velocity là dữ liệu quá khứ để dự báo, không phải KPI hay chỉ tiêu phải tăng. Mức 20 SP tuy nằm trong khoảng cũ của đội, nhưng Sprint 6 có Capacity chỉ còn 186 giờ (giảm khoảng 12%) vì Minh mới vào và Hà nghỉ phép, đồng thời PBI cần thêm để đủ 20 SP (PBI 2) chưa đủ rõ để đưa vào Sprint. Đội đề xuất cam kết 13 SP gắn với Sprint Goal và Done thật; Velocity sẽ tự phục hồi khi nhân sự ổn định, không cần ép con số."
