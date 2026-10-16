<h1 align="center">Hi, I'm Sabelo Thabethe 👋</h1>
<p align="center">
  <b>Software Developer · Enterprise, Mobile &amp; Web</b><br/>
  Cape Town, South Africa · BSc Computer Science &amp; Computer Engineering, University of Cape Town
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/thabethesabelo"><img src="https://img.shields.io/badge/LinkedIn-thabethesabelo-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:thabethesabelo@gmail.com"><img src="https://img.shields.io/badge/Email-thabethesabelo%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.zakamanager.com"><img src="https://img.shields.io/badge/Building-Zaka%20Manager-0F766E" alt="Zaka Manager"/></a>
</p>

---

I build production software end to end: enterprise SaaS in **C# / .NET and React**, fintech mobile apps in **Flutter**, and e-commerce platforms on **Laravel, React and WordPress**. Most of my recent work is **offline-first, test-driven** products: strict TDD, clean architecture, typed contracts from database to UI.

- 🏭 **Now:** Software Developer at **Business Science Corporation**, working on **WiredUp** (formerly PIPware), an enterprise performance platform used by mining operations teams
- 💸 **Building:** **[Zaka Manager](https://www.zakamanager.com)**, a personal and SME finance platform (Flutter app + React/Hono web app on Supabase)
- 🧪 **Into:** offline sync, Postgres-level security (RLS, pgTAP), AI-assisted document extraction, Wear OS companion apps

## 🛠️ Tech I use

<p>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,ts,react,nextjs,flutter,dart,php,laravel,python,django,nodejs,nestjs&perline=13" alt="Languages and frameworks"/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,supabase,firebase,prisma,redis,graphql,tailwind,aws,gcp,azure,docker,githubactions,wordpress&perline=13" alt="Data, cloud and tools"/>
</p>

| | |
|---|---|
| **Backend** | ASP.NET Core, EF Core, Dapper, Hangfire, SignalR · Hono on Bun · NestJS · Laravel · Django · Express |
| **Frontend** | React 18/19, Next.js, TanStack Router/Query/Form, Redux, Zustand, Kendo React, MUI, Tailwind |
| **Mobile** | Flutter (Bloc, Riverpod, Freezed), Wear OS / watchOS companions, React Native / Expo, PWAs |
| **Data** | SQL Server, PostgreSQL, Supabase (RLS, migrations, pgTAP), Firestore, IndexedDB, PowerSync, Redis |
| **AI** | OpenAI, Claude API, Gemini / Genkit, LangChain, AWS Textract, Google Document AI |
| **Testing & Ops** | xUnit + Testcontainers, Vitest, Jest, Playwright, Cypress · AWS CDK, Docker, Podman + Caddy, GitHub Actions, Azure DevOps |

## ⭐ Featured work

### 💸 Zaka Manager · [zakamanager.com](https://www.zakamanager.com) · [business.zakamanager.com](https://business.zakamanager.com)
A finance platform: a Flutter mobile money manager, now growing into an SME accounting web app (bookkeeping, reconciliation, quotes and invoices, reports).
- **Bun + Turborepo monorepo:** React 19 + TanStack web app with end-to-end typed calls through a **Hono** client, Prisma on **Supabase Postgres**, and shared **Zod** contracts.
- **Org-scoped RBAC** defined once in Postgres and enforced through RLS. pgTAP tests check it for every role.
- **AI bank-statement and receipt extraction** pipeline, built over several generations: Camelot/Tabula, AWS Textract, Google Document AI, LangChain on AWS CDK, and now Genkit + Gemini Cloud Functions.

### 🏭 WiredUp (formerly PIPware) · Business Science Corporation
An enterprise platform for mining operations teams: a 600k+ line **.NET 8 + React/TypeScript** codebase with tenant-isolated SQL Server databases, Hangfire jobs, SignalR, SSRS reporting and Kendo React.
- **1,100+ commits** across data import, Ideas, Emissions, Impact, Meetings, Reports and Admin.
- Shipped KPI commentary end to end (database → services → UI → export, with tests). Also built site-aware timezone handling and data-integrity safeguards.

### 🛍️ Luxury retail & web platforms · B Online
Client platforms built at B Online, on WordPress/WooCommerce, React/Redux and Laravel APIs, with shared npm component libraries:
- **[Luxity](https://luxity.co.za):** luxury pre-owned retail platform. Storefront, customer portal and sales apps.
- **RareStep:** sneaker resale platform (Vite-bundled React on WooCommerce, Laravel + GraphQL backend).
- **[Orlichem](https://orlichem.co.za):** industrial chemicals store with SharePoint document sync. I was the main developer.
- **[GS1 South Africa](https://gs1za.org):** barcode standards body website. I was the main developer.
- **[Actuarial Society of South Africa](https://www.actuarialsociety.org.za):** member-portal CPD and work-based-learning flows, plus the exam-results site.

### 🧭 [Experience SA](https://www.experiencesa.co.za)
A marketplace for booking local experiences in South Africa. React 19 + TanStack, a Hono API on Bun, Prisma/Kysely on Postgres, better-auth, and a pgmq email worker. I built the **Paystack payments flow**: payment persistence, secure confirmation, checkout routing, and return/recovery.

## 🧪 Side projects

| Project | What it is | Stack |
|---|---|---|
| **TuckShop Pro** 🔒 | Offline-first point of sale for SA tuck shops. Keeps working during load-shedding, has a credit book with WhatsApp reminders, and encrypts PII locally. | React 19 PWA, Zustand, IndexedDB (AES-GCM), Supabase, Playwright, Podman + Caddy |
| **Lekker Trolley** 🔒 | Offline-first shopping lists with a **Wear OS** companion and voice add, built with strict TDD | Flutter, Riverpod 3, Freezed, Firestore, Dart workspace packages |
| **LekkerList** 🔒 | Shared shopping lists with watchOS + Wear OS apps | Flutter, Supabase + PowerSync, RevenueCat |
| **SignalForge** 🔒 | AI Twitter content generation and scheduling | Next.js, NestJS, Prisma, OpenAI, pnpm + Turborepo |
| **ClipFlow** 🔒 | Turns raw gameplay recordings into YouTube and Shorts edits automatically | Python, librosa, OpenCV, FFmpeg |
| **VibeGames** 🔒 | AI party-games app | Expo / React Native, Claude API, RevenueCat, Reanimated |
| [**SCAD Inventory**](https://github.com/sabeloeric/scad-inventory) | Inventory API with atomic stock transfers that can't oversell, using Postgres row locks | .NET 10, Dapper, PostgreSQL, React, Testcontainers, Playwright |
| [**Weather App**](https://github.com/sabeloeric/weather_app) | Clean Architecture + TDD reference app | Flutter, Bloc |
| [**Zoie Health**](https://github.com/sabeloeric/zoie-health) | Recipe app with tests | React, TypeScript, Vite, Vitest |
| [**Brand Website**](https://github.com/sabeloeric/brand_website) · [live](https://brand-website-three.vercel.app) | Figma-to-code single-page site | Next.js, TypeScript, SCSS |

<sub>🔒 Private repo. Happy to walk through the code on request.</sub>

## 📈 Journey

```
2019  Backend Developer        · Hitchat                     (REST APIs, Azure, MongoDB)
2020  Frontend Developer       · Synsource Solutions         (React, Firebase, Heroku)
2020  BSc CS & Computer Eng.   · University of Cape Town
2021  Frontend Developer       · B Online                    (React, WordPress, Laravel, GraphQL)
2023  Mobile App Developer     · App Developer Studio        (Flutter / FlutterFlow)
2023  Founder / Developer      · Zaka Manager                (Flutter, Supabase, AI)
2023→ Software Developer       · Business Science Corp.      (.NET 8, React, SQL Server)
```

<p align="center"><sub>Open to interesting problems. The fastest way to reach me is <a href="https://www.linkedin.com/in/thabethesabelo">LinkedIn</a>.</sub></p>
