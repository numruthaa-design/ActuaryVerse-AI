# 🎓 ActuaryVerse AI

**Play. Analyze. Predict. Become a General Insurance Actuary.**

An interactive, gamified, browser-based teaching platform for General Insurance / Property & Casualty actuarial education, built around a single flagship exercise: the **NovaShield Motor Insurance Premium Pricing Mission**.

Submitted to the **CAS Student Central Teaching Case Competition**.

---

![Status](https://img.shields.io/badge/status-classroom--ready-brightgreen)
![Platform](https://img.shields.io/badge/platform-HTML%20%2F%20CSS%20%2F%20JavaScript-blue)
![License](https://img.shields.io/badge/install-none%20required-orange)
![Hosting](https://img.shields.io/badge/hosting-GitHub%20Pages%20%7C%20Netlify%20%7C%20Vercel-informational)

---

## ✨ What This Is

Students are hired as a **Junior Pricing Actuary** at a fictional insurer, **NovaShield General Insurance**, which is launching a new private passenger motor product in India. Across 12 guided mission stages, students explore a realistic claims portfolio, calculate claim frequency and severity, build up a premium from pure premium through expense and profit loadings, and defend a final pricing recommendation — the way a real actuary would.

## 🧩 Features

- **No installation required** — pure HTML/CSS/JavaScript, runs in any modern browser
- **Gamified mission structure** — XP, progress tracking, mission roadmap, completion certificate
- **Real (synthetic) portfolio dataset** — 2,400 policies with an in-browser EDA playground (filter, group, chart)
- **Built-in calculators** — frequency, severity, pure premium, loss ratio, expense ratio, combined ratio
- **AI tutor & formula popups** — contextual hints without simply supplying the answer
- **Reflection journal** — saved locally in the student's browser
- **Hidden Instructor Mode** — teaching notes, rubrics, timing guide, and answer key
- **Fully offline-capable** once loaded — no account, login, or data collection

## 🎯 Learning Outcomes

By the end of the mission, students can:
- Calculate claim frequency, severity, and pure premium from raw portfolio data
- Apply expense and profit/risk loadings to build a full gross premium
- Interpret loss ratio, expense ratio, and combined ratio
- Justify pricing assumptions with reference to business, regulatory, and ethical considerations
- Communicate a pricing recommendation to a non-technical stakeholder

See the **CAS Submission Document** (`docs/CAS_Submission_Document.docx`) for the complete list of 15 measurable learning objectives.

## 📂 Repository Structure

```
ActuaryVerse-AI/
├── index.html                          # The complete application (self-contained)
├── README.md                           # This file
├── assets/
│   └── datasets/
│       ├── novashield_policies.csv     # 2,400-row synthetic motor portfolio
│       └── novashield_policies.xlsx    # Same data + data dictionary + read-me sheet
└── docs/
    ├── CAS_Submission_Document.docx    # Sections 1–10, full CAS submission
    ├── Student_Workbook.docx           # Fillable, stage-by-stage student workbook
    ├── Instructor_Guide.docx           # Lesson plans, facilitation notes, timing
    ├── Solution_Booklet.docx           # Instructor-only worked answer key
    ├── Quick_Reference_Sheet.docx      # One-page formula & glossary sheet
    ├── ActuaryVerse_AI_Presentation.pptx  # 15-slide instructor deck
    └── Demo_Video_Script.docx          # Storyboard + narration for a demo video
```

> **Note:** `index.html` is fully self-contained (HTML, CSS, and JavaScript in one file) for maximum portability — there is no separate `style.css` or `script.js` to manage.

## 📊 About the Dataset

`novashield_policies.csv` / `.xlsx` contain 2,400 synthetic policies (1,000 Tier 1 / 800 Tier 2 / 600 Tier 3 city policies). The dataset is generated with a **fixed random seed**, so its aggregate claim frequency, severity, and pure premium by City Tier match the worked example in the Solution Booklet exactly — instructors and students can compare results directly. Fields with no claim (Claim Amount, Accident Type, Weather) are blank by design, not a data error. Full variable definitions are in the **Data Dictionary** sheet of the Excel file and in Section 5 of the CAS Submission Document.

## 🚀 Hosting Instructions (All Free)

No installation, no Python, no Node.js, no packages. Pick any one option:

### Option A — Run Locally
Download this repository as a ZIP, extract it, and double-click `index.html`. Done.

### Option B — GitHub Pages
1. Fork or upload this repository to your own GitHub account.
2. Go to **Settings → Pages**, set Source to the `main` branch, and Save.
3. Your live link: `https://YOUR-USERNAME.github.io/ActuaryVerse-AI/`

### Option C — Netlify
1. Sign up free at [netlify.com](https://netlify.com).
2. Drag and drop this folder onto the Netlify dashboard's deploy area.
3. Optionally rename your site under **Site configuration → Change site name** for a custom URL like `actuaryverse-ai.netlify.app`.

### Option D — Vercel
1. Sign up free at [vercel.com](https://vercel.com).
2. Import this repository (or drag-and-drop the folder) and click **Deploy**.
3. Live in seconds at `your-project-name.vercel.app`.

Works fully offline once downloaded, and in Chrome, Edge, and Firefox on Windows, macOS, and ChromeOS.

## 🏫 For Instructors

Start with `docs/Instructor_Guide.docx` for lesson plans (2-hour workshop, 4-hour lab, or one-week unit), then use `docs/Solution_Booklet.docx` as your answer key while grading. The application's hidden Instructor Mode mirrors this same content for in-app reference.

## 🏆 CAS Student Central Competition

This submission targets the CAS Student Central Teaching Case Competition judging criteria: real-world actuarial relevance, General Insurance / P&C focus, classroom readiness, pedagogical effectiveness, engagement, innovation, technical rigor, clear presentation, instructor usability, and measurable student learning outcomes. See `docs/CAS_Submission_Document.docx` for the complete mapping.

---

*Built for actuarial students and instructors everywhere. No login, no cost, no installation — just open `index.html` and start the mission.*
