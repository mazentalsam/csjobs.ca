# csjobs.ca — AI-Powered CS Job Matching for Canadian Students

> Find your next internship or co-op at Google, Shopify, Amazon, and 200+ more — matched to your resume by AI.

**Live site:** [csjobs.ca](https://csjobs.ca)

---

## What is csjobs.ca?

csjobs.ca is a job board built specifically for Canadian CS students. Unlike generic job boards that dump thousands of US roles, csjobs.ca:

- Scrapes and aggregates **200+ verified Canadian CS internships & co-ops** daily
- Uses **AI (Nova)** to match your resume to every role and score your fit (0–100%)
- Covers **FAANG, unicorns, banks, and fast-growing startups** hiring in Canada
- Tailors your resume bullets to match specific job descriptions in one click

---

## Features

### For Students (Free)
- Browse 200+ curated Canadian CS roles
- Filter by role type, city, company tier, work style
- Job alerts — get new postings emailed daily
- Save and track jobs

### For Pro Users ($7.99/month)
- **AI match scores** — see how well your resume fits each role
- **Nova AI Copilot** — ask questions about any job, get interview prep, skill gap analysis
- **Resume tailoring** — AI rewrites your bullets to match the JD
- **Unlock all roles** — FAANG, unicorn, and Fortune 500 roles hidden from free users
- **Application tracker** — Kanban board to manage your pipeline
- **Resume manager** — version control for tailored resumes

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python / Flask |
| Database | SQLite |
| Frontend | Vanilla HTML, CSS, JavaScript |
| AI | OpenAI GPT-4o |
| Payments | Stripe (subscriptions + trials) |
| Email | SendGrid |
| Auth | Flask-Login + Google OAuth |
| Hosting | Railway |
| Scraping | Custom scrapers (Greenhouse, Lever, Workday, direct APIs) |

---

## How It Works

1. **Scraping** — 15+ scrapers run daily pulling from Greenhouse, Lever, Workday, and direct APIs (Microsoft, Apple, SimplifyJobs)
2. **Deduplication & enrichment** — jobs are normalized, tagged by company tier, and enriched with salary data
3. **AI Matching** — when a user uploads their resume, Nova embeds it and scores each job for fit
4. **Resume Tailoring** — Nova rewrites resume bullet points to align with specific job descriptions

---

## Scraped Companies Include

Google · Shopify · Amazon · Microsoft · Meta · Stripe · Apple · Salesforce · Cohere · Airbnb · Netflix · Uber · RBC · TD Bank · LinkedIn · Manulife · Deloitte · Wattpad · Jobber · Datadog · MongoDB · HashiCorp · Scotiabank · CIBC · Bell · Accenture · Intuit · PwC · KPMG · Manulife · Sun Life · and 150+ more

---

## Screenshots

### Landing Page
![Landing page hero showing AI job matching](https://csjobs.ca/logos/logo.png)

> Live demo at [csjobs.ca](https://csjobs.ca)

---

## Pricing

| Plan | Price | Features |
|------|-------|----------|
| Free | $0/month | Browse listings, alerts, job tracker |
| Pro | $7.99/month | AI matching, Nova copilot, resume tailoring, all roles |

7-day free trial, no credit card required.

---

## Contact

**Email:** contact@csjobs.ca
**Site:** [csjobs.ca](https://csjobs.ca)

---

*Built for Canadian CS students by a Canadian CS student.*
