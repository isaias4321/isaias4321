# Hi 👋, I'm Isaías Maia Frazão

### AI Engineer · Generative AI · LLM Agents

I build applied AI systems — from prototype to product — using LLMs,
tool-using agents, RAG, and automation.

[![Email](https://img.shields.io/badge/Email-isaiasmaiaf%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:isaiasmaiaf@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Isa%C3%ADas%20Maia%20Fraz%C3%A3o-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isa%C3%ADas-maia-fraz%C3%A3o-b3a083280/)
[![GitHub](https://img.shields.io/badge/GitHub-isaias4321-181717?style=flat&logo=github&logoColor=white)](https://github.com/isaias4321)

---

### 👨‍💻 About me

- 🚀 Focused on building AI applications with **LLMs**, **tool-using agents**, **RAG**, and **automation**
- 🌱 Background in IT Infrastructure & Networking, now specialized in Generative AI
- 🛠️ I like projects with **real proof that they work** — every repo below has a video demo/screenshot, not just code
- 📍 São Luís, Maranhão, Brazil

---

### 🚀 Featured projects

#### 🗄️ [langchain-sql-agent](https://github.com/isaias4321/langchain-sql-agent)
An agent built with **LangChain.js** that answers natural-language
questions about a database, exploring the schema dynamically before
generating SQL — instead of a fixed chain with a hardcoded schema in the prompt.
`TypeScript` `LangChain.js` `SQLite` `Node.js`
- Tools (`list_tables`, `get_schema`, `execute_readonly_query`) chosen by the agent itself
- Security layer (`sqlGuard`) that blocks any write SQL, with automated tests

#### 💬 [rag-chat-docs](https://github.com/isaias4321/rag-chat-docs)
A **RAG** (Retrieval-Augmented Generation) system built from scratch, with
no orchestration framework — PDF upload, chunking, embeddings, vector
search, and source-cited answers.
`Python` `FastAPI` `ChromaDB`
- Answers only based on the uploaded document, and clearly says when the answer isn't there (no hallucinating)
- Tested end-to-end with multiple LLM providers (OpenAI, Google Gemini)

#### 🗓️ [meeting-saas](https://github.com/isaias4321/meeting-saas)
A full meeting-summary SaaS: audio upload → transcription (Whisper) →
summary and action items via LLM, with authentication, credits, and billing.
`Python` `FastAPI` `Next.js` `Stripe`
- Asynchronous background processing (upload doesn't block the request)
- Real billing flow with Stripe Checkout and webhooks

#### ⚙️ [ai-gateway-api](https://github.com/isaias4321/ai-gateway-api)
A unified gateway for multiple LLM providers (OpenAI, Anthropic) — one
API for chat completions, with streaming (SSE), rate limiting (token
bucket), TTL cache, and automatic retry with exponential backoff.
`TypeScript` `Fastify` `Zod` `Vitest`
- 23 automated tests (mocked providers, 100% offline and deterministic suite)
- Swappable per-provider adapters — switching from OpenAI to Anthropic is a single field in the request
- Dockerized with a `HEALTHCHECK`, Docker Compose, and CI (GitHub Actions: lint → typecheck → build → test)

#### 📲 [whatsapp-server](https://github.com/isaias4321/whatsapp-server)
A Node.js microservice that connects to WhatsApp via **Baileys** and
exposes a REST API for a main application to send messages/images,
manage sessions (QR-code connection), and list groups.
`Node.js` `Baileys` `Supabase` `Render`
- Session persisted in Supabase — survives server restarts without needing to reconnect the QR code
- API protected by an `x-api-key` header, designed for server-to-server communication between the backend and the main application

#### 📓 [caderno-ia-generativa-negocios](https://github.com/isaias4321/caderno-ia-generativa-negocios)
A study notebook from the **"Exploring NotebookLM as an Active Learning
Tool"** challenge (DIO) — on generative AI applied to business: ROI,
use cases by industry, and real adoption barriers.
`Prompt Engineering` `NotebookLM` `Applied Research`
- 5 strategic prompts documented with results, difficulties, and lessons learned from each
- Curated real sources (Google Cloud, Databricks, Thomson Reuters), a glossary, and reusable prompts for future review

---

### 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**AI**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![RAG](https://img.shields.io/badge/RAG-000000?style=flat)
![AI Agents](https://img.shields.io/badge/AI%20Agents-000000?style=flat)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)

**Automation & DevOps**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 📚 Currently learning

`Agentic AI` · `MCP` · `LangGraph` · `CrewAI` · `LlamaIndex` · `Vector Databases`

---

### 🎓 Certifications

- ✔ Artificial Intelligence: From Zero to Advanced — Udemy (2026)
- ✔ Prompt Engineering
- ✔ AI Applications

---

### 🎯 Goal

Looking for opportunities as: `AI Engineer` · `Generative AI Engineer` · `Prompt Engineer` · `AI Automation Engineer`

---

### 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=isaias4321&show_icons=true&theme=dark&hide_title=false)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=isaias4321&theme=dark)

---

📫 Feel free to reach out — [isaiasmaiaf@gmail.com](mailto:isaiasmaiaf@gmail.com) · [LinkedIn](https://www.linkedin.com/in/isa%C3%ADas-maia-fraz%C3%A3o-b3a083280/)

⭐ Thanks for visiting!
