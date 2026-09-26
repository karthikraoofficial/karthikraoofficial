## Hi, I'm Karthik 👋

I'm a **product manager in cards, payments and banking**, based in Bengaluru.
I've worked across Deloitte, RBL Bank and Publicis Sapient.

I also build. Most of what's here started as a product question I wanted to
answer with working software instead of a slide, usually with Gen-AI and
agentic workflows doing the heavy lifting.

### Featured

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

**[n8n AI agent workflows](https://github.com/karthikraoofficial/my-n8n-workflows)**
Agents for the Indian market: stock analysis, a Zerodha stock holdings recommendation
engine, real-time transaction fraud-risk scoring, and loan eligibility for
customers with no credit bureau history.

### Off the keyboard

I set up and repair guitars. [Luthier services →](https://github.com/karthikraoofficial/luthierservices)

---

**Interested in:** payments infrastructure · lending and credit decisioning ·
agentic AI in financial services · turning product ideas into working prototypes.
