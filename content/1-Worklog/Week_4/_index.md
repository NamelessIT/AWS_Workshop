---
title: "Worklog Week 4"
weight: 4
chapter: false
pre: " <b> 1.4 </b> "
---

### 📌 Objectives

- Develop main management pages: Admin, Artist Dashboard, Categories.
- Build shared components (Card, Modal, Dialog, Sidebar).
- Integrate pages with Backend API to display real data.
- Refactor Frontend folder structure for maintainability.

---

### 🛠 Tasks Performed

| Task                                                                                  | Start Date | End Date   | References                                                                                                                                     |
| ------------------------------------------------------------------------------------- | ---------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Design Admin Dashboard UI (overview, common layout)                                   | 30/03/2026 | 30/03/2026 | https://tailwindcss.com/docs/installation/using-vite <br/> https://www.youtube.com/watch?v=NclbvXqvnyA&list=PLPt6-BtUI22oD3xfWy9VI9klNNxqAnTjb |
| Build user management page (User table, Add/Edit dialogs)                             | 30/03/2026 | 02/04/2026 |                                                                                                                                                |
| Build Song content management page (Song table, management dialogs)                   | 02/04/2026 | 03/04/2026 |                                                                                                                                                |
| Refactor: extract generic Card base component (reusable across pages)                 | 03/04/2026 | 04/04/2026 |                                                                                                                                                |
| Build Categories Page (display songs by genre)                                        | 04/04/2026 | 05/04/2026 |                                                                                                                                                |
| Migrate Liked Songs to a dedicated API on Frontend                                    | 04/04/2026 | 04/04/2026 |                                                                                                                                                |
| Integrate management pages with Backend API (real data)                               | 30/03/2026 | 05/04/2026 |                                                                                                                                                |
| Code review feedback: remove unused constants, extract LANGUAGES                      | 05/04/2026 | 05/04/2026 |                                                                                                                                                |

---

### ✅ Achievements

- Completed basic Admin Dashboard with statistics view and management table.
- User and content management pages are fully functional: add, edit, delete, view detail.
- Card component is reused across many item types (Song, Album, Artist) — significantly reduced duplicate code.
- Categories Page displays song lists by genre.
- Liked Songs split into a dedicated API — better synchronization across devices.
- Frontend now operates end-to-end with the real Backend, no more mock data.
- Learned a professional code review process through team feedback.
