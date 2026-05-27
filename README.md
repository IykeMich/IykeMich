<h1 align="center">Ikechukwu Michael Ogbu</h1>
<p align="center">
  <b>Frontend & Mobile Engineer</b> — Scalable Systems · Cloud · Data
</p>

<p align="center">
  <i>Currently building production platforms across FinTech, HealthTech & SaaS.</i><br/>
  <i>Open to senior frontend / full-stack frontend roles.</i>
</p>

---

## About

I'm a frontend and mobile engineer who ships **end-to-end systems**, not just interfaces. My work spans architecture, API integration, cloud deployment, and data-ready foundations — across **fintech, healthtech, SaaS, and on-demand marketplaces**.

I care about how a system behaves at scale: multi-tenant boundaries, role-based access, real-time state, and dashboards that hold up under real traffic. I bring the same rigor to web (React, Next.js) and mobile (React Native, Expo).

---

## Core Strengths

- **Scalable Frontend Architecture** — React 19, Next.js, TypeScript
- **Cross-Platform Mobile** — React Native, Expo SDK, EAS Build
- **API Integration at Scale** — Redux Toolkit · RTK Query · TanStack Query · Zustand
- **Cloud & CI/CD** — AWS Amplify, S3 (presigned uploads), GitHub Actions
- **Data-Driven UI** — Recharts, ECharts, ApexCharts, ag-Grid
- **Production Observability** — Sentry, Firebase Crashlytics, structured logging

---

## Selected Work

### Vetiva Web Admin — Investment Management Dashboard
**FinTech · Wealth Management**

Engineered an enterprise admin platform for a leading investment firm, enabling back-office teams to manage investors, portfolios, KYC compliance, and financial products at scale. Shipped **234+ React components** and **7 RTK Query API slices** with multi-role auth across Root Admins, Admins, and standard users.

- Built **Investor Management**, **KYC & Compliance**, and **Financial Products** modules (Fixed Income, Treasury Bills, Commercial Paper) with subscription tracking and daily analytics
- Engineered **JWT auth with token refresh**, route guards (Auth / Guest / Setup), and RBAC across all workflows
- Integrated **Recharts + Chart.js** for portfolio distribution, netflow, and fund-performance dashboards; added CSV/Excel export and Sentry error tracking

**Tech:** React 19 · TypeScript · Vite · Redux Toolkit & RTK Query · Tailwind CSS · Radix UI (shadcn) · Recharts · Chart.js · Formik · Yup · Sentry

---

### Kedeh — Multi-Tenant B2B Operations Platform
**SaaS · Enterprise Operations**

Architected a multi-tenant operations platform powering marketing campaigns, loyalty, workforce, and sales tracking for enterprise clients. Delivered **63+ pages**, **43+ RTK Query API modules**, and **62+ modal workflows** across an Admin Portal (platform governance) and a Tenant Portal (business operations).

- Designed **route-level multi-tenant separation** with tenant onboarding wizards, subscription management, RBAC with approval workflows, and system-wide audit logs
- Built **Campaign Management**, a **Loyalty & Rewards engine** (points, gamification, leaderboards), and **Workforce Management** (attendance, shifts, multi-location)
- Shipped **29 enterprise data-table variations** with ag-Grid (filter / sort / paginate) and Recharts analytics dashboards

**Tech:** Next.js 16 · React 19 · TypeScript · Redux Toolkit & RTK Query · Tailwind CSS 4 · HeroUI · Radix UI · ag-Grid · Recharts · Formik · Zod · Framer Motion

---

### Servease — On-Demand Services Marketplace (Mobile)
**Services Marketplace · iOS & Android**

Built a production cross-platform mobile marketplace connecting customers with service providers across the full errand lifecycle — request, bid, track, chat, pay, dispute. Delivered **59+ screens**, **139+ components**, **18 RTK Query API slices**, and **10 Redux slices** supporting two distinct personas with separate onboarding and dashboards.

- Engineered the **Errand Lifecycle** (multi-step creation, real-time status transitions, Google Maps live-tracking) and an **Offer & Negotiation engine** with counter-offer pricing
- Implemented **real-time chat** over Socket.IO (read receipts, typing, presence, MMKV-persisted history) and a **Wallet & Payments** module with OTP-verified bank withdrawals
- Integrated **Dojah KYC** (NIN, document, selfie, bank verification), **AWS S3 presigned uploads**, biometric / Face ID unlock, FCM push notifications with deep links, and EAS Build CI

**Tech:** React Native 0.83 · Expo SDK 55 · TypeScript · Redux Toolkit & RTK Query · Redux Persist · NativeWind · Socket.IO · Firebase (Auth, FCM, Crashlytics) · Dojah KYC · Google Maps · AWS S3 · MMKV · Sentry · Reanimated · EAS Build

---

### Syticks — Multi-Sector Ticketing & Booking Platform
**Ticketing · Hospitality · Transport · Entertainment**

Built a multi-channel booking platform for the Nigerian market enabling consumers to book **hotels, buses, movies, and events** in one place, while giving businesses inventory, online + at-the-gate sales, and real-time analytics. Powers **10,800+ bookings**, **855+ businesses**, and **7,300+ users** across 4 ticket verticals — delivered as a marketing site, consumer web app, operator dashboard, and cross-platform mobile apps.

- Web: sector-aware **discovery, seat/category selection, multi-step checkout, ticket wallet, and QR retrieval**, plus an operator dashboard with inventory wizards per sector and instant withdrawal-to-bank flows
- Mobile: dual **Consumer + Business apps** with an **offline ticket wallet** (MMKV / SecureStore) and a camera-based **QR scanner** for at-the-gate validation with pass/fail feedback
- Integrated a Nigerian payment gateway (card / transfer / USSD) with idempotent webhook handling, plus FCM push + deep-link routing for bookings and payouts

**Tech:** Next.js · React 19 · TypeScript · Redux Toolkit & RTK Query · Tailwind CSS · Radix UI · Recharts · React Native · Expo SDK · NativeWind · Expo Camera · Expo Notifications · MMKV · EAS Build

---

### Weddyn — The Wedding OS
**Wedding-Tech · Events**

Built an end-to-end wedding planning platform connecting engaged couples with vendors through a multi-tenant Next.js app. Spans **50+ pages**, **130+ components**, **12+ RTK Query API modules**, and **25+ modal workflows** across couple-facing and vendor-facing portals.

- **Couple Workspace:** customisable planning checklist, **Guest List & RSVP** (CSV import, table assignment, shareable links), budget tracker with vendor-linked line items, and a wedding website builder with themed templates
- **Vendor Portal:** onboarding + package/pricing builder, **Leads & Bookings pipeline** (inquiry → quote → confirmed → completed) with couple chat threads, and an Earnings & Payouts module
- Implemented **role-aware auth + route guards** so couples and vendors land on their respective dashboards from a single auth surface

**Tech:** Next.js · React 19 · TypeScript · Redux Toolkit & RTK Query · Tailwind CSS · Radix UI / shadcn · Recharts · React Hook Form · Zod · Framer Motion · Cloudinary / S3

---

## Engineering Approach

- **Systems over components** — design for boundaries, state, and scale first
- **Data as a first-class concern** — analytics, audit trails, and reporting baked in, not bolted on
- **Reliable over clever** — observability, RBAC, and refresh-token discipline by default
- **Maintainable over fast-now** — typed APIs, modular forms, and shared design primitives

---

## GitHub Stats

<p align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=IykeMich&show_icons=true&theme=tokyonight&count_private=true" />
  <img height="150em" src="https://github-readme-streak-stats.herokuapp.com/?user=IykeMich&theme=tokyonight" />
</p>

---

## Connect

- **Email** — ikechukwuogbu321@gmail.com
- **LinkedIn** — [linkedin.com/in/ikechukwu-ogbu-a7244219a](https://www.linkedin.com/in/ikechukwu-ogbu-a7244219a/)
- **Portfolio** - https://ikechukwu-portfolio-three.vercel.app

---

<p align="center"><i>I build systems that scale — across users, businesses, and data.</i></p>
