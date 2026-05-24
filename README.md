# CF Problem Pack Generator

> Generate downloadable PDF problem sets from Codeforces — filtered by
> topic, rating, division, and count. Built for competitive programmers,
> coaches, and contest organizers.

## Features
- Filter by 35+ CF problem tags
- Rating range 800–3500 with dual-thumb slider
- Division: Div2, Div3, Div4, Educational
- 10/25/50/100 problems per pack
- Full problem statements: constraints, I/O, examples, notes
- Math formulas rendered cleanly via KaTeX
- Professional PDF: cover page, TOC, page numbers
- Download ready in ~30 seconds



## Quick Start
1. Clone + install: `npm install`
2. Copy `.env.example` → `.env.local` and fill values
3. `npx prisma migrate dev`
4. `npm run dev`

## Environment Variables
| Variable | Purpose |
|---|---|
| DATABASE_URL | Neon Postgres connection string |
| REDIS_URL | Upstash Redis REST URL |
| REDIS_TOKEN | Upstash Redis token |
| BLOB_READ_WRITE_TOKEN | Vercel Blob token |
| CF_API_KEY | Codeforces API key (optional) |

## Deployment
Deploy to Vercel with one click. Requires Neon, Upstash, and Vercel Blob add-ons.


- [ ] Coach mode (curated sheets)
- [ ] Spaced repetition tracker
- [ ] VS Code extension
