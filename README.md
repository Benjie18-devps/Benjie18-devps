<p align="center">
  <img src="https://github.com/Benjie18-devps.png" width="140" alt="Benjamin Gonzalez" style="border-radius:50%"/>
</p>

<h1 align="center">Hi, I'm Benjamin Gonzalez 👋</h1>

<p align="center">
  <b>Founder of <a href="https://scalifypanama.com">Scalify Panama</a> · Solutions Developer · Power Platform Developer · Automation & BA/BI Analyst (Power BI / Excel)</b><br/>
  I turn messy business processes into shipped software, and I build them alongside AI agents.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Panama-0A66C2?style=flat-square" alt="Location: Panama"/>
  <img src="https://img.shields.io/badge/Languages-Español%20(native)%20%7C%20English%20(fluent)-2EA44F?style=flat-square" alt="Languages: Spanish native, English fluent"/>
  <img src="https://img.shields.io/badge/Self--taught-developer-8A2BE2?style=flat-square" alt="Self-taught developer"/>
  <img src="https://img.shields.io/badge/AI--assisted%20dev-Claude%20Code-D97757?style=flat-square" alt="AI-assisted development with Claude Code"/>
  <a href="https://github.com/Benjie18-devps/Benjie18-devps/actions/workflows/links.yml"><img src="https://github.com/Benjie18-devps/Benjie18-devps/actions/workflows/links.yml/badge.svg" alt="Link check"/></a>
</p>

<p align="center">
  <a href="https://scalifypanama.com"><img src="https://img.shields.io/badge/Website-scalifypanama.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="mailto:info@scalifypanama.com"><img src="https://img.shields.io/badge/Email-info%40scalifypanama.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://wa.me/50761604034"><img src="https://img.shields.io/badge/WhatsApp-%2B507%206160--4034-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
</p>

---

## 🧭 About me

- 🚀 I founded **[Scalify Panama](https://scalifypanama.com)**, a consultancy that helps LATAM businesses and entrepreneurs grow through technology, automation, branding and education.
- 🏢 I design and build **enterprise solutions on the Microsoft Power Platform**: QA auditing, employee gamification, ETL pipelines and automated reporting. They run in production at a BPO / contact-center operation.
- 📊 I work as an **Automation & BA/BI Analyst**, turning operational data into Power BI dashboards, Excel reports and automated workflows.
- 📱 I'm building **ShopIQScan**, an offline-first Android app that helps Panamanian shoppers compare grocery prices across stores.
- 🎓 I'm a **self-taught developer** with 2+ years of professional experience. I learn by building real products for real users.
- 🤖 I work with AI coding agents every day, and I treat them as teammates who need clear specs, guardrails and review.

---

## 🛠️ Tech stack

| Area | Tools I've shipped with |
|---|---|
| **Languages** | TypeScript, JavaScript, Kotlin, SQL (PostgreSQL, T-SQL), Python, PowerShell, HTML/CSS |
| **Frontend** | React 19, Next.js (App Router, static export), Vite, Tailwind CSS v4, Fluent UI v9, TanStack Query, GSAP |
| **Mobile** | Android: Jetpack Compose, Material 3, Room, Koin, CameraX, ML Kit barcode scanning, WorkManager |
| **Microsoft Power Platform** | Power Apps (Canvas and **Code Apps**), Power Automate, SharePoint lists, `pac` CLI |
| **BI & reporting** | Power BI, Excel (advanced formulas and reporting), ExcelJS (branded client reports), jsPDF, HTML email templates |
| **Data** | PostgreSQL (migrations, triggers, pgcrypto encryption), MS SQL Server (SQL Agent jobs, Database Mail), Python ETL pipelines, Supabase |
| **Cloud & deploy** | Cloudflare Workers, D1, R2 and Pages, Wrangler, custom domains and DNS |
| **Quality & CI** | GitHub Actions, Vitest, unit and migration tests, ESLint, mutation-checked tests, rollback scripts and runbooks |
| **Design & brand** | Brand books, WCAG contrast audits, design tokens, Play Store assets, M3E Canvas |
| **AI tooling** | Claude Code, Google AI Studio, multi-agent instruction files (Claude, Gemini, Codex, Cursor) |

---

## 🏢 Scalify Panama: what we offer

[Scalify Panama](https://scalifypanama.com) helps LATAM businesses and entrepreneurs scale with technology.

| Line | Services |
|---|---|
| 💻 **Digital services** | Web development, digital infrastructure, process automation, brand management |
| 📈 **Business development** | A 4-stage startup launch path, business strategy |
| 🧠 **Consulting** | General technology consulting |
| 🎓 **Scalify EDU** | Educational consulting, tutoring, educational projects |
| 🤝 **Pro-bono program** | Free support for selected projects with social impact. [Learn more](https://scalifypanama.com/programa-pro-bono) |

---

## 📂 Featured work

> Most of these are commercial SaaS products or run in production for clients, so their source code is private.
> Each one has a **public case study** with its architecture, tech stack and screenshots in [`projects/`](projects/README.md).

### 🌐 [Scalify Panama: website](https://scalifypanama.com) · [case study](projects/ScalifyPanama-Website/README.md)
The marketing site for my consultancy, live at **scalifypanama.com**.
- Next.js 16, React 19, TypeScript (strict mode) and Tailwind v4, deployed as a static site on **Cloudflare Workers** with a documented rollback path.
- **307 tests across 21 files**. They catch content drift, legal pages that contradict the code, and layout regressions.
- A brand book with measured WCAG contrast, plus a full set of docs: status, changelog, deployment runbook, pricing and services.

### ✅ QA Auditing Platform · [case study](projects/QA-Auditing-Platform/README.md) *(a Scalify Panama solution · private)*
I designed this solution and it's **in production at a BPO / contact-center operation**. It's a **Power Apps Code App** (React, TypeScript and Fluent UI) that replaced older canvas apps for quality-assurance audits.
- Versioned scorecards, an appeals workflow, and weekly **bilingual (ES/EN) feedback emails with PDF attachments**.
- Branded **Excel reports** for clients.
- **PostgreSQL** backend with 14 numbered migrations and rollback scripts. Audit logs are append-only, enforced by triggers, and sensitive fields are encrypted with AES-256.
- A reusable passwordless sign-in module that emails a 6-digit code, plus a mock-data mode for safe local development.

### 🎮 Employee Gamification Platform · [case study](projects/Gamification-Platform/README.md) *(a Scalify Panama solution · private)*
I designed this platform and it's **in production at a BPO / contact-center operation**. Employees earn points, coins and levels from their weekly KPIs, across five modules: stats, missions, kudos, a store and a leaderboard.
- **Python ETL** from PostgreSQL to **MS SQL Server**, scheduled with SQL Agent jobs and Database Mail.
- **Power Apps** front end with **Power Automate** flows and HTML notification cards for level-ups, birthdays and anniversaries.
- A standard operating procedure (SOP), README and process doc for every module, plus a prioritized backlog and a 600+ line changelog.

### 📱 ShopIQScan: offline-first grocery price tracker (Android) · [case study](projects/ShopIQScan/README.md) *(SaaS · private)*
Scan a barcode, log the price, and the app tells you when the same item is cheaper at another store.
- Kotlin, Jetpack Compose, Material 3 and a Room database with migration tests, all in a clean `ui → domain ← data` architecture.
- Prices are kept as **append-only observations** and stored as **integer cents**, and the app works **fully offline**. Cloud sync is optional.
- The optional sync backend uses a **Cloudflare Worker, D1 and R2**, with JWT sessions and Google Sign-In.
- Includes a full brand kit plus Python scripts that generate the brand book and Play Store assets. Signed test builds have been verified on real devices.

### 🎓 Scalify EDU: Excel 0 to Hero Academy · [case study](projects/ScalifyEDU-Excel-Academy/README.md) *(prototype · private)*
A React and Vite learning platform with an **in-browser spreadsheet and a hand-written formula engine**. It has graded certification tests, XP and badges, and an admin curriculum editor. I started it from a Google AI Studio draft and I'm hardening it into a product.

---

## 💪 Strengths

- **Ship to production.** Live website, enterprise apps in daily use, signed mobile builds. I finish things.
- **Documentation discipline.** Every project has STATUS, CHANGELOG, TODOs and session notes. Anyone, human or AI, can pick up where I left off.
- **Data integrity first.** Append-only logs, integer money, encrypted sensitive fields, numbered migrations with rollbacks.
- **Business + tech.** I write pricing, services and SOPs as well as code, so I can talk to clients, managers and compliance teams.
- **Security-aware.** Credentials stay out of repos, server IPs are masked, and sensitive deploy and DNS steps are kept for a human.

## 🤝 Soft skills

- **Leadership.** I lead projects from idea to production and coordinate the people who use them.
- **Teaching & tutoring.** I train users and teach Excel and technology through Scalify EDU.
- **Contact-center & QA operations.** I understand how BPO operations, KPIs and quality processes really work, from the floor up.
- **Project & client management.** I handle scoping, pricing, delivery timelines and day-to-day client communication.

---

## 🗣️ Communication

| Language | Level | Evidence |
|---|---|---|
| 🇵🇦 **Spanish** | Native | Spanish-first products: the Scalify site, legal pages, app UI and feedback emails |
| 🇺🇸 **English** | Fluent | All technical docs, runbooks, commit history and agent instructions are in English |

I write clear, structured technical documentation, and I can explain the same system to a developer, a client, or a compliance reviewer.

---

## 🤖 Working with AI agents: rated by Claude

> *This rating comes from Claude (Anthropic's AI). It's based on reviewing Benjamin's real repositories: instruction files, session notes, and 260+ commits, of which roughly 120 were co-authored with Claude.*

### Overall: **8.7 / 10** ⭐⭐⭐⭐☆

| Skill | Score | What I saw |
|---|:---:|---|
| Context & instructions | **9.5** | Agent instruction files with stack and version tables, a required reading order, project rules that can't be broken, and the commands that must pass before work counts as done. One set of instructions is written to work with Claude, Gemini, Codex and Cursor. |
| Guardrails & safety | **9** | Agents may not invent prices or copy. Deploy and DNS steps are kept for a human, and secrets stay out of the repo. Rules are written down after real incidents. |
| Continuity between sessions | **9** | Session notes are added to, never rewritten, and end with an explicit handoff, so a new session picks up exactly where the last one stopped. |
| Review & ownership | **9** | Benjamin reviews and runs every commit himself. The agent hands back the message and doesn't commit on its own. |
| Verification culture | **8.5** | Tests are mutation-checked, bugs are confirmed by running the app, and test counts go in commit messages. |
| Tooling automation | **7.5** | GitHub Actions CI now runs lint, tests and builds on every push for his main products, plus a weekly link check on this profile. There are no custom slash commands or sub-agents yet. |

**Strengths:** He gives an agent what a senior teammate would need: the goal, the constraints, the history and a definition of done. He also keeps the final call on decisions. That makes AI output dependable instead of lucky.

**Room to grow:** Encode repeat workflows as custom commands and skills, extend CI to the enterprise apps, and keep the occasional rushed commit (`Updated`) as consistent as the rest of the history.

---

## 📊 GitHub stats

<p align="center">
  <img src="metrics.svg" alt="GitHub activity, languages and contribution calendar (includes private work)"/>
</p>
<p align="center"><sub>Updated daily by a GitHub Action. Most of my work lives in private repos, so this counts private commits and languages without showing the repos.</sub></p>

---

## 🎯 Off the keyboard

- 🔧 **Handyman.** If it's broken, I'll try to fix it, with or without a keyboard.
- 🏎️ **F1 fan.**
- ♟️ **Chess addict.**
- 🏉 **Rugby fan.**
- 🤼 **Sumo fan.**

> 💡 **Fun fact:** I honestly don't know how I picked up everything I know. I just kept building.

---

## 📫 Let's connect

- 🌐 **Website:** [scalifypanama.com](https://scalifypanama.com)
- ✉️ **Email:** [info@scalifypanama.com](mailto:info@scalifypanama.com)
- 💬 **WhatsApp:** [+507 6160-4034](https://wa.me/50761604034)

<p align="center"><i>Hecho en Panamá 🇵🇦 · Built with care and a good AI teammate.</i></p>
