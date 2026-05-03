---
title: "Worklog Tuần 7"
date: "2026-04-20"
weight: 7
chapter: false
pre: " <b> 1.7 </b> "
---

### 📌 Mục tiêu

- Tham gia xây dựng hệ thống Genre/Category (Backend + Frontend) cùng nhóm.
- Hỗ trợ multi-genre cho bài hát (1 bài có thể thuộc nhiều thể loại).
- Cải thiện responsive UI trên mobile và sửa các bug còn lại.
- Nạp dữ liệu, kiểm thử toàn hệ thống và hoàn thiện sản phẩm để bàn giao.

---

### 🛠 Công việc thực hiện

| Công việc                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                       |
| ----------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------- |
| Tham gia thiết kế trường `genre` cho Song entity và GSI `GenreIndex` trên DynamoDB              | 20/04/2026   | 20/04/2026      | https://docs.aws.amazon.com/dynamodb     |
| Đóng góp vào CRUD API cho Genre/Category (handler endpoint cùng nhóm)                           | 20/04/2026   | 20/04/2026      |                                          |
| Đồng bộ `songCount` giữa Artist và Song khi tạo / xóa bài hát                                   | 20/04/2026   | 20/04/2026      |                                          |
| Frontend: kết nối Categories Page với Category API thực, hỗ trợ multi-genre upload và edit      | 20/04/2026   | 22/04/2026      |                                          |
| Admin Dashboard: thêm cột genre, format ngày tháng                                              | 20/04/2026   | 20/04/2026      |                                          |
| Cải thiện UI responsive trên mobile (fix `mb-20` HomePage để không bị che bởi PlayerBar)        | 22/04/2026   | 24/04/2026      |                                          |
| Fix `artist_id` không persist, redirect sau reload, SearchBar dropdown                          | 22/04/2026   | 22/04/2026      |                                          |
| Fix EditSongPage, ProfilePage follow artists, getSongsByArtist API trả đúng dữ liệu             | 26/04/2026   | 26/04/2026      |                                          |
| Mở Login Modal khi ProtectedRoute redirect (UX tốt hơn)                                         | 26/04/2026   | 26/04/2026      |                                          |
| Thêm Footer page cho website                                                                    | 27/04/2026   | 27/04/2026      |                                          |
| Cải thiện ProfilePage: hiển thị thông tin Artist, follow / unfollow                             | 22/04/2026   | 29/04/2026      |                                          |
| Cải thiện Search: filter tabs, mở rộng genre list                                               | 29/04/2026   | 01/05/2026      |                                          |
| Nạp dữ liệu mẫu (seed data: artists, songs, genres) phục vụ demo                                | 29/04/2026   | 01/05/2026      |                                          |
| Kiểm thử thủ công toàn bộ hệ thống, fix bug giao diện                                           | 02/05/2026   | 07/05/2026      |                                          |
| Hoàn thiện báo cáo thực tập và deploy bản cuối                                                  | 07/05/2026   | 09/05/2026      |                                          |

---

### ✅ Kết quả nhận được

- Hệ thống **Genre/Category hoạt động hoàn chỉnh** end-to-end — bài hát có thể thuộc nhiều thể loại, hiển thị đẹp trên trang Categories.
- DynamoDB GSI giúp query bài hát theo genre nhanh, không phải scan toàn bảng.
- Admin Dashboard có cột Genre và format thời gian rõ ràng.
- UI responsive tốt trên mobile, không còn lỗi PlayerBar che nội dung.
- Các edge case về Auth / Routing / EditSong / ProfilePage được xử lý dứt điểm.
- Search hoạt động tốt với nhiều filter tabs và danh sách genre đầy đủ.
- Có dữ liệu mẫu để demo dễ dàng (nhiều artists, songs, genres).
- **Sản phẩm hoàn chỉnh**: ứng dụng Spotify Clone đầy đủ tính năng (đăng ký, đăng nhập, upload, phát nhạc, playlist với drag & drop, queue, history, notification, share, artist dashboard, admin panel, multi-genre, search nâng cao, responsive mobile).
- Báo cáo thực tập hoàn tất, sẵn sàng bàn giao.
