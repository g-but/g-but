### Decentralization. Automation. Abundance.

Blockchain removes the need to trust institutions. AI removes the need for repetitive labor. Robotics removes the need for human drudgery. Together, they don't just improve the current system — they make it obsolete. We are entering the technological singularity, and the result is a society of sustainable abundance.

I build the infrastructure for that transition.

---

#### The Work

**Decentralized Finance & Governance**

[**OrangeCat**](https://github.com/g-but/orangecat) — Bitcoin-native commerce, funding, and community platform. Entity Registry SSOT drives 13 entity types from one config file. Lightning Network payments with user-selectable display currency (BTC default, CHF as fiat default). Row Level Security at the database level.

[**Solon**](https://github.com/g-but/solon) — Cryptographic democracy. Treasury transactions on-chain, votes signed with Bitcoin keys, decisions tracked against KPIs. Replaces trust with math.

**AI & Autonomous Systems**

[**Botsmann**](https://github.com/g-but/botsmann) — Multi-LLM routing across Groq, OpenRouter, and local Ollama. Six domain-specialized AI professionals with scoped knowledge bases. RAG via pgvector with zero-cost client-side embeddings. Four-layer prompt injection defense.

**Sustainability & Circular Economy**

[**RevampIT**](https://github.com/g-but/revampit) — Swiss nonprofit redistributing technology instead of discarding it. Custom CMS, 165 table constants as SSOT, 312 tests. Open-source because that's what a circular economy looks like in software.

[**SBB Lost & Found**](https://github.com/g-but/sbb-lost-found) — Real-time lost item recovery for Swiss railways. Microservice architecture, Redis pub/sub, Socket.io live notifications. Collapses recovery time from 24 hours to 30 minutes.

[**Reparaturbonus Zürich**](https://github.com/g-but/reparaturbonus-zh) — Government repair bonus platform. Connecting residents with certified repair shops instead of landfills. Repair over replace.

---

#### Engineering Philosophy

**First principles, not best practices.** Before every decision, ask: What problem am I actually solving? What are the real constraints? What is the simplest solution that respects them? If the answer to "why are we doing this?" is "because other projects do it" — stop and rethink. Convention is not a reason. Analogy is not an argument. Derive every decision from ground truths about the domain.

**One source of truth, no exceptions.** Every piece of data lives in exactly one place. Types are derived from schemas, never defined separately. Config files drive behavior. If adding a field requires touching 5 files, the architecture is wrong — fix the architecture, not the symptom.

**Complexity must earn its place.** Every abstraction added today is a tax paid on every change tomorrow. Three similar lines of code is better than a premature abstraction. Don't build for hypothetical future requirements. The right amount of complexity is the minimum needed for the current problem.

**Automate the mechanical, reserve humans for judgment.** Formatting, validation, deployment, testing — machines do these better. Architecture, UX, business decisions — humans do these better. Every manual step that could be automated is a reliability risk.

Every claim on this profile is verifiable in the code. Start with [`.claude/rules/`](https://github.com/g-but/orangecat/tree/main/.claude/rules) in OrangeCat for the architectural patterns, or the [test suites](https://github.com/g-but/revampit/tree/main/tests) in RevampIT for proof of correctness.

---

TypeScript, Next.js, React, PostgreSQL, Supabase, Prisma, Bitcoin/Lightning, Zod, Tailwind
