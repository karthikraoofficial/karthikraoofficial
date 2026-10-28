## Hi, I'm Karthik 👋

I'm a **product manager in cards, payments and banking**, based in Bengaluru.
I've worked across Deloitte, RBL Bank and Publicis Sapient.

I also build. Most of what's here started as a product question I wanted to
answer with working software instead of a slide, usually with Gen-AI and
agentic workflows doing the heavy lifting.

### Featured

**Credit Underwriting Platform** · [live demo](https://credit-underwriting-zeta.vercel.app) (private repo)
Can a lender let AI read the documents without letting it make the credit
decision? A proof-of-concept underwriting platform for Indian personal loans and
credit cards, built to demo to lenders. Models classify and extract payslips and
bank statements, but only after a redaction layer has replaced PAN, Aadhaar,
account numbers and contact details with tokens. The decision comes from a
deterministic five-layer policy engine (eligibility, hard policy, business and
campaign rules, scorecard, fraud) whose rules are versioned YAML packs that are
frozen once shipped. Every outcome, approvals included, carries reason codes.
Decisions are written to an append-only ledger and replay byte-identically from
their stored fact snapshot, and a policy diff shows which applications flip when
one rule changes. An underwriter console handles referrals, deviations and
delegated authority across fifteen synthetic borrower personas, from a clean
approval to a tampered statement. Python, FastAPI, Next.js, TypeScript,
Postgres, Claude API.

**ITR Schedule FA · A3 CSV Generator** · [live demo](https://itr-fa-a3-csv.onrender.com) (private repo)
A paid web app for Indians who hold foreign shares. Upload a holdings sheet in
any layout and get back the CSV the ITR utility imports for Schedule FA,
Section A3. Claude maps the columns but never produces a number: code copies and
checks every amount and date, fills entity details from a checked directory,
and flags anything that looks wrong. The customer sees a masked preview, then
pays ₹50 through Razorpay, and the payment is verified on the server before the
file unlocks. It learns layouts from paid orders, and reuses one only after the
owner approves it. Next.js, TypeScript, Postgres, Claude API, Razorpay (test
mode).

**[Zerodha Basket Planner](https://github.com/karthikraoofficial/zerodha-basket-planner)** · [live demo](https://zerodha-basket-planner.vercel.app)
Given a daily ranked list of stocks and a fixed amount to invest, how many
shares of each should you buy, and at what limit? It logs in with Kite, checks
each name against NSE end-of-day data and sizes a basket weighted by conviction,
with integer-paise money math that never overspends. It shows every name it left
out, and why. Read-only by design: it cannot place orders. Next.js, TypeScript,
Kite Connect API.

**[Job Portal](https://github.com/karthikraoofficial/Job-Portal-Employer_Employee)** · [live demo](https://job-portal-employer-employee.vercel.app/login)
A two-sided hiring platform. Employers post roles and move applicants through a
pipeline, and job seekers search, apply and track every status change. Built with
Next.js, TypeScript, PostgreSQL and Prisma, with role checks on every server
action and resumes validated by their file contents.

**[UPI Enach Card-Autopay Recovery Recommendation Engine & Simulator](https://github.com/karthikraoofficial/Autopay_recovery_simulator-recommender)** · [live demo](https://autopay-recovery-simulator-recommen.vercel.app/)
Recurring-payment retry recovery for India. A discrete-event simulator and scoring service. When a UPI AutoPay, eNACH or
card e-mandate debit fails, what is a better retry policy actually worth? It
measures competing strategies on a synthetic mandate book and recommends a retry
time with the evidence behind it. Python and FastAPI, with a React dashboard.

**[Bank Statement Categorizer](https://github.com/karthikraoofficial/Statement-Categorizer)**: a self-correcting AI loop
The loop writes a keyword rulebook for categorising card-statement narrations,
scores it against labelled data and keeps correcting itself until it reaches
95% accuracy. The model only ever sees the rows it got wrong, and once the
rulebook exists, categorising costs zero tokens. Python, FastAPI, Claude API.

**[Tamper Scanner](https://github.com/karthikraoofficial/tamper-scanner)** · [live demo](https://tamper-scanner-five.vercel.app/)
Has this bank statement PDF been tampered with? Deterministic PDF forensics
collect the evidence, and an optional LLM assessor gives a verdict that cites
it. Every decision leaves an audit trail, reviewer corrections become labelled
regression cases, and a new model or prompt must pass eval thresholds before
it's promoted. Python, FastAPI, OpenAI API.

**Karthik Rao's Guitar Collection** · [live site](https://karthik-guitar-collection.vercel.app) (private repo)
An editorial showcase of the metal and rock guitars I own and play. Each guitar
gets photos, its story, a full spec sheet, a mods and setup log, and demo
videos, and visitors can filter and sort the collection with shareable links.
A private admin that only my GitHub account can sign into lets me add and edit
guitars; changes go live within seconds without a redeploy, and private fields
like serial numbers and prices never reach the public pages. Scores 95+ on
Lighthouse mobile with no axe violations, and every animation respects
reduced-motion settings. Next.js 16, React 19, TypeScript, Tailwind, Drizzle on
Neon Postgres, Vercel Blob, Auth.js.

**[YouTube Description Editor](https://github.com/karthikraoofficial/youtube-description-editor)** · [live app](https://youtube-video-description-editor.vercel.app) · [how it works](https://youtube-video-description-editor.vercel.app/how-it-works.html)
How do you change a link or a line in hundreds of YouTube descriptions without
breaking one? Pick videos, define one edit to the description, title or tags,
and review an exact before/after diff for every video, with the quota cost,
before anything is written. Every run backs up each video first and can be
restored in one click, videos edited in YouTube Studio since the review are
skipped rather than overwritten, and every other field goes back to YouTube
unchanged. Runs on your own machine or on Vercel, where only the owner's Google
account can sign in. Python, FastAPI, React, TypeScript, Postgres, YouTube Data
API.

**[n8n AI agent workflows](https://github.com/karthikraoofficial/my-n8n-workflows)**
Agents for the Indian market: stock analysis, a Zerodha stock holdings recommendation
engine, real-time transaction fraud-risk scoring, and loan eligibility for
customers with no credit bureau history.

**Clean My TV: ad-free Acer Google TV** (private repo)
Can you strip the ads and sponsored rows out of a Google TV without rooting it
or breaking anything? On my Acer Google TV (Android 14), nine ad and telemetry
packages are disabled over ADB in small, reversible batches. Nothing is
uninstalled, and a restore record is taken before the first change. Each batch
has to pass a health check covering the Play Store, every streaming app,
Chromecast, voice search, HDMI and Live TV, and OTA updates. Only changes that
survive a cold boot are kept. The open-source CleanYourTV launcher replaces the
stock Home screen, a runbook covers restoring and rechecking after firmware
updates, and decision records explain the choices. ADB, PowerShell, Python,
Android.

### Off the keyboard

I set up and repair guitars. Check out my services: [Karthik's Guitar Clinic →](https://karthiksguitarclinic.lovable.app/), [Luthier services →](https://github.com/karthikraoofficial/luthierservices)

---

**Interested in:** payments infrastructure · lending and credit decisioning ·
agentic AI in financial services · turning product ideas into working prototypes.
