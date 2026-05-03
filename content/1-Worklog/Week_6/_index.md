---
title: "Worklog Week 6"
weight: 6
chapter: false
pre: " <b> 1.6 </b> "
---

### 📌 Objectives

- Fix outstanding bugs in Player, History, Notification, Share Song.
- Improve UX of Sidebar and Login Modal.
- Finalize Artist Dashboard and synchronize data between Frontend and Backend.
- Contribute to building management APIs on the Backend.

---

### 🛠 Tasks Performed

| Task                                                                                            | Start Date | End Date   | References                                                                      |
| ----------------------------------------------------------------------------------------------- | ---------- | ---------- | ------------------------------------------------------------------------------- |
| Fix Frontend bugs related to song (wrong data, cannot play)                                     | 13/04/2026 | 13/04/2026 |                                                                                 |
| Update PageIntro components and fix Redux selectors (reduce unnecessary re-render)              | 13/04/2026 | 13/04/2026 |                                                                                 |
| Implement Login Modal trigger automatically when user accesses a protected route                | 15/04/2026 | 15/04/2026 |                                                                                 |
| Fix `/liked-songs` route redirect after liking                                                  | 15/04/2026 | 15/04/2026 |                                                                                 |
| Improve Sidebar UX, cleanup Queue Panel                                                         | 15/04/2026 | 15/04/2026 |                                                                                 |
| Fix Player and History bugs (state desync, audio not loading)                                   | 15/04/2026 | 15/04/2026 |                                                                                 |
| Fix Notification, Share Song, Artist Dashboard display issues                                   | 16/04/2026 | 16/04/2026 |                                                                                 |
| Synchronize album, user, history listen data between Frontend and DynamoDB                      | 17/04/2026 | 17/04/2026 |                                                                                 |
| Contribute to Song management API (CRUD endpoint together with the team)                        | 13/04/2026 | 17/04/2026 | https://docs.aws.amazon.com/lambda <br/> https://docs.aws.amazon.com/apigateway |
| Merge code between branches `khiem`, `Huy`, `main` — handle conflicts                           | 13/04/2026 | 19/04/2026 |                                                                                 |

---

### ✅ Achievements

- Player works stably: play / pause / next / prev are accurate, no more audio crashes.
- History timeline updates correctly every time a new song is played.
- Notification displays at the right time, Share Song generates correct shareable links.
- Login Modal appears at the right moment when users access auth-required routes, redirects correctly after login.
- Sidebar is cleaner, Queue Panel no longer has UI bugs.
- Artist Dashboard displays full information from DynamoDB.
- Contributed to building Song management API on the Backend.
- Branch merging handled better; conflicts resolved with the policy of prioritizing `main`.
