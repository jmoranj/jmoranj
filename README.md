# João Gustavo Morandim

Full-stack software engineer — TypeScript, Node/NestJS, React/Next.js — building LLM features that are measured before they ship. Remote from Sorocaba, Brazil (UTC−3).

## What I'm building

**[Job Radar](https://github.com/jmoranj/personal-job-api)** — personal job search over 7 job boards and 400+ company career pages (Rust · Postgres · React · Claude)
- Claude classifier for jobs keyword rules can't place: **97% vs 67% accuracy** on a 150-job labeled eval, zero eligible jobs wrongly hidden, $0.024 per job
- Application-prep agent (web search + structured output) with its own eval: drafts with unsupported claims **8/12 → 1/12**
- MCP server so Claude can search and update the pipeline
- Dashboard: [personal-job-dash](https://github.com/jmoranj/personal-job-dash)

**[job-rag](https://github.com/jmoranj/job-rag)** — ask questions about those postings and get cited answers (Python · pgvector · Claude)
- Hybrid search (Postgres full text + vectors, reciprocal rank fusion): right job in the top 5 for **98%** of eval questions, ranked first for 82% (up from 58% after the eval exposed a weak keyword query)
- 20/20 end-to-end answers cite the source posting

## At work

Contractor at Mind Consulting — main developer of **Supercasa**, a real-estate platform: NestJS + Prisma API, Next.js web app, Expo mobile app, Playwright end-to-end tests.

## Stack

TypeScript · Python · Node.js · NestJS · React · Next.js · React Native/Expo · Prisma · PostgreSQL · MySQL · Redis · Docker · Playwright · Rust · pgvector · Claude API

## Contact

[LinkedIn](https://www.linkedin.com/in/joaomorandim/) · morandim.joao@gmail.com
