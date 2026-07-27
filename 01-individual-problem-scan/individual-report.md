# Case: Bản tổng quan tài liệu - Literature review trước và sau AI

> My, sinh viên nghiên cứu tại Đại học Bách khoa tốn nhiều tuần để làm tổng quan tài liệu (Literature Review) và bước đầu phân tích dữ liệu nghiên cứu. Quy trình tìm, sàng lọc, tóm tắt, tổng hợp dữ liệu lặp lại; dễ sót nguồn quan trọng và khó kiểm soát độ chính xác.

## Phrase 1: Scan rộng

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Tìm paper và tài liệu nghiên cứu trên Google Scholar, Scopus, PubMed, repo từng nguồn rời rạc | Sinh viên nghiên cứu | Tốn nhiều ngày/tuần, phải dò lại nhiều lần |
| 2 | Lặp lại | Sàng lọc paper theo tiêu chí liên quan, phương pháp, dataset | Sinh viên nghiên cứu | Kết quả tìm được nhiều nhưng chưa chắc phù hợp, mất khoảng 2h/tuần |
| 3 | Tốn thời gian | Đọc full text, ghi chú phương pháp, dữ liệu, kết quả, trích dẫn | Sinh viên nghiên cứu, GV hướng dẫn | Mất 1-2 ngày cho từng bài báo |
| 4 | Tốn thời gian | Tổng hợp chủ đề, xây bảng so sánh, đặt lại câu hỏi nghiên cứu | Sinh viên nghiên cứu, GV hướng dẫn | Phải đọc lại nhiều lần, dễ sót nguồn/ý tưởng |
| 5 | Tốn thời gian | Phát hiện khoảng trống nghiên cứu trong các paper hiện có | Sinh viên nghiên cứu | Khoảng trống không rõ, trì hoãn đề cương nghiên cứu |
| 6 | AI có thể tốt hơn | Gợi ý phương pháp phân tích dữ liệu ban đầu, viết code thử, visual hóa kết quả | Sinh viên nghiên cứu | Thử code nhiều lần, mất thời gian debug |
| 7 | Pain từ người khác | Giảng viên hoặc đồng nghiên cứu phàn nàn bản nháp thiếu citations và grounded evidence | Sinh viên nghiên cứu | Nhiều lần phải sửa lại, kéo dài tiến độ |
| 8 | Rủi ro chất lượng | Dễ bịa nguồn, nhầm trích dẫn khi dùng LLM | Sinh viên nghiên cứu, GV hướng dẫn | Nhiều bản nháp phải kiểm tra, có nguy cơ sai lệch thông tin |

##Phrase 2: Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng quan literature review và gap research | Workflow rõ, lặp lại, tốn nhiều tuần, có metric thời gian và chất lượng | Cần làm rõ phần title: AI hỗ trợ tới đâu, researcher vẫn kiểm chứng |
| 2 | Phân tích dữ liệu ban đầu và gợi ý code | Có pain thật, AI có thể giúp giảm bước debug/trial-and-error | Độ chính xác code và interpret phụ thuộc dữ liệu vào tay người dùng |
| 3 | Sàng lọc và trích dẫn nguồn | Nhiều tài liệu rời rạc, dễ sót nguồn quan trọng | Cần kiểm soát rủi ro bịa nguồn, không chỉ là search query |

## Problem Card #1 — Tổng quan literature review

**Problem 1:**  
Nghiên cứu sinh mất nhiều tuần để đi từ nguồn tài liệu thô đến xây dựng literature review vì phải tìm, sàng lọc, tóm tắt và tổng hợp bằng tay, trong khi dễ sót nguồn quan trọng và khó kiểm soát độ chính xác thông tin.

**Actor:**  
Nghiên cứu sinh chịu trách nhiệm viết literature review, xây bảng so sánh, và phát hiện khoảng trống nghiên cứu.

**Thời điểm / bối cảnh:**  
Giai đoạn chuẩn bị đề cương, viết phần tổng quan tài liệu cho luận văn/đề tài nghiên cứu, hoặc làm bài tập lớn cần review nhiều bài báo.

**Current workflow:**

```text
1. Tìm bài báo và tài liệu trên Google Scholar, Scopus, PubMed, repo mã nguồn.
2. Đọc abstract/title, lọc paper theo tiêu chí relevance/phương pháp/dataset.
3. Đọc full text, ghi chú phương pháp, dữ liệu, kết quả, trích dẫn.
4. Tổng hợp nội dung theo chủ đề, so sánh phương pháp và kết quả.
5. Phát hiện khoảng trống nghiên cứu và viết các câu hỏi mở.
6. Bắt đầu phân tích dữ liệu ban đầu: chọn phương pháp, viết code thử, đọc kết quả.
7. Viết bản dự thảo literature review và checklist trích dẫn.
```

**Bottleneck:**  
Bước 3-5 — tóm tắt, tổng hợp và xây bảng so sánh gap research — tốn nhiều thời gian nhất và dễ tạo ra bản nháp thiếu nguồn hoặc thiếu insight.

**Impact:**  
Quy trình này thường kéo dài nhiều tuần cho một đề tài nghiên cứu. Nhiều nguồn quan trọng có thể bị bỏ sót; quality review chậm, tiến độ viết thuyết minh và phân tích dữ liệu ban đầu bị đẩy lùi.

**Success metric:**  
Giảm thời gian ra bản dự thảo đầu tiên từ nhiều tuần xuống còn ít hơn 50%; đạt ít nhất 80% độ chính xác thông tin/trích dẫn trong bản nháp đầu tiên; không tăng số nguồn bị sai hoặc thiếu trong review đầu.

**Non-AI alternative:**  
Checklist sàng lọc literature, mẫu bảng so sánh chủ đề, rubric đánh giá nguồn, và tham khảo review article. Những giải pháp này có thể giảm lặp lại, nhưng không giải quyết nhanh phần tổng hợp và gap discovery từ nhiều paper.

**AI hypothesis:**  
AI trợ lý giúp tìm và sàng lọc paper đúng tiêu chí, tóm tắt nội dung chính, xây bảng so sánh chủ đề và gap. Nghiên cứu viên vẫn kiểm chứng trích dẫn, soát thông tin, và quyết định cuối cùng.

**Quick gut:**  
Workflow — AI hỗ trợ các bước tóm tắt/tổng hợp và gợi ý, researcher giữ vai trò HITL để kiểm soát chất lượng.

### Draft current workflow

```text
CURRENT STATE — 2-3 tuần

[1 Tìm & lọc paper: 3-5 ngày]
→ [2 Đọc full text & ghi chú: 5-7 ngày]
→ [3 Tổng hợp & so sánh: 4-6 ngày]  <-- bottleneck
→ [4 Phát hiện gap research: 2-3 ngày]
→ [5 Viết draft review: 2-3 ngày]
→ [6 Phân tích dữ liệu ban đầu: 2-4 ngày]
```

### Draft future workflow

```text
FUTURE STATE — dưới 1 tuần

[1 Input nguồn & mục tiêu: 1 ngày]
→ [2 AI tóm tắt paper + so sánh chủ đề: 1-2 ngày]
→ [3 Researcher review + chỉnh sửa: 2-3 ngày]  <-- human boundary
→ [4 AI gợi ý code/interpretation ban đầu: 1 ngày]
→ [5 Researcher verify & hoàn thiện draft: 1-2 ngày]

Fallback: AI tóm tắt sai hoặc thiếu nguồn → Researcher tự tóm tắt lại bằng checklist.
```

## Problem Cards #2 và #3 — tóm tắt

| Card | Actor | Bottleneck | Metric | Quick gut | Vì sao chưa chọn làm #1 |
|---|---|---|---|---|---|
| Phân tích dữ liệu ban đầu | Nghiên cứu viên, SV | Viết code và debug nhiều lần để chuyển từ dữ liệu thô sang insight | 2-4 ngày → 1-2 ngày | workflow | Cần rõ dữ liệu đầu vào và scope xử lý, dễ trượt sang toolchain quá lớn |
| Sàng lọc & trích dẫn nguồn | Nghiên cứu viên | Dò lại nhiều nguồn, dễ bỏ sót citation khi dùng LLM | Nhiều tuần → ít hơn 1 tuần | Rule + workflow | Risk bịa nguồn lớn; cần HITL và boundary rõ |
