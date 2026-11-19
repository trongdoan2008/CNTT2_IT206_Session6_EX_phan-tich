# [Phân tích] So sánh Trade-off các giải pháp ra lệnh cho Ứng dụng AI trong Học tập & Nghiên cứu
## **Bước 1: Đề xuất 2 prompt mẫu**

**Prompt 1 – Đơn giản**

Bạn là kỹ sư python Hãy giải thích kiến thức Python theo phương pháp Feynman và chấm bài theo Rubric chỉ ra lỗi sai, cách sửa và nhận xét cụ thể không tự suy đoán

**Prompt 2 – Chi tiết**

Bạn là gia sư AI và giảng viên chấm bài

1. Giải thích kiến thức đơn giản theo Feynman
2. Chấm bài theo Rubric:
   - Đúng logic: 4 điểm.
   - Xử lý lỗi: 3 điểm.
   - Code rõ ràng: 2 điểm.
   - Giải thích: 1 điểm.
3. Chỉ ra lỗi sai và cách sửa
4. Nếu thiếu dữ liệu hoặc sai định dạng, yêu cầu bổ sung
5. Không tự suy đoán dữ liệu

Xuất kết quả gồm giải thích, bảng điểm, nhận xét và tổng điểm

## **Bước 2: Bảng so sánh Trade-off**

| Tiêu chí | Giải pháp 1 | Giải pháp 2 |
| --- | --- | --- |
| Độ dễ hiểu | Cao | Trung bình |
| Tốn token | Ít | Nhiều |
| Chặn lỗi biên | Trung bình  | Rất tốt |
| Độ chi tiết | Thấp  | Cao |

## **Bước 3: Lựa chọn và chạy thử**

**Chọn giải pháp 2** vì có hướng dẫn rõ ràng, chấm điểm chi tiết và hạn chế lỗi dữ liệu

**Kết quả chạy thử:**

| Tiêu chí | Điểm |
| --- | --- |
| Đúng logic | 4/4 |
| Xử lý lỗi | 0/3 |
| Code rõ ràng | 2/2 |
| Giải thích | 1/1 |
| **Tổng** | **7/10** |

**Nhận xét:** Bài làm chưa xử lý danh sách rỗng, có thể gây lỗi chia cho 0

