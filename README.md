<h1 align="center">Hi, I'm Benjamin Gonzalez 👋</h1>

<p align="center">
  <b>Full-stack builder · Power Platform developer · Founder of <a href="https://scalifypanama.com">Scalify Panama</a></b><br/>
  I turn messy business processes into shipped software, and I build them alongside AI agents.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Panama-0A66C2?style=flat-square" alt="Location: Panama"/>
  <img src="https://img.shields.io/badge/Languages-Español%20%7C%20English-2EA44F?style=flat-square" alt="Languages: Spanish and English"/>
  <img src="https://img.shields.io/badge/AI--assisted%20dev-Claude%20Code-D97757?style=flat-square" alt="AI-assisted development with Claude Code"/>
</p>

<!-- TODO(Benjamin): add LinkedIn / email / portfolio links here once confirmed -->

---

## 🧭 About me

- 🏢 I build **enterprise tools on the Microsoft Power Platform**, including QA auditing, employee gamification, ETL pipelines and automated reporting, for a BPO / contact-center operation.
- 🚀 I founded **[Scalify Panama](https://scalifypanama.com)**, a consultancy that helps LATAM businesses and entrepreneurs with web development, process automation, digital infrastructure, branding and education.
- 📱 I'm building **ShopIQScan**, an offline-first Android app that helps Panamanian shoppers compare grocery prices across stores.
- 🤖 I work with AI coding agents every day, and I treat them as teammates who need clear specs, guardrails and review.
- 🌎 I'm bilingual. I ship Spanish-first products for the LATAM market and write technical docs in English.

<!-- TODO(Benjamin): years of experience, education / certifications, current role title -->

---

## 🛠️ Tech stack

| Area | Tools I've shipped with |
|---|---|
| **Languages** | TypeScript, JavaScript, Kotlin, SQL (PostgreSQL, T-SQL), Python, PowerShell, HTML/CSS |
| **Frontend** | React 19, Next.js (App Router, static export), Vite, Tailwind CSS v4, Fluent UI v9, TanStack Query, GSAP |
| **Mobile** | Android: Jetpack Compose, Material 3, Room, Koin, CameraX, ML Kit barcode scanning, WorkManager |
| **Microsoft Power Platform** | Power Apps (Canvas and **Code Apps**), Power Automate, SharePoint lists, `pac` CLI |
| **Data** | PostgreSQL (migrations, triggers, pgcrypto encryption), MS SQL Server (SQL Agent jobs, Database Mail), Python ETL pipelines, Supabase |
| **Cloud & deploy** | Cloudflare Workers, D1, R2 and Pages, Wrangler, custom domains and DNS |
| **Quality** | Vitest, unit and migration tests, ESLint, mutation-checked tests, rollback scripts and runbooks |
| **Reporting** | ExcelJS (branded client reports), jsPDF, HTML email templates |
| **Design & brand** | Brand books, WCAG contrast audits, design tokens, Play Store assets, M3E Canvas |
| **AI tooling** | Claude Code, Google AI Studio, multi-agent instruction files (Claude, Gemini, Codex, Cursor) |

---

## 📂 Featured work

### 🌐 [Scalify Panama: website](https://scalifypanama.com) · [repo](https://github.com/Benjie18-devps/ScalifyPanama_Website)
The marketing site for my consultancy, live at **scalifypanama.com**.
- Next.js 16, React 19, TypeScript (strict mode) and Tailwind v4, deployed as a static site on **Cloudflare Workers** with a documented rollback path.
- **307 tests across 21 files**. They catch content drift, legal pages that contradict the code, and layout regressions.
- A brand book with measured WCAG contrast, plus a full set of docs: status, changelog, deployment runbook, pricing and services.

### 📱 [ShopIQScan](https://github.com/Benjie18-devps/ShopIQScan): offline-first grocery price tracker (Android)
Scan a barcode, log the price, and the app tells you when the same item is cheaper at another store.
- Kotlin, Jetpack Compose, Material 3 and a Room database with migration tests, all in a clean `ui → domain ← data` architecture.
- Prices are kept as **append-only observations** and stored as **integer cents**, and the app works **fully offline**. Cloud sync is optional.
- The optional sync backend uses a **Cloudflare Worker, D1 and R2**, with JWT sessions and Google Sign-In.
- Includes a full brand kit plus Python scripts that generate the brand book and Play Store assets. Signed test builds have been verified on real devices.

### ✅ Enterprise QA Auditing Platform *(private, built for my employer)*
A production **Power Apps Code App** (React, TypeScript and Fluent UI) that replaced older canvas apps for quality-assurance audits.
- Versioned scorecards, an appeals workflow, and weekly **bilingual (ES/EN) feedback emails with PDF attachments**.
- Branded **Excel reports** for clients.
- **PostgreSQL** backend with 14 numbered migrations and rollback scripts. Audit logs are append-only, enforced by triggers, and sensitive fields are encrypted with AES-256.
- A reusable passwordless sign-in module that emails a 6-digit code, plus a mock-data mode for safe local development.

### 🎮 Employee Gamification Platform *(private, built for my employer)*
A Power Apps platform where employees earn points, coins and levels from their weekly KPIs. It has five modules: stats, missions, kudos, a store and a leaderboard.
- **Python ETL** from PostgreSQL to **MS SQL Server**, scheduled with SQL Agent jobs and Database Mail.
- **Power Automate** flows and HTML notification cards for level-ups, birthdays and anniversaries.
- A standard operating procedure (SOP), README and process doc for every module, plus a prioritized backlog and a 600+ line changelog.

### 🎓 [Scalify EDU: Excel 0 to Hero Academy](https://github.com/ScalifyPanama/ScalifyEDU_LearningPlatfrom) *(prototype)*
A React and Vite learning platform with an **in-browser spreadsheet and a hand-written formula engine**. It has graded certification tests, XP and badges, and an admin curriculum editor. I started it from a Google AI Studio draft and I'm hardening it into a product.

---

## 💪 Strengths

- **Ship to production.** Live website, live enterprise app, signed mobile builds. I finish things.
- **Documentation discipline.** Every project has STATUS, CHANGELOG, TODOs and session notes. Anyone, human or AI, can pick up where I left off.
- **Data integrity first.** Append-only logs, integer money, encrypted sensitive fields, numbered migrations with rollbacks.
- **Business + tech.** I write pricing, services and SOPs as well as code, so I can talk to clients, managers and compliance teams.
- **Security-aware.** Credentials stay out of repos, server IPs are masked, and sensitive deploy and DNS steps are kept for a human.

---

## 🗣️ Communication

| Language | Level | Evidence |
|---|---|---|
| 🇵🇦 **Spanish** | Native <!-- TODO(Benjamin): confirm --> | Spanish-first products: the Scalify site, legal pages, app UI and feedback emails |
| 🇺🇸 **English** | Professional <!-- TODO(Benjamin): confirm level / certification --> | All technical docs, runbooks, commit history and agent instructions are in English |

I write clear, structured technical documentation, and I can explain the same system to a developer, a client, or a compliance reviewer.

---

## 🤖 Working with AI agents: rated by Claude

> *This rating comes from Claude (Anthropic's AI). It's based on reviewing Benjamin's real repositories: instruction files, session notes, and 260+ commits, of which roughly 120 were co-authored with Claude.*

### Overall: **8.5 / 10** ⭐⭐⭐⭐☆

| Skill | Score | What I saw |
|---|:---:|---|
| Context & instructions | **9.5** | Agent instruction files with stack and version tables, a required reading order, project rules that can't be broken, and the commands that must pass before work counts as done. One set of instructions is written to work with Claude, Gemini, Codex and Cursor. |
| Guardrails & safety | **9** | Agents may not invent prices or copy. Deploy and DNS steps are kept for a human, and secrets stay out of the repo. Rules are written down after real incidents. |
| Continuity between sessions | **9** | Session notes are added to, never rewritten, and end with an explicit handoff, so a new session picks up exactly where the last one stopped. |
| Review & ownership | **9** | Benjamin reviews and runs every commit himself. The agent hands back the message and doesn't commit on its own. |
| Verification culture | **8.5** | Tests are mutation-checked, bugs are confirmed by running the app, and test counts go in commit messages. |
| Tooling automation | **6.5** | Mostly ad-hoc permission settings. No custom slash commands, sub-agents or CI pipelines yet. |

**Strengths:** He gives an agent what a senior teammate would need: the goal, the constraints, the history and a definition of done. He also keeps the final call on decisions. That makes AI output dependable instead of lucky.

**Room to grow:** Encode repeat workflows as custom commands and skills, add CI so checks run without being asked, and keep the occasional rushed commit (`Updated`) as consistent as the rest of the history.

---

## 📫 Let's connect

<!-- TODO(Benjamin): fill in -->
- 🌐 [scalifypanama.com](https://scalifypanama.com)
- 💼 LinkedIn: *coming soon*
- ✉️ Email: *coming soon*

<p align="center"><i>Hecho en Panamá 🇵🇦 · Built with care and a good AI teammate.</i></p>
