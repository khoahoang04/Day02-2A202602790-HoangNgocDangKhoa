# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Hoàng Ngọc Đăng Khoa
- Mã học viên: 2A202602790
- Nhóm: gì cũng được (Thái Anh, Quang Minh, Doãn Ngọc, Đăng Khoa)
- Candidate problem nhóm chọn: Giải mã công thức toán học và thuật toán phức tạp trong paper kỹ thuật dài phục vụ nghiên cứu & đồ án tốt nghiệp AI

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ 4 lăng kính (Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác), xoay quanh bối cảnh SV năm cuối vừa làm đồ án PTIT vừa học AI tại VinUni | Nhóm có thêm 3 candidates (#10 báo cáo đồ án, #11 file lab loãng thông tin, #12 lên lịch commuter) để so sánh với candidates của các bạn |
| Pitch Problem Card | Pitch Card #10 — Báo cáo tiến độ đồ án cho GVHD: trình bày workflow 7 bước, bottleneck viết narrative 30 phút, metric 60-90 phút/tuần, dẫn số liệu ASEE | Card #10 được nhóm đưa vào shortlist (xếp thứ 2/3 với 32 điểm), chỉ thua Candidate #4 của Quang Minh |
| Challenge bài của bạn khác | Hỏi Quang Minh: "Nếu AI giải thích sai chiều tensor thì sinh viên có đủ nền tảng để phát hiện không? Có nên thêm bước Dimension Check tự động?" | Nhóm bổ sung Human Boundary rõ hơn: bắt buộc người dùng đối chiếu tensor shape trước khi chốt note, thêm link nhảy về trang gốc |
| Gom trùng / cluster | Đề xuất gom Card #10 (báo cáo đồ án) và Card #1 (data contract lab) vào cụm B "Lập trình, Đồ án & Báo cáo GVHD" vì cùng xoay quanh output đồ án năm cuối | Nhóm thống nhất 4 cluster rõ ràng, dễ loại bỏ cụm D (sinh hoạt cá nhân) ngay từ đầu |
| Chọn candidate problem | Ủng hộ Candidate #4 sau khi nhận ra Card #10 của mình có thể giải quyết 70% bằng template (Non-AI), còn bài toán paper math thì không thể giải bằng template | Nhóm đồng thuận chọn Candidate #4, không có phiếu phản đối |
| Validation / research | Hỏi 2 bạn cùng trọ (cùng làm đồ án AI) về trải nghiệm đọc paper: cả 2 xác nhận phần công thức là khâu ngốn thời gian nhất. Tìm thêm tool SciSpace để so sánh | Góp 2 mẫu interview vào bảng validation; SciSpace trở thành benchmark đối chiếu trong bảng research |
| Workflow nhóm | Góp ý về Human Boundary: đề xuất bước "nhấp vào Symbol để nhảy thẳng đến trang gốc" làm cơ chế fallback khi AI sai | Fallback này được đưa vào workflow cuối cùng của nhóm, giải quyết nỗi lo hallucination |
| Problem Statement | Viết bản nháp PS v0 và v1, chuẩn hóa các field Actor/Workflow/Bottleneck/Impact/Boundary cho nhất quán | PS v1 hoàn chỉnh 9 field, được cả nhóm duyệt không cần chỉnh lại lớn |
| Rule / Workflow / Agent | Lập luận tại sao Rule đơn thuần chỉ giải được ~30% (OCR/LaTeX), cần Workflow để xử lý phần ngữ nghĩa mà regex không bao quát | Nhóm chốt Workflow kết hợp Rule, loại Agent ngay từ đầu |
| Decision | Soạn phần Exit/Rollback: nếu AI sai >15% ký hiệu trong 3 paper pilot thì dừng, quay về Mathpix + bảng chú giải thủ công trên Notion | Nhóm có tiêu chí dừng rõ ràng, không bị mắc kẹt nếu pilot thất bại |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người soạn Problem Statement v0/v1 và viết phần Exit/Rollback criteria. Ngoài ra tôi đề xuất cơ chế fallback "nhấp Symbol nhảy về trang gốc" — ý tưởng này xuất phát từ chính trải nghiệm đọc paper của tôi khi làm đồ án: mỗi lần gặp biến lạ phải Ctrl+F lật ngược PDF rất mất flow.
```
---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI: "Với bối cảnh SV năm cuối SWE vừa làm đồ án vừa học AI, liệt kê pain points hàng tuần" | Gợi ý thêm 3 ý tôi chưa nghĩ tới: meeting notes thiếu action items, parse feedback thầy, ghi chú bài giảng | Gợi ý "quản lý tài chính" và "networking industry" — không phải workflow lặp lại, không đo được | Bỏ 2 ý chung chung, chỉ giữ 3 ý khớp với trải nghiệm thật hàng tuần |
| Problem Card | Nhờ AI phản biện Card #1 (báo cáo đồ án): "Metric này có đủ chặt không?" | AI chỉ ra metric "số câu thầy hỏi lại" phụ thuộc style thầy, gợi ý thêm "% draft AI được giữ nguyên" | AI đề xuất làm Agent tự gửi report — quá rộng, không cần thiết | Hạ về Workflow, thêm metric phụ "SV giữ ≥60% draft" |
| Workflow | Nhờ AI chuyển mô tả workflow thành format ASCII rõ ràng hơn | Xuất bản nháp current/future state nhanh, format gọn gàng | AI gộp bước "viết narrative" và "review" thành 1 bước duy nhất | Tách lại vì bottleneck nằm riêng ở bước viết narrative, review là human boundary |
| Research | Tìm data về thời gian SV dành cho documentation đồ án, reading paper | Tìm được số liệu ASEE (25-35% effort cho reporting), Tenopir et al. (35-48 phút/paper) | Có vài claim "tiết kiệm 80% thời gian" không có nguồn cụ thể | Chỉ giữ số liệu có link gốc kiểm chứng được (ASEE, NCES, Inside Higher Ed) |
| Problem Statement | Nhờ AI phản biện PS v0: "Field nào mơ hồ nhất?" | AI phát hiện Success Metric "hiểu đúng thuật toán" là định tính, khó đo | AI gợi ý thêm quá nhiều field mới (stakeholder map, risk matrix) — không cần thiết cho scope lab | Giữ 9 field theo template, chỉ sửa metric thành định lượng: thời gian + tỷ lệ trích xuất đúng tensor |
| Rule / Workflow / Agent | Nhờ AI so sánh ưu nhược điểm Rule vs Workflow vs Agent cho bài toán paper | AI phân tích rõ tại sao Agent rủi ro (infinite loop, chi phí API cao) | AI ban đầu thiên về Agent "cho ngầu" — gợi ý hệ thống tự clone repo GitHub chạy benchmark | Kéo về Workflow, viết rõ 5 câu hỏi chốt chứng minh không cần Agent |
| Decision | Nhờ AI gợi ý tiêu chí exit/rollback | AI đưa ra ngưỡng "nếu sai >20% thì dừng" | Ngưỡng 20% quá cao cho bài toán toán học (sai 1 ký hiệu = sai cả thuật toán) | Hạ ngưỡng xuống 15% và thêm điều kiện: nếu kiểm tra lại lỗi AI mất >45 phút thì cũng dừng |

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
Khi nghe top 3 của Quang Minh, tôi bất ngờ vì bài toán đọc paper nghe quen thuộc nhưng khi Minh trình bày con số 2-3 tiếng chỉ cho phần toán thì tôi mới nhận ra mình cũng mất chừng đó thời gian mà chưa bao giờ đo đếm. Bài toán chấm bài tự luận của Doãn Ngọc cũng mở mắt tôi — workflow sư phạm có cấu trúc rất chặt, nếu cả nhóm cùng hiểu domain giáo dục thì chắc chắn đã chọn bài đó. Lúc đầu tôi khá tự tin vào Card #10 (báo cáo đồ án), nhưng khi Thái Anh challenge "template có giải được 70% không" thì tôi phải thừa nhận là đúng — template cố định kết hợp GitHub summary đã xử lý được phần format, chỉ còn phần narrative là cần AI. Còn bài toán paper math thì template không giúp gì được, nên tôi chấp nhận hội tụ về Candidate #4 của Minh.

Nhóm có một lúc suýt bị solution-first. Quang Minh hào hứng đề xuất làm Agent tự động clone repo GitHub và chạy code kiểm chứng toán. Nghe rất ngầu nhưng Thái Anh kéo lại ngay: "Agent tự chạy code lạ trên máy mình thì ai chịu trách nhiệm nếu nó xóa file?" Câu đó giúp cả nhóm tỉnh lại. Sau đó nhóm đi qua 5 câu hỏi chốt, câu "Rule có giải được 70-80% không" buộc mọi người phải suy nghĩ thật kỹ trước khi leo thang lên Agent.

Phần khó nhất khi viết Problem Statement là metric. Ban đầu tôi viết "sinh viên hiểu đúng thuật toán hơn" — nghe hợp lý nhưng không ai biết đo thế nào. AI cũng chỉ ra điểm này. Cuối cùng tôi phải chuyển sang metric cứng: thời gian giảm từ 165 phút xuống dưới 35 phút, tỷ lệ trích xuất đúng ký hiệu >95%. Boundary cũng khó nhưng theo hướng khác — phải nói rõ "không nhận paper toán thuần túy" vì nhóm biết AI hiện tại chưa thể giải thích tiên đề Measure Theory hay Functional Analysis.

Nếu làm lại, tôi sẽ challenge mạnh hơn ở phần validation. Nhóm chỉ interview 3 bạn và survey 12 bạn, mẫu còn nhỏ. Tôi cũng muốn tự bấm giờ đọc 1 paper từ đầu đến cuối thay vì chỉ ước lượng, để có baseline cá nhân chính xác hơn.
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
