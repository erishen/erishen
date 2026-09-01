<div align="right">
  <a href="README.md">🇺🇸 English</a>
</div>

# 你好，我是孙磊

AI 工程化 / 平台工程 / 资深全栈工程师，关注如何把 AI 落地到真实工程流程。

曾在 PayPal 做金融科技工程，用 React / Next.js / Node.js 构建面向客户的系统。近期关注 AI 辅助工程化、系统安全加固和大版本框架升级。

我关心的是可运行、可复现、可测试、可解释的工程系统，而非一次性 AI Demo。

🔍 正在寻找新机会

---

## 当前关注方向

- AI 落地到真实软件系统（AI 辅助工程化工作流）
- Agent Workflow 设计：规划 / 执行 / 独立评估 / 证据驱动迭代
- 质量与安全工程：可复现工作流、确定性校验、安全加固
- 开发者工具：CLI 工作流、Prompt / Memory 系统、MCP 代码上下文
- 全栈系统：React、Next.js、Node.js、TypeScript、Python、FastAPI、Redis

---

![](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)
![](https://img.shields.io/badge/Rust-000000?logo=rust\&logoColor=white)
![](https://img.shields.io/badge/React-61DAFB?logo=react\&logoColor=black)
![](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs\&logoColor=white)
![](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs\&logoColor=white)
![](https://img.shields.io/badge/FastAPI-009688?logo=fastapi\&logoColor=white)
![](https://img.shields.io/badge/Spring-6DB33F?logo=spring\&logoColor=white)
![](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright\&logoColor=white)
![](https://img.shields.io/badge/Redis-DC382D?logo=redis\&logoColor=white)
![](https://img.shields.io/badge/LLM-Agentic%20Workflow-FF6F00?logo=openai\&logoColor=white)

📍 上海

🌐 技术博客: https://erishen.cn

---

## 精选项目

### [resolve-studio](https://github.com/erishen/resolve-studio)

基于 Cordis 依赖注入容器的完整版 AI Agent 运行时与工程化工作台——LLM 后端/工具/Agent 循环/审批/技能/前端全为插件，切换模型或加工具仅改配置。内置 PSE（Planner/Specialist/Evaluator）三角色验证闭环与 harness 编排能力，整合 Makefile 脚本、MCP 工具与 OS 级沙箱（macOS Seatbelt / Linux bwrap）。resolve-* 工具链成员：resolve-harness（Python/LangGraph 骨架，独创 Fast-path Plugin Runtime——确定性问题零模型调用）、resolve-tui（Rust CLI/TUI 编码 Agent）、resolve-skills（Agent Skills 开放标准，可被 Claude Code / Codex 多端消费）。

### [rag-task-service](https://github.com/erishen/rag-task-service)

基于 Rust / axum 的异步 RAG 文档管线：上传、分块、Embedding、向量写入与混合检索（BM25 + 向量）一体化；七层架构从存储（SQLite 精确去重 + 感知哈希）到检索、LLM 重排、生成逐层解耦。本地优先、隐私导向，纯经典算法 + 启发式而非重型 ML 依赖。

### [datapulse](https://github.com/erishen/datapulse)

AI BI 工作台：连接 SQLite / CSV / PostgreSQL / MySQL，自然语言提问，LLM 写只读 SQL 并渲染 ECharts 看板。确定性 Text2SQL 管线（schema 约束 + 只读执行 + 结果校验）与 ReAct 双路径（工具调用 + 反思重试）并行，兼顾可控性与探索；SQL 执行前做权限 / 作用域校验，面向自助 BI。

### [spring-rbac](https://github.com/erishen/spring-rbac)

从单一 RBAC 鉴权模块演化为小型微服务系统：Eureka 服务发现 + Config + Gateway（PEP + 自研零依赖 JWT）+ auth / rbac 服务，并扩展出 CRM、审计与 BFF 层，形成可复用的企业级后端骨架。

### [ai-chat](https://github.com/erishen/ai-chat)

基于 Next.js 15 的现代 AI 聊天应用，支持流式响应、RAG 文档检索、Markdown 渲染、主题切换和实用对话工作流。

Demo: https://chat.erishen.cn

---

## 技术博客

我在博客 **[erishen.cn](https://erishen.cn)** 上写 AI 工程化、Agent 框架与全栈实践。

- [resolve-studio：Cordis 插件化 Agent 运行时](https://erishen.cn/resolve_studio/) — 用 DI 容器把 LLM 后端、工具、审批流全部变成配置。
- [rag-task-service：一个 Rust RAG 服务的七层设计](https://erishen.cn/rag_task_service/) — 从 SQLite 到 LLM 重排的异步 RAG 文档管线架构。
- [datapulse：Text2SQL 确定性管线 + ReAct 双路径](https://erishen.cn/datapulse/) — AI BI 工作台的架构解析。
- [spring-rbac：从 RBAC 鉴权长成的小微服务系统](https://erishen.cn/spring_rbac/) — Spring Cloud + 零依赖 JWT + CRM + 审计 + BFF。

---

## 工程方向

**AI 工程**  
Agent Workflow、Tool Calling、MCP、RAG、评估循环、Prompt/Memory系统、SSE 执行日志

**平台工程**  
Docker、Makefile、多技术栈环境、可复现工作流、本地工具、开发者效率

**全栈系统**  
React、Next.js、TypeScript、Node.js、Python、FastAPI、Redis、GraphQL、REST API、Playwright

**金融科技**  
面向客户的系统、身份验证、合规工作流、安全全栈开发

---

## 工作经历

- **PayPal** — 资深全栈工程师（2024 – 2026）  
  面向客户的金融科技系统、身份验证、AI 辅助工程化、React/Next.js/Node.js 全栈开发
- **携程 / Trip.com Group** — 资深前端工程师（2017 – 2024）  
  国际内容平台、Node.js SSR、SEO、多语言内容、前端工程演进
- **早期经历** — 软件工程师 → 技术经理（2005 – 2017）  
  企业系统、移动应用、嵌入式 Web、跨团队交付

---

## 联系方式

- 网站: https://erishen.cn
- GitHub: https://github.com/erishen
- 邮箱: erishen@qq.com
