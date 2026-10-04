# Hi, I'm Micheal Akoh-Idoko 👋
**Full-Stack Engineer | React, Next.js, TypeScript & Scalable Systems**  
Lagos, Nigeria (GMT+1) · Open to Global Remote Roles & Contracts

[![Portfolio](https://img.shields.io/badge/Live_Portfolio-michealakoh.vercel.app-4f46e5?style=flat-square&logo=vercel&logoColor=white)](https://michealakohportfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-micheal--akoh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/micheal-akoh)
[![Email](https://img.shields.io/badge/Email-akohmicheal%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:akohmicheal@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-AkohMicheal-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AkohMicheal)

---

I build resilient web applications, headless commerce platforms, and high-integrity data systems. I focus heavily on end-to-end type safety, zero cumulative layout shifts (CLS), and clean component architectures. 

I'm currently working deeply with the Next.js App Router, Supabase, Drizzle ORM, and integrating event-driven webhooks for payment processing. With full overlap across European (GMT/CET) and standard US working hours, I'm currently open for full-time remote roles and long-term contract engagements.

## 🚀 Featured Work & Case Studies

### 1. [FMCG Festival — Ticketing & E-Commerce Platform](https://fmcg-festival.vercel.app/)
> **High-concurrency event registration and multi-tier vendor ticketing platform.**

* **Stack:** Next.js (App Router), TypeScript, Tailwind CSS, Supabase, Drizzle ORM, Paystack, Sanity CMS.
* **The Build:**
  * **Zero-Budget Edge Infrastructure:** Mapped DNS routing between cPanel apex/CNAME records and Vercel edge networks to automate SSL termination without massive infrastructure overhead.
  * **Idempotent Payments:** Secured Paystack webhook ingestion with cryptographic signature verification and database locks to prevent duplicate ticket issuance during traffic spikes.
  * **Performance:** Decoupled content delivery via headless Sanity CMS and ISR to hit LCP < 1.1s and zero CLS.
* **Links:** [Live Platform](https://fmcg-festival.vercel.app/) *(Code is proprietary; full architectural breakdown available on my portfolio)*

---

### 2. [Aura Properties — Modern Real Estate SaaS](https://github.com/AkohMicheal/aura-properties-saas)
> **A high-performance property discovery platform built to fix the bloat of standard real estate templates.**

* **Stack:** Next.js 16, React 19, TypeScript, Tailwind CSS v4, `@base-ui/react`.
* **The Build:**
  * Adopted Tailwind v4's CSS-first configuration and `@base-ui/react` headless components to drastically cut JS bundle size.
  * Synchronized search filters and property facets directly with URL query params, enabling instantaneous, shareable deep-linking without breaking browser history.
  * Engineered for strict layout resilience with zero horizontal scroll overflow across all viewports.
* **Links:** [Source Code](https://github.com/AkohMicheal/aura-properties-saas) · [Live Demo](https://aura-properties-saas.vercel.app)

---

### 3. [GoVolo — Collaborative Workspace Platform](https://github.com/AkohMicheal/govolo)
> **Collaborative full-stack travel coordination and productivity app.**

* **Stack:** Next.js 16, TypeScript, React 19, Tailwind CSS v4.
* **The Build:**
  * Decoupled business logic into immutable service layers for cleaner testing and validation.
  * Leveraged React Server Components (RSC) for initial static data hydration, isolating client interactivity to leaf nodes to eliminate hydration waterfalls.
* **Links:** [Source Code](https://github.com/AkohMicheal/govolo)

---

### 4. [Network Anomaly & DDoS Classifier](https://github.com/AkohMicheal/ddos-detection-api)
> **Deep learning threat detection and volumetric flood ingestion pipeline.**

* **Stack:** Python, TensorFlow (GRU/LSTM), FastAPI, Docker, Next.js.
* **The Build:**
  * Built a low-latency inference pipeline trained on the CIC-DDoS2019 dataset to detect volumetric flood signatures in under 12ms per batch.
  * Containerized the pre-processing boundary via Docker to sanitize and reject corrupted telemetry vectors before they hit the model.
* **Links:** [API Backend](https://github.com/AkohMicheal/ddos-detection-api) · [Frontend UI](https://github.com/AkohMicheal/ddos-detection-ui)

---

## 🛠️ Technical Toolkit

- **Frontend:** Next.js (App Router, SSR, ISR, RSC), React 19, TypeScript, Tailwind CSS, shadcn/ui.
- **Backend & Data:** Node.js, Python, PostgreSQL, Supabase, Drizzle ORM, Prisma, REST APIs.
- **Payments & CMS:** Paystack API, Stripe, Event-Driven Webhooks, Sanity CMS.
- **Infrastructure:** Docker, Vercel Edge CDN, Railway, Git/GitHub Actions, cPanel DNS.
