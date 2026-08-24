<h1 align="center">Gourav Jain</h1>

<p align="center">
  Backend-focused CS student building real products, contributing to open source, and sharpening DSA.
</p>

<p align="center">
  <a href="https://gouravjain.me"><img src="https://img.shields.io/badge/Portfolio-gouravjain.me-0b1120?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://github.com/gouravj25551-afk"><img src="https://img.shields.io/badge/GitHub-gouravj25551--afk-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://x.com/Gourav_jain_7"><img src="https://img.shields.io/badge/X-@Gourav__jain__7-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
</p>

---

### Hi, I'm Gourav 👋

I'm a 19-year-old CS student from Haryana, India, drawn to the parts of software you don't see — the availability engine, the payment hold, the money ledger, the schema underneath. I like turning a fuzzy real-world problem into a system that behaves correctly under load.

Right now I'm focused on:

- **Backend engineering** — APIs, auth, payments and the data model behind a working product
- **Open source** — real, reviewed contributions to projects like Sugar Labs' Music Blocks and JSON Schema
- **DSA / problem solving** — building algorithmic depth through consistent practice
- **Shipping real projects** — end-to-end products, not just tutorials

---

## About Me

Most of what I build is full-stack with the weight on the server side. My recent work spans a salon-booking marketplace with a payment-hold flow and a Postgres money ledger (**Hasino**), a real-time OPD/clinic management SaaS with role-based access (**DocDoor**), and my own developer portfolio.

Along the way I've been contributing to open source — debugging a locale-loading bug and a fullscreen layout bug in **Music Blocks** (both merged), and reporting/fixing an asset bug in the **JSON Schema** website. I work mainly in **TypeScript, JavaScript and Python**, with **Node.js/Express** and **PostgreSQL/Prisma** on the backend.

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk_Auth-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## Featured Projects

### 🪑 [Hasino](https://github.com/gouravj25551-afk/Hasino)
> A salon-booking marketplace built around correct money handling.

**Stack:** TypeScript · PostgreSQL / PL&#47;pgSQL · Clerk · Razorpay · Docker

The interesting problem here is ordering: a booking **holds a chair while the customer pays** and only becomes real once Razorpay verifies the money — so two people can't buy the same slot and no booking exists without a paid, verified transaction behind it. Backed by an availability engine and a Postgres money ledger, with a public storefront and a separate admin panel.

### 🩺 [DocDoor](https://github.com/gouravj25551-afk/DocDoor) &nbsp;·&nbsp; [Live Demo](https://doc-door-kt6r-gouravj25551-afks-projects.vercel.app/)
> Real-time OPD / clinic management where every action reflects across the system instantly.

**Stack:** Next.js 16 (App Router, Server Actions) · TypeScript · Prisma · PostgreSQL · Clerk (RBAC)

Solves information silos in a clinic: a receptionist registers a patient and the doctor sees them in the digital queue immediately; a checkout increments the owner's revenue dashboard in real time. Role-based access separates receptionist, doctor and owner views.

### 🧑‍💻 [newPortfolio](https://github.com/gouravj25551-afk/newPortfolio) &nbsp;·&nbsp; [Live Demo](https://newportfolio-lac-six.vercel.app)
> A dark-first personal developer portfolio driven entirely by a single data file.

**Stack:** React · TypeScript · Vite · Tailwind CSS · Framer Motion

The whole site renders from one typed `site.ts` — change the data, the UI follows — and links/URLs left empty are honestly marked as "not provided yet" rather than faked.

---

## Open Source

I contribute small, well-scoped fixes to projects I actually use and read.

**✅ Merged**

| PR | Project | What it fixed |
|----|---------|---------------|
| [#8104](https://github.com/sugarlabs/musicblocks/pull/8104) | **sugarlabs/musicblocks** | Locale files 404'd for `enUS` / `enUK` / `zhCN` because the language menu ids didn't map to the translation-code filenames. Fixed the mapping (5 files). |
| [#8132](https://github.com/sugarlabs/musicblocks/pull/8132) | **sugarlabs/musicblocks** | The bottom-right canvas buttons floated ~150px above the corner in fullscreen. Pinned them to the viewport. |

**🔵 Open / In review**

- [sugarlabs/musicblocks#8205](https://github.com/sugarlabs/musicblocks/pull/8205) — stop a tooltip re-init from crashing Velocity in the toolbar
- [json-schema-org/website#2452](https://github.com/json-schema-org/website/pull/2452) — fix a broken avatar image path in a blog post

**🐛 Reported**

- [json-schema-org/website#2451](https://github.com/json-schema-org/website/issues/2451) — blog hero avatar 404 from a wrong file extension

---

## DSA / Problem Solving

I genuinely love problem solving. I've solved **350+ problems** across **LeetCode and Codeforces**, mostly in **C++**, and I practice consistently to build algorithmic depth. My [`DailyDSA`](https://github.com/gouravj25551-afk/DailyDSA) repo is where I track that habit.

[![LeetCode](https://img.shields.io/badge/LeetCode-JAINGOURAV-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/JAINGOURAV/)

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=gouravj25551-afk&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=tokyonight" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gouravj25551-afk&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=gouravj25551-afk&hide_border=true&theme=tokyonight" alt="GitHub streak" />
</p>

---

## Currently Learning

- **Backend depth** — Node.js / Express, authentication, and API design that holds up in production
- **Databases** — schema design, relations and query-level thinking with PostgreSQL and Prisma
- **DSA** — data structures and algorithms, one problem at a time
- **Open source** — reading large codebases and landing reviewed contributions

---

## Goals

- Build production-quality backend projects that handle real money and real state correctly
- Get meaningfully stronger at DSA and competitive programming
- Land more merged open-source contributions in established projects
- Keep shipping real-world software end to end, and grow into a well-rounded engineer

---

## Contact

- **Portfolio** — [gouravjain.me](https://gouravjain.me)
- **GitHub** — [@gouravj25551-afk](https://github.com/gouravj25551-afk)
- **LeetCode** — [JAINGOURAV](https://leetcode.com/u/JAINGOURAV/)
- **X / Twitter** — [@Gourav_jain_7](https://x.com/Gourav_jain_7)
- **Email** — [gourav.j25551@nst.rishihood.edu.in](mailto:gourav.j25551@nst.rishihood.edu.in)
<!-- LinkedIn — add link here once you share it -->
