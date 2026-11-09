# Bài 5: Tối ưu quy trình hỗ trợ kỹ thuật nội bộ

## 1. Mẫu Bug Report Template (4 mảnh ghép)

```
**Tiêu đề:** [Tên lỗi ngắn gọn]

**1. Context (Bối cảnh):**
- Hệ điều hành / phiên bản:
- Công cụ đang dùng (Docker, Node...) và phiên bản:
- Mình đang làm gì thì gặp lỗi:

**2. Expected (Mong đợi):**
- Lẽ ra phải xảy ra điều gì:

**3. Actual (Thực tế):**
- Thực tế xảy ra điều gì:

**4. Log (Nhật ký lỗi):**
- Dán nguyên văn thông báo lỗi hoặc đính kèm ảnh chụp:

**Đã thử những cách nào rồi:**
-
```

Ai hỏi cũng phải điền đủ 4 phần trước khi nhắn, nên người hỗ trợ không phải hỏi đi hỏi lại.

## 2. Quy trình 3 bước tự tra cứu (xử lý khoảng 80% vấn đề)

| Bước | Việc cần làm |
|---|---|
| **1. Googling** | Copy nguyên thông báo lỗi dán lên Google, thêm tên công cụ (ví dụ: `docker port already in use`). Đọc tài liệu chính thức trước. |
| **2. Community Search** | Nếu chưa ra thì tìm trên Stack Overflow, GitHub Issues hoặc diễn đàn của công cụ. Xem câu trả lời mới, nhiều upvote và đúng phiên bản. |
| **3. AI Translation** | Nếu thông báo lỗi khó hiểu thì nhờ AI giải thích bằng tiếng Việt dễ hiểu. Chỉ dùng AI để *hiểu*, còn lệnh AI đưa phải kiểm chứng lại. |

Nếu cả 3 bước vẫn chưa xong thì mới tạo issue trên Jira, gắn tag `#BUG`, điền đủ Bug Report Template rồi báo trưởng nhóm. Không nhắn tin dồn vào nhóm chat chung.
