# Dave Motheral

AI engineer in Fort Worth, Texas. I build agentic systems that run in production for paying clients: LLM agents, MCP servers, tool calling, and retrieval (RAG) on Python, Postgres/pgvector and Claude.

**What I've built (Centripetal AI)**
- **Agentic operating system:** concurrent LLM agents that boot from shared state, pick runbooks, record decisions and hand work to each other through tickets and a job queue. Agents reach every system through an MCP server I built.
- **Retrieval layer on pgvector:** ~19,000 embeddings over a knowledge graph, a decision log, runbooks and long-term agent memory, with HNSW indexes on cosine distance. Vectors sit next to the relational record, so row-level security applies to retrieval.
- **Document pipelines:** operator revenue statements (PDFs and portal exports in a dozen formats) parsed and reconciled into a client's accounting system every month.
- **Client help agents** running through the MCP server.

**Public repos here**
- [`centripetal-identity`](https://github.com/dmotheral3-eng/centripetal-identity): one-tap SSO (Google + Microsoft), one identity across many memberships, magic-link fallback, each app on its own Supabase.
- [`centripetal-api`](https://github.com/dmotheral3-eng/centripetal-api): a branded HTTP retrieve endpoint in front of the platform.
- [`universal-ui`](https://github.com/dmotheral3-eng/universal-ui): a shared UI kit with drift-metered design tokens.

Most production work is in private client repos.

**Stack:** Python · SQL · TypeScript · Postgres/Supabase · pgvector · Claude API & Claude Code · OpenAI / Azure OpenAI · MCP · Next.js · Vercel

[centripetal-ai.com](https://centripetal-ai.com) · [LinkedIn](https://www.linkedin.com/in/davemotheral) · dmotheral@centripetal-ai.com
