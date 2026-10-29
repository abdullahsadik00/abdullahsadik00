# Hi, I'm Sadik Shaikh

**Full-Stack Engineer (TypeScript · React · Node.js · PostgreSQL)**: I build products end to end, from the database schema and API to the UI people use.

I like backend-heavy problems: ingestion pipelines, auth, data modelling, and keeping slow work off the request path. I also ship the React frontends that sit on top of them. Based in Pune, India. Open to full-stack, backend and frontend roles.

---

## Featured projects

### [Logly](https://github.com/abdullahsadik00/logly): privacy-first web analytics
A Plausible-style analytics product: a small JS tracking snippet, an ingestion API, and a real-time dashboard.

- **Write path and read path kept separate:** the collector endpoint buffers events in Redis and returns immediately. A separate worker drains the buffer and batch-writes events and idempotent daily rollups to PostgreSQL.
- **Real-time** visitor count streamed to the dashboard over Server-Sent Events.
- **Stripe revenue attribution** with webhook signature verification, covered by unit tests.
- Architecture decisions are written up as ADRs in [`/decisions`](https://github.com/abdullahsadik00/logly/tree/main/decisions). CI type-checks, builds and tests both apps on every push.

`TypeScript` `Express` `Redis` `BullMQ` `PostgreSQL` `Prisma` `React` `TanStack Query` `Recharts` `GitHub Actions`

### Ed-Tech Platform: course marketplace · [**Live demo**](https://ed-tech-platform-frontend-two.vercel.app/login) ([frontend](https://github.com/abdullahsadik00/Ed-Tech-Platform-frontend) · [backend](https://github.com/abdullahsadik00/Ed-Tech-Platform-backend))
Instructors create and publish courses. Students enroll, watch lessons and track progress lesson by lesson.

- **REST API** in Express + TypeScript: JWT auth, role-based access (student/instructor), Zod request validation, Helmet and rate limiting.
- **PostgreSQL schema** designed in Prisma (37 models) with migrations.
- **React SPA**: TanStack Query for server state, Zustand for auth state, shadcn/ui + Tailwind. Includes a course player and an instructor course builder.
- **Deployed on Vercel + Neon Postgres.** Migrations and demo seed data run on every deploy. One-click demo logins for the student and instructor roles.

`TypeScript` `Node.js` `Express` `Prisma` `PostgreSQL` `React` `Vite` `TanStack Query` `Zustand` `Vercel` `Neon`

### [Todo++](https://github.com/abdullahsadik00/Todo-plus-plus): task manager (frontend focus)
Next.js App Router + Zustand (persist + immer). Features: drag-to-reorder with mouse and keyboard (dnd-kit), debounced search, derived selectors, keyboard shortcuts. Tested with Vitest + Testing Library.

`Next.js` `TypeScript` `Zustand` `dnd-kit` `Vitest`

### [NeuroSync](https://github.com/abdullahsadik00/Neuroscience-Habit-App): habit-recovery app
A habit tracker built around recovering from a miss instead of resetting a streak. It has a React 19 PWA (Zustand, offline-capable), a Flutter mobile app with Supabase auth and sync, and a Supabase Edge Function that verifies Stripe webhooks and unlocks the Pro tier.

`React` `TypeScript` `Zustand` `Flutter` `Supabase` `Stripe` `PostHog`

---

## Tech I work with

| Area | Tools |
|---|---|
| **Languages** | TypeScript, JavaScript, SQL, Dart |
| **Frontend** | React, Next.js, Vite, TanStack Query, Zustand, Tailwind CSS, shadcn/ui, React Hook Form |
| **Backend** | Node.js, Express, REST API design, JWT auth, Zod, BullMQ, Server-Sent Events |
| **Data** | PostgreSQL (Neon), Prisma, Redis, Supabase |
| **Tooling** | Git, GitHub Actions, Turborepo, Docker Compose (local dev), Vitest, Vercel |

---

## Let's talk

I'm **open to Full-Stack, Backend and Frontend Developer roles** (on-site in Pune, or remote).

📧 [sadikshaikh3012@gmail.com](mailto:sadikshaikh3012@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/shaikh-sadik/)
