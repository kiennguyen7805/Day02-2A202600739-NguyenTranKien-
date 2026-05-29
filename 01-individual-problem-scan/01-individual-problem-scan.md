# Bảng scan
| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|-----------|----------------------|-------------|---------------|
| 1 | Tốn thời gian | Nhiều sinh viên ở xa trường | Sinh viên | 40% sinh viên di chuyển trên 15 km/ngày |
| 2 | Tốn thời gian | Kẹt xe khiến sinh viên đến lớp trễ | Sinh viên, giảng viên | 20% sinh viên đi muộn ít nhất 2 lần/tuần |
| 3 | Pain từ người khác | Chi phí ăn uống quanh trường cao | Sinh viên | Trung bình 80.000–120.000đ/ngày cho ăn uống |
| 4 | AI có thể tốt hơn | Khó tìm quán ăn phù hợp ngân sách | Sinh viên | Mất 15–20 phút tìm quán mỗi ngày |
| 5 | AI có thể tốt hơn | Khó tìm người đi chung xe để chia chi phí | Sinh viên | 70% sinh viên đi học một mình |
| 6 | Pain từ người khác | Khó tìm phòng trọ gần trường | Tân sinh viên | Mất 1–2 tuần để tìm phòng phù hợp |
| 7 | Tốn thời gian | Khó sắp xếp lịch học và lịch làm thêm | Sinh viên | Xung đột lịch 2–3 lần/tháng |
| 8 | AI có thể tốt hơn | Không biết căng tin khi nào ít đông | Sinh viên | Chờ mua đồ ăn 10–15 phút vào giờ cao điểm |
| 9 | Lặp lại | Hỏi nhau về tuyến xe buýt và đường đi | Sinh viên | Hàng chục câu hỏi giống nhau trong nhóm lớp mỗi tuần |
| 10 | AI có thể tốt hơn | Không biết tuyến đường nào đến trường nhanh nhất theo thời gian thực | Sinh viên | Thời gian di chuyển chênh lệch 20–30 phút tùy ngày |
# Vì sao phần scan này mạnh
- Có scan rộng từ học tập, đi lại, ăn uống đến nhà ở.
- Có nhiều lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.
- Mỗi problem đều có actor rõ ràng.
- Có dấu hiệu định lượng thay vì cảm tính.
- Bắt đầu từ vấn đề thực tế trước khi nghĩ đến AI.
# Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|------|----------|-------------|-------------------|
| 1 | Tìm quán ăn phù hợp ngân sách | Pain thật, xảy ra hằng ngày, AI có thể gợi ý theo ngân sách, vị trí và sở thích | Cần dữ liệu giá quán ăn được cập nhật thường xuyên |
| 2 | Tìm tuyến đường tối ưu đến trường | Nhiều sinh viên gặp phải, có thể giảm thời gian di chuyển và tránh kẹt xe | Cần dữ liệu giao thông thời gian thực |
| 3 | Tìm phòng trọ gần trường | Pain lớn với tân sinh viên, AI có thể lọc theo giá, khoảng cách và tiện ích | Dữ liệu phòng trọ có thể không đầy đủ hoặc lỗi thời |
# Problem Card #1 — Tìm quán ăn phù hợp ngân sách

## Problem 1 câu:

Sinh viên mất nhiều thời gian tìm quán ăn phù hợp với ngân sách, khoảng cách và sở thích, đặc biệt vào giờ nghỉ trưa.

## Actor:

Sinh viên đại học có ngân sách hạn chế và thời gian nghỉ ngắn giữa các buổi học.

## Thời điểm / bối cảnh:

Giờ nghỉ trưa hoặc sau giờ học.

## Current workflow:

1. Mở Google Maps hoặc Facebook
2. Tìm quán ăn gần trường
3. Xem giá và đánh giá
4. So sánh nhiều quán
5. Hỏi bạn bè để xin gợi ý
6. Quyết định nơi ăn
7. Di chuyển đến quán

## Pain points:

- Mất 15–20 phút để tìm quán phù hợp
- Khó biết giá thực tế trước khi đến
- Đánh giá trên mạng đôi khi không đáng tin
- Nhiều quán nhưng không biết quán nào phù hợp ngân sách

## Dấu hiệu định lượng:

- Trung bình mất 15–20 phút/lần tìm quán
- Chi phí ăn uống khoảng 80.000–120.000đ/ngày
- 70% sinh viên hỏi bạn bè trước khi quyết định

## Ý tưởng AI:

AI gợi ý quán ăn dựa trên:
- Ngân sách
- Khoảng cách
- Sở thích ăn uống
- Thời gian hiện có
- Đánh giá từ người dùng
## Bottleneck

Sinh viên mất khoảng 15–20 phút để tìm quán ăn phù hợp ngân sách và khoảng cách. Quá nhiều lựa chọn nhưng thiếu thông tin tập trung.

## Impact

- 15 phút/lần tìm quán
- Trung bình 2 lần/ngày
- Khoảng 30 phút/ngày cho mỗi sinh viên
- Với 1.000 sinh viên có thể lãng phí hơn 500 giờ mỗi ngày

## Success metric

- Giảm thời gian tìm quán từ 15 phút xuống dưới 3 phút
- Trên 80% đề xuất được người dùng chấp nhận
- Tăng mức độ hài lòng của sinh viên về lựa chọn quán ăn

## Non-AI alternative

- Danh sách quán ăn trên Facebook
- Google Maps
- File tổng hợp quán ăn gần trường

Các giải pháp này cung cấp thông tin nhưng chưa cá nhân hóa theo ngân sách và sở thích.

## AI hypothesis

AI có thể đề xuất quán ăn dựa trên:
- Ngân sách hiện có
- Khoảng cách
- Sở thích ăn uống
- Thời gian nghỉ

Người dùng chỉ cần nhập nhu cầu thay vì tự tìm kiếm.

## Quick gut

Workflow
## Draft current workflow

CURRENT STATE — 15 phút

[1 Mở Google Maps/Facebook: 2']

→ [2 Tìm quán gần trường: 3']

→ [3 Xem menu và giá: 4']

→ [4 Đọc đánh giá: 2']

→ [5 So sánh nhiều quán: 3'] <-- bottleneck

→ [6 Quyết định: 1']

Tổng: khoảng 15-20 phút

## Draft future workflow

FUTURE STATE — 2 phút

[1 Nhập ngân sách: 10s]

→ [2 AI phân tích nhu cầu: 10s]

→ [3 AI gợi ý 5 quán phù hợp: 20s]

→ [4 Sinh viên xem kết quả: 30s] <-- human boundary

→ [5 Chọn quán: 50s]

Fallback: Nếu không hài lòng, sinh viên tự tìm trên Google Maps.## Problem Cards #2 và #3 — tóm tắt

| Card | Actor | Bottleneck | Metric | Quick gut | Vì sao chưa chọn làm #1 |
|------|--------|------------|---------|-----------|-------------------------|
| Tìm phòng trọ | Tân sinh viên | Phải tìm kiếm và so sánh hàng chục bài đăng khác nhau | 5 ngày → 1 ngày | Workflow | Dữ liệu phòng trọ khó cập nhật liên tục |
| Tối ưu đường đi đến trường | Sinh viên ở xa trường | Không biết tuyến đường tốt nhất theo thời gian thực | 75 phút → 60 phút | Agent / Workflow | Phụ thuộc dữ liệu giao thông thời gian thực |
