# Savio Filho

I'm a software engineer building backend systems, operational SaaS, and applied AI. I focus on creating predictable, production-grade applications with explicit boundaries and rigorous contracts.

[Website](https://saviocodes.github.io/saviofilho.dev/) · [GitHub](https://github.com/SavioCodes) · [LinkedIn](https://www.linkedin.com/in/savio-filho-7a0212309) · [codessavio@gmail.com](mailto:codessavio@gmail.com)

---

### Focus & Core Philosophy

I design systems that remain explainable under production constraints: auth boundaries, queue-backed workflows, and rate limits. Rather than following industry hype, I write structured documentation, choose strong API contracts (OpenAPI), and ensure AI operations have deterministic fallbacks and cost boundaries.

*   **Bilingual Handoff:** I operate primarily in English for code, documentation, and technical discussions. I am based in Brazil and open to local and remote contracts.

---

### Featured Projects (Ready to Run)

#### 🔹 [OnboardPulse](https://github.com/SavioCodes/OnboardPulse)
Multi-tenant customer onboarding SaaS featuring schema isolation, queue jobs, and payment flows.
*   **Stack:** Next.js, PostgreSQL, Prisma, Stripe / Mercado Pago.
*   **Local Setup:**
    ```bash
    git clone https://github.com/SavioCodes/OnboardPulse.git
    cd OnboardPulse
    npm install
    # Copy .env.example, configure DATABASE_URL, and run migrations
    npx prisma migrate dev
    npm run dev
    ```

#### 🔹 [MailSieve](https://github.com/SavioCodes/MailSieve)
Lightweight, signup-risk API with OpenAPI validation schema.
*   **Stack:** Node.js, TypeScript, OpenAPI, Docker.
*   **Verification:**
    ```bash
    git clone https://github.com/SavioCodes/MailSieve.git
    cd MailSieve
    npm install
    npm run test
    ```

#### 🔹 [rede-neural-do-zero](https://github.com/SavioCodes/rede-neural-do-zero)
Educational feedforward neural network built from scratch (no high-level ML libraries).
*   **Stack:** Python, NumPy.
*   **Run Verification:**
    ```bash
    git clone https://github.com/SavioCodes/rede-neural-do-zero.git
    cd rede-neural-do-zero
    python -m unittest discover tests/
    ```

### Systems Architecture (Private Case Studies)
*Detailed technical reports and workflows are published at [saviofilho.dev/work](https://saviocodes.github.io/saviofilho.dev/work/).*

*   **`VOWGRID`** — Trust and guardrail layer for LLM agents utilizing policy dry-runs, authorization gates, and rollback systems.
*   **`AcessoQR`** — Mobile auditing platform with weighted scoring, content moderation, and physical QR certification.
*   **`ORCEI`** — Mobile quote builder with native WhatsApp delivery and inline business AI assistants.

---

### Core Stack & Rationale

*   **TypeScript & Node.js:** For unified type safety from API contracts down to the database client.
*   **PostgreSQL & Prisma:** To enforce relational integrity and strict database isolation boundaries for multi-tenant SaaS.
*   **Docker:** To guarantee containerized runtime consistency across local development and production.
*   **Python:** For deterministic mathematical evaluations, scripting, and AI integrations.

---

### Technical Writing

I write about real-world software constraints and systems design.
*   [Simulation before execution](https://saviocodes.github.io/saviofilho.dev/writing/simulation-before-execution/) — Building sandboxes for LLM agents.
*   [Billing webhooks need replay discipline](https://saviocodes.github.io/saviofilho.dev/writing/billing-webhooks-need-replay-discipline/) — Resilient Stripe webhook handlers.
*   [Contracts beat clever APIs](https://saviocodes.github.io/saviofilho.dev/writing/contracts-beat-clever-apis/) — Choosing schema validation over brittle code tricks.

---

### How I Work

*   **Explainability Over Cleverness:** If a system fails in production at 3 AM, it should be simple to debug. I write code that is easy to reason about and trace.
*   **Operational Handoff:** Code is only half the job. Complete systems require migration scripts, trade-off documentations (ADRs), and clear disaster recovery procedures.
*   **Production over Demos:** I prioritize well-tested, bounded behaviors over complex features that cannot survive real-world edge cases.
