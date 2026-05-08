<div align="center">

# Hi, I'm Prem Prabhat 👋

### Builder · Full Stack Developer · Systems Thinker

<br/>

> "I don't just build features — I build systems that hold up under real-world pressure."

</div>

---

## 👨‍💻 About Me

**BCA student from Bihar, India** — currently building production-grade software that most people only learn about in system design interviews.

My learning philosophy: **ship real things, break them, fix them properly.**

Right now I'm deep in:

- Designing **distributed systems** — webhook idempotency, race condition prevention, atomic transactions
- Building **financial infrastructure** — multi-gateway payments, host ledgers, payout pipelines, refund engines
- Learning **backend architecture** from the inside — not tutorials, but actual production edge cases

---

## 🚀 What I'm Building

### 🗓️ Zyncro — Enterprise Scheduling SaaS

A full-stack scheduling and payment platform for consultants, freelancers, and teams.

**What's actually under the hood:**

- **Multi-provider calendar sync** — Google Calendar, Microsoft Outlook (two-way, real-time)
- **Video integrations** — Zoom, Google Meet, Microsoft Teams, custom locations
- **Multi-gateway payment system** — Razorpay, Stripe, PayU with per-host gateway routing
- **Host ledger & payout engine** — PENDING → SETTLED → PAID lifecycle, 3-day hold periods, REFUND_DEBIT clawbacks, bank/UPI payout processing
- **Refund system** — policy-based eligibility (FLEXIBLE/MODERATE/STRICT/NO_REFUND), atomic gateway refund with double-processing prevention, MANUAL flow for PayU
- **RBAC admin panel** — refund management, payout approvals, audit logs, settlement health monitoring
- **Notification pipeline** — Email (Resend), WhatsApp (MSG91), In-App with queue-based delivery
- **Webhook infrastructure** — idempotent processing with INSERT-first + P2002 catch pattern, Sentry escalation for orphaned events
- **Cron jobs** — daily settlement, stale threshold health checks

**Tech:** Next.js 15 · TypeScript · PostgreSQL · Prisma · Redis · NextAuth v5

---

### 📚 Disha Class — LMS for Tier-2/3 India

A **Learning Management System** built for coaching institutes outside metro cities.

- Role-based dashboards — Admin / Teacher / Student
- Course and batch management
- Online class scheduling
- Admission workflow
- **Goal:** make quality education infrastructure accessible where it's missing

**Tech:** React · Node.js · MongoDB · modern backend architecture

---

## 🧠 How I Think About Software

- **Correctness before cleverness** — a bug in a payment system isn't a "learning opportunity", it's someone's money
- **Idempotency matters** — if something can run twice, design it to be safe when it does
- **Transactions are not optional** — concurrent writes need atomic operations, not hope
- **Systems > features** — features break; well-designed systems degrade gracefully

---

## 🛠️ Tech Stack

### Frontend
TypeScript · React · Next.js 15 · TailwindCSS · Shadcn/ui

### Backend
Node.js · Next.js API Routes · Prisma ORM  
PostgreSQL · Redis · Upstash

### Payments & Integrations
Razorpay · Stripe · PayU  
Google Calendar API · Microsoft Graph API · Zoom SDK  
Resend · MSG91 · Sentry

### DevOps & Cloud
Vercel · AWS · Google Cloud · Docker · Nginx · GitHub Actions

---

## 📊 GitHub Activity

<div align="center">

<img src="https://nirzak-streak-stats.vercel.app/?user=Prem-Prabhat&theme=radical&hide_border=true" />

</div>

---

## 🤝 Open To

- **Summer 2026 internships** — especially backend, systems, or fintech
- **Startup collaborations** — if you're building something real, let's talk
- **Open-source contributions**

---

<div align="center">

## 📫 Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://premprabhat.site)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prem-prabhat/)
[![Twitter](https://img.shields.io/badge/X-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/prem_prabhat9)

</div>
