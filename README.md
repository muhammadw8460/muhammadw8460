# Muhammad Wali-ur-Rehman

**Software Engineer** | Full-Stack Web Development · Systems Programming · Product Engineering

📍 Victoria, BC &nbsp;|&nbsp; 📧 walirehmanmtd@gmail.com &nbsp;|&nbsp; 🔗 [linkedin.com/in/wali-rehman-14b706253](https://linkedin.com/in/wali-rehman-14b706253)

---

## About Me

I build software that works — and can prove it. My background spans Quality Assurance at **ACD Systems** (120+ defects found, 25% coverage increase) through to full-stack products engineered from requirements to release. I apply principles from **Requirements Engineering (SENG 321)** and **Operating Systems (CSC 360)** to build systems that are not just functional, but defensible, testable, and production-aware.

Most recently, I completed **Forge v2** — a pitch-ready professional networking platform for UVic students focused on verified profiles, project collaboration, and connection-gated messaging. Through this build, I deepened my expertise in modern full-stack architecture, relational data modeling, webhook-driven identity sync, and real-time application flows.

---

## 🛠 Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

**Frameworks & Libraries**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_7-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge)

**Backend & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Supabase Realtime](https://img.shields.io/badge/Supabase_Realtime-3ECF8E?style=for-the-badge)
![Supabase Storage](https://img.shields.io/badge/Supabase_Storage-3ECF8E?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Tools & Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![JIRA](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

**Recently Learned & Applied**

![Clerk Webhooks](https://img.shields.io/badge/Clerk_Webhooks-6C47FF?style=for-the-badge)
![Prisma Migrations](https://img.shields.io/badge/Prisma_Migrations-2D3748?style=for-the-badge)
![Realtime Messaging](https://img.shields.io/badge/Realtime_Messaging-0EA5E9?style=for-the-badge)
![Form Validation](https://img.shields.io/badge/Form_Validation-F43F5E?style=for-the-badge)
![Storage Uploads](https://img.shields.io/badge/Storage_Uploads-10B981?style=for-the-badge)

---

## 🚀 Featured Projects

### Forge v2 — [forge-app-v2](https://github.com/muhammadw8460/forge-app-v2)

> A pitch-ready professional networking platform for UVic students to build verified profiles, find teammates, and grow real technical momentum.

**What it does:**
- Verified student profiles with onboarding data, GitHub sync, and visible technical credibility
- Project marketplace where students create projects, define open roles, and review applications
- Community feed for updates, questions, and project sharing with persisted comments
- Connection workflow that gates direct messaging until a request is accepted
- Real-time messaging powered by persisted PostgreSQL data and Supabase Realtime subscriptions
- Optional avatar uploads using Supabase Storage

**What I built and learned making this:**
- Designed a full relational application model for users, profiles, projects, roles, posts, connections, and messages using Prisma + Supabase Postgres
- Integrated **Clerk authentication** with webhook-driven syncing so identity flows stay separate from application data
- Built connection-gated messaging to keep communication intentional and product-aligned
- Layered real-time subscriptions on top of persisted data instead of relying on live transport alone
- Shipped modern app flows using **Next.js 16**, **React 19**, **Tailwind CSS 4**, **React Hook Form**, **Zod**, and **Framer Motion**

**Tech:** Next.js 16 · React 19 · TypeScript · Tailwind CSS 4 · Prisma 7 · Clerk · Supabase Postgres · Supabase Realtime · Supabase Storage · React Hook Form · Zod · Framer Motion · Vercel

---

### ♟ Chess Pro V2 — [chess-pro-v2](https://github.com/wali-rehman/chess-pro-v2)

> A professional-grade browser chess engine rebuilt in **Next.js + TypeScript** with a fully decoupled logic layer and 49 automated unit tests.

Engineered using Requirements Engineering principles (SENG 321) to ensure 100% adherence to FIDE chess rules, including edge cases like **En Passant**, **Stalemate**, and **Promotion**.

- Architected game logic as a pure TypeScript layer with zero React dependencies — fully unit-testable without a browser
- Implemented immutable state management with complete move history and undo/redo via board state snapshots
- Built check, checkmate, and stalemate detection scanning all legal moves after every turn
- **49 unit tests** covering move validation, piece setup, and coordinate logic using Vitest
- Separated UI from logic via custom React hooks (`useGameState`, `useMoveManager`, `useChessLogic`)

**Tech:** Next.js 15 · TypeScript · Tailwind CSS · Vitest · React Hooks · Vercel

---

### C++ Thread Pool — [cpp-thread-pool](https://github.com/muhammadw8460/cpp-thread-pool)

> A reusable C++17 thread pool implementation focused on predictable task scheduling, synchronization correctness, and clean shutdown behavior.

**What it does:**
- Maintains a fixed-size worker pool with a shared task queue
- Uses `std::condition_variable` for blocking wake-ups (no busy waiting)
- Exposes a `submit()` API that returns `std::future` values
- Runs queued tasks outside the queue lock for better worker throughput
- Guarantees graceful shutdown by notifying and joining all worker threads

**How I validated it:**
- Added behavioral tests for full task execution, correct future-returned results, and destructor shutdown semantics
- Built with modern CMake + C++17 using a separate demo target and test target
- Kept architecture split between public API (`include/ThreadPool.h`) and implementation (`src/ThreadPool.cpp`)

**Tech:** C++17 · std::thread · std::mutex · std::condition_variable · std::future · CMake · CTest

---

### Crow WebSocket Chat Server — [crow-chat-server](https://github.com/muhammadw8460/crow-chat-server)

Built a lightweight web chat server using **Crow + Mustache** with:
- username-based join flow,
- real-time messaging over WebSockets,
- and a simple frontend architecture (no heavy JS framework).

---

### Care Cast BC — [care-cast-bc](https://github.com/muhammadw8460/care-cast-bc)

> A modular forecasting pipeline for allied health workforce planning across BC health authorities.

- Built a reproducible data workflow from public BC sources through cleaning, integration, and modeling
- Implemented a Python preprocessing and quality-validation pipeline using Pandas and NumPy
- Integrated cleaned datasets into a unified analytical table using SQL and DuckDB
- Produced forecasting outputs with R (regression, trend projections, and report artifacts)
- Generated stakeholder-ready outputs including charts, forecast tables, and data quality summaries

**Tech:** Python · Pandas · NumPy · SQL · DuckDB · R · ggplot2

---

## Experience

**Quality Assurance Analyst Co-op** — ACD Systems *(Jan 2024 – Aug 2024)*
- Identified 120+ defects across product lines using black-box testing and JIRA
- Increased test coverage by 25% through comprehensive test plan design
- Delivered a 15% performance boost via recommended feature improvements
- Worked in Agile sprints using Git-based workflows alongside dev teams

---

## Education

**B.Eng. Software Engineering** — University of Victoria *(Expected Dec 2027)*

Relevant coursework: Algorithms & Data Structures · Operating Systems · Requirements Engineering · Human-Computer Interaction · Data Science for Software Engineering · Computability Theory

---

*"Ship it tested, or don't ship it."*
