---
title: "Personal Evaluation"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

### 📊 Self Evaluation

During my internship at Amazon Web Services Vietnam Co., Ltd. from 09/03/2026 to 09/05/2026, I had the opportunity to directly participate in building the **Music Streaming Web (Spotify Clone)** project on AWS Serverless architecture. This was a valuable opportunity to apply academic knowledge to a real-world project, work as a team on the same codebase, and experience a professional software development workflow.

In the project, I focused mainly on **Frontend** (React + Redux Toolkit + Tailwind CSS) and contributed partially to the **Backend Serverless** (especially the Songs / Genre / Category features). Some highlights include:

- Developed many main UI pages: Admin Dashboard, Artist Dashboard, Playlist, My Library, Song Detail Page, Categories Page, Search, Profile.
- Implemented My Playlists with drag & drop reorder and dynamic sidebar.
- Built Song Detail Page with dynamic background color extracted from cover image.
- Participated in designing and implementing the **Genre/Category** system (Backend): added the genre field to the Song entity and supported multi-genre for songs.
- Contributed to the CRUD API for Song and synchronized `songCount` between Artist and Song.
- Fixed many bugs related to Player, History, Notification, Share Song, Login Modal.
- Improved responsive UI for mobile.

In terms of work attitude, I always strive to complete tasks on schedule, proactively communicate with colleagues when facing difficulties, and am open to feedback to improve code quality.

To objectively reflect my internship process, I self-evaluate based on the following criteria:

| Evaluation Criteria              | Description                                                                  | Level (1–5) | Personal Comments |
| -------------------------------- | ---------------------------------------------------------------------------- | ----------- | ----------------- |
| Understanding of AWS             | Master the core services: S3, Lambda, DynamoDB, API Gateway, Cognito         | 3           | Used core services proficiently in a real project. Need to study CloudFront, EventBridge, and advanced monitoring services in more depth. |
| Frontend Development (React)     | Build UI with React + Vite + Tailwind, manage state with Redux Toolkit       | 4           | Developed many pages with good UI/UX, stable state management, and mobile-responsive layout. |
| Frontend ↔ API Integration       | Call backend APIs, handle loading/error states, sync data                    | 4           | Successfully migrated the entire frontend from mock data to real APIs and handled many edge cases. |
| Backend Development (Serverless) | Write Lambda functions, REST APIs for Song / Genre features                  | 3           | Contributed at a moderate level to the backend (mainly Songs / Genre / Category). Need more practice to build a larger backend system independently. |
| NoSQL Database Design            | Design DynamoDB schema and understand GSI                                    | 3           | Understood how to design a GSI for genre queries; still need to learn more about Single-table design patterns. |
| Security Management (IAM, Cognito) | Understand authorization and authentication via Cognito                    | 3           | Worked with Cognito on the frontend (login, signup, refresh token). Still limited at advanced Cognito configuration. |
| Testing and Debugging            | Detect and fix bugs                                                          | 3           | Debugged frontend bugs (Player, History, Routing) effectively. Need to learn how to write proper unit tests. |
| Source Code Management (Git)     | Branching, merge conflict resolution, code review                            | 4           | Familiar with team workflow, handle merge conflicts well, collaborated across multiple branches (Huy, khiem, hieu, main). |
| System Thinking                  | Understand scalable cloud system design                                      | 4           | Good system thinking, understand how to connect AWS services into a complete serverless architecture. |
| Self-learning Ability            | Actively read AWS documentation and apply to project                         | 4           | Proactively learned new technologies like SST Ion, Redux Toolkit, Tailwind CSS and applied them to a real project. |
| Teamwork                         | Coordinate, code review, support other members                               | 4           | Collaborated well with team members. Still need to improve communication when explaining technical issues. |

### Areas for Improvement

- Need to study and practice more on the Backend side to be able to build a complete Serverless system independently.
- Need to learn how to write unit tests and integration tests properly (limited real-world experience).
- Need to learn about CI/CD pipelines (GitHub Actions, AWS CodePipeline) to automate deployment.
- Add monitoring and observability skills (CloudWatch Logs, X-Ray).
- Explore DynamoDB data modeling more deeply, especially Single-table design.
- Improve technical English reading skills to learn new technologies faster.
- Improve time management to avoid concentrating deadlines on the last few days.
- Strengthen presentation skills and writing clear technical documentation for others to read.
