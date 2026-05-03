---
title: "Worklog Tuần 5"
weight: 5
chapter: false
pre: " <b> 1.5 </b> "
---

### 📌 Mục tiêu

- Hoàn thiện các trang quản lý: Album, Nghệ sĩ, Yêu cầu nâng cấp tài khoản.
- Phát triển hệ thống My Library, My Playlists với drag & drop reorder.
- Xây dựng Song Detail Page với hiệu ứng động.
- Xử lý các luồng nâng cao của Authentication (Forgot Password, Play History timeline).

---

### 🛠 Công việc thực hiện

| Công việc                                                                                | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                                                                                             |
| ---------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Hoàn thiện giao diện quản lý nội dung (Report content, dialog xử lý)                     | 06/04/2026   | 07/04/2026      | https://tailwindcss.com/docs/installation/using-vite <br/> https://www.youtube.com/watch?v=NclbvXqvnyA&list=PLPt6-BtUI22oD3xfWy9VI9klNNxqAnTjb |
| Xây dựng giao diện quản lý Album (table, dialog Thêm/Sửa)                                | 08/04/2026   | 08/04/2026      |                                                                                                                                                |
| Xây dựng giao diện quản lý Nghệ sĩ và Yêu cầu nâng cấp (Artist Request)                  | 08/04/2026   | 10/04/2026      |                                                                                                                                                |
| Triển khai Forgot Password flow (gửi mã xác nhận qua Cognito, reset password)            | 06/04/2026   | 10/04/2026      | https://docs.aws.amazon.com/cognito                                                                                                            |
| Triển khai Play History timeline trên Frontend (gọi API, hiển thị danh sách)             | 11/04/2026   | 11/04/2026      |                                                                                                                                                |
| Fix lỗi `require()` ESM trong HistoryService, auto-refresh tab history khi đổi bài       | 06/04/2026   | 06/04/2026      |                                                                                                                                                |
| Phát triển My Library + My Playlists: dynamic sidebar, playlist detail với drag & drop   | 12/04/2026   | 12/04/2026      |                                                                                                                                                |
| Xây dựng Song Detail Page với dynamic color extraction từ ảnh cover                      | 12/04/2026   | 12/04/2026      |                                                                                                                                                |
| Fix bug playlist sai vị trí, history replace song                                        | 12/04/2026   | 12/04/2026      |                                                                                                                                                |
| Xây dựng route điều hướng cho các trang quản lý (Admin sidebar)                          | 10/04/2026   | 10/04/2026      |                                                                                                                                                |

---

### ✅ Kết quả nhận được

- Hoàn thiện các trang quản lý: Album, Nghệ sĩ, Report content với UX tốt.
- Forgot Password / Reset Password chạy hoàn chỉnh qua Cognito.
- My Library và My Playlists hoạt động: tạo / xóa playlist, kéo thả sắp xếp bài hát (D&D reorder).
- **Song Detail Page** có hiệu ứng đổi màu nền dynamic theo ảnh cover bài hát — UX rất ấn tượng.
- Sidebar hiển thị danh sách playlist động, tự động cập nhật khi tạo/xóa playlist.
- Play History được lưu đầy đủ và hiển thị dạng timeline trực quan.
- Fix dứt điểm các lỗi nhỏ về routing, ESM module, đồng bộ history khi đổi bài.
- Hệ thống điều hướng giữa các trang Admin hoạt động mượt mà qua sidebar.
