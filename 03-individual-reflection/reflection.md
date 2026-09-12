# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Phạm Minh Hiếu
- Mã học viên: 2A202602630
- Nhóm: 5changlinhngulam
- Candidate problem nhóm chọn: Học kỹ năng mới, chống quên

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự nghĩ ra bài toán "đọc báo khoa học", sau đó dùng lăng kính tìm thêm bài "Leo rank Valorant" và "Tìm đường". | Có một danh sách problem đa dạng (game, đời sống, học tập) để mang đi đối chiếu với nhóm. |
| Pitch Problem Card | Trình bày bài toán "Leo rank Valorant", đưa ra góc nhìn về nỗi đau của game thủ khi không tự phân tích được VOD. | Nhóm rất thích ý tưởng, nhưng nhận định việc xử lý Computer Vision hơi phức tạp trong giới hạn lab nên đã để lại làm ý tưởng backup. |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện cho bài "Học kỹ năng mới, chống quên": *Làm sao ép user vào làm quiz khi họ vốn đã lười?* | Giúp nhóm nhận ra rủi ro lớn nhất nằm ở tính kỷ luật, từ đó đưa vào phần Fallback và Human Boundary sau này. |
| Gom trùng / cluster | Nhận thấy bài "Học kỹ năng" của bạn trong nhóm và bài "Ôn thi" của tôi có chung mô típ chống quên kiến thức. | Đề xuất gom hai bài này thành một cluster "Spaced Repetition AI". |
| Chọn candidate problem | Đồng thuận vote cho bài "Học kỹ năng mới, chống quên" vì tính ứng dụng rất cao cho cả nhóm sinh viên. | Nhóm chốt được bài toán trọng tâm nhanh chóng và không bị sa đà cãi vã. |
| Validation / research | Đảm nhận chính phần 4.2 trong báo cáo nhóm (Research giải pháp đã có). Đã tìm hiểu Monic.ai, Anki, Khanmigo. | Đưa ra định hướng quan trọng: Nhóm KHÔNG NÊN code lại phần sinh quiz hay thuật toán chống quên, mà chỉ cần build "Agent điều phối". |
| Workflow nhóm | Cùng vẽ luồng Before/After cho bài Học kỹ năng. | Cùng nhóm bóc tách được bước "Học lại từ đầu (20 phút)" chính là Bottleneck lớn nhất cần loại bỏ. |
| Problem Statement | Góp ý viết chặt phần Success Metric. | Đổi từ "nhớ bài lâu hơn" thành con số cụ thể: "Tăng % kiến thức còn nhớ sau 1 tuần từ 30% lên 70%". |
| Rule / Workflow / Agent | Tham gia tranh luận về việc nên dừng ở Workflow hay lên Agent. | Chốt lên Agent vì giải pháp cần một "vòng lặp" (đọc kết quả quiz $\rightarrow$ đổi lịch ôn) chứ không phải đường thẳng. |
| Decision | Vote GO. | Đưa ra đề xuất pilot thử 2 tuần với 5 người học thật để kiểm chứng phần trăm ghi nhớ. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là ở phần 4.2 Research. Từ đó, tôi đã chốt được bài học cốt lõi cho nhóm: "Giá trị của Agent nằm ở khâu Điều phối (Orchestration) vòng lặp học, chứ không phải thuật toán sinh câu hỏi".
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các vấn đề dựa trên bối cảnh sinh viên thông qua 4 lăng kính. | Formulate lại problem rất gọn gàng, chuẩn cấu trúc "Actor - Workflow - Bottleneck". | Đưa ra vài problem hơi vĩ mô hoặc nằm ngoài tầm kiểm soát (ví dụ: tối ưu thủ tục hành chính phường). | Chủ động gạt bỏ các bài toán vĩ mô, tự tay chọn bài Valorant và Tìm đường vì nó có bottleneck cụ thể và thật nhất với tôi. |
| Problem Card | Chuyển ý tưởng thô thành Problem Card chuẩn, vẽ Draft Workflow cho top 3. | Phân bổ thời gian (phút) cho các bước rất hợp lý, làm nổi bật được bước nào là Bottleneck. | AI đôi khi quá "ảo tưởng" về sức mạnh của Agent, đề xuất giải quyết 100% không cần người duyệt. | Tự tay viết thêm phần **Fallback (Rủi ro)** rất thực tế. Ví dụ ở bài Tìm đường, tôi chốt lại là "AI báo sai thì tài xế vẫn phải nhìn biển thật". |
| Workflow | Không dùng | | | Tranh luận trực tiếp cùng nhóm để vẽ workflow. |
| Research | Quét và so sánh các công cụ học tập / spaced repetition hiện có trên thị trường. | Nhanh chóng chỉ ra điểm mạnh/yếu của các đối thủ lớn như Anki, Quizgecko, Khanmigo. | Đôi khi không chỉ ra được điểm khác biệt cốt lõi giữa hệ thống của nhóm (Learning Agent) với các tool tạo quiz thuần túy. | Tự đúc kết ra "Bài học cho nhóm" để ghi vào báo cáo, khẳng định điểm mạnh của Agent nhóm là tính điều phối thay vì bắt chước tính năng của tool khác. |
| Problem Statement | Không dùng | | | Cùng nhóm họp và gõ lại bằng tay, dựa vào logic thảo luận. |
| Rule / Workflow / Agent | Không dùng | | | Tự bám theo ma trận độ phù hợp trong lab để quyết định. |
| Decision | Không dùng | | | |

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
Trước khi vào lab, tôi luôn mang tâm lý "solution-first", muốn làm ra một con AI thật ngầu (như ý tưởng phân tích hình ảnh Valorant của tôi). Tuy nhiên, khi nghe top 3 problems của các bạn khác, tôi nhận ra một bài toán đơn giản bằng text như "Học kỹ năng, chống quên" nhưng đo lường được kết quả rõ ràng lại mang đến giá trị thực tế cao hơn rất nhiều. Việc phải so sánh liên tục Rule -> Workflow -> Agent giúp cả nhóm tỉnh táo hơn, nhận ra nhiều bước chỉ cần Rule là đủ, không cần lạm dụng Agent gây tốn kém. Dấu tay lớn nhất của tôi để lại là việc research kỹ các đối thủ ở phần 4.2, từ đó giúp nhóm không bị đi vào lối mòn "cố gắng code lại thuật toán" mà tập trung định hình con AI như một "Agent điều phối". Cuối cùng, điều khó nhất khi viết Problem Statement với nhóm tôi không phải là metric, mà là xác định rõ Human Boundary (để người dùng vẫn làm chủ việc học chứ không phó mặc hoàn toàn cho AI). Dù AI có thông minh đến đâu, nếu không có chốt chặn an toàn (fallback), sản phẩm đó không thể dùng được.
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
