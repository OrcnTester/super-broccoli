# 📚 Software Engineering Mini-Glossary

[![Awesome](https://img.shields.io/badge/awesome-glossary-%23ff69b4)](https://github.com/OrcnTester)  
[![Made with Markdown](https://img.shields.io/badge/made%20with-markdown-blue)](#)  
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](#)  

✨ **A comprehensive glossary of the most common software engineering terms.**  
Perfect for **interview prep, onboarding, quick refreshers** or just flexing your dev knowledge 💪  

---

## 📑 Table of Contents
- [Database & Data Modeling](#database--data-modeling)  
- [Data Formats & Messaging](#data-formats--messaging)  
- [Backend Architecture Patterns](#backend-architecture-patterns)  
- [Caching & Performance](#caching--performance)  
- [Security](#security)  
- [Testing & Quality](#testing--quality)  
- [Runtime & Languages](#runtime--languages)  
- [HTTP & Web](#http--web)  
- [Frontend Basics](#frontend-basics)  
- [Cloud & DevOps](#cloud--devops)  
- [Data & Analytics](#data--analytics)  
- [Machine Learning & AI](#machine-learning--ai)  
- [Version Control & Git](#version-control--git)  
- [Licensing & Compliance](#licensing--compliance)  
- [Product & Process](#product--process)  

---

## 🚀 Quick Glance
- 🗄️ **Normalization** → reduce redundancy & keep data consistent  
- 🔐 **JWT** → signed token for stateless authentication  
- ⚡ **Caching (TTL)** → store data fast, auto-expire  
- ☁️ **CI/CD** → automate build, test & deploy  
- 🧪 **Unit / Integration / E2E** → levels of testing  

👉 Scroll down for the **full glossary** with 15+ sections and 150+ terms!  

---

## Database & Data Modeling
- **Normalization** → Organize tables to reduce redundancy & keep consistency (1NF/2NF/3NF)  
- **Denormalization** → Add redundancy for faster reads  
- **Primary Key (PK)** → Unique row identifier (`id`)  
- **Foreign Key (FK)** → Relation between tables (`order.customer_id → customers.id`)  
- **Unique / Composite Index** → Constraints & performance boosts  
- **Transaction (ACID)** → Reliable “all or nothing” operations  
- **Isolation Levels** → Control concurrency (Read Committed, Serializable, …)  
- **Sharding / Partitioning** → Horizontal/vertical data splitting  
- **Replication** → Copies of DB for HA & scaling  
- **ORM** → Object-Relational Mapping (Prisma, Hibernate)  
- **N+1 Query Problem** → Multiple redundant queries in loops  
- **Event Sourcing** → Build state from events instead of rows  

---

## Data Formats & Messaging
- **JSON / YAML** → Common data formats  
- **Protobuf / Avro** → Binary, schema-driven formats  
- **gRPC** → High-performance remote procedure calls  
- **REST** → Resource-oriented APIs over HTTP  
- **Webhooks** → Event notification via HTTP calls  
- **Message Queue** → Async pipelines (RabbitMQ, SQS)  
- **Pub/Sub** → Publish–subscribe messaging (Kafka, Pulsar)  
- **Idempotency** → Safe retries without side effects  
- **Exponential Backoff** → Retry delays increasing over time  

---

## Backend Architecture Patterns
- **Monolith** → One big app  
- **Microservices** → Many small apps with independent scaling  
- **Hexagonal / Ports & Adapters** → Isolate business logic from infrastructure  
- **CQRS** → Split read & write models  
- **Saga** → Distributed transaction with compensations  
- **Circuit Breaker** → Stop cascading failures  
- **Bulkhead** → Resource isolation to prevent ripple failures  
- **Rate Limiting** → Control request rates  
- **Feature Flags** → Gradually enable/disable features  

---

## Caching & Performance
- **Caching** → Store frequent data in fast memory (Redis, CDN)  
- **TTL** → Time to live for cache entries  
- **Eviction Policy** → LRU/LFU rules for cache removal  
- **Lazy vs Eager Loading** → Load data on-demand vs upfront  
- **Batching** → Group queries into one  
- **Pagination** → Offset vs keyset scrolling  
- **Keyset Pagination** → Faster page navigation on big data sets  
- **Bloom Filter** → Probabilistic existence check  
- **CDN** → Distribute static assets close to users  

---

## Security
- **Authentication vs Authorization** → Who you are vs what you can do  
- **OAuth2 / OIDC** → Delegated login & identity  
- **JWT** → Signed token for stateless sessions  
- **CSRF / XSS / SQL Injection** → Common web vulnerabilities  
- **CORS** → Cross-domain browser access rules  
- **Secrets Management** → Store credentials securely (Vault, KMS)  
- **Password Hashing** → bcrypt/argon2 instead of plain text  
- **TLS / mTLS** → Encrypted comms & mutual trust  
- **Least Privilege** → Minimal required access principle  
- **Audit Logs** → Track who did what  

---

## Testing & Quality
- **Unit / Integration / E2E** → Different levels of testing  
- **Mocks / Stubs** → Fake dependencies  
- **TDD** → Test-driven development  
- **Coverage** → % of code tested  
- **Static Analysis / Linting** → Detect smells automatically  
- **Property-based Testing** → Validate with random inputs  
- **Canary Release** → Roll out to a small % of users first  

---

## Runtime & Languages
- **JIT / AOT** → Just-in-time vs ahead-of-time compilation  
- **Garbage Collection** → Automatic memory cleanup  
- **Threads / Async IO** → Concurrency vs parallelism  
- **Event Loop** → Node.js async core  
- **Immutable Data** → Prevent side effects  
- **Pure Functions** → Same input, same output  
- **DSL** → Domain-specific languages (SQL, Regex)  

---

## HTTP & Web
- **HTTP Methods** → GET/POST/PUT/PATCH/DELETE  
- **Idempotent** → Safe repeated calls (e.g., PUT, DELETE)  
- **Status Codes** → 2xx success, 4xx client error, 5xx server error  
- **ETag** → Fingerprint for caching validation  
- **HATEOAS** → Discoverable REST APIs with links  
- **SSE / WebSocket** → Server push & real-time communication  
- **SPA / MPA** → Single vs multi-page apps  

---

## Frontend Basics
- **Virtual DOM** → Efficient UI updates  
- **Reconciliation** → Updating only changed nodes  
- **State Management** → Redux/Zustand, central state store  
- **SSR / SSG / ISR** → Rendering strategies in Next.js  
- **Hydration** → Make static HTML interactive  
- **Code Splitting** → Load only what’s needed  
- **Bundling / Transpiling** → Webpack, Vite, Babel  
- **Accessibility (a11y)** → Inclusive design rules  
- **CSS Methodologies** → BEM vs Utility-first (Tailwind)  

---

## Cloud & DevOps
- **CI/CD** → Automate test & deploy pipelines  
- **Blue-Green / Rolling Deploys** → Zero-downtime releases  
- **Infrastructure as Code (IaC)** → Terraform, Pulumi  
- **Containers & Orchestration** → Docker, Kubernetes  
- **Service Mesh** → Routing, mTLS, telemetry (Istio, Linkerd)  
- **Autoscaling (HPA)** → Scale up/down automatically  
- **Observability (O11y)** → Logs, metrics, traces  
- **SLO / SLA / SLI** → Targets, agreements, indicators  
- **Chaos Engineering** → Test resilience by breaking things  
- **FinOps** → Cloud cost optimization  

---

## Data & Analytics
- **OLTP vs OLAP** → Transaction vs analytics workloads  
- **Data Warehouse** → Structured analytics store (BigQuery, Redshift)  
- **Data Lake / Lakehouse** → Raw + structured storage  
- **Star / Snowflake Schema** → OLAP modeling patterns  
- **ETL / ELT** → Data ingestion strategies  
- **Window Functions** → Time-based SQL analytics  
- **Time Series DB** → Specialized for time data (Timescale, InfluxDB)  
- **Feature Store** → ML feature repository  
- **Data Governance** → Lineage, ownership, quality rules  

---

## Machine Learning & AI
- **Supervised vs Unsupervised** → Labeled vs unlabeled learning  
- **Overfitting / Regularization** → Prevent memorization, improve generalization  
- **Embeddings** → Vector representation of data  
- **Vector DB** → Store & search embeddings  
- **RAG** → Retrieval-augmented generation (LLMs + search)  
- **Prompt Engineering** → Guide LLM behavior  

---

## Version Control & Git
- **Semantic Versioning** → MAJOR.MINOR.PATCH  
- **Changelog** → Track changes  
- **Trunk-based Dev** → Small branches, fast merges  
- **Rebase vs Merge** → Clean vs quick history  
- **Conventional Commits** → `feat:`, `fix:`, `chore:` prefixes  
- **Git Hooks** → Pre-commit checks  

---

## Licensing & Compliance
- **MIT / Apache / GPL** → Popular OSS licenses  
- **Copyleft** → Enforces same license downstream  
- **Privacy by Design** → Privacy built in  
- **PII / PD** → Personal data concepts  
- **DLP** → Data loss prevention  

---

## Product & Process
- **Agile / Scrum / Kanban** → Iterative delivery frameworks  
- **User Story** → “As a user, I want …”  
- **Acceptance Criteria** → Clear “done” definition  
- **Definition of Done (DoD)** → Quality checklist  
- **OKRs** → Objectives & Key Results  
- **A/B Testing** → Experiment with two variants  

---

### ✨ Usage
Clone → Read → Show off.  
Great for **interviews, onboarding, meetups, or personal learning**.  

---

Made with ❤️ by [OrcnTester](https://github.com/OrcnTester)  
