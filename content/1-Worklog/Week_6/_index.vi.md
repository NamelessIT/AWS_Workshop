---
title: "Worklog Tuần 6"
weight: 6
chapter: false
pre: " <b> 1.6 </b> "
---

### 📌 Mục tiêu

- Sửa các lỗi tồn đọng của Player, History, Notification, Share Song.
- Cải thiện trải nghiệm Sidebar và Login Modal.
- Hoàn thiện Artist Dashboard và đồng bộ dữ liệu giữa Frontend và Backend.
- Đóng góp vào việc xây dựng các API quản lý ở Backend.

---

### 🛠 Công việc thực hiện

| Công việc                                                                            | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                              |
| ------------------------------------------------------------------------------------ | ------------ | --------------- | ------------------------------------------------------------------------------- |
| Fix lỗi Frontend liên quan đến song (sai data, không play được)                      | 13/04/2026   | 13/04/2026      |                                                                                 |
| Cập nhật PageIntro components và fix Redux selectors (giảm re-render không cần thiết) | 13/04/2026   | 13/04/2026      |                                                                                 |
| Triển khai Login Modal trigger tự động khi user truy cập route protected             | 15/04/2026   | 15/04/2026      |                                                                                 |
| Fix `/liked-songs` route redirect đúng sau khi like                                  | 15/04/2026   | 15/04/2026      |                                                                                 |
| Cải thiện Sidebar UX, cleanup Queue Panel                                            | 15/04/2026   | 15/04/2026      |                                                                                 |
| Fix lỗi Player và History bugs (state desync, audio not loading)                     | 15/04/2026   | 15/04/2026      |                                                                                 |
| Fix lỗi Notification, Share Song, Artist Dashboard hiển thị sai                      | 16/04/2026   | 16/04/2026      |                                                                                 |
| Đồng bộ dữ liệu album, user, history listen giữa Frontend và DynamoDB                | 17/04/2026   | 17/04/2026      |                                                                                 |
| Đóng góp vào API quản lý Song (CRUD endpoint cùng nhóm)                              | 13/04/2026   | 17/04/2026      | https://docs.aws.amazon.com/lambda <br/> https://docs.aws.amazon.com/apigateway |
| Merge code giữa các nhánh `khiem`, `Huy`, `main` — xử lý conflict                    | 13/04/2026   | 19/04/2026      |                                                                                 |

---

### ✅ Kết quả nhận được

- Player phát nhạc ổn định: play / pause / next / prev hoạt động chính xác, không còn audio bị crash.
- History timeline cập nhật đúng mỗi khi đổi bài.
- Notification hiển thị đúng thời điểm, Share Song tạo link chia sẻ chính xác.
- Login Modal xuất hiện đúng lúc người dùng truy cập route cần auth, redirect chính xác sau khi đăng nhập.
- Sidebar gọn gàng, Queue Panel không còn lỗi giao diện.
- Artist Dashboard hiển thị đầy đủ thông tin từ DynamoDB.
- Đóng góp được vào việc xây dựng API quản lý Song ở Backend.
- Quản lý merge giữa các nhánh tốt hơn, conflict được giải quyết hợp lý theo policy ưu tiên `main`.
