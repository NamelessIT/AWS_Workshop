---
title: "Worklog Week 7"
date: "2026-04-20"
weight: 7
chapter: false
pre: " <b> 1.7 </b> "
---

### 📌 Objectives

- Participate in building the Genre/Category system (Backend + Frontend) with the team.
- Support multi-genre for songs (one song can belong to multiple genres).
- Improve responsive UI on mobile and fix remaining bugs.
- Seed data, test the entire system, and finalize the product for delivery.

---

### 🛠 Tasks Performed

| Task                                                                                            | Start Date | End Date   | References                              |
| ----------------------------------------------------------------------------------------------- | ---------- | ---------- | --------------------------------------- |
| Participate in designing `genre` field for Song entity and `GenreIndex` GSI on DynamoDB         | 20/04/2026 | 20/04/2026 | https://docs.aws.amazon.com/dynamodb    |
| Contribute to CRUD API for Genre/Category (handler endpoint with the team)                      | 20/04/2026 | 20/04/2026 |                                         |
| Sync `songCount` between Artist and Song on create / delete                                     | 20/04/2026 | 20/04/2026 |                                         |
| Frontend: connect Categories Page to real Category API, support multi-genre upload and edit     | 20/04/2026 | 22/04/2026 |                                         |
| Admin Dashboard: add genre column, format date display                                          | 20/04/2026 | 20/04/2026 |                                         |
| Improve responsive UI on mobile (fix `mb-20` on HomePage to avoid being covered by PlayerBar)   | 22/04/2026 | 24/04/2026 |                                         |
| Fix `artist_id` not persisting, redirect after reload, SearchBar dropdown                       | 22/04/2026 | 22/04/2026 |                                         |
| Fix EditSongPage, ProfilePage follow artists, getSongsByArtist API returning correct data       | 26/04/2026 | 26/04/2026 |                                         |
| Open Login Modal when ProtectedRoute redirects (better UX)                                      | 26/04/2026 | 26/04/2026 |                                         |
| Add Footer page for the website                                                                 | 27/04/2026 | 27/04/2026 |                                         |
| Improve ProfilePage: display Artist info, follow / unfollow                                     | 22/04/2026 | 29/04/2026 |                                         |
| Improve Search: filter tabs, expand genre list                                                  | 29/04/2026 | 01/05/2026 |                                         |
| Seed sample data (artists, songs, genres) for demo                                              | 29/04/2026 | 01/05/2026 |                                         |
| Manual testing of the whole system, fix UI bugs                                                 | 02/05/2026 | 07/05/2026 |                                         |
| Finalize internship report and deploy the final version                                         | 07/05/2026 | 09/05/2026 |                                         |

---

### ✅ Achievements

- The **Genre/Category system works fully** end-to-end — songs can belong to multiple genres and display nicely on the Categories page.
- DynamoDB GSI enables fast querying of songs by genre, avoiding full table scans.
- Admin Dashboard has a Genre column and clear date formatting.
- UI is responsive on mobile, no more PlayerBar overlap issues.
- Edge cases for Auth / Routing / EditSong / ProfilePage are fully resolved.
- Search works well with multiple filter tabs and an expanded genre list.
- Seed data is available to demo easily (many artists, songs, genres).
- **Final product complete**: a Spotify Clone with full features (register, login, upload, music playback, playlist with drag & drop, queue, history, notification, share, artist dashboard, admin panel, multi-genre, advanced search, mobile-responsive).
- Internship report finalized, ready for delivery.
