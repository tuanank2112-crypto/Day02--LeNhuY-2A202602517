# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Như Ý
- Mã học viên: 2A202602517
- Nhóm: Người cao tuổi
- Candidate problem nhóm chọn: Khó khăn khi thực hiện thủ tục hành chính công trực tuyến của người lớn tuổi.
---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi tự scan và đưa ra các problems như trong `individual-report.md`: tìm API miễn phí, chẩn đoán lỗi cấu hình API bên thứ ba, đánh giá máy tính cũ. | Tạo được bộ 3 problem cards rõ workflow, bottleneck, impact và metric, giúp nhóm có lựa chọn đa dạng. |
| Pitch Problem Card | Tôi pitch Card 2 về chẩn đoán lỗi cấu hình API và hệ điều hành. Nhóm nhận xét bài ổn nhưng chưa đủ sức thuyết phục vì baseline còn chủ yếu ở trải nghiệm cá nhân. | Nhóm thấy workflow cụ thể nhưng cuối cùng không chọn vì thiếu bằng chứng phổ biến và tính ứng dụng chưa phù hợp bài toán nhóm. |
| Challenge bài của bạn khác | Tôi challenge các bạn về tính thực tế, tính lặp lại và khả năng đo của problem. | Các bài được thu hẹp lại theo actor, workflow và metric, thay vì chỉ nói “AI có thể giúp”. |
| Gom trùng / cluster | Tôi góp ý gom các ý theo đặc điểm chung của người dùng và rào cản thao tác số. | Giúp nhóm thấy bài “người lớn tuổi khó dùng dịch vụ số” liên quan tới interface, hướng dẫn và thói quen. |
| Chọn candidate problem | Tôi ưu tiên các lựa chọn có tính ứng dụng thực tế cao và dữ liệu dễ kiểm chứng. | Nhóm chọn problem rào cản tiếp cận dịch vụ số của người lớn tuổi vì có dữ liệu khảo sát HUST 2021 và nhu cầu xã hội rõ. |
| Validation / research | Người khác trong nhóm chịu chính vì candidate này theo ý kiến của bạn đó; tôi theo dõi và tham gia chốt lại ý nghĩa số liệu. | Tôi hiểu rằng ba tỷ lệ là multi-select, không cộng thành 100%, và nhóm cần tách problem khỏi solution. |
| Workflow nhóm | Tôi góp ý xây dựng tool và áp dụng vào tình huống thực tế thay vì làm một hệ thống quá rộng. | Workflow hướng tới voice-based AI agent cho 1–2 dịch vụ cụ thể, có xác nhận từng bước và fallback người thật. |
| Problem Statement | Tôi nhấn mạnh actor, bottleneck và boundary để bài không dừng ở “người già khó dùng app”. | Problem Statement tập trung vào thiếu thói quen, giao diện phức tạp và thiếu hướng dẫn cụ thể. |
| Rule / Workflow / Agent | Tôi góp ý chọn rule kỹ thuật phù hợp với từng bước của quy trình. | Nhóm cân nhắc dùng AI cho hội thoại/hướng dẫn nhưng giữ human boundary cho các bước quan trọng. |
| Decision | Tôi ưu tiên lựa chọn có tính ứng dụng cao và có thể pilot được. | Bài nhóm đi theo hướng pilot cụ thể thay vì dừng ở ý tưởng tổng quát. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là scan cá nhân, pitch Card 2 về chẩn đoán cấu hình API, challenge các bài theo tính thực tế và đóng góp ưu tiên giải pháp có ứng dụng cao.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI phản biện và cấu trúc problem cards. | AI gợi ý cách chia problem, workflow, bottleneck và metric. | AI dễ đưa ý quá rộng hoặc chưa gắn với trải nghiệm thật. | Tôi chỉ giữ các problem mình từng gặp và bổ sung actor, số liệu, workflow. |
| Problem Card | Dùng AI để hoàn thiện field cho Card 2 về cấu hình API và hệ điều hành. | AI giúp mô tả bottleneck rõ hơn và đặt câu hỏi kiểm chứng. | Card chưa đủ thuyết phục vì thiếu bằng chứng từ nhiều người. | Tôi thừa nhận điểm yếu này và để nhóm chọn bài có dữ liệu xã hội rõ hơn. |
| Workflow | Dùng AI gom bước trước/sau và đề xuất human boundary. | AI giúp thấy điểm nghẽn và chỗ cần người thật kiểm tra. | AI có thể vẽ workflow đẹp nhưng thiếu tình huống thực tế. | Tôi điều chỉnh theo tình huống sử dụng cụ thể. |
| Research | Dùng AI hỗ trợ phân tích cách trình bày số liệu HUST và giải pháp voice. | AI hiểu ngữ cảnh tốt khi tôi mô tả đúng yêu cầu và ràng buộc. | AI không thay thế được bằng chứng từ người dùng thật. | Tôi ghi rõ multi-select và tách problem khỏi solution. |
| Problem Statement | Dùng AI phản biện các field còn mơ hồ. | AI nhắc cần làm rõ actor, workflow, metric, boundary. | AI dễ nhảy sang giải pháp voice agent quá sớm. | Tôi giữ mạch problem trước, solution sau. |
| Rule / Workflow / Agent | Dùng AI so sánh mức phù hợp và rule kỹ thuật. | AI giúp phân biệt bước máy, bước AI, bước người. | AI có xu hướng đề xuất Agent phức tạp hơn cần thiết. | Tôi ưu tiên rule rõ ràng cho bước đơn giản và human boundary cho bước quan trọng. |
| Decision | Dùng AI kiểm tra logic pilot và risk. | AI gợi ý metric và fallback hợp lý. | Quyết định cuối vẫn cần dữ liệu nhóm và nhu cầu thật. | Tôi chọn hướng ứng dụng thực tế và khả năng pilot cao. |

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
Nhóm có nhiều bài đúng technical nhưng tôi học được rằng problem càng phổ biến và có bằng chứng xã hội thì càng dễ thuyết phục. Bài về người lớn tuổi khiến tôi chuyển từ góc nhìn kỹ thuật sang góc nhìn người dùng và rào cản thực tế.

Điểm khó nhất là tách problem khỏi solution: dữ liệu cho thấy người lớn tuổi khó dùng dịch vụ số, nhưng không chứng minh ngay voice-based AI agent là giải pháp đúng. Vì vậy nhóm phải tách bottleneck thành thiếu thói quen, giao diện phức tạp và thiếu hướng dẫn, rồi pilot từng phần.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở bước chọn problem: yêu cầu mỗi candidate đều có actor, workflow, bằng chứng và metric trước khi vote. Tôi cũng sẽ hỏi sớm hơn: “Giải pháp này người dùng có thật sự muốn dùng không, và bước nào cần người thật xác nhận?”. Điều tôi mang đi là tinh thần đồng đội, lắng nghe ý kiến bạn khác, ưu tiên ứng dụng thực tế và không để AI thay tư duy quyết định của nhóm.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

