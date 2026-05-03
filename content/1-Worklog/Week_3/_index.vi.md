---
title: "Worklog Tuần 3"
weight: 3
chapter: false
pre: " <b> 1.3 </b> "
---

### 📌 Mục tiêu

- Hoàn thiện cấu trúc Frontend, lựa chọn các thư viện chính (React Router, Redux Toolkit, Axios).
- Thiết kế và xây dựng các trang giao diện cơ bản (Home, Login, Register).
- Kết nối Frontend với hệ thống Authentication (Cognito).
- Đóng góp vào Backend ở phần entity Song, Artist, Album cùng nhóm.

---

### 🛠 Công việc thực hiện

| Công việc                                                                            | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                |
| ------------------------------------------------------------------------------------ | ------------ | --------------- | ----------------------------------------------------------------- |
| Phân tích lý do chọn React + Vite + Tailwind cho Frontend (hiệu năng, hệ sinh thái)  | 23/03/2026   | 23/03/2026      |                                                                   |
| Cấu hình React Router cho hệ thống điều hướng giữa các trang                         | 23/03/2026   | 24/03/2026      | https://reactrouter.com/                                          |
| Cài đặt Redux Toolkit, thiết lập store ban đầu (auth slice, player slice)            | 24/03/2026   | 25/03/2026      | https://redux-toolkit.js.org/                                     |
| Thiết kế và xây dựng giao diện trang Home (sections gợi ý nhạc, layout chính)        | 24/03/2026   | 26/03/2026      | https://tailwindcss.com/                                          |
| Xây dựng giao diện trang Login / Register, kết nối với AWS Cognito                   | 25/03/2026   | 27/03/2026      | https://docs.aws.amazon.com/cognito                               |
| Tham gia thiết kế Song / Artist / Album entity (Backend) cùng nhóm                   | 26/03/2026   | 28/03/2026      |                                                                   |
| Tích hợp gọi API CRUD Song từ Frontend (lấy danh sách bài hát, hiển thị Home)        | 27/03/2026   | 28/03/2026      |                                                                   |
| Test luồng đăng ký – đăng nhập – nhận JWT token từ Cognito                           | 28/03/2026   | 29/03/2026      |                                                                   |

---

### ✅ Kết quả nhận được

- Hệ thống điều hướng giữa các trang hoạt động ổn định với React Router.
- Redux store được thiết lập rõ ràng, dễ mở rộng cho các slice tiếp theo (player, history, queue).
- Giao diện trang Home có layout đẹp, responsive và phù hợp với theme Spotify.
- Luồng Authentication với Cognito chạy thành công: đăng ký → nhận mã xác nhận → đăng nhập → nhận JWT token.
- Đóng góp được vào việc thiết kế Song / Artist / Album entity ở Backend.
- Frontend đã có thể gọi và hiển thị danh sách bài hát từ API thực.
- Hiểu rõ luồng tương tác giữa Frontend (React) và Backend (Lambda + API Gateway + Cognito).
