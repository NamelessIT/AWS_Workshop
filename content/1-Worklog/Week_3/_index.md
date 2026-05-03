---
title: "Worklog Week 3"
weight: 3
chapter: false
pre: " <b> 1.3 </b> "
---

### 📌 Objectives

- Finalize Frontend structure and choose main libraries (React Router, Redux Toolkit, Axios).
- Design and build basic UI pages (Home, Login, Register).
- Connect Frontend to the Authentication system (Cognito).
- Contribute to Backend on Song, Artist, Album entities together with the team.

---

### 🛠 Tasks Performed

| Task                                                                                  | Start Date | End Date   | References                              |
| ------------------------------------------------------------------------------------- | ---------- | ---------- | --------------------------------------- |
| Analyze why React + Vite + Tailwind is chosen for Frontend (performance, ecosystem)   | 23/03/2026 | 23/03/2026 |                                         |
| Configure React Router for navigation between pages                                   | 23/03/2026 | 24/03/2026 | https://reactrouter.com/                |
| Install Redux Toolkit, set up initial store (auth slice, player slice)                | 24/03/2026 | 25/03/2026 | https://redux-toolkit.js.org/           |
| Design and build Home page UI (recommended music sections, main layout)               | 24/03/2026 | 26/03/2026 | https://tailwindcss.com/                |
| Build Login / Register UI, integrate with AWS Cognito                                 | 25/03/2026 | 27/03/2026 | https://docs.aws.amazon.com/cognito     |
| Participate in designing Song / Artist / Album entities (Backend) with the team       | 26/03/2026 | 28/03/2026 |                                         |
| Integrate CRUD Song API call from Frontend (fetch song list, render on Home)          | 27/03/2026 | 28/03/2026 |                                         |
| Test the Register – Login – receive JWT token flow from Cognito                       | 28/03/2026 | 29/03/2026 |                                         |

---

### ✅ Achievements

- Page navigation system works smoothly with React Router.
- Redux store is set up clearly, easy to extend with more slices (player, history, queue).
- Home page UI has nice layout, responsive, and matches Spotify theme.
- Cognito Authentication flow works successfully: register → receive verification code → login → get JWT token.
- Contributed to designing Song / Artist / Album entities on Backend.
- Frontend can fetch and display song list from real API.
- Clear understanding of how Frontend (React) and Backend (Lambda + API Gateway + Cognito) interact.
