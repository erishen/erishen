<div align="right">
  <a href="README.zh-CN.md">🇨🇳 中文</a>
</div>

# Hi, I'm Lei Sun

AI engineering / platform engineering / senior full-stack engineer focused on landing AI in real engineering workflows.

Previously built customer-facing FinTech systems at PayPal with React, Next.js, and Node.js. Recent focus areas include AI-assisted engineering workflows, system security hardening, and large-scale framework upgrades.

I care less about one-off AI demos and more about systems that are runnable, reproducible, testable, and explainable.

🔍 Open to opportunities

---

## Current Focus

- Landing AI in real software systems (AI-assisted engineering workflows)
- Agent workflow design: planning / execution / independent evaluation / evidence-driven iteration
- Quality & security engineering: reproducible workflows, deterministic checks, and security hardening
- Developer tooling: CLI workflows, prompt / memory systems, and MCP-based code context
- Full-stack systems with React, Next.js, Node.js, TypeScript, Python, FastAPI, Redis, and APIs

---

![](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)
![](https://img.shields.io/badge/Rust-000000?logo=rust\&logoColor=white)
![](https://img.shields.io/badge/C++-00599C?logo=cplusplus\&logoColor=white)
![](https://img.shields.io/badge/React-61DAFB?logo=react\&logoColor=black)
![](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs\&logoColor=white)
![](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs\&logoColor=white)
![](https://img.shields.io/badge/FastAPI-009688?logo=fastapi\&logoColor=white)
![](https://img.shields.io/badge/Spring-6DB33F?logo=spring\&logoColor=white)
![](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright\&logoColor=white)
![](https://img.shields.io/badge/Redis-DC382D?logo=redis\&logoColor=white)
![](https://img.shields.io/badge/LLM-Agentic%20Workflow-FF6F00?logo=openai\&logoColor=white)

📍 Shanghai, China

🌐 Blog: https://erishen.cn

---

## Featured Projects

### [resolve-studio](https://github.com/erishen/resolve-studio)

A full AI Agent runtime and engineering workbench on the Cordis DI container — LLM backend / tools / Agent loop / approvals / skills / frontend are all plugins; switching models or adding tools is config-only. Built-in PSE (Planner/Specialist/Evaluator) three-role verification loop and harness orchestration, integrating Makefile scripts, MCP tools and OS-level sandbox (macOS Seatbelt / Linux bwrap). Part of the resolve-* toolchain: resolve-harness (Python/LangGraph skeleton with Fast-path Plugin Runtime — zero model calls for deterministic problems), resolve-tui (Rust CLI/TUI coding Agent), resolve-skills (Agent Skills open standard, consumable by Claude Code / Codex).

### [rag-task-service](https://github.com/erishen/rag-task-service)

An async RAG document pipeline in Rust / axum: upload, chunking, embedding, vector write and hybrid retrieval (BM25 + vector) in one service; a seven-layer architecture decouples storage (SQLite exact dedup + perceptual hash) through retrieval, LLM re-ranking to generation. Local-first and privacy-oriented, built on classic algorithms + heuristics rather than heavy ML dependencies.

### [datapulse](https://github.com/erishen/datapulse)

An AI BI workbench: connect SQLite / CSV / PostgreSQL / MySQL, ask in natural language, LLM writes read-only SQL and renders ECharts dashboards. A deterministic Text2SQL pipeline (schema constraints + read-only execution + result validation) runs in parallel with a ReAct dual-path (tool calls + reflection/retry), balancing control and exploration; pre-execution permission / scope checks for self-service BI.

### [spring-rbac](https://github.com/erishen/spring-rbac)

Evolved from a single RBAC auth module into a small microservice system: Eureka discovery + Config + Gateway (PEP + hand-rolled zero-dependency JWT) + auth / rbac services, extended with CRM, audit and a BFF layer into a reusable enterprise backend skeleton.

### [firefly-studio](https://github.com/erishen/firefly-studio)

A debuggable C++ Electron digital human workbench — porting the firefly 3D virtual human (React + three.js / R3F) to Electron, with the main process loading C++ native modules via node-addon-api: audio energy / VAD / microphone capture / ASR / TTS wrappers. Integrates Whisper.cpp local offline speech recognition, Piper local speech synthesis, RNNoise noise suppression, and music playback; supports setting breakpoints and debugging C++ directly in VSCode (Node debug main process + lldb attach).

---

## Writing

I write about AI engineering, agent frameworks, and full-stack practice on my blog: **[erishen.cn](https://erishen.cn)**.

- [resolve-studio: Cordis Plugin-Based Agent Runtime](https://erishen.cn/resolve_studio-en/) — Turning LLM backend, tools, and approval flows into config via DI container.
- [rag-task-service: A Seven-Layer Design for a Rust RAG Service](https://erishen.cn/rag_task_service-en/) — An async RAG document pipeline from SQLite to LLM re-ranking.
- [datapulse: Deterministic Text2SQL Pipeline + ReAct Dual-Path](https://erishen.cn/datapulse-en/) — Architecture breakdown of the AI BI workbench.
- [spring-rbac: From RBAC Auth to a Small Microservice System](https://erishen.cn/spring_rbac-en/) — Spring Cloud + zero-dependency JWT + CRM + audit + BFF.

---

## Engineering Themes

**AI Engineering**  
Agent workflows, tool calling, MCP, RAG, evaluation loops, prompt systems, memory systems, SSE execution logs.

**Platform Engineering**  
Docker, Makefile, multi-stack environments, reproducible workflows, local tooling, developer productivity.

**Full-Stack Systems**  
React, Next.js, TypeScript, Node.js, Python, FastAPI, Redis, GraphQL, REST APIs, Playwright.

**FinTech**  
Customer-facing systems, identity verification, compliance workflows, secure full-stack development.

---

## Background

- **PayPal** — Senior Full-Stack Engineer (2024 – 2026)  
  Customer-facing FinTech systems, identity verification, AI-assisted engineering workflows, full-stack development with React/Next.js/Node.js
- **Trip.com Group** — Senior Frontend Engineer (2017 – 2024)  
  International content platforms, Node.js SSR, SEO, multilingual content, frontend engineering evolution
- **Earlier** — Software Engineer → Technical Manager (2005 – 2017)  
  Enterprise systems, mobile apps, embedded web, cross-team delivery

---

## Links

- Website: https://erishen.cn
- GitHub: https://github.com/erishen
- Email: erishen@qq.com
