---
title: "Worklog Tuần 2"
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### 📌 Mục tiêu

- Hiểu các dịch vụ cốt lõi của AWS: S3, DynamoDB, API Gateway, Lambda, Cognito.
- Thiết kế kiến trúc hệ thống theo mô hình serverless.
- Khởi tạo repository và setup hạ tầng dự án (Frontend + Backend).
- Phân tích yêu cầu chức năng / phi chức năng và thiết kế Database Schema NoSQL ban đầu.

---

### 🛠 Công việc thực hiện

| Công việc                                                                           | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                     |
| ----------------------------------------------------------------------------------- | ------------ | --------------- | -------------------------------------- |
| Tìm hiểu Amazon S3 (object storage, lưu trữ file audio và cover image)              | 16/03/2026   | 17/03/2026      | https://docs.aws.amazon.com/s3         |
| Tìm hiểu DynamoDB (NoSQL, partition key, sort key, GSI, query-first design)         | 17/03/2026   | 18/03/2026      | https://docs.aws.amazon.com/dynamodb   |
| Tìm hiểu AWS Lambda và mô hình serverless                                           | 18/03/2026   | 19/03/2026      | https://docs.aws.amazon.com/lambda     |
| Tìm hiểu API Gateway (REST API, routing, JWT Authorizer)                            | 19/03/2026   | 19/03/2026      | https://docs.aws.amazon.com/apigateway |
| Tìm hiểu AWS Cognito (User Pool, JWT, Authentication & Authorization)               | 19/03/2026   | 20/03/2026      | https://docs.aws.amazon.com/cognito    |
| Khởi tạo repository GitHub `aws-prj-spotify`, setup gitignore, cấu trúc thư mục     | 16/03/2026   | 18/03/2026      |                                        |
| Setup base project Frontend (React + Vite + Tailwind CSS) cùng nhóm                 | 18/03/2026   | 19/03/2026      | https://vitejs.dev/                    |
| Cài đặt và cấu hình SST Ion (Infrastructure as Code) cho Backend                    | 19/03/2026   | 20/03/2026      | https://sst.dev/                       |
| Phân tích yêu cầu chức năng (đăng ký, đăng nhập, nghe nhạc, playlist, search)       | 20/03/2026   | 20/03/2026      |                                        |
| Thiết kế Database Schema NoSQL cho User, Song, Artist, Album, Playlist              | 20/03/2026   | 22/03/2026      |                                        |

---

### ✅ Kết quả nhận được

- Hiểu rõ vai trò và cách hoạt động của 5 dịch vụ AWS cốt lõi: S3, DynamoDB, Lambda, API Gateway, Cognito.
- Nắm được mô hình kiến trúc serverless: tự động scale, không cần quản lý server, tối ưu chi phí.
- Thiết kế được kiến trúc tổng thể: **Frontend → API Gateway → Cognito Authorizer → Lambda → DynamoDB / S3**.
- Khởi tạo thành công repository và cấu trúc dự án rõ ràng (frontend / backend tách biệt).
- Setup được môi trường phát triển Frontend với React + Vite + Tailwind CSS.
- Phân tích được yêu cầu chức năng / phi chức năng của hệ thống.
- Thiết kế DynamoDB schema NoSQL theo hướng query-first design cho các thực thể chính.
- Hiểu được cách lựa chọn Free Tier hợp lý để tối ưu chi phí.
