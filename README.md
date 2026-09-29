<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,18&height=220&section=header&text=Vinay%20Kumar%20Ksheera%20Sagar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Staff%20Software%20Architect%20%7C%20Enterprise%20AI%20Data%20Governance%20%26%20Zero-Trust%20Infrastructure&descAlignY=60&descAlign=50" width="100%" alt="Header" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/vinaykumar-ksheerasagar-92270024"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sagarv.kumar48@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/sagarv48"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## 🎯 Architectural Philosophy & Engineering Convictions

I architect, build, and maintain production-grade open-source systems specializing in **Enterprise AI Data Governance**, **Zero-Trust Retrieval Infrastructure**, **Deterministic Action Contracts**, and **Time-Travel Debugging for Autonomous Agents**.

- **Database Consolidation Over Vector Sprawl**: Solving enterprise RAG directly on battle-tested relational engines (PostgreSQL with `pgvector` HNSW + BM25 full-text search) instead of introducing costly, un-audited secondary vector databases.
- **Zero-Trust Cryptographic Tripwires**: Watermarking retrieved enterprise context with 4-ary zero-width HMAC tokens and scanning streaming egress at wire speed (<0.8ms) to kill prompt-injection exfiltration before data leaves the network.
- **Deterministic Action Contracts for Autonomous AI**: Probabilistic models should draft plans; deterministic, out-of-band policy engines with HMAC-SHA256 signatures must govern and execute them.
- **Zero-Trust Enterprise Ingestion**: Guaranteeing that enterprise data pipelines automatically scrub secrets, API keys, and PII before chunks ever enter an embedding or vector index.
- **Interactive Time-Travel Debugging for Agents**: Replacing primitive "restart-from-scratch" batch debugging with microsecond state checkpoints, anti-oscillation watchdogs, and live memory rewind.

---

## 🌟 Featured Flagship Ecosystem

A cohesive, open-source infrastructure stack designed for enterprise-grade generative AI, retrieval, data security, agent governance, and time-travel debugging.

### 1. [Knowledge Fabric](https://github.com/sagarv48/knowledge-fabric)
> **Vendor-neutral, governance-first hybrid evidence retrieval for AI systems.**

[![CI](https://img.shields.io/badge/CI-passing-brightgreen.svg)](https://github.com/sagarv48/knowledge-fabric/actions)
[![Release](https://img.shields.io/badge/Release-v0.1.1-blue.svg)](https://github.com/sagarv48/knowledge-fabric/releases)
[![Docker](https://img.shields.io/badge/GHCR-Multi--Arch-2496ED?logo=docker&logoColor=white)](https://ghcr.io/sagarv48/knowledge-fabric)
[![Helm OCI](https://img.shields.io/badge/Helm%20OCI-v0.1.1-0F1689?logo=helm&logoColor=white)](https://ghcr.io/sagarv48/charts/knowledge-fabric)
[![MCP Native](https://img.shields.io/badge/MCP-Native%20Server-purple.svg)](https://modelcontextprotocol.io)

- **PostgreSQL-Native Hybrid Retrieval**: Combines `pgvector` HNSW indexing with native PostgreSQL full-text search (`tsvector`) via Reciprocal Rank Fusion (RRF, k=60).
- **Dual-Mode Multi-Tenancy**: Application-level isolation by default, with opt-in **PostgreSQL Row-Level Security (RLS)** for HIPAA and SOC 2 compliance.
- **Model Context Protocol (FastMCP)**: Native MCP tools (`retrieve_evidence`, `get_document`, `explain_retrieval`) enabling plug-and-play memory for Claude Desktop, Cursor, and enterprise agent workflows.
- **Turnkey Production Ops**: Multi-arch Docker containers, official Helm chart with external secret injection, and sub-10ms query latency.

---

### 2. [Canary Fabric (canary-fabric)](https://github.com/sagarv48/canary-fabric)
> **Invisible cryptographic tripwires and sub-millisecond data-leak circuit breakers for RAG & AI agents.**

[![CI](https://img.shields.io/badge/CI-passing-brightgreen.svg)](https://github.com/sagarv48/canary-fabric/actions)
[![Release](https://img.shields.io/badge/Release-v0.1.0-blue.svg)](https://github.com/sagarv48/canary-fabric/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/sagarv48/canary-fabric/blob/main/LICENSE)
[![MCP Native](https://img.shields.io/badge/MCP-Native%20Security-purple.svg)](https://modelcontextprotocol.io)

- **4-ary Zero-Width Steganography**: Injects 64-bit HMAC-derived canary tokens (`\u200B`, `\u200C`, `\u200D`, `\uFEFF`) invisibly into retrieved chunks, 100% invisible to humans and preserved in LLM context.
- **Sub-Millisecond (<0.8ms / 3.12µs) Stream Circuit Breaker**: Zero-buffering sliding ring buffer scanning outbound SSE streams and tool parameters, instantly severing the socket upon exfiltration attempt.
- **Cryptographic Leak Certificates**: Issues tamper-evident, HMAC-signed forensic certificates binding the leak to the source chunk, tenant ID, and prompt hash.
- **Universal Adapters**: Native integration with Knowledge Fabric, Intent Fabric, FastMCP `@canary_gate`, and standalone streaming reverse proxy for OpenAI / Anthropic / LiteLLM.

---

### 3. [Intent Fabric](https://github.com/sagarv48/intent-fabric)
> **Policy-governed autonomous agent planning and non-repudiation execution framework.**

[![CI](https://img.shields.io/badge/CI-passing-brightgreen.svg)](https://github.com/sagarv48/intent-fabric/actions)
[![Release](https://img.shields.io/badge/Release-v0.1.1-blue.svg)](https://github.com/sagarv48/intent-fabric/releases)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![MCP Native](https://img.shields.io/badge/MCP-Native%20Server-purple.svg)](https://modelcontextprotocol.io)

- **Deterministic Action Contracts**: Decouples probabilistic LLM reasoning from API execution by enforcing strict typed step definitions.
- **Out-of-Band Policy Engine**: Hot-reloadable YAML policy rules that independently inspect and gate every proposed agent mutation.
- **Cryptographic HMAC-SHA256 Approvals**: Human-in-the-loop sign-offs produce tamper-evident cryptographic approval tokens, providing end-to-end non-repudiation.
- **Indirect Prompt Injection Defense**: Sandboxes untrusted retrieved data within strict `<retrieved_evidence>` XML boundaries with regex-enforced identifiers.

---

### 4. [Knowledge Fabric Enterprise Adapters](https://github.com/sagarv48/knowledge-fabric-enterprise-adapters)
> **Enterprise SaaS connectors, automated DLP secret scrubbing, and cryptographic write gates.**

[![CI](https://img.shields.io/badge/CI-passing-brightgreen.svg)](https://github.com/sagarv48/knowledge-fabric-enterprise-adapters/actions)
[![Release](https://img.shields.io/badge/Release-v0.1.1-blue.svg)](https://github.com/sagarv48/knowledge-fabric-enterprise-adapters/releases)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](Dockerfile)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Manifests-326CE5?logo=kubernetes&logoColor=white)](deploy/kubernetes)

- **Automated DLP Secret Scrubbing**: Real-time `SecretScrubber` detecting AWS keys, private RSA keys, JWT tokens, Bearer tokens, and email PII prior to chunk indexing.
- **Bi-Directional SaaS Connectors**: Pre-built, production-tested adapters for Jira, Confluence, Slack, GitHub, and PostgreSQL.
- **Cryptographic Write Gates**: Enforces HMAC-SHA256 signature verification before any SaaS adapter can mutate production systems (e.g., ticket creation or comment updates).

---

### 5. [Unloop](https://github.com/sagarv48/unloop)
> **The time-travel debugger for AI agents — pause, rewind, and mutate memory in-flight.**

[![CI](https://github.com/sagarv48/unloop/actions/workflows/ci.yml/badge.svg)](https://github.com/sagarv48/unloop/actions)
[![Release](https://img.shields.io/badge/Release-v0.1.0-blue.svg)](https://github.com/sagarv48/unloop/releases)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/sagarv48/unloop/blob/main/LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-unloop-3776AB?logo=pypi&logoColor=white)](https://pypi.org/project/unloop/)

- **Interactive Time-Travel Debugging**: Step backward through cognitive turns and inspect execution history like a video player instead of restarting multi-turn agent runs from scratch.
- **Anti-Oscillation Watchdog**: Automated sliding-window loop detection catching critique spirals, identical tool calls, and state cycles before burning token budgets.
- **In-Place State Mutation & DAG Branching**: Mutate corrupted agent memory in-flight and fork exploratory branches without restarting.
- **High-Performance SQLite WAL Cassettes**: Microsecond commit overhead (<2ms) for portable, zero-cost deterministic replay in CI/CD pipelines.

---

## 🛠️ Systems & Technical Competencies

| Domain | Core Technologies & Architectural Patterns |
| :--- | :--- |
| **Databases & Vector Storage** | **PostgreSQL** (HNSW, IVFFlat, RLS, WAL, Partitioning), `pgvector`, Redis, **SQLite WAL**, ACID Transactions, Connection Pooling (PgBouncer) |
| **AI Infrastructure & Security** | **Canary Fabric (canary-fabric - Cryptographic Tripwires)**, **unloop (Agent Time-Travel Debugger)**, **Model Context Protocol (MCP)**, FastMCP, Hybrid Retrieval (BM25 + Dense Vectors), Reciprocal Rank Fusion (RRF), Cross-Encoder Reranking |
| **Agent Safety & Governance** | Cryptographic Non-Repudiation (HMAC-SHA256), Deterministic Action Contracts, Indirect Prompt Injection Defense, Anti-Oscillation Watchdogs, STRIDE Threat Modeling |
| **Languages & Runtimes** | **Python** (psycopg3, FastAPI, FastMCP, Textual, Click, PyYAML, Pytest), **Java / Kotlin**, **Go**, Shell Scripting (Bash / PowerShell) |
| **Cloud & Distributed Ops** | **Kubernetes**, **Helm (OCI)**, **Docker** (Multi-arch / Non-root), GitHub Actions CI/CD, Azure DevOps, Linux Systems Internals |

---

## 📈 GitHub Statistics & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sagarv48&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sagarv48&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

## 💬 Connect & Inquiries

I am always interested in discussing high-concurrency systems architecture, enterprise AI data governance, and open-source infrastructure:

- **LinkedIn**: [linkedin.com/in/vinaykumar-ksheerasagar-92270024](https://www.linkedin.com/in/vinaykumar-ksheerasagar-92270024/)
- **Email**: [sagarv.kumar48@gmail.com](mailto:sagarv.kumar48@gmail.com)
- **GitHub**: [@sagarv48](https://github.com/sagarv48)