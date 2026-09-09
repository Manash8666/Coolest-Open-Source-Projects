# 🚀 Coolest Open Source Projects

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg?style=for-the-badge" alt="Maintained" />
  <img src="https://img.shields.io/badge/Curated_for-Junior_Devs_%26_Freshers-blue.svg?style=for-the-badge" alt="Curated For Junior Developers" />
  <img src="https://img.shields.io/badge/License-MIT-orange.svg?style=for-the-badge" alt="License" />
  <img src="https://img.shields.io/badge/PRs-Welcome-purple.svg?style=for-the-badge" alt="PRs Welcome" />
</p>

> A curated, battle-tested directory of world-class open-source systems designed to help **Junior Developers, Freshers, and Aspiring Software Engineers** master real-world software architecture, navigate production codebases, and bridge the gap between hobby tutorials and enterprise systems.

---

## 📚 Dedicated Learning Playbooks

Before diving into the codebases below, make sure to read our companion guides:
- 🧭 **[How to Study 100k+ Line Codebases Without Overwhelm](./docs/how-to-study-codebases.md)** — A 5-stage reconnaissance playbook for tracing real-world execution flows.
- 🏛️ **[Software Architecture Patterns for Beginners](./docs/architecture-patterns-for-beginners.md)** — Clear breakdowns of Clean Architecture, Event Queues, Monorepos, and Multi-Tenancy.

---

## 📑 Table of Contents

- [🤖 Artificial Intelligence & LLM Systems](#-artificial-intelligence--llm-systems)
- [📈 Marketing, Growth & Engagement Tech](#-marketing-growth--engagement-tech)
- [💼 Sales, CRM & Business Operations](#-sales-crm--business-operations)
- [📊 Business Analysis, BI & Data Engineering](#-business-analysis-bi--data-engineering)
- [🎨 UI/UX Design Systems & Prototyping](#-uiux-design-systems--prototyping)
- [🖌️ Graphic Design, Creative Media & VFX](#️-graphic-design-creative-media--vfx)
- [⚙️ Tech Development: Core Engineering](#️-tech-development-core-engineering)
  - [Backend Frameworks & Distributed Systems](#backend-frameworks--distributed-systems)
  - [Backend-as-a-Service (BaaS) & Realtime Stacks](#backend-as-a-service-baas--realtime-stacks)
  - [Databases, Search Engines & Vector Stores](#databases-search-engines--vector-stores)
  - [DevOps, Cloud Platforms & Self-Hosting PaaS](#devops-cloud-platforms--self-hosting-paas)
  - [Developer Tooling, APIs & Testing](#developer-tooling-apis--testing)
  - [Identity, Authentication & Secrets Management](#identity-authentication--secrets-management)
- [💡 How to Contribute](#-how-to-contribute)

---

## 🤖 Artificial Intelligence & LLM Systems

Production AI architectures showing model serving, retrieval-augmented generation (RAG), agent loops, and vector indexing.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Ollama](https://github.com/ollama/ollama)** | `Go`, `C++`, `llama.cpp` | Run large language models (Llama 3, Mistral, Gemma) locally with a clean REST API. | Exemplary Go-to-C++ interoperability (cgo), streaming HTTP responses, and hardware accelerator binding. |
| **[vLLM](https://github.com/vllm-project/vllm)** | `Python`, `C++`, `CUDA` | High-throughput, memory-efficient LLM serving engine using PagedAttention. | Learn advanced memory management, multi-GPU orchestration, and kernel optimization. |
| **[Dify](https://github.com/langgenius/dify)** | `Python`, `Next.js`, `Celery` | Production-ready LLM application development platform featuring visual workflow orchestration. | Demonstrates how to design an enterprise agent runner, asynchronous Celery task pipelines, and plugin systems. |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | `SvelteKit`, `Python`, `FastAPI` | Feature-packed, privacy-first UI for interacting with local and remote LLMs. | Study modern Svelte state management, WebSocket streaming, and dynamic tool-calling interfaces. |
| **[LangChain](https://github.com/langchain-ai/langchain)** | `Python` | Standard framework for composing chains, memory, and agents with language models. | Understand abstraction hierarchies, interface design, and prompt template composition. |
| **[LlamaIndex](https://github.com/run-llama/llama_index)** | `Python` | Data framework for building RAG applications connecting custom data to LLMs. | Study index data structures, chunking strategies, and hybrid vector-keyword retrieval techniques. |
| **[Flowise](https://github.com/FlowiseAI/Flowise)** | `TypeScript`, `Node.js`, `React` | Drag-and-drop visual UI to construct and deploy customized LLM chains and agents. | Learn how visual graph execution engines are built on React Flow and evaluated on Node backends. |
| **[LocalAI](https://github.com/mudler/LocalAI)** | `Go`, `C++` | Drop-in OpenAI REST API replacement for local CPU/GPU inferencing. | Master API adapter patterns, binary lifecycle management, and gRPC backends. |
| **[Transformers](https://github.com/huggingface/transformers)** | `Python`, `PyTorch` | State-of-the-art machine learning architectures for text, vision, and audio models. | Study software engineering at scale in deep learning: dynamic configuration, modular models, and hardware backends. |

---

## 📈 Marketing, Growth & Engagement Tech

High-throughput systems for product analytics, email delivery, notification orchestration, and viral loops.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[PostHog](https://github.com/PostHog/posthog)** | `Python`, `TypeScript`, `ClickHouse`, `Kafka` | Complete product analytics suite: session replay, feature flags, A/B testing, and heatmaps. | Master massive-scale event ingestion using Kafka and high-speed analytical querying with ClickHouse. |
| **[Novu](https://github.com/novuhq/novu)** | `TypeScript`, `NestJS`, `Redis`, `MongoDB` | Unified notification infrastructure for email, SMS, push, chat, and in-app feeds. | Understand multi-provider abstractions, queue rate-limiting, and template digest strategies. |
| **[Umami](https://github.com/umami-software/umami)** | `TypeScript`, `Next.js`, `Prisma` | Privacy-focused, lightweight alternative to Google Analytics. | Clean, minimal full-stack Next.js project showcasing fast aggregations and lightweight script bundling. |
| **[Plausible Analytics](https://github.com/plausible/analytics)** | `Elixir`, `Phoenix`, `ClickHouse` | Ultra-fast, cookie-free web analytics platform. | Experience functional programming with Elixir's BEAM concurrency model combined with ClickHouse storage. |
| **[Ghost](https://github.com/TryGhost/Ghost)** | `Node.js`, `JavaScript`, `MySQL` | Modern publishing and newsletter platform for creators and media businesses. | Benchmark for Node.js production service design, member subscription logic, and custom theme engines. |
| **[Listmonk](https://github.com/knadh/listmonk)** | `Go`, `PostgreSQL`, `Vue.js` | High-performance, self-hosted newsletter and mailing list manager. | Observe hyper-optimized Go concurrency capable of dispatching millions of emails per hour with low CPU usage. |
| **[Dub.co](https://github.com/dubinc/dub)** | `TypeScript`, `Next.js`, `Tailwind` | Modern link management infrastructure with real-time analytics and custom domain routing. | Exemplary Turborepo monorepo setup, edge middleware routing, and polished UI component design. |
| **[Mautic](https://github.com/mautic/mautic)** | `PHP`, `Symfony`, `MySQL` | Enterprise marketing automation platform for lead nurturing and campaigns. | Study mature campaign execution trees, cron-driven state machines, and lead scoring architectures. |

---

## 💼 Sales, CRM & Business Operations

Systems handling complex relational data, multi-tenancy, workflow automations, and transactional pipelines.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Twenty](https://github.com/twentyhq/twenty)** | `TypeScript`, `NestJS`, `React`, `PostgreSQL` | Modern, visual CRM with customizable relational data objects. | Benchmark for NestJS clean architecture, GraphQL code generation, and metadata-driven database schemas. |
| **[Cal.com](https://github.com/calcom/cal.com)** | `TypeScript`, `Next.js`, `Prisma`, `TRPC` | Open scheduling platform handling multi-calendar integrations and bookings. | Outstanding example of complex timezone arithmetic, third-party OAuth syncing, and tRPC type safety. |
| **[Chatwoot](https://github.com/chatwoot/chatwoot)** | `Ruby on Rails`, `Vue.js`, `Redis` | Omnichannel customer support platform with live chat, email, and social messaging. | Classic Rails service-object pattern, ActionCable WebSockets, and webhook ingestion engines. |
| **[Documenso](https://github.com/documenso/documenso)** | `TypeScript`, `Next.js`, `Prisma` | The open-source DocuSign alternative for cryptographic digital signatures. | Learn PDF manipulation, canvas coordinate tracking for sign fields, and audit-trail logging. |
| **[ERPNext](https://github.com/frappe/erpnext)** | `Python`, `Frappe`, `MariaDB`, `Redis` | Comprehensive ERP suite covering accounting, inventory, HR, sales, and manufacturing. | Learn how meta-data driven frameworks allow non-developers to configure custom doc types and business rules. |
| **[Formbricks](https://github.com/formbricks/formbricks)** | `TypeScript`, `Next.js`, `Tailwind` | Privacy-first experience management and in-app micro-survey suite. | Learn SDK injection into web apps, conditional survey logic, and webhook dispatchers. |

---

## 📊 Business Analysis, BI & Data Engineering

Systems for extracting, transforming, orchestrating, and visualizing enterprise datasets.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Apache Superset](https://github.com/apache/superset)** | `Python`, `Flask`, `React`, `SQLAlchemy` | Enterprise-level data exploration and interactive dashboard visualization platform. | Understand SQL dialect translation across 40+ DB engines, caching layers, and asynchronous query workers. |
| **[Metabase](https://github.com/metabase/metabase)** | `Clojure`, `React`, `TypeScript` | Intuitive BI tool that allows teams to ask questions and generate dashboards without SQL. | Learn visual query builders (GUI-to-SQL translation), embedded analytics sandboxing, and Clojure patterns. |
| **[Airbyte](https://github.com/airbytehq/airbyte)** | `Java`, `Python`, `Temporal`, `Docker` | The standard open-source ELT data integration and sync platform. | Master the connector protocol specification, job scheduling with Temporal, and isolated Dockerized workers. |
| **[Dagster](https://github.com/dagster-io/dagster)** | `Python`, `React`, `GraphQL` | Modern data orchestrator focusing on data assets, lineage, and local testability. | See how modern data pipelines treat data as software assets with built-in unit-testing capabilities. |
| **[DuckDB](https://github.com/duckdb/duckdb)** | `C++`, `Python` | In-process SQL OLAP database management system (the "SQLite for Analytics"). | Explore columnar vector execution, fast Parquet/CSV scanning, and zero-dependency embedded database engines. |
| **[Lightdash](https://github.com/lightdash/lightdash)** | `TypeScript`, `Node.js`, `React`, `dbt` | Open-source Looker alternative translating dbt metrics into self-serve BI charts. | Excellent reference for integrating with external semantic layers (dbt) and generating dynamic charts. |
| **[Evidence](https://github.com/evidence-dev/evidence)** | `JavaScript`, `Svelte`, `DuckDB-Wasm` | Business intelligence as code: create interactive reports using Markdown and SQL. | Learn how WebAssembly and in-browser SQL allow zero-latency interactive data dashboards. |

---

## 🎨 UI/UX Design Systems & Prototyping

Tools and component architectures powering world-class digital user interfaces.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Penpot](https://github.com/penpot/penpot)** | `Clojure`, `ClojureScript`, `SVG` | Open-source design and prototyping tool native to web standards (SVG, CSS Grid, Flexbox). | Understand vector geometry manipulation, collaborative canvas rendering, and real-time multiplayer crdt/sync. |
| **[Shadcn UI](https://github.com/shadcn-ui/ui)** | `TypeScript`, `Tailwind CSS`, `Radix UI` | Reusable accessible component collection distributed via CLI directly into your codebase. | The gold standard for modern component architecture: unstyled primitives combined with utility styling. |
| **[Storybook](https://github.com/storybookjs/storybook)** | `TypeScript`, `React`, `Vite`, `Webpack` | Frontend workshop for building, testing, and documenting UI components in isolation. | Learn modular compiler architecture, iframe sandboxing, and automated accessibility test runners. |
| **[Excalidraw](https://github.com/excalidraw/excalidraw)** | `TypeScript`, `React`, `HTML5 Canvas` | Virtual collaborative whiteboard for sketching hand-drawn like diagrams. | Master custom HTML5 Canvas rendering math, roughjs styling, and end-to-end encrypted collaboration. |
| **[tldraw](https://github.com/tldraw/tldraw)** | `TypeScript`, `React` | Infinite canvas SDK and digital whiteboarding toolkit. | Excellent example of finite state machines (FSM) driving complex user interactions and pointer gesture events. |
| **[Tremor](https://github.com/tremorlabs/tremor)** | `TypeScript`, `React`, `Tailwind` | Modular React components specifically built for fast dashboard and metrics visualization. | Study clean prop design, composable chart wrappers, and responsive data density. |

---

## 🖌️ Graphic Design, Creative Media & VFX

Industrial-grade creative suites pushing the boundaries of 2D/3D graphics, motion, and digital audio.

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Blender](https://github.com/blender/blender)** | `C`, `C++`, `Python` | Comprehensive 3D creation suite: modeling, rigging, animation, simulation, and rendering. | The world's premier open-source creative codebase: learn high-performance GPU shaders, scene graphs, and Python API bindings. |
| **[Krita](https://github.com/KDE/krita)** | `C++`, `Qt` | Digital painting and 2D animation studio designed for illustrators and concept artists. | Study high-performance pixel brush engines, layer blending mathematics, and tablet pressure event pipelines. |
| **[Inkscape](https://gitlab.com/inkscape/inkscape)** | `C++`, `GTK` | Professional vector graphics software implementing W3C SVG standards. | Master Bézier curve algorithms, path boolean operations, and SVG specification parsing. |
| **[Shotcut](https://github.com/mltframework/shotcut)** | `C++`, `Qt`, `MLT`, `FFmpeg` | Cross-platform, non-linear video editing suite. | Learn audio/video timeline sequencing, OpenGL hardware accelerated filtering, and FFmpeg transcoding wrappers. |
| **[Audacity](https://github.com/audacity/audacity)** | `C++`, `wxWidgets` | Multi-track audio recording and editing software. | Understand digital signal processing (DSP), waveform rendering, and non-destructive audio effect pipelines. |
| **[Glaxnimate](https://gitlab.com/glaxnimate/glaxnimate)** | `C++`, `Qt` | Vector graphics animation tool focused on exporting Lottie animations. | Learn vector keyframe interpolation, timeline tweening, and cross-platform export codecs. |

---

## ⚙️ Tech Development: Core Engineering

### Backend Frameworks & Distributed Systems

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[NestJS](https://github.com/nestjs/nest)** | `TypeScript`, `Express`, `Fastify` | Enterprise Node.js framework leveraging decorators and modular dependency injection. | Understand Angular-inspired architecture, dependency injection containers, and lifecycle interceptors. |
| **[FastAPI](https://github.com/fastapi/fastapi)** | `Python`, `Starlette`, `Pydantic` | Modern, high-performance web framework for building APIs with automatic OpenAPI docs. | Learn Python type annotations, ASGI concurrency, and automated schema generation. |
| **[Gin](https://github.com/gin-gonic/gin)** | `Go` | Ultra-fast HTTP web framework featuring a custom radix tree router. | Study minimalistic middleware chaining, low memory allocation strategies, and Go profiling. |
| **[Axum](https://github.com/tokio-rs/axum)** | `Rust`, `Tokio`, `Tower` | Ergonomic and modular web framework built on the Tokio async ecosystem. | Master Rust type-safe request extractors, zero-cost abstractions, and Tower middleware service trees. |

---

### Backend-as-a-Service (BaaS) & Realtime Stacks

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Supabase](https://github.com/supabase/supabase)** | `Elixir`, `TypeScript`, `Go`, `PostgreSQL` | Open-source Firebase alternative providing Auth, Storage, Edge Functions, and Realtime DB. | Master Postgres Row-Level Security (RLS), change-data-capture (CDC) with logical replication, and API orchestration. |
| **[Appwrite](https://github.com/appwrite/appwrite)** | `PHP`, `Node.js`, `Docker` | End-to-end backend server with Auth, Databases, Storage, and serverless Cloud Functions. | Study microservices coordinated via Docker Compose, event buses, and multi-language SDK generators. |
| **[PocketBase](https://github.com/pocketbase/pocketbase)** | `Go`, `SQLite`, `Svelte` | Embedded, single-binary backend with realtime subscriptions and admin dashboard. | *The best beginner codebase to read*: see how an entire production backend can fit cleanly inside Go and SQLite. |

---

### Databases, Search Engines & Vector Stores

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Meilisearch](https://github.com/meilisearch/meilisearch)** | `Rust` | Ultra-fast, typo-tolerant search engine with customizable ranking rules. | Master prefix search, LMDB disk storage, and inverted index construction in Rust. |
| **[Qdrant](https://github.com/qdrant/qdrant)** | `Rust` | Production vector database and search engine with extended payload filtering. | Learn HNSW (Hierarchical Navigable Small World) graphs, cosine similarity metrics, and payload indexes. |
| **[Milvus](https://github.com/milvus-io/milvus)** | `Go`, `C++` | Cloud-native vector database designed for billion-scale similarity search. | Study distributed storage/compute separation, message brokers, and horizontal sharding. |

---

### DevOps, Cloud Platforms & Self-Hosting PaaS

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Coolify](https://github.com/coollabsio/coolify)** | `PHP`, `Laravel`, `Livewire`, `Docker` | Self-hostable, all-in-one PaaS alternative to Heroku and Vercel. | Learn how web dashboards communicate with the Docker daemon via SSH, manage SSL with Traefik, and run buildpacks. |
| **[Portainer](https://github.com/portainer/portainer)** | `Go`, `Angular` | Lightweight service delivery platform for managing Docker and Kubernetes environments. | Understand Docker socket APIs, container clustering, and user role management. |
| **[Traefik](https://github.com/traefik/traefik)** | `Go` | Cloud-native edge router and reverse proxy with automatic SSL certificate management. | Study dynamic configuration discovery, automatic Let's Encrypt renewal, and load-balancing algorithms. |

---

### Developer Tooling, APIs & Testing

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** | `TypeScript`, `Vue.js` | Lightweight, open-source API development ecosystem (Postman alternative). | Learn browser-based HTTP/WebSocket/SSE/GraphQL clients, proxy interceptors, and PWA techniques. |
| **[Bruno](https://github.com/usebruno/bruno)** | `JavaScript`, `Electron`, `React` | Fast and Git-friendly open-source API client that saves requests as plaintext files. | See how to build offline-first desktop developer tools that integrate directly with version control. |
| **[Locust](https://github.com/locustio/locust)** | `Python` | Scalable user load testing tool with test scenarios defined in pure Python. | Learn coroutine-based load generation (gevent) and distributed master-worker test execution. |

---

### Identity, Authentication & Secrets Management

| Project | Primary Stack | Core Description | Why Junior Devs Should Study It |
| :--- | :--- | :--- | :--- |
| **[Authentik](https://github.com/goauthentik/authentik)** | `Python`, `Django`, `Go`, `Web Components` | Flexible, open-source identity provider implementing OAuth2, SAML, and LDAP. | Master SSO flow mechanics, stage/binding execution policies, and outpost gateway architectures. |
| **[Infisical](https://github.com/Infisical/infisical)** | `TypeScript`, `Node.js`, `Go`, `PostgreSQL` | End-to-end encrypted secrets management platform for environments and CI/CD. | Understand envelope encryption, cryptographic key management, and zero-knowledge architectures. |

---

## 🔍 Language Directory Index

Jump directly to projects written in your primary language:

- **TypeScript / JavaScript**: [Twenty](#-sales-crm--business-operations), [Cal.com](#-sales-crm--business-operations), [PostHog](#-marketing-growth--engagement-tech), [Novu](#-marketing-growth--engagement-tech), [Dub.co](#-marketing-growth--engagement-tech), [Shadcn UI](#-uiux-design-systems--prototyping), [NestJS](#backend-frameworks--distributed-systems), [Hoppscotch](#developer-tooling-apis--testing).
- **Python**: [FastAPI](#backend-frameworks--distributed-systems), [LangChain](#-artificial-intelligence--llm-systems), [LlamaIndex](#-artificial-intelligence--llm-systems), [Apache Superset](#-business-analysis-bi--data-engineering), [Dagster](#-business-analysis-bi--data-engineering), [Locust](#developer-tooling-apis--testing).
- **Go**: [PocketBase](#backend-as-a-service-baas--realtime-stacks), [Ollama](#-artificial-intelligence--llm-systems), [Listmonk](#-marketing-growth--engagement-tech), [Gin](#backend-frameworks--distributed-systems), [Traefik](#devops-cloud-platforms--self-hosting-paas).
- **Rust**: [Meilisearch](#databases-search-engines--vector-stores), [Qdrant](#databases-search-engines--vector-stores), [Axum](#backend-frameworks--distributed-systems).
- **C++**: [DuckDB](#-business-analysis-bi--data-engineering), [Blender](#️-graphic-design-creative-media--vfx), [Krita](#️-graphic-design-creative-media--vfx), [Audacity](#️-graphic-design-creative-media--vfx).
- **PHP**: [Coolify](#devops-cloud-platforms--self-hosting-paas), [Appwrite](#backend-as-a-service-baas--realtime-stacks), [Mautic](#-marketing-growth--engagement-tech).
- **Elixir**: [Plausible Analytics](#-marketing-growth--engagement-tech), [Supabase Realtime](#backend-as-a-service-baas--realtime-stacks).

---

## 💡 How to Contribute

We welcome additions of exceptional open-source systems that offer high educational and architectural value!

1. Check our [Curation Guidelines in CONTRIBUTING.md](./CONTRIBUTING.md).
2. Follow our [Code of Conduct](./CODE_OF_CONDUCT.md).
3. Submit a Pull Request following the established table structure.

---

## 📄 License

This repository is licensed under the [MIT License](./LICENSE). Feel free to share this with fellow developers, bootcamps, university cohorts, and engineering teams!
