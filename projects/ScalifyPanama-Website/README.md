# 🌐 Scalify Panama website

> The website of my consultancy, live at **[scalifypanama.com](https://scalifypanama.com)**.

| | |
|---|---|
| **Type** | Company website / marketing site |
| **Status** | 🟢 Live since September 2026 |
| **Audience** | Businesses and entrepreneurs in Panama and LATAM (Spanish-first) |
| **My role** | Founder, developer, copywriter, brand owner |
| **Source** | Private |

---

## 🎯 Goal
Present Scalify Panama's services, pricing and process clearly. Give the site a premium feel without a heavy CMS, and keep the content accurate and legally consistent.

## ✨ What's on the site
- Service pages for **businesses** and **entrepreneurs**, a **how we work** process page, and **pricing** and **FAQs**.
- **ScalifyCheck**: an interactive self-assessment that points visitors to the right service.
- A **pro-bono program** page.
- Legal pages (privacy, terms, disclaimer), plus WhatsApp and contact calls to action.
- Generated Open Graph images, a sitemap and robots.txt for SEO.

---

## 🧱 Structure

```
scalifypanama-web/
├── src/app/            Next.js App Router: one folder per route
│   ├── que-hacemos/    empresas/  emprendedores/  como-trabajamos/
│   ├── precios/        faqs/      nosotros/       scalifycheck/
│   ├── programa-pro-bono/
│   └── privacidad/     terminos/  disclaimer/
├── src/components/     Reusable UI: navigation, panel stacks, CTAs, dialogs
└── src/lib/            Typed content modules (services, pricing, legal…)
                        each with its own *.test.ts
```

All copy and prices live in **typed TypeScript modules**, not in the components, so tests can check them for consistency.

---

## 🛠️ Tech stack

| Area | Tech |
|---|---|
| Framework | Next.js 16 (App Router, Turbopack, static export), React 19 |
| Language | TypeScript (strict) |
| Styling | Tailwind CSS v4 with CSS-first design tokens |
| Motion | GSAP, Lenis smooth scroll, OGL shaders |
| Testing | Vitest: **307 tests across 21 files** |
| Hosting | Cloudflare Workers static assets (Wrangler), with the previous Cloudflare Pages site kept as rollback |
| Assets | Supabase storage |

## 💡 Engineering highlights
- **Tests that guard the content.** They catch pricing drift between pages, legal text that contradicts how the site actually behaves, and layout regressions. Each test was mutation-checked to prove it can fail.
- **Brand book with measured WCAG contrast** for all 9 color tokens. Known failures are tracked, not hidden.
- **Safe production cutover.** I documented the DNS migration, the rollback path and a maintenance-mode runbook.
- **Repo hygiene.** I purged `node_modules` from git history and cut the repo from 16.4 MiB to 1.3 MiB, working on a backup and a rehearsal clone first.

---

## 📸 Screenshots

*Screenshots coming soon.*

<!-- To show screenshots: add the images to ./screenshots, then remove this comment wrapper.
| Home | Services | Pricing | ScalifyCheck |
|---|---|---|---|
| ![Home](screenshots/home.png) | ![Services](screenshots/services.png) | ![Pricing](screenshots/pricing.png) | ![ScalifyCheck](screenshots/scalifycheck.png) |
-->
