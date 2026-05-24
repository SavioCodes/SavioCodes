# Savio Filho

Software engineer specializing in backend product systems, operational SaaS, and applied AI. Focused on architectural boundaries, reliable execution, and production-grade discipline.

[saviofilho.dev](https://saviocodes.github.io/saviofilho.dev/) · [github.com/SavioCodes](https://github.com/SavioCodes) · [linkedin](https://www.linkedin.com/in/savio-filho-7a0212309) · [codessavio@gmail.com](mailto:codessavio@gmail.com)

---

### Bio
I design and build backend systems that remain explainable and resilient under real-world constraints—such as network timeouts, rate limits, billing failures, and non-deterministic LLM outputs. My approach favors strong schema contracts, idempotent operations, and thorough runbook documentation over hype-driven engineering.

Based in Brazil. Available for remote or local contracts.

---

### Public Projects

*   **[OnboardPulse](https://github.com/SavioCodes/OnboardPulse)** — Multi-tenant customer onboarding platform featuring schema isolation, queue-based scheduling, integrated payment flows, and programmatic AI budget controls.
*   **[MailSieve](https://github.com/SavioCodes/MailSieve)** — Lightweight email risk validation API designed with contract-first OpenAPI discipline.
*   **[rede-neural-do-zero](https://github.com/SavioCodes/rede-neural-do-zero)** — Educational implementation of a neural network from scratch using raw NumPy matrix math for deterministic execution.

### Case Studies
*Technical deep-dives on private systems available at [saviofilho.dev/work](https://saviocodes.github.io/saviofilho.dev/work/).*

*   **`VOWGRID`** — Trust and guardrail layer for LLM agents utilizing policy dry-runs, authorization gates, and rollback systems.
*   **`AcessoQR`** — Mobile auditing platform with weighted scoring, content moderation, and physical QR certification.
*   **`ORCEI`** — Mobile quotation builder with native WhatsApp delivery and inline business AI assistants.

---

### Technology Focus

I work primarily with **TypeScript/Node.js**, **Next.js**, **Python**, and **SQL**.

*   **Backend & APIs:** REST APIs, OpenAPI, API Versioning, Route Handlers.
*   **Databases & Queues:** PostgreSQL, Prisma ORM, Redis, Transaction Isolation.
*   **Operations & Infrastructure:** Docker, GitHub Actions, Idempotent Webhook Replay.

---

### Writing & Field Reports
I write about systems design, billing infrastructure, and AI guardrails.

*   [Simulation before execution](https://saviocodes.github.io/saviofilho.dev/writing/simulation-before-execution/) — Building sandboxes for LLM agents.
*   [Billing webhooks need replay discipline](https://saviocodes.github.io/saviofilho.dev/writing/billing-webhooks-need-replay-discipline/) — Resilient Stripe webhook handlers.
*   [Contracts beat clever APIs](https://saviocodes.github.io/saviofilho.dev/writing/contracts-beat-clever-apis/) — Choosing schema validation over brittle code tricks.

---

### Core Principles

1.  **Explainability Over Cleverness:** If a system fails in production at 3 AM, it should be simple to debug. I write code that is easy to reason about and trace.
2.  **Operational Handoff:** Code is only half the job. Complete systems require migration scripts, trade-off documentations (ADRs), and clear disaster recovery procedures.
3.  **Production over Demos:** I prioritize well-tested, bounded behaviors over complex features that cannot survive real-world edge cases.
