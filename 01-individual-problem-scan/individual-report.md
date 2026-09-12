# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đào Thanh Trường
- Mã học viên: 2A202602683
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
- Chạy bộ
- Nấu ăn 
- Check quảng cáo facebook
- Gọi điện với bạn bè
- Học thêm kiến thức mới
- Lên lịch google calendar dựa trên thời khóa biểu và công việc

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Tổng hợp các câu hỏi, tỉ lệ đặt hàng và hiệu quả quảng cáo trong chiến dịch facebook  | customer, me | 60p/tuần |
| 2 | Tốn thời gian | Chạy bộ | me | 2, 3 ngày chạy bộ 60p |
| 3 | AI có thể tốt hơn | Lên lịch trên google calendar dựa trên thời khóa biểu và công việc| me |15p/ngày |
| 4 | Pain từ người khác | Nấu ăn | me, roomate| 30-60p/ngày |
| 5 |Lặp lại| Tổng hợp kiến thức hoặc các ý tưởng trong ngày vào sổ tay| me| 15-20p/ngày|
| 6 | Tốn thời gian  | Check tin nhắn ,thông báo, gmail | me | 30-45p/ngày |
| 7 | Lặp lại | Học toeic | me | 60p/tuần |
| 8 | Lặp lại | Check  | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Check tin nhắn ,thông báo, gmail |Tần suất diễn ra liên tục, có nhiều thông báo,tin nhắn rác, dễ bỏ sót các thông tin quan trọng |  |
| 2 | Lên lịch trên google calendar dựa trên thời khóa biểu và công việc | Nhu cầu cố định hàng ngày(tuần), dễ đặt nhầm lịch trùng với các sự kiện diễn ra | |
| 3 | Tổng hợp kiến thức hoặc các ý tưởng trong ngày vào sổ tay| Tần suất diễn ra hàng ngày, dễ bỏ sót các kiến thức, ý tưởng| |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Check tin nhắn ,thông báo, gmail]

```text
Problem 1 câu: Người dùng tốn quá nhiều thời gian để xem, lọc tin nhắn rác và phân loại.

Actor: Sinh viên , người đi 

Thời điểm / bối cảnh: Đầu ngày làm việc hoặc cuối 

Current workflow 3-7 bước:
1. Mở lần lượt Gmail, Zalo, Slack, Messenger.
2. Đọc lướt từng thông báo để nhận diện tin rác vs. tin có việc cần làm.
3. Ghi chép thủ công các deadline hoặc việc cần làm ra giấy/app ghi chú.
4. Trả lời các tin nhắn khẩn cấp.
5. Đánh dấu 'Unread' hoặc 'Star' cho các email cần xử lý sau.

Bottleneck: Bước 2 và 3 — Tốn thời gian đọc quét thủ công và tổng hợp các action item rải rác.

Impact: Mất 30–45 phút mỗi ngày chỉ để check tin; dễ sót đầu việc quan trọng gây trễ hạn.

Success metric: Giảm thời gian rà soát xuống dưới 10 phút/ngày; tỷ lệ sót việc giảm về 0%.

Non-AI alternative: Tạo rule/filter tự động chuyển thư mục trong Gmail; tắt thông báo nhóm chat không quan trọng.

AI hypothesis: Sử dụng LLM để đọc, phân loại mức độ ưu tiên và trích xuất bảng việc cần làm kèm deadline theo định dạng ngắn gọn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ X ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — __40_ phút

[1 . Mở app: _5p_'] → [2 . Đọc lướt tin nhắn rác: 15p'] → [3 . Ghi chú lại : 15p'] → [4 Phản hồi tin nhắn gấp: 5p']  <-- bottleneck

FUTURE STATE — 8 phút

[1 Pipeline gom tin nhắn từ các nền : __'] → [2. LLM trích xuất tin nhắn và tóm tắt: '] → [3 Review và phê duyệt task: __']  <-- human boundary

Fallback: nếu AI sai thì parser sai thông 
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Lên lịch trên google calendar dựa trên thời khóa biểu và công việc]

```text
Problem 1 câu: Việc nhập tay từng buổi học, ca làm và deadline từ nhiều định dạng khác nhau vào Google Calendar tốn thời gian và dễ nhầm lẫn giờ giấc.

Actor: Sinh viên đại học có lịch học thay đổi theo tuần kết hợp lịch làm việc/dự án.

Thời điểm / bối cảnh: Đầu kỳ học mới, mỗi đầu tuần hoặc khi nhận thông báo thay đổi lịch thi/lịch học bù.

Current workflow 3-7 bước:
1. Mở file thời khóa biểu (thường là PDF, Excel hoặc ảnh chụp màn hình từ portal trường).
2. Mở song song Google Calendar.
3. So sánh khoảng trống giữa các môn học và lịch làm thêm/dự án.
4. Tạo từng sự kiện trên Google Calendar, nhập thủ công thời gian, phòng học, mã môn.
5. Cài đặt thông báo nhắc hẹn trước 15-30 phút cho từng sự kiện.

Bottleneck: Bước 4 — Nhập liệu thủ công từng block sự kiện lặp đi lặp lại rất tốn công và dễ nhầm giờ.

Impact: Mất 1–2 giờ mỗi khi đổi lịch; dễ nhầm phòng học hoặc trùng ca làm việc.

Success metric: Tự động hóa quá trình nhập lịch trong dưới 2 phút; độ chính xác về thời gian và địa điểm đạt 100%.

Non-AI alternative: Xuất file .ics trực tiếp từ trang tín chỉ của trường (nếu hệ thống hỗ trợ) hoặc dùng template Google Sheets để import hàng loạt.

AI hypothesis: Dùng Multimodal AI để nhận diện lịch từ file ảnh/PDF, trích xuất cấu trúc JSON (Tên môn, Thời gian, Phòng, Tuần học) rồi gọi API đồng bộ vào Google Calendar.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ X ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — _15__ phút

[1 Đọc file PDF, ảnh: 5p] → [2 Đối chiếu với lịch hiện tại: 5p] → [3 Điền lịch trên google calendar: 5p]  <-- bottleneck

FUTURE STATE — 3 phút

[1 Tải file lịch lên hệ thống: 1p] → [2 OCR, LLM sinh danh sách sự kiện ] → [3 Review lại sự kiện đã điền]  <-- human boundary

Fallback: Định dạng file sai thì sửa lại, danh sách sự kiện bị lỗi thì check lại danh sách.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tổng hợp kiến thức hoặc các ý tưởng trong ngày vào sổ tay]

```text
Problem 1 câu: Việc ghi chép, tổng hợp và phân loại thủ công các kiến thức, ý tưởng rải rác trong ngày vào sổ tay/app ghi chú tốn thời gian và dễ làm thất lạc ý tưởng hay.

Actor: Sinh viên năm 4 / Người tự học có thói quen thu thập kiến thức, ý tưởng hằng ngày.

Thời điểm / bối cảnh: Cuối ngày sau khi học tập/làm việc hoặc ngay sau khi đọc/học xong một nội dung mới.

Current workflow 3-7 bước:
1. Thu thập ghi chú/ý tưởng thô từ nhiều nguồn (ảnh chụp slide, tin nhắn note-to-self, bookmark trình duyệt, nháp nhanh).
2. Mở app ghi chú chính (Notion / Obsidian / Apple Notes / Sổ tay).
3. Đọc lại toàn bộ ghi chú thô trong ngày để lọc ra các ý chính.
4. Tóm tắt, gõ lại và phân loại thủ công (gắn tag) theo từng chủ đề/dự án/môn học.
5. Format lại nội dung (thêm bullet points, highlight) để tiện tra cứu sau này.

Bottleneck: Bước 3 và 4 — Đọc lại, tổng hợp và phân loại/gắn tag thủ công gây mệt mỏi nhận thức vào cuối ngày, dẫn đến hay trì hoãn hoặc bỏ dở.

Impact: Tốn 15–20 phút mỗi ngày (~2 giờ/tuần); dễ bỏ sót các ý tưởng sáng tạo hoặc bài học quan trọng do không phân loại hệ thống.

Success metric: Giảm thời gian tổng hợp ghi chú xuống dưới 5 phút/ngày; 100% ý tưởng rải rác được gom nhóm và phân loại chính xác theo chủ đề.

Non-AI alternative: Sử dụng template ghi chú cố định (daily log template) kết hợp các quy tắc đặt tên/tag cố định trong Notion, nhưng vẫn phải nhập liệu và phân loại thủ công.

AI hypothesis: Dùng LLM trích xuất tự động các ý chính từ input dạng thô (text/voice/image), tự động phân loại tag theo cấu trúc có sẵn và sinh bản tóm tắt định dạng Markdown để đồng bộ vào Notion/Obsidian.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ X ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 20 phút

[1 Gom note thô rải rác: 3p] → [2 Đọc lại & lọc ý chính: 7p] → [3 Tóm tắt & gõ vào sổ/app: 7p] → [4 Phân loại tag & format: 3p]  <-- bottleneck

FUTURE STATE — 4 phút

[1 Push note thô (voice/text/ảnh) vào 1 inbox chung: 1p] → [2 LLM tóm tắt, trích xuất key insights & gắn tag tự động: 1p] → [3 Review & duyệt lưu vào Notion/Obsidian: 2p]  <-- human boundary

Fallback: Nếu AI phân loại sai tag hoặc hiểu sai ngữ cảnh, người dùng tự chỉnh lại tag/sửa nhanh trên Notion trong bước Review.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Check tin nhắn, thông báo, gmail
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Card #1 giải quyết workflow rà soát thông báo rải rác hằng ngày, cắt giảm từ 5 bước đọc quét thủ công xuống 3 bước tự động hóa nhờ LLM tóm tắt và gom nhóm. Giúp giảm thời gian từ 30–45 phút xuống dưới 10 phút/ngày và đưa tỷ lệ bỏ sót deadline quan trọng về 0%. Đây là pain point diễn ra vô cùng thường xuyên với tần suất liên tục của sinh viên và người đi làm.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm thế nào để đảm bảo AI không bỏ sót các tin nhắn/thông báo quan trọng hoặc khẩn cấp (tránh sai sót false negative)?
2. Tích hợp API và đọc dữ liệu từ nhiều nền tảng (Gmail, Zalo, Slack, Messenger) có gặp rào cản lớn về chính sách quyền riêng tư và độ bảo mật không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Phụ thuộc nhiều vào kết nối API các bên thứ 3 và nguy cơ rò rỉ thông tin riêng tư khi gửi nội dung tin nhắn qua LLM.
- Tôi sửa gì: Thiết lập Human Boundary bắt buộc (người dùng tự review và xác nhận action item) và giới hạn scope chỉ quét tiêu đề/tóm tắt ngắn thay vì đẩy toàn bộ nội dung tin nhắn nhạy cảm lên AI.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

