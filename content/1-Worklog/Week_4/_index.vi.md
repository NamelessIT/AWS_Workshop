---
title: "Worklog Tuần 4"
weight: 4
chapter: false
pre: " <b> 1.4 </b> "
---

### 📌 Mục tiêu

- Phát triển các trang quản lý chính: Admin, Artist Dashboard, Categories.
- Xây dựng các component dùng chung (Card, Modal, Dialog, Sidebar).
- Tích hợp các trang với API Backend để hiển thị dữ liệu thực.
- Refactor cấu trúc thư mục Frontend cho dễ bảo trì.

---

### 🛠 Công việc thực hiện

| Công việc                                                            | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                                                                                             |
| -------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Thiết kế giao diện trang Admin Dashboard (overview, layout chung)    | 30/03/2026   | 30/03/2026      | https://tailwindcss.com/docs/installation/using-vite <br/> https://www.youtube.com/watch?v=NclbvXqvnyA&list=PLPt6-BtUI22oD3xfWy9VI9klNNxqAnTjb |
| Xây dựng trang quản lý người dùng (User table, dialog Thêm/Sửa)      | 30/03/2026   | 02/04/2026      |                                                                                                                                                |
| Xây dựng trang quản lý nội dung Song (Song table, dialog quản lý)    | 02/04/2026   | 03/04/2026      |                                                                                                                                                |
| Refactor: extract generic Card base component (tái dùng nhiều nơi)   | 03/04/2026   | 04/04/2026      |                                                                                                                                                |
| Xây dựng trang Categories Page (hiển thị bài hát theo thể loại)      | 04/04/2026   | 05/04/2026      |                                                                                                                                                |
| Migrate Liked Songs sang dedicated API ở Frontend                    | 04/04/2026   | 04/04/2026      |                                                                                                                                                |
| Tích hợp các trang quản lý với API Backend (real data)               | 30/03/2026   | 05/04/2026      |                                                                                                                                                |
| Code review feedback: remove unused constants, extract LANGUAGES     | 05/04/2026   | 05/04/2026      |                                                                                                                                                |

---

### ✅ Kết quả nhận được

- Hoàn thành Admin Dashboard cơ bản với giao diện thống kê và bảng quản lý.
- Trang quản lý người dùng và nội dung hoạt động đầy đủ: thêm, sửa, xóa, xem chi tiết.
- Component Card được tái sử dụng cho nhiều loại item (Song, Album, Artist) — giảm duplicate code.
- Categories Page hiển thị danh sách bài hát theo từng thể loại.
- Liked Songs tách thành API riêng — đồng bộ tốt hơn giữa các thiết bị.
- Frontend đã hoạt động end-to-end với Backend thực, không còn mock data.
- Học được quy trình code review chuyên nghiệp qua các góp ý của nhóm.
