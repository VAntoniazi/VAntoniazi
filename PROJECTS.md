# Victor Antoniazi Gonzalez — Engineering Portfolio

**Backend and full-stack software development · SaaS architecture · Enterprise APIs · SQL/data systems · Automation · Healthcare software**

[← GitHub profile](README.md) · [Português](README.pt-BR.md) · [Español](README.es.md) · [Scientific research](RESEARCH.md) · [LinkedIn](https://www.linkedin.com/in/victor-antoniazi/)

This is a technical portfolio of the **software systems and engineering problems** I have worked on. It is designed to complement my [GitHub profile](https://github.com/VAntoniazi), not to imply that all source code is public or that every historical feature is currently deployed.

My professional focus is **backend engineering with full-stack product ownership**: relational data, business logic, API design, security, software modernization, automated workflows, UI and delivery.

## At a glance

| Product / domain | Primary engineering themes | Public evidence |
| --- | --- | --- |
| Enterprise operations and compliance | Modernization, REST APIs, authorization, approvals, auditability, SQL | Private/client-controlled systems |
| PinePet | SaaS design, customer workflows, multi-tenant concerns, scheduling, commerce | [Product website](https://pinepet.com.br) |
| Pineapple Lab | Custom software, business automation, services and integrations | [Company website](https://pineapplelab.net/) |
| PetFlow.PRO | Product iterations, registration, authentication, service integration, migrations | Mostly private |
| Healthcare operations | Scheduling, staff workflows, layered architecture, relational data | Private academic project |
| PineLine | Research workflow tooling and structured scientific data | Private exploratory project |
| Peer-reviewed research | Study design, analysis, healthcare data and scientific communication | [Wiley DOI](https://doi.org/10.1111/ijn.13313) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/39431424/) |
| Funny-button | Plain JavaScript interactions and responsive browser behavior | [Public source code](https://github.com/VAntoniazi/Funny-button) |

---

## 01 — Enterprise systems, operations and compliance

**Context:** Internal business platforms, company-controlled repositories and client-confidential code.

**My focus:** Backend services, full-stack administrative applications, application architecture, integration, database evolution and security.

### Engineering problems

Enterprise software rarely starts with a blank slate. Existing processes depend on legacy databases, integrations, approval hierarchies and permissions. A technically attractive rewrite can still fail if it interrupts a business workflow or weakens authorization.

### Engineering work

- **Architecture and modernization:** separating UI, controllers, API routes, services and repositories; introducing incremental changes while retaining contracts relied upon by existing processes.
- **API-first integration:** building and consuming REST APIs to connect operational modules and avoid direct database access from unrelated components.
- **Authorization:** role-based access control (RBAC), granular capabilities, server-side verification, audit evidence and careful handling of public/private endpoints.
- **Approval and workflow design:** organizational relationships, multi-stage approvals, document processes, task assignments, notifications and controlled state transitions.
- **Data and financial processes:** relational modeling, structured imports/exports, fiscal information workflows, validation, idempotency and transaction boundaries.
- **Operational tooling:** logs, regression checks, deployment constraints, CI/CD and environment separation across development, testing and production.
- **User experience:** responsive, data-rich interfaces for administrative workflows, complex filters, compact tables, modals and operational reporting.

### Decisions that matter

| Concern | Engineering priority |
| --- | --- |
| Legacy migration | Incremental compatibility instead of large unverified cutovers |
| Access control | Enforcement at the API/service boundary, not only hiding controls in the UI |
| Business transactions | Idempotency, consistent state, explicit failure handling and auditability |
| Operational visibility | Logs and tests that connect technical behavior to business consequences |
| Data ownership | Reuse owner APIs/contracts rather than introducing conflicting sources of truth |

**Visibility and limits:** This summarizes representative technical experience, not one single public product. Specific customer records, infrastructure, proprietary business rules, credentials and institutional source code are excluded. Individual modules may be in different stages of delivery or validation.

---

## 02 — PinePet: business management SaaS for pet services

**Context:** Software for pet shops, grooming services, boarding/day care and veterinary-related operations.

**Public product:** [pinepet.com.br](https://pinepet.com.br)

### Product complexity

Pet businesses combine a surprising number of operational domains: customer records, animal records, recurring appointments, service execution, stock, commercial transactions, team permissions and administrative oversight. A SaaS product must support these workflows without losing isolation between customers or becoming difficult to maintain.

### Engineering focus

- **Core business data:** customer and pet records, relationships, validation and secure access.
- **Scheduling:** appointments, service calendars, workflow status and operational organization.
- **Commerce and stock:** point-of-sale requirements, inventory movements, financial and payment-related flows.
- **Account lifecycle:** registration, onboarding, authentication, subscription-related integration and access boundaries.
- **Tenant-aware services:** data separation, session and permission checks and administrative roles.
- **Migration and operations:** assisted data onboarding, background processes, document/media workflows and integrations.
- **Application experience:** responsive administration interfaces and usable flows for daily operations.

### Architecture considerations

**SQL design and data integrity** are central to appointments, stock and transactions. **Asynchronous work** is appropriate for slow integrations or document/media handling. **Explicit authorization** protects tenant boundaries independently of how an interface renders controls.

The product's current state should be assessed through its live website and application; this portfolio does not claim that every item above is released or production-complete.

---

## 03 — Pineapple Lab: software services and operations platform

**Context:** My independent software and automation business.

**Public website:** [pineapplelab.net](https://pineapplelab.net/)

Pineapple Lab connects my public service offerings with internal tools for delivering and operating software projects. The business offers software, websites, integrations, automation and data-oriented solutions.

### Engineering work

- Building public-facing web experiences and supporting applications.
- Structuring customer, contract and project-related information.
- Integrating communication channels and workflow automation.
- Using background jobs and scheduled processes for recurring operations.
- Managing infrastructure, application services and deployment workflows.
- Developing AI-assisted editorial systems with deterministic workflow controls.

### Example: research-oriented content automation

This is a useful illustration of how I combine **conventional software and AI**. An editorial workflow needs more than text generation:

1. A controlled catalogue of topics, categories and editorial rules determines what may be researched.
2. Topic discovery and source gathering collect relevant material, including primary sources and scientific literature where appropriate.
3. Previously published ideas and configured duplication windows help prevent repetitive output.
4. Generation is followed by validation, editorial states and a review process.
5. Scheduling, retries, queue processing and publication status are handled by deterministic application logic.

**Design principle:** Use a language model for tasks that benefit from it; keep permissions, state transitions, validation, scheduling and persistence under explicit software control.

---

## 04 — PetFlow.PRO: product iteration and architectural evolution

**Context:** Earlier and evolving pet-business SaaS implementations across multiple applications and supporting services.

**Engineering themes:** Registration and authentication, frontend applications, portals, regional variants, backend services, messaging integrations, deployment and product redesign.

PetFlow work helped surface the kinds of problems that appear when a product grows: fragmented services, inconsistent data contracts, duplicated frontend behavior, fragile routes, complex deployment configurations and changing user journeys.

The relevant experience is not simply building individual pages. It includes comparing architectures, deciding which responsibilities belong in APIs, improving operational workflows and planning safe migrations rather than preserving every legacy technology forever.

**Status:** Historical and ongoing work varies across implementations; individual repositories are not presented as uniformly active or production-ready.

---

## 05 — Healthcare workflow software

**Context:** A Nursing graduation intervention project associated with **Hospital Moinhos de Vento**.

**Problem domain:** Staff schedules and operational organization under healthcare-specific constraints.

### Technical work

- Modeling scheduling and administrative workflows from domain requirements.
- Using **Controller → Service → Repository** separation to keep business rules understandable.
- Representing records and relationships with a relational database.
- Designing interfaces around the information professionals need for daily decisions.
- Applying healthcare-domain understanding to requirements, terminology and validation.

**Why it matters:** Healthcare software requires sensitivity to workflows, traceability and human factors. The same engineering decisions affect the safety, usability and maintainability of operational enterprise systems.

**Visibility:** Academic/private repository. No confidential personnel data or hospital source material is published here.

---

## 06 — PineLine: research workflow software

**Context:** Exploratory software for organizing scientific research and structured information.

The project investigates ways software can support research organization, document/data workflows and scientific production. It remains a **background/exploratory project**, not an actively marketed or daily-use product.

The engineering principles are the most transferable: **data provenance, reproducibility, explicit assumptions, validation and sensible automation**.

---

## 07 — Peer-reviewed research and health data

**Publication:** [*Economic Analysis of Falls in a Private Hospital in Southern Brazil—A Case–Control Study*](https://doi.org/10.1111/ijn.13313)

**First author:** Victor Antoniazi Gonzalez · *International Journal of Nursing Practice* (Wiley), **2024**, 30(6), e13313.

**Research design:** Matched case-control study analyzing inpatient falls and hospital costs, accounting for relevant confounding characteristics.

**Published finding:** Median costs were **US$7,520.26** for fall cases and **US$6,144.24** for nonfall cases (**p < 0.01**). This finding comes from the peer-reviewed study and is not a software outcome claim.

[Read the research summary](RESEARCH.md) · [PubMed record](https://pubmed.ncbi.nlm.nih.gov/39431424/) · [ORCID](https://orcid.org/0000-0001-7577-464X)

The research experience informs how I work with healthcare datasets, analysis, operational reporting and evidence-based engineering decisions.

---

## 08 — Public source code and experiments

### [Funny-button](https://github.com/VAntoniazi/Funny-button)

A compact experiment in native HTML, CSS and JavaScript, featuring pointer and touch handling, responsive behavior and viewport-aware positioning. It requires no runtime dependencies or build pipeline to open locally.

It demonstrates focused frontend fundamentals but is **not** representative of the full scope of my private business software.

[Browse my public GitHub repositories](https://github.com/VAntoniazi?tab=repositories)

---

## Engineering methods & technology

| Discipline | Tools / approaches |
| --- | --- |
| Backend | Python, FastAPI, PHP, Node.js, Go, REST APIs, service/repository boundaries |
| Frontend | TypeScript, JavaScript, React, HTML, CSS, responsive and data-heavy interfaces |
| Data | PostgreSQL, MySQL, SQL, Python/Pandas, R, relational modeling, operational reporting |
| Security | Authentication, RBAC, tenant boundaries, server-side checks, audit trails |
| Reliability | Validations, idempotency, logging, contract/regression checks, safe releases |
| Automation | Background workers, scheduled tasks, queues, APIs and messaging integrations |
| Delivery | Docker, Nginx, Linux, Git, GitHub, Azure DevOps and CI/CD |
| AI in engineering | Context engineering, assisted development/review, structured tasks and source-based research |

### What I look for in a technical problem

**Clear domain requirements, meaningful data, accountable design decisions, secure integrations and the ability to improve a system after the first release.** My strongest work combines development with the investigation and ownership needed to make complicated software dependable.

---

## Verification and confidentiality

**Directly verifiable:** [GitHub profile](https://github.com/VAntoniazi), [Funny-button source](https://github.com/VAntoniazi/Funny-button), [Pineapple Lab website](https://pineapplelab.net/), [PinePet website](https://pinepet.com.br), [2024 published research](https://doi.org/10.1111/ijn.13313).

**Private/limited visibility:** commercial and client software, internal APIs, enterprise data, deployment systems and academic operational projects. Their technical descriptions are summaries, not authorization to distribute source code.

**No fabricated numbers:** this portfolio intentionally avoids invented customer counts, revenue, system throughput, repository activity or production-readiness claims.

[← Back to my GitHub profile](README.md) · [Research](RESEARCH.md) · [LinkedIn](https://www.linkedin.com/in/victor-antoniazi/) · [Contact](mailto:victor@petflow.pro)
