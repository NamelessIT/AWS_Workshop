---
title: "Đánh giá cá nhân"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

### 📊 Self Evaluation

Trong suốt thời gian thực tập tại Công ty TNHH Amazon Web Services Việt Nam từ 09/03/2026 đến 09/05/2026, tôi đã có cơ hội tham gia trực tiếp vào việc xây dựng dự án **Music Streaming Web (Spotify Clone)** trên kiến trúc Serverless AWS. Đây là cơ hội quý giá để áp dụng kiến thức đã học vào một dự án thực tế, làm việc nhóm trên cùng một codebase và trải nghiệm quy trình phát triển phần mềm chuyên nghiệp.

Trong dự án, tôi tập trung phần lớn vào **Frontend** (React + Redux Toolkit + Tailwind CSS) và đóng góp một phần ở **Backend Serverless** (đặc biệt là tính năng Songs / Genre / Category). Một số đóng góp nổi bật bao gồm:

- Phát triển nhiều trang giao diện chính: Admin Dashboard, Artist Dashboard, Playlist, My Library, Song Detail Page, Categories Page, Search, Profile.
- Triển khai My Playlists với drag & drop reorder, dynamic sidebar.
- Xây dựng Song Detail Page với hiệu ứng đổi màu nền theo ảnh cover.
- Tham gia thiết kế và triển khai hệ thống **Genre/Category** (Backend): thêm trường genre vào Song entity, hỗ trợ multi-genre cho bài hát.
- Đóng góp vào CRUD API cho Song và đồng bộ `songCount` giữa Artist và Song.
- Fix nhiều bug về Player, History, Notification, Share Song, Login Modal.
- Cải thiện responsive UI cho mobile.

Về tác phong, tôi luôn cố gắng hoàn thành đúng tiến độ, chủ động trao đổi với đồng nghiệp khi gặp vướng mắc và sẵn sàng nhận góp ý để cải thiện chất lượng code.

Để phản ánh khách quan quá trình thực tập, tôi xin tự đánh giá bản thân theo các tiêu chí dưới đây:

| Tiêu chí đánh giá              | Mô tả                                                                | Mức độ (1–5) | Nhận xét cá nhân |
| ------------------------------ | -------------------------------------------------------------------- | ------------ | ---------------- |
| Hiểu về AWS                    | Nắm các dịch vụ chính: S3, Lambda, DynamoDB, API Gateway, Cognito    | 3            | Đã sử dụng thành thạo các dịch vụ cốt lõi qua dự án thực tế. Cần tìm hiểu sâu hơn về CloudFront, EventBridge và các dịch vụ monitoring. |
| Phát triển Frontend (React)    | Xây dựng UI với React + Vite + Tailwind, quản lý state với Redux Toolkit | 4         | Phát triển được nhiều trang với UI/UX tốt, state management ổn định, responsive trên mobile. |
| Tích hợp Frontend với API      | Gọi API backend, xử lý loading/error state, đồng bộ dữ liệu          | 4            | Đã chuyển toàn bộ frontend từ mock data sang real API thành công, xử lý được nhiều edge case. |
| Phát triển Backend (Serverless)| Viết Lambda function, REST API cho tính năng Song / Genre            | 3            | Đóng góp ở mức vừa phải vào backend (chủ yếu phần Songs / Genre / Category). Cần luyện tập thêm để tự xây dựng hệ thống backend lớn hơn. |
| Thiết kế cơ sở dữ liệu NoSQL   | Thiết kế schema DynamoDB, hiểu GSI                                   | 3            | Hiểu được cách thiết kế GSI cho query genre, nhưng vẫn cần học thêm về Single-table design pattern. |
| Quản lý bảo mật (IAM, Cognito) | Hiểu phân quyền, xác thực qua Cognito                                | 3            | Đã làm việc với Cognito trong frontend (login, signup, refresh token). Vẫn còn hạn chế ở phần cấu hình Cognito nâng cao. |
| Kiểm thử và debug              | Phát hiện và xử lý bug                                               | 3            | Debug khá ổn ở các bug về frontend (Player, History, Routing). Cần học thêm cách viết unit test bài bản. |
| Quản lý source code (Git)      | Branching, merge conflict, code review                               | 4            | Đã quen với workflow nhóm, xử lý merge conflict tốt, hợp tác qua nhiều nhánh (Huy, khiem, hieu, main). |
| Tư duy hệ thống                | Hiểu cách thiết kế hệ thống cloud theo hướng scalable                | 4            | Có tư duy hệ thống tốt, hiểu được cách kết nối các dịch vụ AWS thành một kiến trúc serverless hoàn chỉnh. |
| Khả năng tự học                | Chủ động tìm hiểu tài liệu AWS và áp dụng vào project                | 4            | Chủ động tìm hiểu các công nghệ mới như SST Ion, Redux Toolkit, Tailwind CSS và áp dụng được vào dự án thực tế. |
| Làm việc nhóm                  | Phối hợp, code review, hỗ trợ thành viên khác                        | 4            | Phối hợp tốt với các thành viên trong nhóm. Còn cần cải thiện khả năng giao tiếp khi giải thích vấn đề kỹ thuật. |

### Cần cải thiện

- Cần học thêm và thực hành nhiều hơn ở mảng Backend để có thể tự xây dựng hệ thống Serverless hoàn chỉnh.
- Cần học cách viết unit test, integration test bài bản (chưa có nhiều kinh nghiệm thực tế).
- Cần học thêm về CI/CD pipeline (GitHub Actions, AWS CodePipeline) để tự động hóa deploy.
- Bổ sung kỹ năng monitoring và observability (CloudWatch Logs, X-Ray).
- Tìm hiểu sâu hơn về DynamoDB data modeling, đặc biệt là Single-table design.
- Cải thiện kỹ năng đọc tài liệu tiếng Anh chuyên ngành để học công nghệ mới nhanh hơn.
- Cải thiện kỹ năng quản lý thời gian, tránh tập trung deadline vào những ngày cuối.
- Tăng khả năng trình bày và viết documentation kỹ thuật rõ ràng cho người khác đọc.
