# Hi, I'm Benjamin

**IT Administrator & Systems Engineer** building tooling for enterprise-scale problems -- migrations, monitoring, compliance, and the kind of automation that keeps complex infrastructure running.

## What I do

I work at the intersection of legacy enterprise systems and modern tooling. By day I manage ECM platforms, high-availability storage, and ERP archiving integrations handling hundreds of millions of documents. I build the tooling that makes these systems manageable -- automating migrations, validating compliance, and keeping complex multi-domain environments running.

Outside of work I explore Rust, performance optimization, and AI-assisted development workflows.

## Recent public work

- **[claude-config-broker](https://github.com/nemekath/claude-config-broker)** -- PowerShell daemon that prevents `.claude.json` corruption from concurrent Claude Code sessions. Named Mutex locking + JSON deep-merge + atomic writes.
- **[TSSN](https://github.com/nemekath/TSSN)** -- TypeScript-Style Schema Notation. A compact format for representing database schemas in LLM contexts, achieving ~40-60% token reduction vs JSON Schema.



## other work

Things I've been building but haven't open-sourced yet:

-  **Optimizations for LLAMA.CPP**  for AMD based RDNA3 GPUs

- A **C# migration pipeline** (Clean Architecture, Producer/Consumer pattern, COM Interop with STA threading) processing thousands of documents per hour with checkpoint-based resume
- A **reconciliation and monitoring system** with Bayesian confidence scoring, bidirectional matching across SQL Server and file systems, and a live dashboard -- backed by 30+ Architecture Decision Records
- A **documentation crawler** that parses proprietary TOC formats and exports to LLM/RAG-ready chunks


## Tech stack

### Daily drivers

![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### Building with

![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### Focus areas

Systems-level performance -- PKI & certificate infrastructure -- GDPR-compliant analytics -- AI-assisted development workflows -- COM Interop & legacy system integration

## Approach

I prefer understanding the underlying principles over applying quick fixes. Most of my projects start with a real operational problem -- a race condition corrupting config files, a matching algorithm producing false positives from encoding bugs, a migration that needs verification at scale -- and grow into proper tooling from there.

I document obsessively. My larger projects carry 30+ ADRs with dependency chains, supersession tracking, and hex-verified encoding tables. If I'm solving a problem, I want the solution to outlast the context I built it in.

---

*Based in Germany. Currently deep-diving into RAG Pipelines and AI MCP development. Occasional tabletop RPG player when not debugging production systems.*
