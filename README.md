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

Track N’ Stick (web + API)
- Role: sole builder. Habit tracking PWA with timezone‑aware analytics and an edge API.
- Stack: React/Vite PWA · Cloudflare Workers + Hono · D1/SQLite · Zod · Vitest.
- Repos: frontend https://github.com/jayvicsanantonio/tracknstick.com · API https://github.com/jayvicsanantonio/tracknstick-api
- Proof: API validators (`src/validators`) https://github.com/jayvicsanantonio/tracknstick-api/tree/main/src/validators · Timezone utils https://github.com/jayvicsanantonio/tracknstick-api/blob/main/src/utils/timezone.ts · Deploy workflow https://github.com/jayvicsanantonio/tracknstick-api/blob/main/.github/workflows/deploy.yml · PWA config https://github.com/jayvicsanantonio/tracknstick.com/blob/main/vite.config.ts

AI Timeline Automation
- Role: author. Weekly automation that collects, dedupes, analyzes, and PRs AI news.
- Stack: Node/TypeScript · OpenAI · GitHub Actions · Jest/Vitest.
- Repo: https://github.com/jayvicsanantonio/ai-timeline-automation
- Proof: Weekly workflow https://github.com/jayvicsanantonio/ai-timeline-automation/blob/main/.github/workflows/weekly-update.yml · Analyzer https://github.com/jayvicsanantonio/ai-timeline-automation/blob/main/src/analyzers/event-analyzer.ts · Retry/circuit breaker https://github.com/jayvicsanantonio/ai-timeline-automation/tree/main/src/utils

Sync Flow
- Role: author. Two‑way sync between Apple Reminders and Google Tasks with rate‑limited webhooks.
- Stack: Vercel Edge Functions · Hono · Upstash/Redis · Zod.
- Repo: https://github.com/jayvicsanantonio/sync-flow
- Proof: Architecture https://github.com/jayvicsanantonio/sync-flow/blob/main/docs/Architecture.md · Webhook handler https://github.com/jayvicsanantonio/sync-flow/blob/main/src/handlers/webhook.ts · Rate limit util https://github.com/jayvicsanantonio/sync-flow/blob/main/src/utils/rate-limit.ts

Personal Site
- Role: author. Portfolio with CI‑enforced Lighthouse budgets and typed env config.
- Stack: Next.js 15 · React 19 · TypeScript · Lighthouse CI · Vercel.
- Repo: https://github.com/jayvicsanantonio/jayvicsanantonio.dev
- Proof: Lighthouse CI workflow https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/.github/workflows/lighthouse-ci.yml · Perf budgets https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/lighthouse-budgets.json · Env schema (Zod) https://github.com/jayvicsanantonio/jayvicsanantonio.dev/blob/main/env.ts

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
