# 03 — Individual Reflection (Bản nhìn lại cá nhân)

> **Lưu ý:** Đây là file ghi nhận quá trình đóng góp của cá nhân trong lab và cách bản thân đã sử dụng AI. Dữ liệu được ghi trung thực dựa trên trải nghiệm thực tế.

## 1. Tôi đã tham gia vào phần nào trong nhóm?

Dù bài được nhóm chọn cuối cùng không phải là bài "Leo rank Valorant" của tôi, nhưng tôi đã có nhiều đóng góp xuyên suốt các phase làm việc nhóm:

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng đối với nhóm |
|---|---|---|
| **Scan cá nhân** | Tự nghĩ ra bài toán "đọc báo khoa học", sau đó dùng lăng kính để tìm thêm bài "Leo rank Valorant" và "Tìm đường tránh phạt nguội". | Có một danh sách problem đa dạng (game, đời sống, học tập) để mang đi đối chiếu với nhóm. |
| **Pitch Problem Card** | Trình bày bài toán "Leo rank Valorant", đưa ra góc nhìn về nỗi đau của game thủ khi không tự phân tích được VOD. | Nhóm rất thích ý tưởng, nhưng nhận định việc xử lý Computer Vision hơi phức tạp trong giới hạn lab nên đã để lại làm ý tưởng backup. |
| **Challenge bài của bạn khác** | Đặt câu hỏi phản biện cho bài "Học kỹ năng mới, chống quên": *Làm sao ép user vào làm quiz khi họ vốn đã lười?* | Giúp nhóm nhận ra rủi ro lớn nhất nằm ở tính kỷ luật, từ đó đưa vào phần Fallback và Human Boundary sau này. |
| **Gom trùng / cluster** | Nhận thấy bài "Học kỹ năng" của bạn trong nhóm và bài "Ôn thi" của tôi có chung mô típ chống quên kiến thức. | Đề xuất gom hai bài này thành một cluster "Spaced Repetition AI". |
| **Chọn candidate problem** | Đồng thuận vote cho bài "Học kỹ năng mới, chống quên" vì tính ứng dụng rất cao cho cả nhóm sinh viên. | Nhóm chốt được bài toán trọng tâm nhanh chóng và không bị sa đà cãi vã. |
| **Validation / research** | **Đảm nhận chính phần 4.2 trong báo cáo nhóm** (Research giải pháp đã có). Đã tìm hiểu Monic.ai, Anki, Khanmigo. | Đưa ra định hướng quan trọng: Nhóm KHÔNG NÊN code lại phần sinh quiz hay thuật toán chống quên, mà chỉ cần build "Agent điều phối". |
| **Workflow nhóm** | Cùng vẽ luồng Before/After cho bài Học kỹ năng. | Cùng nhóm bóc tách được bước "Học lại từ đầu (20 phút)" chính là Bottleneck lớn nhất cần loại bỏ. |
| **Problem Statement** | Góp ý viết chặt phần Success Metric. | Đổi từ "nhớ bài lâu hơn" thành con số cụ thể: "Tăng % kiến thức còn nhớ sau 1 tuần từ 30% lên 70%". |
| **Rule / Workflow / Agent** | Tham gia tranh luận về việc nên dừng ở Workflow hay lên Agent. | Chốt lên Agent vì giải pháp cần một "vòng lặp" (đọc kết quả quiz $\rightarrow$ đổi lịch ôn) chứ không phải đường thẳng. |
| **Decision** | Vote GO. | Đưa ra đề xuất pilot thử 2 tuần với 5 người học thật để kiểm chứng phần trăm ghi nhớ. |

---

## 2. Bảng dùng AI trong quá trình làm Lab

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Phase 1: Scan Problem** | Gợi ý thêm các vấn đề dựa trên bối cảnh sinh viên thông qua 4 lăng kính (Lặp lại, Tốn thời gian...). | Formulate lại problem rất gọn gàng, chuẩn cấu trúc "Actor - Workflow - Bottleneck". | Đưa ra vài problem hơi vĩ mô hoặc nằm ngoài tầm kiểm soát (ví dụ: tối ưu thủ tục hành chính phường). | Chủ động gạt bỏ các bài toán vĩ mô, tự tay chọn bài Valorant và Tìm đường vì nó có bottleneck cụ thể và thật nhất với tôi. |
| **Phase 2: Problem Card & Workflow** | Chuyển ý tưởng thô thành Problem Card chuẩn, vẽ Draft Workflow (Before/After) cho top 3. | Phân bổ thời gian (phút) cho các bước rất hợp lý, làm nổi bật được bước nào là Bottleneck. | AI đôi khi quá "ảo tưởng" về sức mạnh của Agent, đề xuất giải quyết 100% không cần người duyệt. | Tự tay viết thêm phần **Fallback (Rủi ro)** rất thực tế. Ví dụ ở bài Tìm đường, tôi chốt lại là "AI báo sai thì tài xế vẫn phải nhìn biển thật". |
| **Phase 4.2: Research (Làm cho nhóm)** | Dùng AI để quét và so sánh các công cụ học tập / spaced repetition hiện có trên thị trường. | Nhanh chóng chỉ ra điểm mạnh/yếu của các đối thủ lớn như Anki, Quizgecko, Khanmigo. | Đôi khi không chỉ ra được điểm khác biệt cốt lõi giữa hệ thống của nhóm (Learning Agent) với các tool tạo quiz thuần túy. | Tự đúc kết ra "Bài học cho nhóm": Điểm ăn tiền của Agent nhóm mình nằm ở tính **Orchestration (Điều phối)** vòng lặp học, chứ không phải thuật toán sinh câu hỏi. |

## 3. Bài học rút ra sau Lab

1. **Problem first, not AI first:** Trước khi vào lab, tôi luôn nghĩ phải làm ra một con AI thật ngầu (như con phân tích hình ảnh Valorant). Nhưng qua quá trình làm nhóm, tôi nhận ra giải quyết một bài toán đơn giản bằng text như "Học kỹ năng, chống quên" nhưng đo lường được kết quả rõ ràng lại mang đến giá trị thực tế cao hơn rất nhiều.
2. **Không phải cứ AI là Agent:** Ở Phase 6, việc ép bản thân phải so sánh Rule $\rightarrow$ Workflow $\rightarrow$ Agent giúp tôi tỉnh táo hơn, nhận ra nhiều bước chỉ cần Rule (đặt lịch cố định) là đủ, không cần lạm dụng Agent gây tốn kém và rủi ro cao.
3. **Giá trị của "Human Boundary" và "Fallback":** Dù AI có thông minh đến đâu, nếu không có chốt chặn an toàn (người dùng tự quyết định hướng đi tiếp theo, tài xế tự nhìn biển báo), thì sản phẩm đó không thể dùng thực tế được.
