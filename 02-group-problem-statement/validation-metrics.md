# Validation Data — Rào cản dịch vụ số của người lớn tuổi

## 1. Nguồn dữ liệu đã human confirm

- Khảo sát HUST năm 2021.
- Tổng mẫu: 1.043 người từ 55 tuổi trở lên.
- Nhóm phân tích lý do không sử dụng dịch vụ online: 609 người.
- Người trả lời có thể chọn nhiều lý do, nên các tỷ lệ dưới đây không cộng thành 100%.

## 2. Kết quả chính

| Lý do không sử dụng dịch vụ online | Tỷ lệ trong nhóm 609 người |
|---|---:|
| Thiếu thói quen sử dụng dịch vụ online | 73,6% |
| Ứng dụng có giao diện phức tạp, khó khai thác | 36,8% |
| Thiếu hướng dẫn cụ thể để thao tác | 28,1% |

## 3. Đọc số liệu đúng cách

- Đây là tỷ lệ trong nhóm 609 người trả lời lý do không dùng dịch vụ online, không phải tỷ lệ trên toàn bộ 1.043 người.
- Vì được chọn nhiều lý do, tổng 73,6% + 36,8% + 28,1% không có ý nghĩa thống kê và không cần cộng.
- Số liệu cho thấy ba rào cản chính, nhưng chưa chứng minh voice-based AI agent là giải pháp phù hợp nhất.

## 4. Metric cho pilot voice-based AI agent

| Metric | Baseline không dùng agent | Mục tiêu pilot | Cách đo |
|---|---:|---:|---|
| Tỷ lệ hoàn thành 1 thủ tục | Chưa có; cần đo với 5–10 người | ≥ 70% hoàn thành khi dùng voice agent | Ghi kết quả hoàn thành / không hoàn thành |
| Thời gian hoàn thành | Chưa có | Giảm ít nhất 30% so với baseline | Bấm giờ từ bắt đầu đến hoàn thành |
| Số lần nhờ hỗ trợ | Chưa có | Giảm ít nhất 30% | Đếm số lần phải nhờ người hỗ trợ |
| Số vòng xác nhận lại | Không áp dụng | Số vòng hợp lý, không gây khó chịu | Đếm số lần agent hỏi lại do nghe sai |
| Mức độ tin tưởng | Chưa có | Trung bình ≥ 4/5 | Hỏi người dùng sau khi dùng agent |

## 5. Rủi ro cần kiểm soát

- AI nghe sai tiếng Việt, giọng địa phương hoặc người nói chậm.
- AI hướng dẫn sai bước trong thủ tục công việc.
- Người dùng không tin giao diện voice hoặc sợ bị lừa đảo.
- Thủ tục nhạy cảm cần người thật xác nhận cuối cùng.
