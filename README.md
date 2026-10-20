# MisBug

A bug tracker with a Node.js and Express backend and a React frontend.

<img width="1657" height="840" alt="mis-bug screenshot" src="https://github.com/user-attachments/assets/76f75994-d003-48ed-9848-c80d8709b853" />

## Features

- Create, edit and delete bugs, with severity and labels
- Filter, sort and paginate the bug list
- Signup, login and logout, with an encrypted login token in a cookie
- Admins can manage users, and every user has a page with their own bugs
- A cookie limits how many bugs a visitor can open within a few seconds

## Tech

- Backend: Node.js, Express, cookie-parser and Cryptr, with data stored in JSON files
- Frontend: React, React Router and Axios, loaded in the browser (no build step), served from `public/`

## Run locally

```bash
npm install
node server.js
```

Then open http://localhost:3030

---

Built by **Yahav Mor** · [Portfolio](https://yahavmor.github.io) · [LinkedIn](https://www.linkedin.com/in/yahav-mor-566291270/) · [GitHub](https://github.com/yahavmor)
