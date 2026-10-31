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

#### 2. [Job Portal](https://github.com/karthikraoofficial/Job-Portal-Employer_Employee) · [live demo](https://job-portal-employer-employee.vercel.app/login)

> *What does a complete two-sided hiring platform look like, end to end?*

Employers post roles and move applicants through a pipeline, and job seekers
search, apply and track every status change. Role checks run on every server
action, and resumes are validated by their file contents, not their extension.
<sub>Next.js · TypeScript · PostgreSQL · Prisma · Better Auth</sub>

#### 3. ITR Schedule FA · A3 CSV Generator · [live demo](https://itr-fa-a3-csv.onrender.com) · private repo

> *Can AI turn a messy foreign-holdings sheet into a tax filing without ever producing a number?*

A paid web app for Indians who hold foreign shares. Upload a holdings sheet in
any layout and get back the CSV the ITR utility imports for Schedule FA,
Section A3. Claude maps the columns, while code copies and checks every amount
and date and flags anything that looks wrong. The customer sees a masked
preview, pays ₹50 through Razorpay, and the payment is verified on the server
before the file unlocks.
<sub>Next.js · TypeScript · Neon Postgres · Claude API · Razorpay</sub>

---

### 💳 More fintech

| Project | The question it answers | Built with |
|---|---|---|
| **[UPI · eNACH · Card Autopay Recovery Simulator](https://github.com/karthikraoofficial/Autopay_recovery_simulator-recommender)** · [live demo](https://autopay-recovery-simulator-recommen.vercel.app/) | When a recurring debit fails, what is a better retry policy actually worth? Simulates retry strategies on a synthetic mandate book and recommends a retry time. | Python · FastAPI · React |
| **[Tamper Scanner](https://github.com/karthikraoofficial/tamper-scanner)** · [live demo](https://tamper-scanner-five.vercel.app/) | Has this bank statement PDF been tampered with? Deterministic forensics plus an LLM verdict that cites the evidence, gated by evals. | Python · FastAPI · OpenAI API |
| **[Bank Statement Categorizer](https://github.com/karthikraoofficial/Statement-Categorizer)** | A self-correcting AI loop writes a rulebook that categorises card transactions to 95% accuracy, then runs at zero tokens. | Python · FastAPI · Claude API |
| **[Zerodha Basket Planner](https://github.com/karthikraoofficial/zerodha-basket-planner)** · [live demo](https://zerodha-basket-planner.vercel.app) | Given a ranked stock list and a fixed amount, how many shares of each should you buy? Read-only: it can't place orders. | Next.js · TypeScript · Kite Connect |
| **[n8n AI agent workflows](https://github.com/karthikraoofficial/my-n8n-workflows)** | Agents for stock analysis, holdings recommendations, real-time fraud-risk scoring and thin-file loan eligibility. | n8n |

### 🛠️ Tools and apps

| Project | What it does | Built with |
|---|---|---|
| **[YouTube Description Editor](https://github.com/karthikraoofficial/youtube-description-editor)** · [live app](https://youtube-video-description-editor.vercel.app) | Bulk-edit descriptions, titles and tags across hundreds of videos, with a diff for each one, a backup before every write and one-click restore. | Python · FastAPI · React · YouTube Data API |

### 🏠 Home lab: debloating, safely

Same approach on each device: back up first, change in small reversible steps, and
prove with checks that nothing I use broke.

| Project | What it does | Built with |
|---|---|---|
| **[Windows Debloat](https://github.com/karthikraoofficial/windows-debloat)** | Strips ads, Copilot, Xbox extras and preinstalled apps from a Windows 11 laptop with Win11Debloat at a pinned release. Pester tests prove the Store, Update and every app I use still work, and were re-run after the 26H2 update. | PowerShell · Pester · Claude Code |
| **[Clean My TV](https://github.com/karthikraoofficial/clean-my-tv-acer)** · [before/after](https://github.com/karthikraoofficial/clean-my-tv-acer#screenshots) | Ad-free Acer Google TV without rooting: nine ad and telemetry packages disabled over ADB, with streaming, Chromecast, voice and Live TV still working. | ADB · PowerShell · Android |

### 🎸 Off the keyboard: guitars

Away from fintech I set up and repair guitars, and play metal and rock. The same
care for detail goes into a fret level as into a policy engine.

| Project | What it is | Built with |
|---|---|---|
| **Karthik Rao's Guitar Collection** · [live site](https://karthik-guitar-collection.vercel.app) · private repo | An editorial showcase of the metal and rock guitars I own and play: photos, stories, spec sheets, setup logs and demo videos, with a private admin. Scores 95+ on Lighthouse mobile with no accessibility violations. | Next.js 16 · React 19 · Drizzle · Neon Postgres |
| **Karthik's Guitar Clinic** · [book a setup →](https://karthiksguitarclinic.lovable.app/) | My guitar setup and repair service. See what I offer and get in touch. | Lovable |
| **[Luthier services](https://github.com/karthikraoofficial/luthierservices)** | Guitar setup and repair services by Karthik Rao. | HTML |
