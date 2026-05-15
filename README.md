# L'Agence French — Student Learning Portal

A responsive student portal prototype built for [L'Agence French](https://www.lagencefrench.com), a French language tutoring school based in Toronto. Developed as part of a web development placement application at Seneca Polytechnic.

Built with vanilla HTML, CSS, and JavaScript — no frameworks or build tools required.

---

## Features

- **Login flow** — email/password login with session state and sign out
- **Dashboard** — progress overview, streak tracker, upcoming class reminders, and latest teacher feedback
- **Lessons** — module-based lesson list with locked/unlocked states and in-progress tracking
- **Homework** — file upload with real file picker, 10 MB size validation, submission status, and grade display with teacher feedback per assignment
- **Messages** — two-column inbox with conversation threads, live compose, and simulated teacher replies
- **Practice today** — word of the day card with definition, example sentence, and drill CTA
- **Notification badges** — unread message indicators on sidebar and mobile nav, cleared on read
- **Account dropdown** — user info, account settings, and sign out
- **Responsive layout** — persistent sidebar on desktop, bottom navigation on mobile

---

## Screenshots

> Login · Dashboard · Lessons · Homework · Messages

*(Add screenshots here)*

---

## Stack

This is a frontend-only prototype. No build step or server required — open `index.html` directly in a browser.

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | [Tabler Icons](https://tabler.io/icons) |
| Typography | [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) · [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |

### Planned Production Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Flask (Python) |
| Auth | Supabase Auth |
| Database | PostgreSQL via Supabase |
| File storage | Supabase Storage |
| Hosting | Vercel (frontend) · Render (backend) |

---

## Getting Started

No installation needed.

```bash
git clone https://github.com/your-username/lagence-french-portal.git
cd lagence-french-portal
open index.html
```

Or just download the file and open it in any browser.

---

## Project Structure

```
lagence-french-portal/
└── index.html        # Full prototype — markup, styles, and scripts in one file
└── README.md
```

---

## Prototype Notes

- All data is static — no real backend, database, or authentication
- File uploads open the real file picker and validate size, but files are not sent anywhere
- The message composer simulates a reply after 1.5 seconds
- Login accepts any credentials

---

## About

Built by **Abenezer Balcha** as part of a placement application for L'Agence French via Seneca Polytechnic.

- Email: abbalcha@myseneca.ca
- School: Seneca Polytechnic, Toronto
