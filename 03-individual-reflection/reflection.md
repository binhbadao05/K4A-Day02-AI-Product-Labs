# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Phú Bình 
- Mã học viên: 2A202602410
- Nhóm: 2M4W
- Candidate problem nhóm chọn: Phân loại và chuẩn hóa Bug Report từ Discord thành Issue có cấu trúc — trích xuất thông tin thô từ tin nhắn

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi liệt kê 8 vấn đề từ trải nghiệm học tập và dùng 4 lăng kính để lọc: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác. | Giúp nhóm có nhiều candidate ban đầu và giúp tôi chọn được 3 vấn đề mạnh nhất để pitch. |
| Pitch Problem Card | Tôi trình bày card “Tìm câu trả lời cũ trong Discord” và giải thích vì sao đây là vấn đề lặp lại, rõ actor và có bottleneck rõ. | Nhóm dễ đồng ý vì câu chuyện gần với thực tế học tập của mọi người. |
| Challenge bài của bạn khác | Tôi hỏi 2 câu nhấn mạnh vào scope và metric: “Vấn đề này có lặp lại hằng tuần không?” và “AI có thể hỗ trợ phần nào mà không thay người dùng?” | Giúp nhóm loại bỏ những bài quá rộng hoặc dễ giải bằng process fix. |
| Gom trùng / cluster | Tôi giúp nhóm nhóm các bài tương tự vào cluster “tìm thông tin cũ / thông tin phân tán”. | Tạo ra hướng hội tụ rõ ràng và hạn chế tình trạng chọn nhiều bài chồng chéo. |
| Chọn candidate problem | Tôi tham gia chấm điểm 3 bài và vạch ra lý do vì sao “tìm câu trả lời cũ trong Discord” là bài mạnh nhất. | Nhóm thống nhất chọn candidate problem đúng hướng, không chạy theo idea quá ngầu. |
| Validation / research | Tôi hỗ trợ rà soát xem bài toán có thật sự lặp lại và có cần AI không; không đi sâu vào số liệu ngoài nguồn đáng tin cậy. | Đảm bảo bài toán vẫn dựa trên pain thực và không bị solution-first. |
| Workflow nhóm | Tôi đóng góp vào việc vẽ workflow hiện tại và chia rõ bước nào là thông tin, bước nào là bottleneck, bước nào cần AI hỗ trợ. | Workflow nhóm trông rõ hơn và dễ chuyển sang Problem Statement sau này. |
| Problem Statement | Tôi góp ý về actor, bottleneck và boundary để tránh viết quá rộng. | Giúp mạch problem → workflow → impact → metric được chặt hơn. |
| Rule / Workflow / Agent | Tôi tham gia so sánh 3 mức: Rule, Workflow, Agent và đặt câu hỏi liệu bài toán có cần AI tự chủ hay chỉ cần hỗ trợ gợi ý. | Giúp nhóm không nhảy vào “Agent” quá sớm và chọn mức phù hợp hơn. |
| Decision | Tôi góp phần đánh giá Go / Not Yet / No-Go dựa trên evidence và rủi ro. | Chốt được quyết định hợp lý hơn là “muốn làm AI thì làm”. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người giúp nhóm tập trung vào bài toán “tìm lại câu trả lời cũ trong Discord”, đồng thời góp ý chặt chẽ ở phần scope, bottleneck và mức độ phù hợp với AI. Dấu tay của tôi nằm ở việc giữ bài toán không quá rộng, có actor rõ và có workflow dễ đo lường.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi hỏi AI gợi ý thêm lỗi theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác. | AI giúp mở rộng danh sách problem và kiểm tra xem mình có bỏ sót góc nhìn nào. | AI có xu hướng đề xuất các ý quá rộng hoặc chance-based, không phải pain thật. | Tôi giữ lại những ý gần với trải nghiệm thực và bỏ những ý quá chung như “trợ lý AI toàn năng”. |
| Problem Card | Tôi dùng AI để phản biện card của mình, hỏi xem actor, workflow, bottleneck và metric có đủ chặt không. | AI giúp phát hiện lỗ hổng trong cách mô tả và dấu hiệu cần chỉnh. | AI không thể biết trải nghiệm thật của tôi nên không thể tự xác định pain có đáng giải quyết không. | Tôi chỉnh lại scope, làm rõ actor và bottleneck bằng suy nghĩ của bản thân. |
| Workflow | Tôi dùng AI để gợi ý cách viết workflow theo dạng before/after rõ hơn. | AI giúp sắp xếp logic của workflow và làm nó dễ đọc hơn. | AI có thể đặt quá nhiều step hoặc mô tả trừu tượng, không phản ánh thực tế. | Tôi tự sửa lại từng bước để giữ đúng thực tế và rõ bottleneck. |
| Research | Tôi không dùng AI để đưa số liệu mà chỉ dùng để tìm hướng nghiên cứu và nguồn tham khảo. | AI giúp gợi ý từ khóa và ví dụ công cụ tương tự. | AI dễ đưa ra nguồn không chắc chắn hoặc số liệu không có kiểm chứng. | Tôi chỉ giữ những thông tin có link rõ ràng và kiểm tra lại tính hợp lý. |
| Problem Statement | Tôi dùng AI để hỏi “field nào còn mơ hồ?” và “metric đã đo được chưa?”. | AI giúp phát hiện điểm mơ hồ trong vấn đề và boundary. | AI không thể đánh giá toàn bộ ngữ cảnh nhóm nên dễ viết lại theo kiểu generic. | Tôi tự định nghĩa actor, workflow và boundary theo đúng bài toán của chúng tôi. |
| Rule / Workflow / Agent | Tôi dùng AI để hỏi xem bài toán này thuộc loại nào: Rule, Workflow hay Agent. | AI giúp đặt các câu hỏi chốt và khung so sánh. | AI có thể “quyết định thay mình” nếu không có người thật kiểm tra. | Tôi giữ quyết định cuối dựa trên logic và rủi ro trong nhóm. |
| Decision | Tôi không để AI quyết định thay mình; chỉ dùng AI để kiểm tra logic. | AI giúp nhìn lại vì sao cần Go / Not Yet / No-Go. | AI dễ khiến nhóm sa vào “muốn làm AI” hơn là “nên làm gì”. | Tôi tự đánh giá dựa trên rủi ro, evidence và khả năng kiểm soát của con người. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe các top 3 problems của bạn khác, tôi nhận ra một điều quan trọng: nhiều bài toán đều có “pain” thật, nhưng không phải bài nào cũng đủ chặt để làm AI. Một số bài gợi ý rất hay nhưng quá rộng hoặc bị giải quyết bằng process fix, nên chúng không phải là vấn đề AI cần can thiệp. Qua quá trình bị challenge, tôi đổi ý về cách chọn problem: thay vì chọn bài “đẹp” hay “AI-friendly”, tôi ưu tiên bài có actor rõ, workflow dễ vẽ, bottleneck rõ và có thể đo được. Tôi nghĩ nhóm có lúc hơi bị solution-first ở giai đoạn đầu, khi ai cũng nghĩ đến AI ngay, nhưng sau khi thảo luận lại, chúng tôi hiểu rằng không phải vấn đề nào cũng phải dùng Agent. Dấu tay của tôi trong artifact cuối là giữ scope của bài toán đúng mức, sửa lại phần bottleneck và nhấn mạnh boundary để không cho bài quá rộng. Điều khó nhất là viết Problem Statement vì metric và boundary dễ bị mơ hồ hơn mình tưởng; nếu không làm chặt, bài toán sẽ trở thành một câu chuyện chung chung. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở chỗ “đây có thực sự là problem hay chỉ là công việc cần tổ chức lại?”, và sẽ ép đúng hơn về metric trước khi nói đến AI.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

