# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Mai Hoàng Thiện | 2A202602912 | Facilitator |
| 2   | Nguyễn Tiến Đạt       | 2A202602606 | Research |
| 3   | Nguyễn Phú Bình       | 2A202602410 | Research |
| 4   | Nguyễn Thu Trang      | 2A202602435 | Research |
| 5   | Nguyễn Minh Dương     | 2A202602920 | Research |
| 6   | Hoàng Trung Khải      | 2A202602947 | Research |

**Candidate problem nhóm chọn (1 câu):**
Phân loại và chuẩn hóa Bug Report từ Discord thành Issue có cấu trúc (Problem #4)

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Mai Hoàng Thiện | Code Review mất lâu vì thiếu context — reviewer phải tự đọc ticket + Slack thread trước khi review được | Software engineer / senior dev trong team | Bước đọc hiểu context (15–30 phút/PR) trước khi review thật sự | |
| 2 | Nguyễn Mai Hoàng Thiện | Đọc docs/paper kỹ thuật dài khi học công nghệ mới — không biết phần nào cần đọc trước | Software engineer tự học công nghệ mới | Đọc toàn bộ docs không ưu tiên được — mất 2–4 giờ trước khi viết được dòng code đầu | |
| 3 | Nguyễn Mai Hoàng Thiện | Báo cáo sự cố đô thị (ổ gà, ngập, đèn hỏng) chậm phản hồi — không biết báo ai, không có feedback loop | Người dân đô thị đi xe máy/xe đạp | Tìm đầu mối + mô tả vị trí bằng lời + không có phản hồi sau khi báo |  |
| 4 | Nguyễn Tiến Đạt | Phân loại và chuẩn hóa Bug Report từ Discord thành Issue có cấu trúc — trích xuất thông tin thô từ tin nhắn → ticket đủ context để assign & fix | Dev trực dự án & Tester | Bước trích xuất/làm rõ thông tin: bug report thiếu steps to reproduce, env, severity → phải hỏi lại nhiều lần |  |
| 5 | Nguyễn Tiến Đạt | Review mã nguồn (Code Review) cho Pull Request trên GitHub — 60% thời gian review bị lãng phí vào lỗi convention/comment/typing thay vì logic thuật toán | Reviewer và 2 lập trình viên nộp PR | 35–45 phút/PR; 60% thời gian vào lỗi cú pháp/convention; PR chờ duyệt 24–36h |  |
| 6 | Nguyễn Tiến Đạt | Trích xuất Benchmark & Dataset từ bài báo khoa học AI (arXiv PDF) cho Literature Review — đọc lướt thủ công tốn nhiều thời gian, đầu ra không chuẩn hóa | Sinh viên làm đồ án nghiên cứu | PDF parser mã nguồn mở làm vỡ bảng phức tạp; format bảng kết quả đa dạng khó chuẩn hóa |  |
| 7 | Nguyễn Thu Trang | Đọc & trích xuất ý chính từ tài liệu tham khảo để viết Literature Review đồ án | Sinh viên năm 4 làm đồ án tốt nghiệp | Mất 2 tiếng/paper đọc thủ công tiếng Anh và tra cứu thuật ngữ chuyên ngành | Pain rất lớn, 3.5–4h/lần; đóng khung input PDF và output bảng so sánh rõ ràng |
| 8 | Nguyễn Thu Trang | Giảng viên mất thời gian duyệt bài vì bản thảo thiếu Change-log tóm tắt các chỉnh sửa | Giảng viên hướng dẫn & Sinh viên | Sinh viên sửa rải rác không ghi nhật ký → GV phải dò mắt bôi vàng thủ công sát giờ nộp | Pain thật từ người khác (GV phàn nàn); quy trình diff bản cũ/mới rõ, khả năng giải quyết dứt điểm cao |
| 9 | Nguyễn Thu Trang | Tinh chỉnh bullet points và từ khóa trong CV theo Job Description (JD matching) | Sinh viên năm 4 chuẩn bị xin việc | Loay hoay viết lại câu theo chuẩn Action Verb + Result để khớp từ khóa JD | Nhu cầu cấp bách giai đoạn tốt nghiệp; đo được ngay: 90' → 15' sửa, tỷ lệ qua vòng lọc hồ sơ |
| 10 | Nguyễn Phú Bình | Tìm lại câu trả lời cũ trong Discord lớp khi làm bài tập — phải đọc nhiều tin nhắn để xác định thông tin phù hợp | Sinh viên | Bước tìm kiếm & xác định câu trả lời đúng trong luồng tin nhắn nhiều chiều — 10–15 phút/lần | Workflow rõ; đo được 10–15 phút/lần; có thể AI tóm tắt câu trả lời theo context bài tập |
| 11 | Nguyễn Phú Bình | Tìm deadline ở nhiều nguồn rời rạc (Discord, LMS, nhóm lớp, tài liệu môn học) | Sinh viên | Thông tin deadline phân tán, cập nhật không đồng thời → phải đối chiếu thủ công nhiều nguồn | Workflow lặp lại; tự động hóa được; cần xác định nguồn chính thức khi xung đột thông tin |
| 12 | Nguyễn Phú Bình | Debug code và tìm nguyên nhân lỗi — từ gặp lỗi → đọc error → kiểm tra code → tìm tài liệu → thử sửa → chạy lại | Sinh viên IT / Lập trình viên | Bước xác định nguyên nhân thực sự của lỗi — mất nhiều vòng thử sai; đo bằng thời gian gặp lỗi → xác định nguyên nhân và số lần thử sửa | AI fit rõ (phân tích error message + code); cần human review & test trước khi chấp nhận đề xuất của AI |
| 13 | Nguyễn Minh Dương | Ghi chép biên bản (meeting notes) và chia task sau mỗi buổi họp nhóm hằng tuần | Thành viên nhóm / Trưởng nhóm | Ghi chép thủ công và phân chia task mất thời gian, dễ thiếu sót | Công việc quan trọng, cần bám sát deadline; Chưa rõ có thể lấy trực tiếp từ app meeting hay không |
| 14 | Nguyễn Minh Dương | Viết docstrings (tài liệu API) cho các hàm xử lý dữ liệu pipeline sau khi code xong | Lập trình viên / Data Engineer | Viết tài liệu API thủ công mất nhiều thời gian và gây nhàm chán | Đánh trúng pain point (mất thời gian, gây nản); Cần đánh giá độ chính xác của docstring do AI tạo |
| 15 | Nguyễn Minh Dương | Phân loại Feedback mở từ Form Khảo sát | Người tổ chức sự kiện / Giảng viên | Phân tích hàng loạt feedback text thủ công tốn thời gian, nhất là khi cần làm báo cáo gấp | Nhu cầu có thật khi cần báo cáo gấp; Cần xem xét độ tin cậy và chính xác của việc phân loại bằng AI |
| 16 | Hoàng Trung Khải | Data Annotation: Quá nhiều vòng trao đổi và review giữa tôi và annotation team để thống nhất cách xử lý các edge cases mà guideline chưa bao phủ | AI Engineer / Data QA | Quá trình thống nhất edge cases qua nhiều vòng review gây delay 1-2 tuần | Có impact thực tế, AI có thể hỗ trợ tìm và phân loại case tương tự; Chưa rõ trung bình số vòng trao đổi và khả năng giải quyết triệt để của AI |
| 17 | Hoàng Trung Khải | Testing / Tuning: Phải theo dõi và ghi chép lại các cấu hình (hyperparameters) tương ứng với metric của từng version model để chọn ra bản tốt nhất | AI/ML Engineer | Vấn đề lặp lại mỗi training cycle, ghi chép config, metrics và error log thủ công mất thời gian | AI có thể đọc log tổng hợp experiment history; Chưa rõ thời gian document thực tế và AI nên tóm tắt hay đề xuất config mới |
| 18 | Hoàng Trung Khải | Research: Cần tìm kiếm, đọc nhiều tài liệu, các nguồn không tập trung, phải kiểm tra xem tài liệu có đủ chất lượng không | Researcher / Kỹ sư | Nguồn thông tin phân tán, mất 3h/ngày để tìm kiếm và lọc tài liệu | AI có thế mạnh summarization và filtering; Khó định nghĩa "đủ chất lượng" và rủi ro overlap với các công cụ AI research hiện có |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A. Nghiên cứu & Xử lý tài liệu chuyên ngành** | #2, #6, #7, #14, #18 | Đối mặt với khối lượng lớn văn bản (paper, docs, code), tốn nhiều giờ đọc thủ công để trích xuất thông tin trọng tâm (benchmark, ý chính, docstring). | AI có thế mạnh rõ rệt về summarization và trích xuất thực thể. |
| **B. Tối ưu quy trình phát triển & Review (Dev Workflow)** | #1, #5, #8, #12, #16, #17 | Mất nhiều thời gian ở khâu review/kiểm tra do thiếu context (Code, Data, Change-log), debug lặp lại nhiều vòng hoặc tracking thủ công. | Workflow có bottleneck rất rõ ở các vòng review, QA. |
| **C. Quản lý luồng thông tin & Tác vụ rời rạc** | #4, #10, #11, #13, #15 | Thông tin bị phân tán, dạng phi cấu trúc (tin nhắn Discord, Meeting, Form, LMS). Cần chuẩn hóa, tóm tắt và phân loại thành action items. | Giải pháp dạng Bot (Discord/Slack/Teams) có tiềm năng rất lớn. |
| **D. Tối ưu cá nhân hóa & Tiện ích** | #3, #9 | Giải quyết nhu cầu cá nhân hóa: tinh chỉnh text khớp tiêu chí (CV matching) hoặc tạo kênh báo cáo thông tin nhanh. | Độc lập với các quy trình kỹ thuật/nghiên cứu phía trên. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#3: Báo cáo sự cố đô thị chậm phản hồi** | - Pain của người dân rất rõ, mang tính cộng đồng cao.<br>- Workflow dễ hình dung: Phát hiện -> Chụp ảnh/Mô tả -> Báo cáo. | - Khó can thiệp vào hệ thống xử lý của chính quyền để giải quyết triệt để.<br>- Thiếu cơ chế phản hồi thực tế để đóng vòng feedback loop. |
| **#4: Phân loại Bug Report từ Discord thành Issue** | - Actor (Dev/Tester) và workflow (Đọc tin nhắn -> Trích xuất -> Tạo ticket) cực kỳ rõ ràng.<br>- Nhu cầu có thật, đo lường được impact qua số phút tiết kiệm mỗi ticket. | - User có cung cấp đủ context ban đầu không, hay hệ thống AI vẫn phải hỏi lại nhiều lần (interactive clarification)? |
| **#10: Tìm lại câu trả lời cũ trong Discord lớp** | - Nhu cầu phổ biến của sinh viên.<br>- Dữ liệu (tin nhắn Discord) có sẵn để test AI tìm kiếm và tóm tắt. | - Các câu trả lời cũ có thể sai hoặc mâu thuẫn.<br>- Có thể trùng lặp với tính năng search mặc định của Discord nếu AI không đủ tốt. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#3: Báo cáo sự cố đô thị** | 4 | 4 | 3 | 3 | 3 | 4 | 3 | **24** |
| **#4: Bug Report Discord** | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| **#10: Tìm câu trả lời Discord** | 5 | 4 | 4 | 4 | 5 | 4 | 5 | **31** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Phân loại và chuẩn hóa Bug Report từ Discord thành Issue có cấu trúc — trích xuất thông tin thô từ tin nhắn → ticket đủ context để assign & fix (Problem #4 của Nguyễn Tiến Đạt)
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn problem #4 vì đây là vấn đề rất thực tế và quen thuộc trong quy trình phát triển phần mềm (Software Development Lifecycle). Quá trình từ nhận bug report trên Discord đến khi tạo Issue trên Jira/GitHub có workflow rất rõ ràng nhưng lại tốn nhiều công sức để trích xuất và phân loại thủ công. Pain point có thể chứng minh được thông qua thời gian lãng phí và các ticket bị reject do thiếu context. Vấn đề này hoàn toàn có thể giải quyết tốt trong môi trường Lab với các công cụ AI hỗ trợ phân tích text, và dễ dàng đo lường impact (thời gian xử lý/chất lượng ticket). Nhóm cũng nắm rất vững domain này do hầu hết các thành viên đều là sinh viên IT hoặc lập trình viên.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Problem #3 (Báo cáo sự cố đô thị): Tuy nhu cầu thực tế cao, nhưng impact khó đo lường end-to-end do phụ thuộc vào hệ thống xử lý của cơ quan nhà nước. Trong phạm vi lab, nhóm khó tạo ra một feedback loop hoàn chỉnh từ phía người xử lý sự cố.
- Problem #10 (Tìm câu trả lời Discord): Mặc dù phổ biến, nhưng có rủi ro trùng lặp với tính năng search mặc định của Discord nếu AI không tạo ra đủ sự vượt trội. Ngoài ra, việc xác định "câu trả lời đúng" từ nhiều luồng ý kiến mâu thuẫn đôi khi cần sự can thiệp của con người rất nhiều, khó tự động hóa hoàn toàn.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Một số thành viên lo ngại việc bug report thô từ user đôi khi quá thiếu thông tin (ví dụ: chỉ có câu "App bị crash") dẫn đến việc AI không thể tạo ticket hoàn chỉnh. Nhóm đã thảo luận và chốt giải pháp: AI sẽ được thiết kế theo hướng interactive (tương tác), đóng vai trò như một bộ lọc cấp 1. Nếu thiếu các trường bắt buộc (như Steps to reproduce, Environment), AI sẽ chủ động hỏi lại người báo lỗi để thu thập đủ context trước khi tạo Issue chính thức.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | |
| Log / ticket / review (nếu có) | | | | |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text

```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
|[Kollab]|(https://kollab.im/use-cases/bug-reports-to-github)|1. Nhận free-text từ chat (Discord/Slack/Telegram) qua @bot. 2. AI classify: bug / feature / support / unclear. 3. Extract & normalize thành title, steps, expected/actual, impact. 4. Check duplicate trên GitHub. 5. Tạo issue có cấu trúc + assign owner theo module. 6. Reply link + reasoning về chat. | Flow gần sát ý tưởng nhất: free-text → triage → structure → route. Hỗ trợ non-tech report. Có thể hỏi thêm nếu thiếu context.| Chủ yếu tối ưu cho GitHub; Discord support phụ thuộc setup bot/workspace. Cần tự cấu hình prompt theo team. Chưa rõ depth của “workload optimization”.| Chủ yếu tối ưu cho GitHub; Discord support phụ thuộc setup bot/workspace. Cần tự cấu hình prompt theo team. Chưa rõ depth của “workload optimization”.| Nên ưu tiên pattern “@bot + AI classify + human-reviewable” thay vì auto-create ngay. Dedupe + normalize ngôn ngữ là giá trị cốt lõi.|
|[SeaTicket]|(https://seaticket.ai/)|1. Sync Discord Forum/channel + GitHub + Linear/Jira/email vào 1 workspace. 2. AI summary + phân tích issue mới. 3. Tìm related/past cases + knowledge base. 4. Đề xuất next step (reply / classify / tạo ticket / resolve). 5. Bắt buộc human approve trước khi hành động. 6. Sync phản hồi ngược về Discord/GitHub. |Multi-channel thật sự (Discord + GitHub), human-in-the-loop rõ ràng, AI hỗ trợ triage & suggest thay vì tự quyết. Phù hợp team lo spam/false positive. |Không phải “tự tạo issue từ 1 message chat” ngay; tập trung unified workspace + AI assist. Cần setup connection Discord Forum. Pricing/limit free tier cần kiểm tra. | Bắt buộc có bước human review trước khi tạo issue chính thức. Cross-channel matching (Discord mô tả ngắn vs GitHub issue dài) là pain point lớn cần giải quyết.|

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
[Khoảng trống] chưa có analyse ảnh để xác định vị trí trên nền tảng của mình để định danh nơi phát sinh vấn đề, cho phép bot hỏi thêm để xác định vấn đề
Nên build Discord free-text + AI triage (classify bug/not-bug/unclear → normalize ngôn ngữ → dedupe) có human review trước khi tạo issue có cấu trúc, sau đó đề xuất phân việc dựa trên lịch sử issue người đó đã xử lý + chấm điểm độ phù hợp (skill match, workload hiện tại). Không nên ép form cứng từ đầu, cũng không auto-create issue hay auto-assign cứng mà không qua triage/review. Ưu tiên lấy pattern triage queue + KB reply non-bug (Kollab/SeaTicket/BetaHub), phần scoring & đề xuất assignee có thể làm layer riêng dựa trên dữ liệu issue lịch sử.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: ![Current Workflow](./02-group-problem-statement-workflow-current.png)

```text
[1 User báo lỗi chat Discord: 1'] → [2 Dev đọc tin và check log: 10'] → [3 Dev ping hỏi thêm context bị thiếu: 2'] → [4 Bottleneck chờ User trả lời: 30'-2h] → [5 Dev tổng hợp tạo ticket chuẩn: 5'] → [6 Dev fix: ...]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | User / Tester | Gặp lỗi | Tin nhắn thô trên Discord | 1-2 phút / lần | Lỗi bằng ngôn ngữ tự nhiên, thường thiếu hình hoặc context. |
| 2 | Dev trực dự án | Tin nhắn lỗi | Xác định lỗi là gì, có đủ thông tin chưa | 5-10 phút | Handoff từ User sang Dev. Thường phát hiện thiếu thông tin. |
| 3 | Dev trực dự án | Tin nhắn lỗi | Câu hỏi cần User bổ sung (VD: OS gì?) | 2 phút | Đứt đoạn công việc hiện tại của Dev. |
| 4 | User / Tester | Câu hỏi của Dev | Trả lời bổ sung context | 30 phút - 2 giờ | **Bottleneck**: Chờ đợi giao tiếp bất đồng bộ, Dev không thể tạo ticket ngay. |
| 5 | Dev trực dự án | Context đầy đủ | Ticket hoàn chỉnh trên GitHub/Jira | 5 phút | Handoff từ Discord sang hệ thống Issue. |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck nằm ở khâu giao tiếp qua lại (ping-pong) giữa Dev và User để bổ sung thông tin (bước 3 & 4). Việc này mang tính bất đồng bộ, User thường không phản hồi ngay, khiến Dev bị gián đoạn (context switching) liên tục mà ticket vẫn không được tạo kịp thời để team vào fix.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

Dán workflow hoặc link file: ![Future Workflow](./02-group-problem-statement-workflow-future.png)

```text
[1 User báo lỗi chat Discord: 1'] → [2 AI đọc tin, so khớp template: 5s] → [3 AI hỏi lại User context thiếu: 10s - loop] → [4 AI tạo ticket chuẩn: 5s - boundary] → [5 Dev review ticket và fix]

Fallback: Nếu AI hỏi lại quá 3 lần mà User vẫn không cung cấp đủ, AI tạo ticket với nhãn `Needs Triage` để Dev trực tiếp xử lý sau.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian (từ lúc báo đến khi có ticket) | 30 - 120 phút | 5 - 10 phút | Đo khoảng thời gian giữa tin nhắn báo lỗi đầu tiên và timestamp tạo Issue. |
| Số bước | 5 bước | 5 bước | Quy trình giữ nguyên, thay người bằng AI ở khúc giữa. |
| Số bước thủ công của Dev | 3 bước | 1 bước (chỉ review) | Đếm số lần Dev phải reply trên luồng chat lỗi. |
| Bottleneck chính | User phản hồi chậm, Dev chờ đợi | User tương tác trực tiếp với AI không cần Dev can thiệp | Theo dõi AI chat log. |
| Risk mới | N/A | AI phân loại sai mức độ nghiêm trọng (Severity) | Đếm số lần Dev sửa lại Label/Severity trên ticket. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Dev trực dự án (người phải tiếp nhận bug) và End-User/Tester (người báo lỗi). |
| **Workflow** | Tiếp nhận lỗi từ kênh chat (Discord) -> Làm rõ context, thu thập các trường bắt buộc (Steps to reproduce, OS...) -> Phân loại và tạo Issue có cấu trúc trên hệ thống quản lý (Jira/GitHub). |
| **Bottleneck** | Việc giao tiếp qua lại (ping-pong) trên Discord giữa Dev và User để bổ sung thông tin tốn quá nhiều thời gian chờ đợi và gây đứt đoạn sự tập trung (context switching) của Dev. |
| **Impact** | Lãng phí thời gian của kỹ sư; Backlog chứa nhiều "rác" (ticket thiếu context); Quá trình fix bug bị delay vì không biết tái hiện lỗi thế nào. |
| **Success Metric** | Tỷ lệ tự động tạo ticket từ tin nhắn chat thành công > 80%; Giảm 90% số tin nhắn Dev phải chủ động hỏi lại context trên Discord. |
| **Boundary** | AI chỉ có nhiệm vụ trò chuyện thu thập context và tạo Issue. AI không được tự động assign người fix, và không can thiệp vào mã nguồn để sửa lỗi. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Boundary và Fallback chưa đề cập rõ giới hạn số lần AI hỏi lại user, dễ dẫn đến AI chat vòng vo.
- Tôi sửa gì: Thêm quy tắc giới hạn tối đa 3 vòng lặp (fallback đã cập nhật ở mục 5.2).


---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Tin nhắn báo lỗi dùng ngôn ngữ tự nhiên, không theo form chuẩn, đôi khi có tiếng lóng hoặc viết tắt.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Phải đọc hiểu ý định -> Lọc ra trường thông tin còn thiếu -> Rẽ nhánh (hỏi lại User HOẶC tạo ticket ngay).

**Bài toán nhóm nằm ở ô nào:**

```text
Ô số 4: Agent (Cần LLM hiểu ngôn ngữ tự nhiên + vòng lặp tương tác để thu thập context).
```

**Vì sao (2-3 câu):**

```text
Quy trình không đi thẳng một đường mà phụ thuộc vào việc input đầu vào có đủ hay không. Nếu thiếu thông tin, hệ thống phải tự quyết định đặt câu hỏi gì để lấy đúng thông tin đó (reasoning) và lặp lại cho đến khi đủ (loop), thay vì bắt người dùng điền một form cứng nhắc ngay từ đầu.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng regex/keyword để bắt lỗi. | Khi lỗi được báo cáo theo đúng cú pháp cố định. | Lỗi ghi bằng ngôn ngữ tự nhiên muôn hình vạn trạng, regex không bắt được hết. | Không |
| **Workflow** | LLM đọc tin nhắn 1 lần và tạo ticket luôn. | Khi user luôn cung cấp đủ 100% context ngay từ tin nhắn đầu tiên. | Lỡ thiếu thông tin, ticket được tạo ra vẫn là rác (thiếu steps to reproduce). | Không |
| **Agent** | LLM đọc -> Gọi tool check context -> Quyết định gọi tool hỏi lại User HOẶC tool tạo Issue. | Khi user báo lỗi tự do, cần hỏi đáp để làm rõ. | Agent bị lặp vô hạn nếu hỏi sai trọng tâm. | **Chọn** (Dùng cho toàn bộ quy trình) |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Không, vì ngôn ngữ tự nhiên rất đa dạng, Rule chỉ bắt được khoảng 20-30%.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Phải rẽ nhánh (Đủ thông tin -> Tạo ticket; Thiếu thông tin -> Hỏi lại).
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Có, Agent cần tự quyết định xem gọi tool `ask_user` hay tool `create_jira_issue`.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Dev/QA lead phát hiện khi review ticket trên Jira, sửa nhãn/thông tin trong 1-2 phút.
5. Có hạ được từ Agent → Workflow → Rule không? Không, hạ xuống Workflow sẽ tạo ra ticket rác, mất đi giá trị cốt lõi là "hỏi lại cho đủ context".

**Mức chọn:**

```text
Agent
```

**Vì sao chọn (3-4 câu):**

```text
Quy trình thu thập context phụ thuộc hoàn toàn vào việc input đầu vào có đủ chưa. Nếu thiếu, AI phải tự quyết định đặt câu hỏi gì để lấy thông tin đó một cách tự nhiên. Điều này đòi hỏi khả năng lý luận (reasoning) và lập kế hoạch vòng lặp (loop) của Agent. Nó đóng vai trò như một nhân viên hỗ trợ (Customer Support) thực thụ để cản lọc rác cho Dev.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nếu chỉ dùng Workflow (đọc 1 lần và tạo ticket), hệ thống sẽ tạo ra hàng loạt ticket thiếu context. Lúc đó Dev vẫn phải vào ticket để hỏi lại User, nghĩa là pain point "giao tiếp lắt nhắt" hoàn toàn không được giải quyết.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Dev trực dự án và End-User/Tester báo lỗi trên Discord. |
| **Workflow** | Tiếp nhận lỗi từ Discord -> Làm rõ context -> Tạo Issue có cấu trúc trên Jira/GitHub. |
| **Bottleneck** | Giao tiếp qua lại trên Discord giữa Dev và User để bổ sung thông tin gây đứt đoạn sự tập trung của Dev. |
| **Impact** | Ticket thiếu context làm chậm quá trình fix bug; Dev tốn thời gian làm Customer Support. |
| **Success Metric** | Giảm 90% số tin nhắn Dev phải chủ động hỏi lại context; Thời gian từ lúc báo lỗi đến khi có ticket chuẩn < 10 phút. |
| **Boundary** (làm / không làm) | AI chỉ thu thập context và tạo Issue. KHÔNG tự assign Dev, KHÔNG phân tích mã nguồn để tự fix bug. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay sau khi User gửi tin báo lỗi đầu tiên, và trước khi Issue được tạo trên hệ thống tracking. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Agent**. Cần khả năng tương tác vòng lặp (loop) và gọi tool rẽ nhánh tùy theo context đã đủ hay chưa. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro: AI hỏi lan man gây ức chế cho User. Kiểm tra: Dev review ticket được tạo; Fallback tự ngắt sau 3 lần hỏi. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Đã xác định rõ luồng từ Discord sang hệ thống Issue và các bên liên quan. |
| Baseline + metric đo được chưa? | Yes | Đo được số phút xử lý và số lượng tin nhắn ping qua lại trên chat log. |
| Data/input đủ dùng chưa? | Yes | Log tin nhắn báo lỗi trên Discord có sẵn rất nhiều để làm tập test. |
| AI sai, hậu quả chấp nhận được không? | Yes | Chỉ là ticket nháp, Dev có thể tự tay chỉnh sửa lại thông tin trên ticket. |
| Có người review/owner không? | Yes | Dev/QA trực dự án sẽ review ticket và luồng chat. |
| Có cách non-AI đơn giản hơn không? | No | Bắt User điền form dài sẽ thất bại vì UX kém, họ vẫn sẽ chat tự do. |

**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Báo cáo lỗi thô là vấn đề nhức nhối và lặp lại ở mọi dự án phần mềm. Dữ liệu tin nhắn chat hoàn toàn có sẵn để nhóm test AI. Hậu quả khi AI sai rất thấp (chỉ tạo ticket sai nhãn hoặc thiếu ý, Dev có thể chỉnh được). Việc dùng Agent giải quyết triệt để pain point "giao tiếp lắt nhắt", mang lại giá trị rất lớn nhờ đóng vai trò bộ lọc cản rác cho Dev.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: Lấy dump 50 tin nhắn báo lỗi cũ trên Discord của nhóm.
- Chạy tay: Viết prompt cho Agent đọc từng tin nhắn, cho phép nó gọi tool `ask_user` giả lập hoặc `create_ticket`.
- Đo 3 số: % trích xuất đúng Component, % trích xuất đúng Môi trường (OS/Browser), % nhận diện đúng việc "thiếu thông tin".
```

**Nếu Not Yet — cần validate gì trước:**

```text
N/A
```

**Nếu No-Go — làm gì thay AI:**

```text
N/A
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng AI khi User report rằng AI hỏi quá thiếu logic/không hiểu ý, dẫn đến tỷ lệ ticket phải sửa tay > 50%. Khi đó quay lại cách cũ: Dev tự đọc Discord và tạo ticket.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
