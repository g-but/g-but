### Software should serve humans, not the other way around.

Every line of code I write starts from that premise. I build open-source systems where transparency isn't a feature — it's the architecture. Where a single config change propagates through the entire stack. Where 760 tests prove correctness, not just coverage.

Pseudonymous by choice. The work speaks for itself.

---

#### The Work

**Transparency & Bitcoin**

[**OrangeCat**](https://github.com/g-but/orangecat) — Bitcoin transparency platform with a single Entity Registry that drives 13 entity types, all CRUD operations, navigation, and validation from one source of truth. Satoshis-only storage (no floats), Row Level Security at database level, middleware composition that eliminates 95% of auth duplication. 84 test files, 5 CI workflows.

[**Solon**](https://github.com/g-but/solon) — Bitcoin-native governance where every financial transaction lives on-chain, every vote is cryptographically signed, and every decision has a KPI trail. Four pillars: transparent treasury, law framework, service marketplace, open voting. Prisma schema as SSOT, i18n for 4 languages.

**Human Empowerment**

[**Botsmann**](https://github.com/g-but/botsmann) — Multi-LLM platform routing across Groq, OpenRouter, and local Ollama. Six domain-specialized professionals, each with scoped document access. RAG via pgvector (384-dim embeddings, client-side, zero API cost). Four-layer prompt injection defense. Privacy-first: RLS everywhere, no cross-user data leakage.

[**AOZ Housing**](https://github.com/g-but/aoz-housing) — Refugee housing compatibility matching. 38 resident factors scored across 4 dimensions, apartment-level aggregate matching with blocking conflict detection. Config-driven: add a factor in 2 files. We never track medical diagnoses, immigration status, or religion — only functional housing needs. 212 unit tests + 45 E2E tests.

**Sustainability & Data**

[**RevampIT**](https://github.com/g-but/revampit) — Swiss nonprofit giving technology a second life. Custom CMS (not Strapi — lighter, faster, full control), 165 table constants in a single SSOT, Stripe integration, HIRN AI knowledge system. 312 tests across 24 suites.

[**DataCat**](https://github.com/g-but/datacat) — Universal data pipeline: ingest (forms, photos, APIs) → AI analysis (GPT-4 Vision, Google Vision, with fallbacks) → action delivery. Drag-and-drop form builder, schema versioning, one-command white-label rebranding for any vertical. tRPC for end-to-end type safety.

---

#### Engineering Philosophy

One source of truth for every piece of data. Types derived from schemas, never defined separately. Config files drive behavior — if adding a field requires touching 5 files, the architecture is wrong. Validate at boundaries, trust internal code. Complexity must earn its place.

Every claim on this profile is verifiable in the code. Start with [`.claude/rules/`](https://github.com/g-but/orangecat/tree/main/.claude/rules) in OrangeCat for the architectural patterns, or the [test suites](https://github.com/g-but/aoz-housing/tree/main/src) in AOZ Housing for proof of correctness.

---

TypeScript, Next.js, React, PostgreSQL, Supabase, Prisma, Bitcoin/Lightning, Zod, Tailwind
