# Olá 👋, sou o Isaías Maia Frazão

### AI Engineer · Generative AI · LLM Agents

Construo sistemas de IA aplicada — do protótipo ao produto — usando LLMs,
agentes com ferramentas, RAG e automação.

[![Email](https://img.shields.io/badge/Email-isaiasmaiaf%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:isaiasmaiaf@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Isa%C3%ADas%20Maia%20Fraz%C3%A3o-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isa%C3%ADas-maia-fraz%C3%A3o-b3a083280/)
[![GitHub](https://img.shields.io/badge/GitHub-isaias4321-181717?style=flat&logo=github&logoColor=white)](https://github.com/isaias4321)

---

### 👨‍💻 Sobre mim

- 🚀 Foco em construir aplicações de IA com **LLMs**, **agentes com ferramentas**, **RAG** e **automação**
- 🌱 Vim de Infraestrutura de TI e Redes, hoje especializado em IA Generativa
- 🛠️ Gosto de projetos com **prova real de funcionamento** — todo repositório abaixo tem demo em vídeo/print, não só código
- 📍 São Luís, Maranhão, Brasil

---

### 🚀 Projetos em destaque

#### 🗄️ [langchain-sql-agent](https://github.com/isaias4321/langchain-sql-agent)
Agente construído com **LangChain.js** que responde perguntas em português
sobre um banco de dados, explorando o schema dinamicamente antes de gerar o
SQL — em vez de um chain fixo com schema fixo no prompt.
`TypeScript` `LangChain.js` `SQLite` `Node.js`
- Ferramentas (`list_tables`, `get_schema`, `execute_readonly_query`) escolhidas pelo próprio agente
- Camada de segurança (`sqlGuard`) que bloqueia qualquer SQL de escrita, com testes automatizados

#### 💬 [rag-chat-docs](https://github.com/isaias4321/rag-chat-docs)
Sistema de **RAG** (Retrieval-Augmented Generation) construído do zero, sem
framework de orquestração — upload de PDF, chunking, embeddings, busca
vetorial e resposta com citação da fonte.
`Python` `FastAPI` `ChromaDB`
- Responde apenas com base no documento enviado, e diz claramente quando a resposta não está lá (sem alucinar)
- Testado end-to-end com múltiplos provedores de LLM (OpenAI, Google Gemini)

#### 🗓️ [meeting-saas](https://github.com/isaias4321/meeting-saas)
SaaS completo de resumo de reuniões: upload de áudio → transcrição (Whisper)
→ resumo e lista de ações via LLM, com autenticação, créditos e cobrança.
`Python` `FastAPI` `Next.js` `Stripe`
- Processamento assíncrono em background (upload não trava a requisição)
- Fluxo de billing real com Stripe Checkout e webhooks

#### ⚙️ [ai-gateway-api](https://github.com/isaias4321/ai-gateway-api)
Gateway unificado para múltiplos provedores de LLM (OpenAI, Anthropic) —
uma única API para chat completions, com streaming (SSE), rate limiting
(token bucket), cache com TTL e retry automático com backoff exponencial.
`TypeScript` `Fastify` `Zod` `Vitest`
- 23 testes automatizados (provedores mockados, suíte 100% offline e determinística)
- Adapters intercambiáveis por provedor — trocar de OpenAI pra Anthropic é mudar um campo no request

#### 📲 [whatsapp-server](https://github.com/isaias4321/whatsapp-server)
Microsserviço Node.js que conecta ao WhatsApp via **Baileys** e expõe uma
API REST para uma aplicação principal enviar mensagens/imagens, gerenciar
sessões (conexão por QR code) e listar grupos.
`Node.js` `Baileys` `Supabase` `Render`
- Sessão persistida no Supabase — sobrevive a reinicializações do servidor sem precisar reconectar o QR code
- API protegida por header `x-api-key`, pensada para comunicação servidor-a-servidor entre o backend e a aplicação principal

#### 📓 [caderno-ia-generativa-negocios](https://github.com/isaias4321/caderno-ia-generativa-negocios)
Caderno de estudo do desafio **"Explorando o NotebookLM como Ferramenta de
Aprendizagem Ativa"** (DIO) — sobre IA generativa aplicada a negócios: ROI,
casos de uso por setor e barreiras reais de adoção.
`Prompt Engineering` `NotebookLM` `Pesquisa aplicada`
- 5 prompts estratégicos documentados com resultado, dificuldade e aprendizado de cada um
- Curadoria de fontes reais (Google Cloud, Databricks, Thomson Reuters), glossário e prompts reutilizáveis para revisão futura

---

### 🛠 Tech Stack

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**IA**

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

**Automação & DevOps**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 📚 Estudando agora

`Agentic AI` · `MCP` · `LangGraph` · `CrewAI` · `LlamaIndex` · `Vector Databases`

---

### 🎓 Certificações

- ✔ Artificial Intelligence: From Zero to Advanced — Udemy (2026)
- ✔ Prompt Engineering
- ✔ AI Applications

---

### 🎯 Objetivo

Buscando oportunidades como: `AI Engineer` · `Generative AI Engineer` · `Prompt Engineer` · `AI Automation Engineer`

---

### 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=isaias4321&show_icons=true&theme=dark&hide_title=false)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=isaias4321&theme=dark)

---

📫 Fico à disposição — [isaiasmaiaf@gmail.com](mailto:isaiasmaiaf@gmail.com) · [LinkedIn](https://www.linkedin.com/in/isa%C3%ADas-maia-fraz%C3%A3o-b3a083280/)

⭐ Obrigado pela visita!
