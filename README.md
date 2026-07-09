# Aiden | Full-stack AI Engineer

I build evidence-first RAG and AI Agent applications with **Next.js**, **FastAPI**, **PostgreSQL/pgvector**, and evaluation-ready engineering workflows.

My focus is turning LLM capabilities into usable full-stack systems: document ingestion, retrieval, citations, guarded synthesis, tool traces, evaluation, and clean developer experience.

中文简介：我关注全栈 AI 应用工程，尤其是 RAG、AI Agent、文档智能、证据引用、工具调用追踪和可复现实验评估。

## Featured Projects

| Project | What it demonstrates | Stack | Engineering highlights |
| --- | --- | --- | --- |
| [BidGuard AI](https://github.com/AZ123IT/BidGuard-AI) | Evidence-first tender and contract review RAG agent | Next.js, FastAPI, SQLAlchemy, SQLite, PostgreSQL, pgvector | PDF/DOCX/TXT ingestion, hybrid retrieval, guarded LLM synthesis, risk rules, cross-document diff, agent trace, eval runner, provider smoke, CI |
| [ResearchPilot](https://github.com/AZ123IT/ResearchPilot) | AI research agent workflow for literature discovery and evidence tracking | Next.js, FastAPI, LangGraph, MCP-style tools, DeepSeek, arXiv | Multi-step research workflow, source validation, citation generation, tool-call audit, reusable memory |
| [AI Document Chat](https://github.com/AZ123IT/ai-document-chat) | RAG document Q&A application | Next.js, Supabase, pgvector, DeepSeek, TypeScript | PDF/TXT upload, chunking, retrieval orchestration, evidence display, persistent chat history |
| [DDL Helper Mini Program](https://github.com/AZ123IT/ddl-helper-miniprogram) | WeChat mini program for turning group notices into deadline tasks | WeChat Mini Program, CloudBase, cloud functions, cloud database | Notice parsing, editable task list, shareable deadline cards, OpenID-based data isolation |

## What I Build

- Evidence-first RAG applications where answers cite retrieved source chunks or clearly refuse when evidence is insufficient.
- AI Agent workflows with explicit tool calls, intermediate outputs, latency, and traceability.
- Document workflows for upload, parsing, chunking, retrieval, review, comparison, and report generation.
- Portfolio-grade full-stack systems with local setup, tests, CI, docs, demo data, and repeatable verification.

## Core Stack

| Area | Tools |
| --- | --- |
| Frontend | Next.js, React, TypeScript, Tailwind CSS |
| Backend | FastAPI, SQLAlchemy, Pydantic, REST APIs |
| Data | PostgreSQL, pgvector, SQLite, Supabase |
| AI systems | RAG, embeddings, OpenAI-compatible providers, guarded LLM synthesis, tool-calling agents |
| Engineering | pytest, Ruff, GitHub Actions, Docker, evaluation scripts, smoke tests |
| Also used | Vue 3, Vite, WeChat Mini Program, CloudBase, Redis basics |

## Engineering Principles

- **Evidence first:** AI answers should be grounded in retrieved documents, with visible citations and fallback behavior.
- **Observable agents:** Tool calls, retrieval method, scores, latency, and outputs should be inspectable.
- **Evaluation ready:** RAG systems need repeatable eval cases, not only manual demos.
- **Practical delivery:** Frontend, backend, database, docs, CI, and local setup should work together.

## Current Focus

- Hardening RAG systems with pgvector, real embedding providers, and better retrieval evaluation.
- Improving evidence UX so users can trace answers back to pages, chunks, and source snippets.
- Building AI Agent demos that are small enough to understand but complete enough to interview well.

## Contact

- GitHub: [AZ123IT](https://github.com/AZ123IT)
- Email: 3780151175@qq.com
