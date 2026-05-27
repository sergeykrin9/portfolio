# Sergey Krinitsyn

**AI Product Engineer · Full-stack (React + Python) · LLM Pipelines**

Nha Trang, Vietnam · Open to relocation (Serbia, Armenia, UAE, EU)
Email: sergeykrin98@gmail.com · GitHub: [github.com/SergeyKrin9](https://github.com/SergeyKrin9)
Timezone: UTC+7 (flexible: MSK ± 4h, EU-late OK)

---

## About

End-to-end product engineer who ships AI-driven products from LLM pipeline and FastAPI backend to production deploy and SEO automation. Over the past year I built and shipped **10+ products** across PropTech, AI content, marketing automation, and paid Telegram bots.

I work across the whole stack without handoffs: design → frontend → Python/Node backend → AI logic → SEO/ads/analytics. My edge is the combination of **AI engineering, modern frontend, production Python backend, and a growth mindset** — not "another React dev," not "another ML researcher."

---

## Tech Stack

**AI / LLM**
OpenAI, Anthropic Claude, NVIDIA NIM (Llama), Google Gemini, prompt engineering, cost-optimized cascade fallbacks, RAG patterns, structured outputs, multi-modal pipelines

**Frontend**
React 18, Vite, TypeScript, Tailwind CSS, Framer Motion, Three.js / React-Three-Fiber, React Router 7, lazy-loading, PWA, SEO prerender

**Backend**
Node.js 20, Firebase (Firestore, Cloud Functions, Auth, Storage, Hosting), security rules, REST / webhook APIs, Google Sign-In, custom claims, multi-tenant isolation

**Python (backend + automation)**
Python 3, **FastAPI, SQLAlchemy, APScheduler**, Flask, ffmpeg, Pillow, BeautifulSoup, requests, Firebase Admin SDK, SQLite, systemd services, cron pipelines, Telegram Stars payments

**Marketing Engineering**
Yandex.Direct API, Yandex.Metrika, Google Search Console, n8n, Telegram Bot API, VK API, YouTube Data API v3, SEO automation

**DevOps / Tools**
Git, GitHub, Firebase CLI, Ubuntu / systemd, Playwright (E2E), Vitest, MCP servers for AI agents

---

## Selected Projects

### eDaru.su — Full-cycle growth automation platform
A complete marketing machine for a courier referral business (Yandex.Eda partner): SEO landing + backend + bot + workers. Auto-generated SEO content via Gemini, ad campaign management via Yandex.Direct API, analytics through Yandex.Metrika, autoposting to Telegram and VK, lead capture through a bot. Seven custom MCP servers wire it all into the AI agent loop.

**Stack:** React 18 + Vite, Firebase Cloud Functions, Gemini API, Yandex.Direct API, Yandex.Metrika, Google Search Console, VK API, Telegram Bot API, Yandex Webmaster, YouTube Data API
**Outcome:** combined the work of a marketer + content manager + SEO specialist into one automated pipeline
**Role:** solo full-stack + growth engineering

### Broker Reels Studio — AI text-to-video for real estate marketing
A Python pipeline that turns a listing into a TikTok/Reels-style short video. LLM writes the script, an image module picks visuals, ffmpeg composes the video with Ken Burns, smooth text animation, and music. Triggered from the broker dashboard via a Cloud Function; HTTP server in Flask. Replaces a marketer/SMM specialist for small real estate agencies.

**Stack:** Python, ffmpeg, Pillow, Flask, OpenAI/Anthropic API, Firebase Functions, Telegram Bot API
**Role:** sole owner — concept, architecture, implementation, deployment

### AxonLeads — Production SaaS for real estate developers
A platform for developer companies: project ingestion, unit-grid with ROI calculation, generated PDF presentations, multi-role auth (superadmin / developer / broker / client). Web app + investor portal with unlock logic and AI-driven price-list parsing.

**Stack:** React 18, Vite, Tailwind, Firestore (deep subcollections), Cloud Functions, Firebase Auth + custom claims, jsPDF, pdfjs-dist
**Scale:** ~127K LOC, live in production
**Role:** solo full-stack — schema, security rules, backend, frontend, deploy

### daily-poster — Autonomous AI content engine
A daemon that, once a day, picks a topic, generates a post via NVIDIA Llama, creates an illustration via Gemini Image, composes the final card in Pillow, and publishes it to a Telegram channel and a VK group. Cost-optimized cascade: cheap models for scoring, expensive ones only for the final pass.

**Stack:** Python, NVIDIA NIM, Gemini API, ffmpeg, Firebase Admin SDK, systemd timer, Telegram/VK APIs
**Outcome:** replaced manual SMM with full autopilot, running daily on a production server
**Role:** concept, build, operate

### BrokerOS — Multi-role CRM for real estate
A CRM with three roles (agent / broker / admin): leads, listings, "rooms" — shareable client demos, conversion analytics, and an AI matcher that picks listings to a client brief. Firestore security rules with tenant isolation, real-time subscriptions via `onSnapshot`.

**Stack:** React, Firestore security rules, Cloud Functions, onSnapshot, custom claims
**Role:** data architecture, frontend, AI integrations

### ClientRoom — TikTok-style listing showcase
A mobile-first showcase with a vertical feed (Reels-style), Framer Motion animations, lazy-loaded chunks, view analytics, and shareable broker links. Performance work: prerender, code-splitting, image optimization.

**Stack:** React, Framer Motion, Vite chunk splitting, dynamic imports
**Role:** UX design + implementation

### EnergyBot — Production Telegram bot with GPT-4 and payments
A paid Telegram bot for consultations. **FastAPI** + SQLAlchemy + SQLite, dialog state with OpenAI GPT-4o-mini and caching, payments via Telegram Stars, APScheduler for broadcasts and scheduled publications, an admin CRM bot for ops (stats, broadcasts, content management). Custom MCP server for Telegram publishing.

**Stack:** Python, FastAPI, SQLAlchemy, OpenAI API, APScheduler, python-telegram-bot, SQLite, MCP
**Role:** backend architecture, bot logic, payments, admin tooling

### Agnis Portal — B2B portal with AI and Telegram Mini Apps
A consultation booking portal + Gemini AI assistant + financial charts + Sanity CMS + Telegram Web App SDK integration. Netlify Functions as backend, real-time data, Framer Motion animations.

**Stack:** React 19, Vite, Telegram Web App SDK, Google Generative AI (Gemini), Sanity CMS, Netlify Functions, Chart.js
**Role:** full-stack + AI integrations

---

## Additional Work

- **7+ custom MCP servers** for AI agent integrations: Click.ru (Telegram Ads, VK Ads, Yandex.Direct), Yandex.Direct (campaigns, bids), Yandex Webmaster, Google Search Console, YouTube Data API, VK API, custom Telegram publisher. Covers the whole marketing stack for agent workflows.
- **Financial automation:** Tochka Bank API integration, statement parsing, monthly P&L reporting, Bybit card tracking
- **Scraping pipelines** (FazWaz, DotProperty, Bayut, YouTube, VK): Python + BS4 + rate limiting + dedup + Firestore + systemd
- **In-house design system** "warm precision luxury": design tokens, typography (Cinzel + Josefin Sans), Liquid Glass surfaces, used across 5+ products
- **Game experiments** (Phaser, Three.js): a GTA-style courier mini-game — for performance/canvas practice

---

## Languages

- **Russian** — native
- **English** — Intermediate working proficiency (B1-B2), actively improving to B2+
- Comfortable with technical written English, async work, and code review in English. Pair-programming on calls works best with patient teammates.

---

## What I'm looking for

Full-time remote employment (W-2, contractor, or EOR) in UTC-2 .. UTC+5. Open to relocating to Serbia, Armenia, UAE, or the EU.

**Target roles:** AI Product Engineer · AI Solutions Engineer · Senior Full-stack (React + Python + LLM) · Marketing/Growth Engineer with AI focus · Product Engineer at a PropTech startup.
