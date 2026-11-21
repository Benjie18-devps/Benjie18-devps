# 🎓 Scalify EDU: Excel 0 to Hero Academy

> A Scalify EDU product that teaches Excel from zero to advanced by having learners practice in a real spreadsheet inside the browser.

| | |
|---|---|
| **Type** | E-learning SaaS |
| **Status** | 🧪 Working prototype, being hardened for production |
| **Audience** | Students and professionals in LATAM who want to learn Excel |
| **My role** | Product owner, front-end developer, curriculum designer |
| **Source** | Private |

---

## ✨ Features
- **An in-browser spreadsheet** with a **formula engine I wrote myself**. Learners type real formulas and see real results.
- **Step-by-step tutorials** organized into a curriculum.
- **Graded certification tests** that check the learner's answers automatically.
- **Gamification**: XP, badges and a learner profile.
- **Admin portal** for editing the curriculum without touching code.
- Google sign-in.

---

## 🧱 Structure

```
src/
├── components/
│   ├── ExcelGrid.tsx      Interactive spreadsheet grid
│   ├── TutorialView.tsx   Lessons
│   ├── TestView.tsx       Graded certification tests
│   ├── ProfileView.tsx    XP, badges, progress
│   ├── AdminPortal.tsx    Curriculum editor
│   └── LoginPage.tsx
├── utils/
│   ├── excelEngine.ts     Formula parser and evaluator
│   └── googleAuth.ts      Google Identity Services
└── data/
    └── defaultCurriculum.ts
```

## 🛠️ Tech stack

| Area | Tech |
|---|---|
| Front end | React 19, TypeScript, Vite 6 |
| Styling & motion | Tailwind CSS v4, Motion, lucide icons |
| Auth | Google Identity Services |
| Origin | Started from a Google AI Studio draft, then rebuilt and extended |

## 🗺️ Roadmap
A backend for learner progress (data currently lives in the browser), payments, more courses, and production hardening of the formula engine.

---

## 📸 Screenshots

*Screenshots coming soon.*

<!-- To show screenshots: add the images to ./screenshots, then remove this comment wrapper.
| Spreadsheet lesson | Certification test | Profile & badges | Admin portal |
|---|---|---|---|
| ![Lesson](screenshots/lesson.png) | ![Test](screenshots/test.png) | ![Profile](screenshots/profile.png) | ![Admin](screenshots/admin.png) |
-->
