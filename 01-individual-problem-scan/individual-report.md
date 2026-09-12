# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lê Như Ý
- Mã học viên: 2A202602517
- Vai trò / bối cảnh: Sinh viên, thường làm dự án coding cá nhân và thử nghiệm công cụ AI/API.
- Công việc hằng tuần:
  - Tìm và thử nghiệm API miễn phí cho coding và TTS.
  - Cấu hình công cụ coding như Antigravity và Codex với API bên thứ ba.
  - Nghiên cứu cấu hình máy tính cũ trước khi mua.
  - Học và làm bài tập liên quan đến AI workflow.

---

## Phase 1 — Scan 5+ problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại / Tốn thời gian | Phải dừng coding để tìm API miễn phí cho coding hoặc TTS trên nhiều nguồn khác nhau | Sinh viên có tài chính hạn chế | Xảy ra trên 10 lần/tháng; mỗi lần từ 5–10 phút, có trường hợp kéo dài vài ngày |
| 2 | AI có thể tốt hơn | Khó đánh giá API miễn phí nào đủ ổn định, có limit rõ ràng và còn hoạt động lâu dài | Sinh viên dùng API cho dự án cá nhân | API tìm được không phải lúc nào ổn định; nguồn tổng hợp dễ lỗi thời |
| 3 | Lặp lại / Tốn thời gian | Gặp lỗi cấu hình API bên thứ ba trong Antigravity hoặc Codex | Người dùng Antigravity và Codex | Xảy ra trên 5 lần/tháng; thời gian sửa từ 5 phút đến 1 tuần |
| 4 | AI có thể tốt hơn | Khó phân biệt lỗi DNS, authentication, endpoint sai và model routing khi gọi API bên thứ ba | Người dùng công cụ coding | Lỗi khiến công việc coding dừng hoàn toàn; có tài liệu lỗi cũ trên cloud để đối chiếu |
| 5 | Pain từ người khác | Gọi nhầm API gốc thay vì endpoint của nhà cung cấp bên thứ ba | Người dùng cấu hình API | Là một trong các lỗi cấu hình lặp lại trên 5 lần/tháng |
| 6 | Pain từ người khác | Cấu hình chứa API key nên khó chia sẻ để nhờ hỗ trợ chẩn đoán | Người dùng và người hỗ trợ kỹ thuật | Rủi ro lộ thông tin nhạy cảm khi paste log/config |
| 7 | Tốn thời gian / Pain từ người khác | Phải nghiên cứu nhiều mã CPU, GPU, RAM khi cân nhắc mua máy cũ | Sinh viên có ngân sách hạn chế | Quá trình nghiên cứu có thể kéo dài vài ngày |
| 8 | AI có thể tốt hơn | Không biết kiểm tra lỗi máy cũ nào tại cửa hàng và không có checklist chuẩn | Sinh viên mua máy cũ lần đầu | Quyết định sai gây thiệt hại tài chính lớn; thao tác kiểm tra cần làm trực tiếp |

**AI đã dùng ở Phase 1:**

- Prompt đã hỏi: Xây dựng 3 Problem Cards từ các vấn đề cá nhân, kèm điểm mạnh và challenge.
- Ý dùng được: Workflow cụ thể, tần suất, impact, metric có thể đo và các câu hỏi kiểm chứng rủi ro.
- Ý bỏ vì không phải pain thật: Các giải pháp quá rộng kiểu “tạo API marketplace” khi vấn đề cốt lõi chưa được xác nhận là tìm API hay đánh giá API.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu “mất nhiều thời gian”

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Chẩn đoán lỗi cấu hình API bên thứ ba | Workflow và lỗi cụ thể, hậu quả làm dừng coding, có tài liệu lỗi cũ để nghiên cứu | Khả năng chuẩn hóa các loại lỗi khác nhau và bảo vệ API key |
| 2 | Tìm API miễn phí và ổn định | Tần suất cao, nỗi đau tài chính rõ, có nhiều nguồn dữ liệu để kiểm chứng | Vấn đề chính là tìm API hay đánh giá API; API miễn phí vốn không cam kết ổn định |
| 3 | Đánh giá máy tính cũ trước khi mua | Tác động tài chính cao, người dùng rõ, có thể xây dựng checklist kiểm tra | Tần suất thấp và chưa có bằng chứng cá nhân từng mua nhầm hoặc gặp máy lỗi |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Tìm API miễn phí và ổn định

```text
Problem 1 câu:
Sinh viên có tài chính hạn chế thường xuyên phải dừng coding để tìm API miễn phí cho coding và TTS trên nhiều nguồn khác nhau, mà API tìm được không chắc ổn định lâu dài.

Actor:
Sinh viên dùng API cho các dự án coding và TTS cá nhân.

Thời điểm / bối cảnh:
Khi bắt đầu dự án mới, cần thêm tính năng, hoặc API cũ hết hạn/quota.

Current workflow 3-7 bước:
1. Xác định nhu cầu: dùng cho coding hay TTS, format input/output, giới hạn chi phí.
2. Tìm kiếm trên nhiều nguồn: GitHub, blog, danh sách API, nhóm cộng đồng.
3. So sánh giá, quota, endpoint, docs và điều khoản sử dụng.
4. Test thử với request nhỏ.
5. Ghi lại API và theo dõi khi có lỗi hoặc thay đổi limit.

Bottleneck:
Bước 2 và 3 — phải tổng hợp nhiều nguồn rồi tự đánh giá độ tin cậy, quota và khả năng duy trì lâu dài.

Impact:
Xảy ra trên 10 lần/tháng. Case đơn giản mất 5–10 phút, case khó có thể mất vài ngày. Việc này làm gián đoạn coding và có thể khiến dự án phụ thuộc vào API dễ gãy.

Success metric:
- Baseline: trên 10 lần/tháng; mỗi lần 5–10 phút cho case đơn giản, có trường hợp vài ngày.
- Mục tiêu: ít nhất 80% lần tìm kiếm hoàn tất danh sách API ứng viên trong 30 phút; sau 14 ngày, tỷ lệ API được chọn nhưng hết hoạt động/đổi limit bất thường dưới 20%.
- Cách đo: log mỗi lần tìm kiếm, thời gian bỏ ra, API chọn, kết quả health-check sau 7 và 14 ngày.

Non-AI alternative:
Tự duy trì một bảng API theo nhu cầu, ghi nguồn chính thức, ngày kiểm tra cuối và API backup. Cách này rẻ nhưng dễ lỗi thời nếu không rà soát định kỳ.

AI hypothesis:
AI giúp rút gọn danh sách API theo nhu cầu, tóm tắt docs/quota/endpoint và cảnh báo các tiêu chí cần kiểm tra. Người dùng vẫn tự test API và quyết định dùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Điểm mạnh:**
- Tần suất cao.
- Nỗi đau tài chính thực tế.
- Có nhiều nguồn dữ liệu để nghiên cứu.
- Có thể đo thời gian tìm kiếm và thời gian API hoạt động.

**Challenge cần kiểm chứng:**
- Vấn đề nằm ở “tìm API” hay “đánh giá API”?
- API miễn phí không cam kết ổn định, nên giải pháp cần nhấn mạnh health-check và backup.
- Danh sách tổng hợp dễ lỗi thời nếu không có cơ chế rà soát.
- Không nên khuyến khích dùng API không rõ nguồn gốc hoặc vi phạm điều khoản.

**Draft workflow Card #1**

```text
CURRENT STATE — 5–10 phút/case đơn giản, có thể vài ngày/case khó

[1 Xác định nhu cầu: 2']
→ [2 Tìm nhiều nguồn: 5'–nhiều giờ']  <-- bottleneck
→ [3 So sánh docs/quota/điều khoản: 5–15']  <-- bottleneck
→ [4 Test API: 5–20']
→ [5 Ghi lại + theo dõi: 5']

FUTURE STATE — khoảng 19 phút/case thông thường

[1 Xác định nhu cầu: 2']
→ [2 AI đề xuất 3–5 API + tiêu chí kiểm tra: 2']
→ [3 Người dùng test API và đọc docs gốc: 10']  <-- human boundary
→ [4 Ghi nguồn, limit, ngày kiểm tra: 3']
→ [5 Health-check sau 7/14 ngày: 2']

Fallback: nếu AI gợi ý API không còn hoạt động, không rõ nguồn gốc hoặc lệch điều khoản, người dùng bỏ ứng viên đó và kiểm tra tài liệu chính thức; luôn giữ ít nhất một API backup.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Chẩn đoán lỗi cấu hình API bên thứ ba

```text
Problem 1 câu:
Người dùng Antigravity và Codex với API bên thứ ba thường mất nhiều thời gian phân biệt lỗi DNS, đăng nhập, endpoint hoặc model routing, khiến công việc coding bị dừng hoàn toàn.

Actor:
Người dùng Antigravity và Codex đang cấu hình API bên thứ ba.

Thời điểm / bối cảnh:
Khi cài đặt lần đầu, đổi API provider, cập nhật công cụ, hoặc sau khi endpoint/key/model thay đổi.

Current workflow 3-7 bước:
1. Gặp lỗi khi gọi API hoặc chạy công cụ.
2. Đọc thông báo lỗi và config hiện tại.
3. Phân biệt nguyên nhân: DNS, authentication, endpoint sai, model routing sai.
4. Tìm tài liệu chính thức và tài liệu lỗi cũ trên cloud.
5. Sửa config, chạy lại và kiểm tra.

Bottleneck:
Bước 3 và 4 — phân loại đúng nguyên nhân rồi tìm cách sửa phù hợp với công cụ, hệ điều hành và nhà cung cấp API.

Impact:
Xảy ra trên 5 lần/tháng; mỗi lần mất từ 5 phút đến 1 tuần. Trong thời gian đó, người dùng không code được bằng môi trường mong muốn.

Success metric:
- Baseline: trên 5 lần/tháng; thời gian khôi phục từ 5 phút đến 1 tuần.
- Mục tiêu: ít nhất 70% trường hợp chẩn đoán được nhóm lỗi trong 10 phút và hoàn tất thử sửa trong 30 phút; không làm lộ API key trong quá trình hỗ trợ.
- Cách đo: log mỗi lỗi, nhóm nguyên nhân, thời gian chẩn đoán, thời gian sửa, kết quả retest.

Non-AI alternative:
Chuẩn bị runbook theo từng lỗi: kiểm tra DNS, key, endpoint, model và version công cụ. Cách này rẻ nhưng cần cập nhật khi tài liệu hoặc phiên bản thay đổi.

AI hypothesis:
AI đọc log/config đã ẩn API key, gom các giả thuyết lỗi, đề xuất lệnh kiểm tra an toàn và giải thích cách phân biệt DNS/authentication/endpoint/model routing. Người dùng tự áp dụng thay đổi và xác nhận.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Điểm mạnh:**
- Workflow và lỗi cụ thể.
- Hậu quả rõ ràng: coding dừng hoàn toàn.
- Có tài liệu lỗi cũ trên cloud để nghiên cứu.
- Có thể đo thời gian khôi phục môi trường.
- Có thể giới hạn phạm vi vào hai công cụ và hai hệ điều hành.

**Challenge cần kiểm chứng:**
- Các lỗi có khác nhau quá nhiều để chuẩn hóa không?
- AI có đủ bối cảnh để phân biệt DNS, authentication, endpoint và model routing?
- Cấu hình có thể kiểm tra tự động, nhưng người dùng vẫn cần hiểu đủ để tránh sửa sai.
- API key phải được ẩn/mask trước khi đưa vào bất kỳ công cụ AI nào.
- Tài liệu cũ có thể mất hiệu lực khi công cụ hoặc API đổi phiên bản.

**Draft workflow Card #2**

```text
CURRENT STATE — 5 phút đến 1 tuần/lỗi

[1 Gặp lỗi: 1']
→ [2 Đọc log/config: 2']
→ [3 Phân loại nguyên nhân: 5'–nhiều giờ']  <-- bottleneck
→ [4 Tìm docs/case cũ: 5'–nhiều giờ']  <-- bottleneck
→ [5 Sửa + retest: 5'–nhiều giờ']

FUTURE STATE — 17–32 phút/trường hợp phổ biến

[1 Capture lỗi + config: 2']
→ [2 Mask API key: 1']  <-- human boundary
→ [3 AI phân loại giả thuyết lỗi: 2']
→ [4 Chạy checklist kiểm tra an toàn: 5–15']
→ [5 Người dùng áp dụng fix: 5–10']  <-- human boundary
→ [6 Retest + ghi kết quả: 2']

Fallback: nếu AI chẩn đoán sai, người dùng quay lại runbook thủ công, đối chiếu tài liệu chính thức và support của nhà cung cấp; không cấp quyền thay đổi hệ thống cho AI khi chưa có kết quả kiểm tra.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Đánh giá máy tính cũ trước khi mua

```text
Problem 1 câu:
Sinh viên có ngân sách hạn chế mất nhiều ngày nghiên cứu CPU, GPU, RAM và cách kiểm tra lỗi trước khi mua máy cũ, trong khi quyết định sai gây thiệt hại tài chính lớn.

Actor:
Sinh viên cần mua máy tính cũ phục vụ học tập và coding.

Thời điểm / bối cảnh:
Trước khi mua máy cũ tại cửa hàng hoặc từ người bán cá nhân.

Current workflow 3-7 bước:
1. Xác định ngân sách và nhu cầu sử dụng: học, code, đồ họa, AI cơ bản.
2. Tìm cấu hình cũ trên mạng và so sánh giá.
3. Tra mã CPU, GPU, RAM và đời máy.
4. Tìm hiểu lỗi thường gặp của model máy.
5. Chuẩn bị cách kiểm tra tại cửa hàng.
6. Quyết định mua hoặc bỏ.

Bottleneck:
Bước 3 và 5 — vừa khó hiểu spec, vừa không biết kiểm tra lỗi vật lý nào đủ tin cậy trong thời gian ngắn.

Impact:
Nghiên cứu có thể kéo dài vài ngày. Nếu mua sai, sinh viên mất tiền và phải tiếp tục dùng máy yếu hoặc tìm cách sửa.

Success metric:
- Baseline: nghiên cứu có thể mất vài ngày; chưa có checklist kiểm tra chuẩn.
- Mục tiêu: giảm thời gian chuẩn bị trước khi đi xem máy xuống 45–90 phút cho một budget cụ thể; hoàn thành 100% checklist kiểm tra quan trọng trước khi quyết định.
- Cách đo: bấm giờ thời gian chuẩn bị, đếm số mục checklist hoàn thành tại cửa hàng, ghi kết quả kiểm tra và quyết định cuối.

Non-AI alternative:
Dùng bảng so sánh CPU/GPU, forum review và checklist in sẵn. Cách này có thể ổn nhưng tốn thời gian và dễ bỏ sót kiểm tra vật lý.

AI hypothesis:
AI giúp chuyển ngân sách và nhu cầu thành checklist, giải thích mức CPU/GPU/RAM và cảnh báo model máy nên tránh. Người dùng tự kiểm tra máy tại cửa hàng và quyết định.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Điểm mạnh:**
- Tác động tài chính cao.
- Đối tượng người dùng rõ: sinh viên ngân sách hạn chế.
- Có thể xây dựng checklist kiểm tra.
- Nhu cầu phổ biến hơn một cá nhân.

**Challenge cần kiểm chứng:**
- Một người không mua máy thường xuyên nên tần suất thấp.
- Giá và cấu hình thay đổi liên tục.
- Kiểm tra tại cửa hàng cần thao tác vật lý, AI không thay thế được.
- Không thể đảm bảo phát hiện mọi lỗi tiềm ẩn.
- Chưa có bằng chứng cá nhân từng mua nhầm hoặc gặp máy lỗi.

**Draft workflow Card #3**

```text
CURRENT STATE — vài ngày nghiên cứu

[1 Xác định budget/nhu cầu: 10']
→ [2 Tìm cấu hình + giá: nhiều giờ']  <-- bottleneck
→ [3 Tra CPU/GPU/RAM/đời máy: 30'–nhiều giờ']  <-- bottleneck
→ [4 Tìm lỗi model: 30'–nhiều giờ']
→ [5 Kiểm tra tại cửa hàng: không có checklist chuẩn']
→ [6 Quyết định mua/bỏ']

FUTURE STATE — 45–90 phút chuẩn bị + 20–30 phút kiểm tra tại cửa hàng

[1 Xác định budget/nhu cầu: 5']
→ [2 AI draft checklist + ngưỡng cấu hình: 10']
→ [3 Người dùng verify giá/spec bằng nguồn độc lập: 20–30']  <-- human boundary
→ [4 Kiểm tra vật lý tại cửa hàng: 20–30']  <-- human boundary
→ [5 Quyết định mua/bỏ: 5']

Fallback: nếu AI đưa spec hoặc cảnh báo không khớp nguồn độc lập, người dùng ưu tiên specs chính thức và review thật; nếu cửa hàng không cho kiểm tra đủ, bỏ mua.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Card #2 — Chẩn đoán lỗi cấu hình API bên thứ ba trong Antigravity và Codex.
```

**Vì sao:**

```text
Workflow lỗi rất cụ thể và lặp lại trên 5 lần/tháng. Hậu quả lớn vì coding có thể dừng từ 5 phút đến 1 tuần. Bài toán có thể thu hẹp phạm vi thành hai công cụ, hai hệ điều hành và các nhóm lỗi DNS/authentication/endpoint/model routing, nên dễ thiết kế pilot và đo thời gian khôi phục.
```

**Câu hỏi tôi muốn nhóm challenge:**

```text
Cách nào chuẩn hóa chẩn đoán các loại lỗi khác nhau mà vẫn bảo vệ API key và không phụ thuộc vào tài liệu cũ có thể lỗi thời?
```

**AI phản biện Card:**

- Điểm yếu AI chỉ ra:
  - Các lỗi có thể quá khác nhau để chuẩn hóa.
  - AI có thể thiếu bối cảnh để phân biệt đúng nguyên nhân.
  - API key là thông tin nhạy cảm.
  - Tài liệu cũ dễ mất hiệu lực khi công cụ/API đổi phiên bản.
- Tôi sửa gì:
  - Giới hạn phạm vi hai công cụ và hai hệ điều hành.
  - Bắt buộc mask key trước khi đưa log/config vào AI.
  - Dùng checklist kiểm tra có kết quả đúng/sai rõ ràng.
  - Luôn đối chiếu tài liệu chính thức và để người dùng áp dụng fix.

### Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
