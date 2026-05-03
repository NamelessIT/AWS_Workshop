---
title: "Worklog Week 5"
weight: 5
chapter: false
pre: " <b> 1.5 </b> "
---

### 📌 Objectives

- Finalize management pages: Album, Artist, Account upgrade requests.
- Develop My Library and My Playlists with drag & drop reorder.
- Build Song Detail Page with dynamic effects.
- Handle advanced Authentication flows (Forgot Password, Play History timeline).

---

### 🛠 Tasks Performed

| Task                                                                                            | Start Date | End Date   | References                                                                                                                                     |
| ----------------------------------------------------------------------------------------------- | ---------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Finalize content management interface (Report content, handling dialogs)                        | 06/04/2026 | 07/04/2026 | https://tailwindcss.com/docs/installation/using-vite <br/> https://www.youtube.com/watch?v=NclbvXqvnyA&list=PLPt6-BtUI22oD3xfWy9VI9klNNxqAnTjb |
| Build Album management UI (table, Add/Edit dialogs)                                             | 08/04/2026 | 08/04/2026 |                                                                                                                                                |
| Build Artist management and Account Upgrade Request UI                                          | 08/04/2026 | 10/04/2026 |                                                                                                                                                |
| Implement Forgot Password flow (send confirmation code via Cognito, reset password)             | 06/04/2026 | 10/04/2026 | https://docs.aws.amazon.com/cognito                                                                                                            |
| Implement Play History timeline on Frontend (call API, render history list)                     | 11/04/2026 | 11/04/2026 |                                                                                                                                                |
| Fix `require()` ESM error in HistoryService, auto-refresh history tab when changing song        | 06/04/2026 | 06/04/2026 |                                                                                                                                                |
| Develop My Library + My Playlists: dynamic sidebar, playlist detail with drag & drop reorder    | 12/04/2026 | 12/04/2026 |                                                                                                                                                |
| Build Song Detail Page with dynamic color extraction from cover image                           | 12/04/2026 | 12/04/2026 |                                                                                                                                                |
| Fix bug: playlist wrong position, history replace song                                          | 12/04/2026 | 12/04/2026 |                                                                                                                                                |
| Build navigation routing for admin pages (Admin sidebar)                                        | 10/04/2026 | 10/04/2026 |                                                                                                                                                |

---

### ✅ Achievements

- Finalized management pages: Album, Artist, Report content with great UX.
- Forgot Password / Reset Password works fully via Cognito.
- My Library and My Playlists work: create / delete playlist, drag & drop to reorder songs.
- **Song Detail Page** has dynamic background color effect based on song cover — very impressive UX.
- Sidebar shows dynamic playlist list, auto-updates on create/delete.
- Play History is fully stored and displayed as a clear timeline.
- Fixed minor issues with routing, ESM modules, and history sync when changing songs.
- Admin page navigation works smoothly through the sidebar.
