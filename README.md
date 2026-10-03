# Faraz Ali Ahmed

I build AI automation into the workflows people already use — and the full-stack products
around them.

**Stack:** React · Next.js · TypeScript · Node · Ruby on Rails · Python (FastAPI) · PHP · PostgreSQL · MongoDB

### What I work on

**[Compliance Evidence Tracker](https://github.com/farazahmed7530/compliance-evidence-tracker)**
— FastAPI + React. Track compliance requirements, collect evidence against them, and keep a
**tamper-evident** record of it all. Every state change appends to a SHA-256 hash-chained
audit log, so editing any historical row breaks every hash after it and `/api/audit/verify`
reports exactly where. Because the auditor's real question isn't *"what does the record say?"*
— it's *"can you prove it wasn't edited?"*

**[Sourcedeck](https://github.com/farazahmed7530/sourcedeck)** — Next.js + TypeScript. Upload
documents, name a topic, get a deck where every bullet is quoted from a source and every slide
cites where it came from. Retrieval decides what is true; generation only decides how it reads.
Structure-aware chunking, BM25 ranking rather than embeddings (no API key, and the ranking is
explainable), and a deterministic default mode that cannot hallucinate.

**[Policy Attestation Platform](https://github.com/farazahmed7530/policy-attestation-platform)**
— FastAPI + Next.js. Publish internal policies, collect attestations, and prove afterwards
exactly which words each person agreed to. Policy versions are immutable: editing publishes a
new version rather than mutating an old one, so a signature made in January still means what
it meant in January, even after a March rewrite.

**Sales workflow automation** (Programmers Force) — automation for account executives: a
copilot for the repetitive parts of the sales motion, and a document-to-deck pipeline that
retrieves the relevant source material and generates the presentation an AE would otherwise
assemble by hand.

**[Wisper](https://github.com/FarazAliAhmed/wisper-reseller-api)** — mobile-data reseller
platform, live in production. Node/Express + MongoDB with wallet accounting, API-key auth for
business clients, payments, and failover between two upstream telecom providers switchable
without a redeploy.

**Client work** — a recruitment platform and a compliance SaaS on Next.js, Rails, GraphQL and
PostgreSQL. Client codebases, so the source isn't public.

I use AI-assisted development to move quickly, and I stay the engineer responsible for
architecture, debugging, testing and deployment.

📫 farazali7530@gmail.com · [LinkedIn](https://www.linkedin.com/in/faraz-ahmed-61a544219/)
