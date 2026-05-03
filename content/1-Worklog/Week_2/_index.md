---
title: "Worklog Week 2"
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### 📌 Objectives

- Understand the core AWS services: S3, DynamoDB, API Gateway, Lambda, Cognito.
- Design system architecture following the serverless model.
- Initialize the repository and set up project infrastructure (Frontend + Backend).
- Analyze functional / non-functional requirements and design the initial NoSQL Database Schema.

---

### 🛠 Tasks Performed

| Task                                                                                  | Start Date | End Date   | References                              |
| ------------------------------------------------------------------------------------- | ---------- | ---------- | --------------------------------------- |
| Study Amazon S3 (object storage, audio files & cover images)                          | 16/03/2026 | 17/03/2026 | https://docs.aws.amazon.com/s3          |
| Study DynamoDB (NoSQL, partition key, sort key, GSI, query-first design)              | 17/03/2026 | 18/03/2026 | https://docs.aws.amazon.com/dynamodb    |
| Study AWS Lambda and serverless model                                                 | 18/03/2026 | 19/03/2026 | https://docs.aws.amazon.com/lambda      |
| Study API Gateway (REST API, routing, JWT Authorizer)                                 | 19/03/2026 | 19/03/2026 | https://docs.aws.amazon.com/apigateway  |
| Study AWS Cognito (User Pool, JWT, Authentication & Authorization)                    | 19/03/2026 | 20/03/2026 | https://docs.aws.amazon.com/cognito     |
| Initialize GitHub repository `aws-prj-spotify`, set up gitignore, folder structure    | 16/03/2026 | 18/03/2026 |                                         |
| Set up base Frontend project (React + Vite + Tailwind CSS) with the team              | 18/03/2026 | 19/03/2026 | https://vitejs.dev/                     |
| Install and configure SST Ion (Infrastructure as Code) for Backend                    | 19/03/2026 | 20/03/2026 | https://sst.dev/                        |
| Analyze functional requirements (register, login, music streaming, playlist, search)  | 20/03/2026 | 20/03/2026 |                                         |
| Design NoSQL Database Schema for User, Song, Artist, Album, Playlist                  | 20/03/2026 | 22/03/2026 |                                         |

---

### ✅ Achievements

- Clearly understood the role and operation of 5 core AWS services: S3, DynamoDB, Lambda, API Gateway, Cognito.
- Grasped the serverless architecture model: auto scaling, no server management, cost optimization.
- Designed the overall architecture: **Frontend → API Gateway → Cognito Authorizer → Lambda → DynamoDB / S3**.
- Successfully initialized the repository with a clear project structure (frontend / backend separated).
- Set up Frontend development environment with React + Vite + Tailwind CSS.
- Analyzed functional / non-functional requirements of the system.
- Designed DynamoDB NoSQL schema following query-first design for main entities.
- Understood how to choose Free Tier services to optimize cost.
