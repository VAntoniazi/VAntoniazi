# Victor Antoniazi Gonzalez

**Software Developer · Backend & Full-Stack Systems · AI-Assisted Development · Data & Automation**

Brazilian developer based between Brazil and Buenos Aires, Argentina. I build production software for **SaaS, enterprise operations, healthcare, data-intensive workflows and automation**, with a strong focus on maintainability, security, observability and pragmatic use of artificial intelligence.

I have been building **personal software projects since 2018** and working on **enterprise/corporate software since 2023–2024**. AI-assisted development has been part of my workflow since the public emergence of modern generative AI in **late 2022 / early 2023**.

My background also includes scientific research and healthcare, which gives me domain context for healthtech, regulated data, operational workflows and evidence-based decision-making.

---

## What I Work On

- **Backend & full-stack software development** — web applications, internal systems, SaaS products, APIs and operational tooling.
- **Backend & API design** — REST APIs, service/repository layers, multi-tenant systems, integrations, background jobs and data synchronization.
- **Legacy modernization** — incremental refactoring, migration from tightly coupled applications to modular architectures, API-first boundaries and safer deployment workflows.
- **Security-oriented development** — authentication, authorization, RBAC, tenant isolation, CSRF protection, secure session/token design, opaque public identifiers, input validation, rate limiting, auditability and secret management.
- **Data-intensive systems** — SQL, large transactional datasets, operational analytics, ETL-style routines, workflow automation and research datasets.
- **AI-assisted development** — structured prompting, code generation, refactoring, test generation, documentation, debugging and technical review with human validation.
- **AI-driven research & publishing automation** — source-grounded research, topic selection, editorial validation, scheduling, deduplication, SEO and controlled publication workflows.
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

### Automated Research & Editorial Publishing Systems

I designed and developed automated editorial pipelines used across **PinePet, Pineapple Lab and earlier PetFlow.PRO implementations**. These systems go beyond simple AI text generation: they combine research, deterministic controls, editorial rules, scheduling and post lifecycle management around the language model.

The workflow includes:

- **topic discovery and research** based on current, relevant subjects within predefined business/editorial themes;
- a managed **repository of categories and editorial scopes** that constrains what the system should research and publish;
- **automatic or manual category selection**, while preserving operator control over themes and publication strategy;
- comparison against previously generated/published subjects and configurable **duplicate-topic windows** to reduce repeated or overly similar articles;
- manual ideas as well as automatically selected topics, with similarity checks before scheduling;
- **calendar-based scheduling**, configurable publication intervals and multiple future publication dates;
- configurable AI provider, text/image models, prompts, language, editorial format, author and publication destination;
- research before generation, prioritizing **real, verifiable sources**, including primary/official sources and **scientific literature when relevant**;
- generation followed by **editorial and structural validation**, rather than accepting model output directly;
- source/reference persistence so generated claims can remain connected to the research used during production;
- draft/review/published lifecycle control, article regeneration and controlled retry/cancellation of automation jobs;
- SEO-oriented metadata generation and maintenance, together with search/indexing integrations;
- background workers and queued jobs for generation and editorial maintenance instead of coupling expensive AI work to user HTTP requests;
- administrative control over schedules, categories, prompts, publication states and generated content.

The design principle is the same as in my development workflow: **AI performs the probabilistic work, while deterministic software controls scope, state, validation, scheduling, security and persistence**.

---

## Software Development Practices

| Area | Practices |
|---|---|
| **Architecture** | MVC, Controller/Service/Repository separation, modular domains, API-first boundaries, background workers, transactional workflows |
| **Backend** | PHP, Python, Go, FastAPI-oriented services, Node.js, REST APIs, server-side validation, integrations |
| **Frontend** | JavaScript, TypeScript, React, responsive interfaces, progressive enhancement, reusable UI components |
| **Databases** | PostgreSQL, MySQL/MariaDB, schema design, foreign keys, transactions, idempotency, prepared statements |
| **Security** | RBAC, tenant isolation, JWT/session controls, CSRF, Argon2id/password hashing, opaque IDs, rate limiting, audit logs, secret separation |
| **Testing** | regression checks, API/contract validation, UI validation, responsive-layout checks, deployment validation, edge-case testing |
| **Infrastructure** | Docker, Docker Compose, Nginx, PHP-FPM, Linux, environment separation, scheduled jobs, object storage |
| **CI/CD** | Azure DevOps, GitHub, automated validation gates, branch-based delivery workflows |
| **Data** | SQL, Python, R, Pandas, statistical analysis, operational analytics, scientific datasets |
| **Automation** | Python/Node/PHP scripts, background workers, scheduled jobs, queues, workflow automation, synchronization routines, messaging/integration services, AI-assisted editorial pipelines |

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
- **AI-assisted automated blog/research publishing with scheduling, category control, topic deduplication, source validation, editorial policies and SEO maintenance**;
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

### 🍍 Pineapple Lab — Service Business Platform, Portfolio & Contract Management

Pineapple Lab is the system I developed to support my own activity as an independent software/service provider. It combines the public-facing side of my work with the operational tools I use to organize service delivery.

The ecosystem includes:

- my professional landing page and public presentation;
- presentation of products and services;
- management of contracts and information related to service engagements;
- client/service-provider operational workflows;
- portal and supporting application services;
- messaging and automation integrations;
- **an automated editorial/blog workflow for researching, generating, validating, scheduling and managing relevant content**;
- internal routines and infrastructure used to support my work.

The publishing workflow is designed around predefined categories and themes, avoids unnecessary repetition of prior subjects, preserves control over schedules and topics, and uses real references — including scientific literature when appropriate — as part of a more reliable content-generation process.

The main web platform uses a static-first delivery path for public content together with a PHP MVC application for dynamic features, supported by **PostgreSQL, Docker, Nginx and Node-based build/deployment validation**.

Rather than being only a portfolio website, Pineapple Lab functions as part of the operational software behind my own service business.

---

### 🐶 PetFlow.PRO — Original Veterinary SaaS / Predecessor to PinePet

PetFlow.PRO was the initial version of the veterinary/pet-business SaaS concept that later gave rise to **PinePet**.

It evolved across multiple repositories and services, including application, portal, onboarding/login, Node.js services, messaging integrations, regional variants and **automated blog/content publishing workflows**. The experience accumulated in PetFlow.PRO exposed architectural and product limitations that motivated a **large-scale redesign and restructuring**, ultimately leading to the current PinePet architecture.

This project family contributed practical experience in:

- product iteration from an initial architecture to a substantially redesigned system;
- splitting functionality across deployable services;
- Docker/Nginx/PHP/Node environments;
- authentication and onboarding flows;
- multi-application product architecture;
- messaging integrations;
- AI-assisted content/research automation and scheduled publishing;
- migration and modernization decisions based on lessons from a real previous version.

---

### 🔬 PineLine — Research-Oriented Scientific Software

PineLine is a research-oriented software project designed to assist scientific production and structured research workflows.

The project explores tooling for organizing and supporting activities such as research data handling, scientific workflow organization and other tasks around the production of academic work. It currently remains **in the background / not actively used in my day-to-day workflow**, but represents the application of software development to scientific-research processes.

My research background influences how I approach this type of software: traceability, reproducibility, explicit assumptions, measurable outcomes and careful treatment of data are considered part of the development process rather than afterthoughts.

---

### 🏥 Nursing Graduation Intervention Project — Hospital Moinhos de Vento

As part of my **Bachelor's degree in Nursing at Faculdade do Hospital Moinhos de Vento**, I developed an intervention project associated with **Hospital Moinhos de Vento** focused on improving healthcare staffing/schedule management.

The software was created to facilitate the organization and management of staff schedules under real operational constraints, translating a practical healthcare-management problem into a working software solution.

The project uses a layered **Controller → Service → Repository** architecture with **MySQL and Docker**, combining my nursing-domain experience with software development and process improvement.

---

### 📊 Scientific Research & Health-Economic Analysis

My scientific work combines healthcare-domain knowledge, structured datasets, statistical analysis and economic evaluation.

#### Published research

**Economic Analysis of Falls in a Private Hospital in Southern Brazil: A Case-Control Study**  
**Principal researcher / first author: Victor Antoniazi Gonzalez**  
*International Journal of Nursing*  
**Status:** Published  
DOI: [10.1111/ijn.13313](https://doi.org/10.1111/ijn.13313) · PubMed: [39431424](https://pubmed.ncbi.nlm.nih.gov/39431424/)

The study involved **database construction, data validation, statistical analysis, economic/cost modeling and scientific writing in English**, applied to the financial impact of patient falls in a private hospital setting.

#### Ongoing research

**Economic analysis of healthcare expenditure using DATASUS data**  
**Status:** Ongoing

An additional research project focused on comparing and analyzing healthcare expenditure using public health data from **DATASUS**, combining data preparation, economic analysis and health-system information to investigate expenditure patterns and related outcomes.

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
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
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

**ChatGPT / OpenAI · Codex · Claude · local LLMs · prompt scripting · context engineering · AI-assisted code review · automated test generation · source-grounded research automation · editorial validation · scheduled publishing · documentation automation**

---

## Background

- **Software development:** personal projects since **2018**; enterprise/corporate software since **2023–2024**.
- **AI-assisted development:** continuous use since **late 2022 / early 2023**, evolving from conversational assistance to structured development workflows.
- **Healthcare:** Bachelor's degree in Nursing — **completion expected in 2026**.
- **Research:** principal-researcher/first-author experience, healthcare economic analysis, scientific initiation and peer-reviewed publication.
- **Languages:** Portuguese, Spanish and English.
- **Location:** permanent resident of Argentina, with activity between Buenos Aires and Brazil.

The combination of software, data, healthcare and research is especially useful in **healthtech, regulated systems, operational software and data-intensive products**.

---

## Professional Interests

My primary professional focus is **backend development with full-stack capability**. I am especially interested in roles where I can own meaningful parts of a system, work with substantial amounts of data and retain enough technical autonomy to investigate problems, design solutions and improve architecture rather than being limited to isolated implementation tasks.

Areas of particular interest include:

- backend and full-stack product development;
- data-intensive applications and high-volume operational datasets;
- SaaS platforms;
- healthtech and health informatics;
- API and systems integration;
- legacy modernization;
- AI-assisted development workflows;
- automation and distributed/background processing;
- secure internal/enterprise systems.

I particularly value environments that combine **technical ownership, autonomy, complex data and real operational problems**.


---

## Open-source experiments

### Funny-button

A tiny dependency-free browser interaction experiment built with plain HTML, CSS and JavaScript, with pointer/touch handling, viewport-aware positioning, CI validation and public contribution documentation.

[![GitHub stars](https://img.shields.io/github/stars/VAntoniazi/Funny-button?style=flat-square&logo=github)](https://github.com/VAntoniazi/Funny-button)
[![Repository](https://img.shields.io/badge/Repository-Funny--button-181717?style=flat-square&logo=github)](https://github.com/VAntoniazi/Funny-button)

→ [View Funny-button on GitHub](https://github.com/VAntoniazi/Funny-button)

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vantoniazi)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:victor@petflow.pro)
[![PubMed](https://img.shields.io/badge/PubMed-326599?style=flat-square&logo=pubmed&logoColor=white)](https://pubmed.ncbi.nlm.nih.gov/39431424/)

---

> **Note for recruiters:** many of the most substantial repositories on this account are private because they contain active products, enterprise systems or NDA-restricted work. Public repository visibility should not be interpreted as the full scope of the work described above.