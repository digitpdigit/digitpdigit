# Hi, I'm Digit

I'm a software engineer in Yogyakarta, Indonesia. For about 5 years I've built
backend systems, mostly in TypeScript and NestJS. At work I own problems from the
first client conversation to production. On the side I build small products, a few
of them for Indonesian users.

I like asking whether something needs to be built, or needs AI, before I build it.

## Side projects

**[Pasak](https://github.com/dpraktikastudio/pasak-web)** · [live app](https://pasak-web-production.up.railway.app/)
A voice-first expense tracker for Indonesian speech. Whisper runs in the browser
(ONNX), so audio never leaves the device and expenses stay in IndexedDB. A small
FastAPI server only serves model manifests and takes opt-in, scrubbed text for training.
I fine-tuned whisper-small for Indonesian and cut word error rate on the FLEURS test
set from 36.1% to 14.4%. It still misses my own accuracy gate for amounts, and the
repo says so.
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**[Kapan Libur](https://github.com/dpraktikastudio/kapanlibur)** · [kapanlibur.com](https://kapanlibur.com)
Indonesian national holidays and cuti bersama, as an interactive calendar plus a
reference page for each year. Plain HTML, CSS and JavaScript with no framework. Holiday data is one JSON file per year,
and the build minifies the pages and validates the JSON-LD for SEO.
![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?style=flat-square&logo=javascript&logoColor=323330)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

**[Fast Todo](https://github.com/digitpdigit/fast-todo)**
An offline-first weekly planner for the desktop, with a week grid, color-coded tasks
and a system tray view for today. Data stays in a local SQLite file, with no account
and no cloud.
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-2C4F7C?style=flat-square&logo=solid&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

Also: [cron-hq](https://github.com/digitpdigit/cron-hq-node), a small dashboard and
API for scheduling outbound HTTP jobs with cron expressions.

## At work
- Architected a KPI performance management system for 30,000+ users at a state-owned enterprise
- Led an AWS to Huawei Cloud migration of an 11-service platform, about 37.8% lower cloud cost
- Cut AI video analysis cost by up to 80% by using the VLM only where it was needed
- Redis caching that took a user lookup from 100-200ms down to about 50ms

## What I use
![TypeScript](https://img.shields.io/badge/TypeScript-007BCD?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

## Reach me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dpraktikastudio/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dpraktikastudio@gmail.com)
