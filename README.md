# Victor Antoniazi Gonzalez

**Software Developer · Full-Stack & Backend Systems · AI-Assisted Development · Data & Automation**

Brazilian developer based between Brazil and Buenos Aires, Argentina. I build production software for **SaaS, enterprise operations, healthcare, data-intensive workflows and automation**, with a strong focus on maintainability, security, observability and pragmatic use of artificial intelligence.

I have been building **personal software projects since 2018** and working on **enterprise/corporate software since 2023–2024**. AI-assisted development has been part of my workflow since the public emergence of modern generative AI in **late 2022 / early 2023**.

My background also includes scientific research and healthcare, which gives me domain context for healthtech, regulated data, operational workflows and evidence-based decision-making.

---

## What I Work On

- **Full-stack software development** — web applications, internal systems, SaaS products, APIs and operational tooling.
- **Backend & API design** — REST APIs, service/repository layers, multi-tenant systems, integrations, background jobs and data synchronization.
- **Legacy modernization** — incremental refactoring, migration from tightly coupled applications to modular architectures, API-first boundaries and safer deployment workflows.
- **Security-oriented development** — authentication, authorization, RBAC, tenant isolation, CSRF protection, secure session/token design, opaque public identifiers, input validation, rate limiting, auditability and secret management.
- **Data & automation** — SQL, transactional datasets, operational analytics, ETL-style routines, workflow automation and research datasets.
- **AI-assisted development** — structured prompting, code generation, refactoring, test generation, documentation, debugging and technical review with human validation.
- **DevOps & delivery** — Docker, Nginx, PHP-FPM, Linux, CI/CD, Azure DevOps, GitHub and production-oriented environment separation.

---

## AI-Assisted Development

I have used **ChatGPT since late 2022 / early 2023**, and over time expanded the workflow to include **OpenAI Codex, Claude, local LLMs and other models evaluated for specific development tasks**.

I treat AI as an engineering accelerator, not as an authority. The objective is to reduce low-value repetitive work while preserving technical judgment, security, reproducibility and maintainability.

### How I use AI in software development

- **Prompt scripting and task decomposition** — converting product or technical requirements into structured implementation plans, reusable prompt specifications, acceptance criteria and validation steps.
- **Context engineering** — providing the model with the minimum relevant architecture, contracts, schemas and constraints required to solve the task without unnecessary exposure of unrelated data.
- **Implementation assistance** — scaffolding modules, APIs, repositories, services, SQL changes, scripts and infrastructure configuration.
- **Refactoring and legacy analysis** — comparing implementations, identifying duplicated logic, mapping dependencies and proposing incremental modernization paths.
- **Security review** — checking authentication flows, authorization boundaries, input validation, token/session handling, secret exposure, predictable identifiers and unsafe defaults.
- **Automated test generation** — creating regression tests, API contract checks, validation scripts, edge-case matrices and deployment guards.
- **Debugging** — analyzing logs, stack traces, HTTP flows, SQL behavior, frontend regressions and environment differences.
- **Documentation** — maintaining architecture notes, operational procedures, API contracts, migration instructions and README documentation close to the code.
- **Code review support** — using multiple model passes when useful, then validating recommendations against the actual codebase, runtime behavior and project constraints.

### Responsible and resource-aware AI use

- Cloud models are used when they materially improve quality or speed.
- Local models are evaluated when privacy, cost, latency or offline execution make them more appropriate.
- Proprietary/NDA-restricted information is not intentionally exposed to third-party AI services without authorization.
- AI-generated code is treated as untrusted until reviewed, tested and validated.
- I avoid using a large model for tasks that deterministic code, SQL, static analysis or a small local model can solve more efficiently.
- The goal is **useful AI**, not AI everywhere.

---

## Software Development Practices

| Area | Practices |
|---|---|
| **Architecture** | MVC, Controller/Service/Repository separation, modular domains, API-first boundaries, background workers, transactional workflows |
| **Backend** | PHP, Python, FastAPI-oriented services, Node.js, REST APIs, server-side validation, integrations |
| **Frontend** | JavaScript, TypeScript, React, responsive interfaces, progressive enhancement, reusable UI components |
| **Databases** | PostgreSQL, MySQL/MariaDB, schema design, foreign keys, transactions, idempotency, prepared statements |
| **Security** | RBAC, tenant isolation, JWT/session controls, CSRF, Argon2id/password hashing, opaque IDs, rate limiting, audit logs, secret separation |
| **Testing** | regression checks, API/contract validation, UI validation, responsive-layout checks, deployment validation, edge-case testing |
| **Infrastructure** | Docker, Docker Compose, Nginx, PHP-FPM, Linux, environment separation, scheduled jobs, object storage |
| **CI/CD** | Azure DevOps, GitHub, automated validation gates, branch-based delivery workflows |
| **Data** | SQL, Python, R, Pandas, statistical analysis, operational analytics, scientific datasets |
| **Automation** | Python/Node/PHP scripts, scheduled jobs, workflow automation, synchronization routines, messaging/integration services |

---

## Selected Systems & Project Families

### 🐾 PinePet — Veterinary SaaS

Current product work focused on a multi-tenant SaaS platform for pet shops, grooming businesses, hotels/day care and veterinary operations.

The ecosystem includes a public site and authenticated application with work across:

- customer and pet management;
- scheduling and service execution;
- inventory and transactional stock movement;
- POS / payments and financial workflows;
- onboarding and assisted data migration;
- permissions, sessions and tenant isolation;
- billing/subscription integration;
- private object storage and signed media access;
- OCR-assisted document workflows;
- scheduled jobs and background processing;
- responsive UI and deployment validation.

The current architecture uses **PHP 8.x, PostgreSQL, Docker, Nginx, JavaScript/Node tooling and service/repository patterns**, with security controls such as CSRF validation, prepared statements, Argon2id, opaque identifiers and server-side authorization.

PinePet also contains executable validation routines for areas such as **identity separation, registration contracts, webhook authentication, responsive layout, UI structure and deployment structure**.

→ [pinepet.com.br](https://pinepet.com.br)

---

### 🏢 Enterprise Management, Audit & Compliance Systems — Private / NDA

I work on internal enterprise systems that combine operational workflows, audit/compliance requirements, document management and integration with existing corporate data.

Work in this area includes:

- modernization of legacy PHP/JavaScript applications;
- migration toward modular MVC/service/repository structures;
- API-first access for domains that need to scale or be reused across modules;
- authentication and authorization redesign;
- RBAC and granular permissions;
- document workflows and electronic-signature integration;
- employee, vehicle, parking, asset and operational records;
- finance/NFSe workflows and approval chains;
- scheduled automation and notification routines;
- SQL/schema refactoring and data migration;
- CI/CD and environment separation;
- progressive movement of shared/high-growth services toward **Python/FastAPI-based APIs**.

Some repositories are synchronized or mirrored between **corporate version-control environments (including Azure DevOps)** and private GitHub repositories when contractually permitted. The public profile intentionally does not expose proprietary code, credentials, business rules or confidential infrastructure details.

---

### 🍍 Pineapple Lab — Web Platform & Automation Ecosystem

A collection of web, portal, messaging and infrastructure services used for product experiments, automation and production tooling.

The main web platform uses a static-first delivery path for the public site plus a PHP MVC application for dynamic content, with **PostgreSQL, Docker, Nginx, Node-based build validation and production deployment tooling**.

Related private repositories cover portal/application services, messaging integrations, routines and supporting infrastructure.

---

### 🐶 PetFlow.PRO — Earlier Veterinary SaaS Ecosystem

An earlier generation of veterinary/pet-business software that evolved across multiple repositories and services, including application, portal, onboarding/login, Node.js services, messaging integrations and regional variants.

This project family contributed practical experience in:

- splitting a product into deployable services;
- Docker/Nginx/PHP/Node environments;
- authentication and onboarding flows;
- multi-application product architecture;
- messaging integrations;
- SaaS product iteration and migration toward newer architecture.

---

### 🔬 PineLine & Research-Oriented Software

Private research/software projects focused on scientific workflows, structured data and health-related applications. The repository family includes containerized PHP/Nginx application foundations and supporting app work.

My research background influences how I approach software: traceability, reproducibility, explicit assumptions, measurable outcomes and careful treatment of data are part of the development process rather than afterthoughts.

---

### 🏥 Healthcare Operational Software

A private graduation intervention project for healthcare staffing/scheduling uses a layered **Controller → Service → Repository** architecture with **MySQL and Docker**.

This work combines domain knowledge from nursing with software development for real operational constraints in healthcare environments.

---

### 📊 Data, Analytics & Scientific Research

I also work with structured analytical datasets and scientific research.

**Peer-reviewed publication:**

**Economic Analysis of Falls in a Private Hospital in Southern Brazil — A Case-Control Study**  
*International Journal of Nursing*  
DOI: [10.1111/ijn.13313](https://doi.org/10.1111/ijn.13313) · PubMed: [39431424](https://pubmed.ncbi.nlm.nih.gov/39431424/)

The work involved database construction, data validation, statistical analysis, cost modeling and scientific writing in English.

I have also worked with large transactional datasets for business and research use cases, including data preparation, KPI modeling, operational analysis and automation.

---

## Repository Landscape & NDA Work

This GitHub account contains a mix of:

- active product repositories;
- private enterprise repositories;
- legacy systems under modernization;
- product/service experiments;
- research and healthcare software;
- infrastructure and automation repositories;
- public demonstration/learning repositories.

**GitHub is not a complete inventory of my professional work.** A significant portion of custom enterprise development remains in client/company-controlled repositories or other version-control environments due to **NDA, intellectual-property and access-control requirements**.

Where permitted, selected repositories or branches may be synchronized between systems such as **Azure DevOps and private GitHub repositories** for development continuity, refactoring or migration. Confidential code is not made public simply to expand a portfolio.

---

## Tech Stack

### Languages

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

### Backend, Data & Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

### Frontend & Analytics

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

### AI Development Workflow

**ChatGPT / OpenAI · Codex · Claude · local LLMs · prompt scripting · context engineering · AI-assisted code review · automated test generation · documentation automation**

---

## Background

- **Software development:** personal projects since **2018**; enterprise/corporate software since **2023–2024**.
- **AI-assisted development:** continuous use since **late 2022 / early 2023**, evolving from conversational assistance to structured development workflows.
- **Healthcare:** Bachelor's degree in Nursing — **completion expected in 2026**.
- **Research:** scientific initiation, healthcare/economic research and peer-reviewed publication.
- **Languages:** Portuguese, Spanish and English.
- **Location:** permanent resident of Argentina, with activity between Buenos Aires and Brazil.

The combination of software, data, healthcare and research is especially useful in **healthtech, regulated systems, operational software and data-intensive products**.

---

## Professional Interests

I am especially interested in software-development roles involving:

- backend and full-stack product development;
- SaaS platforms;
- healthtech and health informatics;
- API and systems integration;
- legacy modernization;
- AI-assisted development workflows;
- automation and data-intensive applications;
- secure internal/enterprise systems.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vantoniazi)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:victor@petflow.pro)
[![PubMed](https://img.shields.io/badge/PubMed-326599?style=flat-square&logo=pubmed&logoColor=white)](https://pubmed.ncbi.nlm.nih.gov/39431424/)

---

> **Note for recruiters:** many of the most substantial repositories on this account are private because they contain active products, enterprise systems or NDA-restricted work. Public repository visibility should not be interpreted as the full scope of the work described above.
