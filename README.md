## Hi, I'm Karthik 👋

**Product manager in cards, payments and banking**, based in Bengaluru.
Previously at Deloitte, RBL Bank and Publicis Sapient.

I answer product questions with working software instead of a slide, usually
with Gen-AI and agentic workflows doing the heavy lifting.

**Interested in:** payments infrastructure · lending and credit decisioning ·
agentic AI in financial services · turning product ideas into working prototypes.

---

### ⭐ Start here

#### 1. Credit Underwriting Platform · [live demo](https://credit-underwriting-zeta.vercel.app) · private repo

> *Can a lender let AI read the documents without letting it make the credit decision?*

A proof-of-concept underwriting platform for Indian personal loans and credit
cards. Models read payslips and bank statements only after a redaction layer has
replaced PAN, Aadhaar, account numbers and contact details with tokens. A
deterministic five-layer policy engine (eligibility, hard policy, business
rules, scorecard, fraud) makes every decision, with reason codes on approvals
too. Decisions go to an append-only ledger and replay byte-identically, a policy
diff shows which applications flip when one rule changes, and an underwriter
console handles referrals and delegated authority across fifteen synthetic
borrowers.
<sub>Python · FastAPI · Next.js · TypeScript · Postgres · Claude API</sub>

#### 2. [UPI · eNACH · Card Autopay Recovery Simulator](https://github.com/karthikraoofficial/Autopay_recovery_simulator-recommender) · [live demo](https://autopay-recovery-simulator-recommen.vercel.app/)

> *When a recurring debit fails, what is a better retry policy actually worth?*

A discrete-event simulator and scoring service for UPI AutoPay, eNACH and card
e-mandates. It measures competing retry strategies on a synthetic mandate book
and recommends a retry time, with the evidence behind it.
<sub>Python · FastAPI · React</sub>

#### 3. [Tamper Scanner](https://github.com/karthikraoofficial/tamper-scanner) · [live demo](https://tamper-scanner-five.vercel.app/)

> *Has this bank statement PDF been tampered with?*

Deterministic PDF forensics collect the evidence, and an optional LLM assessor
gives a verdict that cites it. Every decision leaves an audit trail, reviewer
corrections become regression cases, and a new model or prompt must pass eval
thresholds before it's promoted.
<sub>Python · FastAPI · OpenAI API</sub>

---

### 💳 More fintech

| Project | The question it answers | Built with |
|---|---|---|
| **ITR Schedule FA CSV** · [live demo](https://itr-fa-a3-csv.onrender.com) · private repo | Hold foreign shares? Upload a holdings sheet in any layout, pay ₹50, get the CSV the ITR utility imports. Claude maps the columns; code checks every figure. | Next.js · Postgres · Claude API · Razorpay |
| **[Bank Statement Categorizer](https://github.com/karthikraoofficial/Statement-Categorizer)** | A self-correcting AI loop writes a rulebook that categorises card transactions to 95% accuracy, then runs at zero tokens. | Python · FastAPI · Claude API |
| **[Zerodha Basket Planner](https://github.com/karthikraoofficial/zerodha-basket-planner)** · [live demo](https://zerodha-basket-planner.vercel.app) | Given a ranked stock list and a fixed amount, how many shares of each should you buy? Read-only: it can't place orders. | Next.js · TypeScript · Kite Connect |
| **[n8n AI agent workflows](https://github.com/karthikraoofficial/my-n8n-workflows)** | Agents for stock analysis, holdings recommendations, real-time fraud-risk scoring and thin-file loan eligibility. | n8n |

### 🛠️ Tools and apps

| Project | What it does | Built with |
|---|---|---|
| **[YouTube Description Editor](https://github.com/karthikraoofficial/youtube-description-editor)** · [live app](https://youtube-video-description-editor.vercel.app) | Bulk-edit descriptions, titles and tags across hundreds of videos, with a diff for each one, a backup before every write and one-click restore. | Python · FastAPI · React · YouTube Data API |
| **[Job Portal](https://github.com/karthikraoofficial/Job-Portal-Employer_Employee)** · [live demo](https://job-portal-employer-employee.vercel.app/login) | Two-sided hiring: employers run an applicant pipeline, job seekers search, apply and track every status change. | Next.js · Prisma · PostgreSQL |

### 🏠 Home lab: debloating, safely

Same approach on each device: back up first, change in small reversible steps, and
prove with checks that nothing I use broke.

| Project | What it does | Built with |
|---|---|---|
| **[Windows Debloat](https://github.com/karthikraoofficial/windows-debloat)** | Strips ads, Copilot, Xbox extras and preinstalled apps from a Windows 11 laptop with Win11Debloat at a pinned release. Pester tests prove the Store, Update and every app I use still work, and were re-run after the 26H2 update. | PowerShell · Pester · Claude Code |
| **[Clean My TV](https://github.com/karthikraoofficial/clean-my-tv-acer)** · [before/after](https://github.com/karthikraoofficial/clean-my-tv-acer#screenshots) | Ad-free Acer Google TV without rooting: nine ad and telemetry packages disabled over ADB, with streaming, Chromecast, voice and Live TV still working. | ADB · PowerShell · Android |

### 🎸 Off the keyboard

I set up and repair guitars, and play metal and rock.
[My guitar collection →](https://karthik-guitar-collection.vercel.app) ·
[Karthik's Guitar Clinic →](https://karthiksguitarclinic.lovable.app/) ·
[Luthier services →](https://github.com/karthikraoofficial/luthierservices)
