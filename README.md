# Elliott Rosenberg

I build software for creative practices — the operational layer that design studios and independent
practitioners actually run on. My background is in the design cycle: research, hypothesis, iteration.
Most of what's here is me applying that loop to shipping product.

---

### 🌿 [Perennial](https://github.com/elliottsrosenberg-byte/perennial-app) · [app.perennial.design](https://app.perennial.design)

A business operating system for creative practices. One app instead of six tools:

| Module | What it does |
| --- | --- |
| **Finance** | Invoicing with public pay links, Stripe Connect payouts, Plaid bank feeds, transaction categorization and receipt matching |
| **Calendar** | Week/month grids with drag-create, task rescheduling, Google + Outlook sync, embedded scheduling links |
| **Network** | Contacts and organizations with a detail-panel workflow |
| **Projects & Tasks** | Project tracking wired into the calendar and notes |
| **Notes** | Rich-text editor (TipTap) with image upload and shareable public links |
| **Outreach** | Pipeline for business development |
| **Opportunities** | A curated feed of grants, residencies, and calls |
| **Ash** | An AI assistant mounted globally across every module |

**Stack:** Next.js (App Router) · Supabase (Postgres + RLS + Vault) · Stripe Connect · Plaid ·
TypeScript · Tailwind v4 · Sentry · PostHog · Vercel

Built for multi-tenancy from the start — 40 of 41 tables carry row-level security policies, with
service-role escape hatches for cron ingestion, public invoice payment, and anonymous booking.

---

### 🤖 [cofounder](https://github.com/elliottsrosenberg-byte/cofounder)

A local-first AI founder OS built as a Claude Code plugin. Four department agents (strategy, product,
marketing, sales) and thirteen skills covering venture validation, Mom Test customer interviews,
positioning, pricing, launch planning, and pre-ship review. Includes a portfolio hub and a
zero-dependency dashboard.

The design principle: *execute internal, ask external.* Agents write freely inside repos; anything
outward-facing lands in an approval queue and waits for a human.

---

### 🗂 [Personal site](https://github.com/elliottsrosenberg-byte/26-site)

Portfolio and writing, built in Astro.

---

### What I'm interested in

Tools that respect the shape of creative work. Most business software assumes a sales team and a
quarterly forecast; practices run on projects, relationships, and irregular money. Perennial is my
attempt at building for that reality instead of against it.

---

📬 elliottsrosenberg@gmail.com
