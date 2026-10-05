# Aiden | 全栈 AI 应用开发

**简体中文** | [English](https://github.com/AZ123IT/AZ123IT/blob/main/README.en.md)

我使用 **Next.js、FastAPI 和 PostgreSQL/pgvector** 构建证据优先的 RAG 与 AI Agent 应用，并通过可重复的测试和评估验证实现。

我关注从模型能力到完整应用的工程过程：文档解析、检索、来源引用、受证据约束的回答生成、工具调用追踪，以及前后端交互与本地运行体验。

## 精选项目

| 项目 | 应用场景 | 技术栈 | 工程实现 |
| --- | --- | --- | --- |
| [BidGuard AI](https://github.com/AZ123IT/BidGuard-AI) | 证据优先的招投标与合同文档审查 | Next.js、FastAPI、SQLAlchemy、SQLite、PostgreSQL、pgvector | PDF/DOCX/TXT 解析、混合检索、证据门控、风险规则、文档对比、调用追踪、评估、Provider smoke 与 CI |
| [ResearchPilot](https://github.com/AZ123IT/ResearchPilot) | 文献发现与证据追踪的科研辅助工作流 | Next.js、FastAPI、LangGraph、MCP-style tools、DeepSeek、arXiv | 多步骤检索与整理、来源检查、引用生成、工具调用审计与记忆存储 |
| [AI Document Chat](https://github.com/AZ123IT/ai-document-chat) | RAG 文档问答 | Next.js、Supabase、pgvector、DeepSeek、TypeScript | PDF/TXT 上传、分块、检索编排、证据展示与聊天记录持久化 |
| [DDL 小助手](https://github.com/AZ123IT/ddl-helper-miniprogram) | 将微信群通知整理成截止日期任务 | 微信小程序、CloudBase、云函数、云数据库 | 通知解析、可编辑任务清单、截止日期分享卡与基于 OpenID 的数据隔离 |

## 开发方向

- **证据优先的 RAG 应用：** 展示检索来源，并为证据不足的情况设置明确的拒答或回退路径。
- **可追踪的 Agent 工作流：** 保留工具调用、中间输出与耗时，便于解释和定位问题。
- **文档处理应用：** 串联上传、解析、分块、检索、审查、比较与报告生成。
- **可复现的全栈项目：** 提供本地启动步骤、测试、文档、演示数据与验证命令。

## 主要技术栈

| 方向 | 技术与工具 |
| --- | --- |
| 前端 | Next.js、React、TypeScript、Tailwind CSS |
| 后端 | FastAPI、SQLAlchemy、Pydantic、REST API |
| 数据存储 | PostgreSQL、pgvector、SQLite、Supabase |
| AI 应用 | RAG、Embedding、OpenAI-compatible Provider、受证据约束的生成、工具调用工作流 |
| 工程验证 | pytest、Ruff、GitHub Actions、Docker、评估脚本、smoke 测试 |
| 其他项目经验 | Vue 3、Vite、微信小程序、CloudBase、Redis 基础 |

## 工程原则

- **结果有依据：** 回答应能关联到检索文档，来源和回退行为应当可查看。
- **过程可检查：** 展示工具调用、检索方法、分数、耗时与输出。
- **改进靠评估：** 使用可重复的案例与实验，不只依赖一次手工演示。
- **交付可运行：** 让前端、后端、数据库、文档与验证流程相互衔接。

## 当前关注

- 结合 pgvector、真实 Embedding Provider 与检索评估，改进 RAG 系统。
- 改善证据查看体验，让用户能够从回答回到页码、文本块和原文。
- 构建范围清楚、可以运行、能够解释设计取舍与已知局限的 AI Agent 项目。

## 联系方式

- GitHub：[AZ123IT](https://github.com/AZ123IT)
- 邮箱：3780151175@qq.com
