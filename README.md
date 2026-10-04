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

### 1. [AkohGrid — Distributed Event-Driven Commerce Platform](https://github.com/AkohMicheal/AkohGrid)
> **High-throughput microservices commerce platform coordinated via an Apache Kafka event bus.**

* **Stack:** Turborepo, Next.js 15 (App Router), React 19, TypeScript, Node.js (Express 5 / Hono), Apache Kafka, Supabase (PostgreSQL), Drizzle ORM.
* **The Build:**
  * **Event-Driven Choreography:** Decoupled order fulfillment and customer notifications from the checkout path using Kafka message topics (`payment.successful`, `order.created`), eliminating fragile synchronous HTTP cascades.
  * **Dual-Gateway Webhook Verification:** Engineered secure ingestion pipelines for both Stripe and Paystack (HMAC SHA512 buffer validation), backed by transaction idempotency locks to eliminate duplicate charging.
  * **Unified Relational Core:** Centralized domain entities across services into a shared `@repo/db` package using Drizzle ORM and PostgreSQL with strict enum state machines.
* **Links:** [Source Code](https://github.com/AkohMicheal/AkohGrid)

---

### 2. [FMCG Festival — Ticketing & E-Commerce Platform](https://fmcg-festival.vercel.app/)
> **High-concurrency event registration and multi-tier vendor ticketing platform.**

* **Stack:** Next.js (App Router), TypeScript, Tailwind CSS, Supabase, Drizzle ORM, Paystack, Sanity CMS.
* **The Build:**
  * **Zero-Budget Edge Infrastructure:** Mapped DNS routing between cPanel apex/CNAME records and Vercel edge networks to automate SSL termination without massive infrastructure overhead.
  * **Idempotent Payments:** Secured Paystack webhook ingestion with cryptographic signature verification and database locks to prevent duplicate ticket issuance during traffic spikes.
  * **Performance:** Decoupled content delivery via headless Sanity CMS and ISR to hit LCP < 1.1s and zero CLS.
* **Links:** [Live Platform](https://fmcg-festival.vercel.app/) *(Code is proprietary; full architectural breakdown available on my portfolio)*

---

### 3. [AkohFlow (FocusPaws) — Cross-Platform Productivity & Companion Engine](https://github.com/AkohMicheal/AkohFlow)
> **Production-ready cross-platform task manager for Android and Web built with React 19, Capacitor, Flask, and Supabase.**

* **Stack:** React 19, Tailwind CSS v4, Capacitor 8 (Android), Python Flask, Supabase (PostgreSQL), SQLAlchemy, Google AdMob.
* **The Build:**
  * **Zero-Dropoff Gamification:** Solved standard to-do abandonment by tying task completion to critter companion energy meters, daily paw streaks, and avatar unlocks.
  * **Hybrid Cross-Platform Bridge:** Compiled a unified React 19 codebase into native Android packages using Capacitor 8, integrating native hardware back-button interceptors and splash screens.
  * **$0/Month Serverless Economics:** Decoupled persistence between Supabase PostgreSQL connection poolers and client JWT auth, enabling continuous ad-monetized operation at zero infrastructure overhead.
* **Links:** [Source Code](https://github.com/AkohMicheal/AkohFlow)

---

### 4. [Aura Properties — Modern Real Estate SaaS](https://github.com/AkohMicheal/aura-properties-saas)
> **A high-performance property discovery platform built to fix the bloat of standard real estate templates.**

* **Stack:** Next.js 16, React 19, TypeScript, Tailwind CSS v4, `@base-ui/react`.
* **The Build:**
  * Adopted Tailwind v4's CSS-first configuration and `@base-ui/react` headless components to drastically cut JS bundle size.
  * Synchronized search filters and property facets directly with URL query params, enabling instantaneous, shareable deep-linking without breaking browser history.
  * Engineered for strict layout resilience with zero horizontal scroll overflow across all viewports.
* **Links:** [Source Code](https://github.com/AkohMicheal/aura-properties-saas) · [Live Demo](https://aura-properties-saas.vercel.app)

---

### 5. [GoVolo — Collaborative Workspace Platform](https://github.com/AkohMicheal/govolo)
> **Collaborative full-stack travel coordination and productivity app.**

* **Stack:** Next.js 16, TypeScript, React 19, Tailwind CSS v4.
* **The Build:**
  * Decoupled business logic into immutable service layers for cleaner testing and validation.
  * Leveraged React Server Components (RSC) for initial static data hydration, isolating client interactivity to leaf nodes to eliminate hydration waterfalls.
* **Links:** [Source Code](https://github.com/AkohMicheal/govolo)

---

### 6. [Dual-Stream Deepfake Detection System](https://github.com/AkohMicheal/Deepfake-Complete-WebApp-Project)
> **End-to-end deepfake verification platform combining spatial CNNs with frequency-domain DCT analysis and Grad-CAM explainability.**

* **Stack:** Python, TensorFlow/Keras, OpenCV, Discrete Cosine Transform (DCT), FastAPI, Next.js, Docker.
* **The Build:**
  * **Dual-Stream Forensic Pipeline:** Combines spatial visual artifact detection with frequency-domain spectrum analysis to expose subtle blending boundaries and compression artifacts that fool standard single-stream classifiers.
  * **Explainable AI (XAI):** Integrated Grad-CAM to render real-time visual heatmaps directly on suspected facial crops, giving users transparent, visual justification behind confidence scores.
  * **Decoupled Architecture:** Built a FastAPI microservice backend capable of chunked video frame extraction and batched model inference, feeding results asynchronously to a Next.js interface.
* **Links:** [Source Code](https://github.com/AkohMicheal/Deepfake-Complete-WebApp-Project) · [Live Demo](https://deepfake-scanner-web.vercel.app/)

---

### 7. [Akoh Inference API — Production ML Inference Microservice](https://github.com/AkohMicheal/akoh-inference-api)
> **Containerized FastAPI inference service serving clinical diagnostic and industrial telemetry models.**

* **Stack:** Python 3.11, FastAPI, Pydantic v2, scikit-learn, Docker, Uvicorn, Pandas.
* **The Build:**
  * **Strict Runtime Gateways:** Enforced boundary validation with Pydantic v2 to catch and reject corrupted telemetry vectors (out-of-bounds vitals, invalid sensor RPMs) with 422 responses before touching inference pipelines.
  * **Dynamic Binary Loader:** Designed a resilient model loader that automatically discovers and binds serialized `.pkl` pipelines via `joblib`, backed by deterministic clinical and industrial baseline heuristics during model retraining windows.
  * **Containerized Deployment:** Packaged into a minimal `python:3.11-slim` container with native OpenAPI/Swagger interactive documentation.
* **Links:** [Source Code](https://github.com/AkohMicheal/akoh-inference-api)

---

### 8. [Akoh Chat SDK — Embeddable Support Intelligence Runtime](https://github.com/AkohMicheal/akoh-chat-sdk)
> **Lightweight multi-domain customer intelligence runtime and zero-dependency embeddable chat widget.**

* **Stack:** Python 3.11, FastAPI, Scikit-Learn, Pydantic v2, Vanilla JS Widget, Docker.
* **The Build:**
  * **Domain Partitioning:** Pre-trained separate intent classification pipelines for E-Commerce (tracking, refunds), SaaS (billing, API keys), and General business FAQs.
  * **Continuous Mistake-Learning:** Built a `/v1/feedback` ingestion hook that captures user sentiment and corrections into a retraining buffer to eliminate repetitive hallucinations.
  * **Zero-Dependency Frontend:** Bundled a lightweight vanilla JavaScript floating widget embeddable via a single `<script>` tag on any web storefront.
* **Links:** [Source Code](https://github.com/AkohMicheal/akoh-chat-sdk)

---

## 🛠️ Technical Toolkit

- **Frontend:** Next.js (App Router, SSR, ISR, RSC), React 19, TypeScript, Tailwind CSS, shadcn/ui.
- **Backend & Data:** Node.js, Python, PostgreSQL, Supabase, Drizzle ORM, Prisma, REST APIs, Apache Kafka.
- **Payments & CMS:** Paystack API, Stripe, Event-Driven Webhooks, Sanity CMS.
- **Infrastructure:** Docker, Vercel Edge CDN, Railway, Git/GitHub Actions, cPanel DNS.
