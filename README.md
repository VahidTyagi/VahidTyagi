# VahidQA — Personal QA Knowledge Hub 🚀

> **Live Website** → [vahidqa-dev.vercel.app](https://vahidqa-dev.vercel.app)

A personal QA knowledge website built by **Vahid Tyagi** — Senior QA Automation Engineer & SDET with 8+ years of experience. This site documents real-world QA notes, automation tutorials, and interview prep resources — helping me grow and giving back to the QA community.

---

## 🌐 What's on the Website

| Topic | Status | URL |
|---|---|---|
| 🌐 Manual Testing | ✅ Live | `/notes/manual-testing` |
| ⚙️ Selenium WebDriver (Java) | ✅ Live | `/notes/selenium` |
| 🎭 Playwright (JS/TS) | ✅ Live | `/notes/playwright` |
| 🔗 API Testing — Network Tab + Postman + Rest Assured | ✅ Live | `/notes/api-testing` |
| 🗄️ SQL for Testers | ✅ Live | `/notes/sql-for-testers` |
| 🚀 CI/CD & DevOps for QA | ✅ Live | `/notes/cicd-devops` |
| 🧪 TestNG — Deep Guide + Interview Q&A | ✅ Live | `/notes/testng` |
| 🥒 Cucumber BDD — Complete Framework Guide | ✅ Live | `/notes/cucumber-bdd` |
| 🤖 AI & Agentic QA Testing | ✅ Live | `/notes/ai-agentic-qa` |
| 🏗️ Framework Design Patterns | 🔄 Coming Soon | — |
| 📊 Allure & Extent Reports | 🔄 Coming Soon | — |
| 🎥 Video Tutorials | 🔄 Coming Soon | — |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Next.js 15 (App Router), React, TypeScript |
| **Styling** | Tailwind CSS v4 |
| **Database** | Supabase (PostgreSQL) |
| **Email** | Resend API |
| **Deployment** | Vercel (CI/CD — auto-deploys on every git push) |
| **Version Control** | Git + GitHub |
| **Font** | Syne (Google Fonts via Next.js) |

---

## ✨ Features

- 🔍 **Live search** across all notes topics
- 📊 **Progress tracker** — shows live vs coming soon topics
- 📬 **Contact form** — saves to Supabase + sends email notification via Resend
- 🏷️ **Full SEO** — meta tags, OG image, sitemap.xml, robots.txt, JSON-LD
- 📱 **Mobile responsive** — works on all screen sizes
- 🔗 **LinkedIn button** in global navbar
- ⚡ **Fast** — static generation with Next.js App Router

---

## 🗂️ Project Structure

```
vahidqa.dev/
├── app/
│   ├── layout.tsx              # Global navbar, SEO metadata, Google Analytics
│   ├── page.tsx                # Homepage — hero, search, notes grid, about, contact
│   ├── globals.css             # Global styles, Tailwind v4
│   ├── sitemap.ts              # Auto-generates /sitemap.xml
│   ├── robots.ts               # Auto-generates /robots.txt
│   ├── opengraph-image.tsx     # Dynamic OG image for social sharing
│   ├── about/
│   │   └── page.tsx            # Full resume — skills, experience, certs
│   ├── contact/
│   │   └── page.tsx            # Contact form with validation
│   ├── api/
│   │   └── contact/
│   │       └── route.ts        # API route — saves to Supabase + sends email
│   └── notes/
│       ├── manual-testing/
│       ├── selenium/
│       ├── playwright/
│       ├── api-testing/
│       ├── sql-for-testers/
│       ├── cicd-devops/
│       ├── testng/
│       ├── cucumber-bdd/
│       └── ai-agentic-qa/
├── .env.local                  # Supabase + Resend keys (not committed)
└── package.json
```

---

## 🚀 Running Locally

```bash
# Clone the repo
git clone https://github.com/VahidTyagi/vahidqa.dev.git
cd vahidqa.dev

# Install dependencies
npm install

# Set up environment variables
# Create .env.local and add:
# NEXT_PUBLIC_SUPABASE_URL=your_url
# NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
# SUPABASE_SERVICE_ROLE_KEY=your_key
# RESEND_API_KEY=your_key

# Start development server
npm run dev
# Open http://localhost:3000
```

---

## 🔁 CI/CD Pipeline

```
git push origin main
      ↓
GitHub receives code
      ↓
Vercel detects new commit
      ↓
Builds Next.js project automatically
      ↓
Deploys to vahidqa-dev.vercel.app ✅
```

Every push to `main` auto-deploys — zero manual steps needed.

---

## 👨‍💻 About the Author

**Vahid Tyagi** — Senior QA Automation Engineer & SDET

- 8+ years across FinTech, Banking, Payroll & eCommerce
- Currently: Testing Lead at DMI Finance Pvt. Ltd.
- Expert in: Selenium, Playwright, API Testing, CI/CD, AI-Enabled Testing

📧 [vahidtyagi007@gmail.com](mailto:vahidtyagi007@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/vahid-tyagi-953087bb)
🌐 [vahidqa-dev.vercel.app](https://vahidqa-dev.vercel.app)

---

> *"Breaking software so users don't have to."*
