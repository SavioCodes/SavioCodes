# Savio Filho

Software engineer specializing in backend product systems, operational SaaS, and applied AI. Focused on architectural boundaries, reliable execution, and production-grade discipline.

[Portfolio](https://saviocodes.github.io/saviofilho.dev/) · [Case Studies](https://saviocodes.github.io/saviofilho.dev/work/) · [Writing](https://saviocodes.github.io/saviofilho.dev/writing/) · [LinkedIn](https://www.linkedin.com/in/savio-filho-7a0212309) · [Email](mailto:codessavio@gmail.com)

---

<blockquote>
  <strong>🇧🇷 Procurando a versão em Português?</strong>
  <details>
    <summary>Clique para expandir</summary>
    <br />
    <p align="justify">
      Eu projeto e implemento sistemas de backend, plataformas SaaS e soluções de IA aplicada com limites arquiteturais claros, execução confiável e rigor de produção. Trabalho com foco em contratos de API rígidos, validação de esquemas e comportamento pós-lançamento previsível.
    </p>
  </details>
</blockquote>

### Focus & Core Philosophy

I design systems that remain explainable and resilient under real-world constraints—such as network timeouts, rate limits, billing failures, and non-deterministic LLM outputs. My approach favors strong schema contracts, idempotent operations, and thorough runbook documentation over hype-driven engineering.

---

### Featured Projects (Ready to Run)

#### 🔹 [OnboardPulse](https://github.com/SavioCodes/OnboardPulse)
Multi-tenant customer onboarding SaaS featuring schema isolation, queue-backed automation jobs, and stripe billing.  
`Next.js` · `TypeScript` · `PostgreSQL` · `Prisma` · `Stripe`

```bash
git clone https://github.com/SavioCodes/OnboardPulse.git
cd OnboardPulse
npm install
# Set up DATABASE_URL in .env
npx prisma migrate dev
npm run dev
```

#### 🔹 [MailSieve](https://github.com/SavioCodes/MailSieve)
Lightweight email risk validation API designed around strict OpenAPI contract discipline.  
`Node.js` · `TypeScript` · `OpenAPI` · `Docker`

```bash
git clone https://github.com/SavioCodes/MailSieve.git
cd MailSieve
npm install
npm run test
```

#### 🔹 [rede-neural-do-zero](https://github.com/SavioCodes/rede-neural-do-zero)
Educational implementation of a neural network from scratch using raw NumPy matrix math.  
`Python` · `NumPy`

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
