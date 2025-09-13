# 👋 Hi, I'm Jayvic San Antonio

Full‑stack web engineer building typed, tested web systems on React/Next.js and Cloudflare Workers/Hono. I care about clean boundaries (Zod at the edges), useful CI (that blocks regressions), and small UX details that make products feel polished. Recently focused on practical AI agents and developer‑first automation.

---

## What I’m Known For

- Typed serverless APIs paired with modern React frontends.
- Engineering hygiene: strict TypeScript, Zod validation, and meaningful tests.
- Practical AI: structured outputs with guardrails; maintainable, not just demos.
- Developer automation: scheduled Actions, PR bots, coverage gates, perf budgets.

---

## Selected Work

Personal Site (jayvicsanantonio.dev)
- Role: author. Portfolio with CI‑enforced Lighthouse budgets and typed env config.
- Stack: Next.js 15 · React 19 · TypeScript · Lighthouse CI · Vercel.
- Repo: https://github.com/jayvicsanantonio/jayvicsanantonio.dev
- Proof: Lighthouse CI https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/.github/workflows/lighthouse-ci.yml · Perf budgets https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/lighthouse-budgets.json · Env schema (Zod) https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/env.ts
- Outcomes: CI budgets enforce FCP ≤ 2.0s, LCP ≤ 2.5s, TTI ≤ 4.0s on home; total bytes ≤ 800KB (home), scripts ≤ 450KB, 3P ≤ 300KB; scaled budgets for `/projects` and `/work` routes.
- Live Lighthouse: https://pagespeed.web.dev/analysis?url=https%3A%2F%2Fjayvicsanantonio.dev

AI Humanity Passport
- Role: author. Next.js + Prisma system that analyzes GitHub repos with a Groq LLM, persists verdicts, and serves dynamic badges with caching/ETag.
- Stack: Next.js · TypeScript · Prisma (Postgres) · Groq LLM · Zod.
- Repo: https://github.com/jayvicsanantonio/ai-humanity-passport
- Proof: Analyze API https://github.com/jayvicsanantonio/ai-humanity-passport/blob/main/src/app/api/analyze/route.ts · Badge API https://github.com/jayvicsanantonio/ai-humanity-passport/blob/main/src/app/api/badge/%5Bowner%5D/%5Brepo%5D/route.ts · Prisma schema https://github.com/jayvicsanantonio/ai-humanity-passport/blob/main/prisma/schema.prisma · Groq client https://github.com/jayvicsanantonio/ai-humanity-passport/blob/main/src/lib/llm.ts
- Outcomes: POST /api/analyze rate‑limited to 5 req/60s (default); badge responses cached (Cache‑Control: max‑age=300, s‑maxage=600) with ETag/304 support.

Track N’ Stick (frontend)
- Role: sole builder. Habit tracking PWA with offline support and API‑aware caching.
- Stack: React 19 · Vite · TypeScript · VitePWA · Tailwind.
- Repo: https://github.com/jayvicsanantonio/tracknstick.com
- Proof: PWA config https://github.com/jayvicsanantonio/tracknstick.com/blob/main/vite.config.ts · SW register https://github.com/jayvicsanantonio/tracknstick.com/blob/main/src/main.tsx · PWA docs https://github.com/jayvicsanantonio/tracknstick.com/blob/main/docs/PWA_IMPLEMENTATION.md
- Outcomes: PWA audit 100/100 (per docs); offline‑first with runtime caching for API and Google Fonts; auto‑update service worker.

Web Development Hub
- Role: author. Resource hub deployed via OpenNext on Cloudflare.
- Stack: Next.js 15 · TypeScript · OpenNext Cloudflare.
- Repo: https://github.com/jayvicsanantonio/web-development-hub
- Proof: OpenNext init https://github.com/jayvicsanantonio/web-development-hub/blob/main/next.config.mjs · CF deploy scripts https://github.com/jayvicsanantonio/web-development-hub/blob/main/package.json#L13-L16
- Outcomes: Includes a checked‑in Lighthouse report for transparency; ongoing perf tuning alongside Cloudflare deployment.

Barbenheimer VS Code Theme
- Role: author & publisher. Three‑variant theme extension (light + darks) published under `jayvicsanantonio`.
- Stack: VS Code extension (themes contribution).
- Repo: https://github.com/jayvicsanantonio/barbenheimer-vscode-theme
- Proof: Extension manifest https://github.com/jayvicsanantonio/barbenheimer-vscode-theme/blob/main/package.json

---

## Engineering Practices

- Strict TypeScript across repos; Zod at trust boundaries.
- Tests with Vitest/Jest + Testing Library; coverage enforced where it matters.
- CI/CD via GitHub Actions: type‑check, lint, test, deploy; scheduled automations; performance budgets.
- Edge/serverless patterns: Cloudflare Workers, Vercel Edge; D1/SQLite, Upstash/Redis; PWA for offline UX.

---

## Core Stack

TypeScript · React/Next.js · Node.js · Hono · Cloudflare Workers · Prisma/SQLite & D1 · Upstash/Redis · Zod · Vitest/Jest · Testing Library · GitHub Actions · Vite

---

## Links

- Portfolio: https://jayvicsanantonio.dev
- Email: codes@jayvicsanantonio.dev
