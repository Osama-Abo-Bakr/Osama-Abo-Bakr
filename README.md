<div align="center">

# Osama Abo-Bakr Khalifa

### I build AI Agents and RAG systems that work in production — not just in demos.

*Senior AI Engineer · CTO @ NexAI (Riyadh) · Top-Rated Upwork Freelancer · Kaggle Expert*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/osama-abo-bakr-293614259)
[![Upwork](https://img.shields.io/badge/Upwork-6fda44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/osamaa305)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/osamaabobakr)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://osama-abo-bakr.vercel.app/)

</div>

---

Most AI projects fail not because the model is wrong — but because they never connect to real business data or real workflows.

I specialize in **Agentic AI systems** and **RAG pipelines** that actually integrate into how businesses run: agents that reason and act autonomously, knowledge bases built from *your* data, and automation that eliminates hours of manual work.

Currently leading the engineering team at **NexAI (Riyadh)** as CTO — designing system architecture, making technical decisions, and shipping production AI products. Previously built AI agents and vector search systems for banking operations at **CIB**. I bring that same production-grade thinking to every engagement, no matter the size.

---

## 🎯 What I Specialize In

| Area | What I Build | Core Tech |
|------|-------------|-----------|
| 🤖 **AI Agents** | Multi-agent pipelines that fetch, reason, and act in sequence — autonomously | LangGraph · CrewAI · LangChain |
| 📚 **RAG Systems** | Production knowledge bases from docs, PDFs, databases — hybrid search + memory | LlamaIndex · Weaviate · Pinecone |
| 🏛️ **Enterprise AI Apps** | End-to-end AI platforms with auth, dashboards, real integrations | FastAPI · Next.js · PostgreSQL |
| 🔄 **Workflow Automation** | Pipelines connecting CRM, Slack, WhatsApp, email — zero manual intervention | n8n · Make · Custom APIs |

---

## 🚀 Featured Projects

### 💬 [SaaS RAG Chatbot](https://github.com/Osama-Abo-Bakr/SaaS-RAG-chatbot)

**The problem:** Organizations drowning in documents with no way to query them intelligently.

**What I built:** Production RAG platform that ingests 1,000+ documents into Weaviate, runs hybrid search (dense + sparse), and delivers contextual answers with conversation memory. Full FastAPI backend + Next.js frontend. Delivered in under 2 weeks.

**Architecture decisions:** Chose Weaviate over Pinecone for native hybrid search support. Used Cohere reranking on top of vector retrieval to improve answer relevance. Conversation memory handled via sliding window buffer — balances context length vs. cost.

`FastAPI` `Weaviate` `RAG` `Hybrid Search` `Cohere Reranking` `PostgreSQL` `Next.js` `Docker`

---

### 📈 [Stock Market Analysis Agent](https://github.com/Osama-Abo-Bakr/Stock-Agent)

**The problem:** Manually tracking news sentiment + technical indicators across stocks is slow and error-prone.

**What I built:** 4 specialized agents working in sequence — news fetcher → sentiment scorer → technical indicator analyzer → signal generator. Each agent has a single responsibility; outputs chain into the next.

**Architecture decisions:** Chose CrewAI over LangGraph for its role-based agent design — cleaner for sequential pipelines where each agent has a clear persona. GPT-4 for reasoning steps, lighter models for data retrieval to reduce cost.

`CrewAI` `GPT-4` `LangChain` `Technical Analysis` `Sentiment NLP` `Real-time APIs`

---

### 🏛️ [InstaMasr](https://github.com/Osama-Abo-Bakr/instamasr)

**The problem:** Egyptian citizens navigating government services face complex forms and no guidance.

**What I built:** Full-stack AI platform for a startup client — AI chat assistant, intelligent form automation, Arabic RTL support, JWT auth, dark/light theming. End-to-end from architecture to production deployment.

**Architecture decisions:** Arabic NLP required careful embedding model selection — tested multiple models for Arabic text quality before settling on final stack. RTL + dark mode handled at Tailwind config level for consistency across all components.

`Next.js` `FastAPI` `LangChain` `JWT` `Arabic NLP` `PostgreSQL` `Tailwind`

---

### 📊 [Financial Data Analysis — CrewAI](https://github.com/Osama-Abo-Bakr/financial-data-analysis-crewai)

**The problem:** Financial analysts spend hours manually pulling and cross-referencing data from multiple sources.

**What I built:** Agent team that autonomously extracts insights from structured and unstructured financial sources, summarizes trends, and surfaces actionable signals — no human in the loop.

**Architecture decisions:** Used Llama 3.2 locally to avoid API costs on high-frequency data pulls. Agent roles split by data type (structured vs. unstructured) rather than by task step — better parallelism.

`CrewAI` `Llama 3.2` `Multi-Agent` `Financial NLP` `Local LLM`

---

## 🛠️ Full Tech Stack

<table>
<tr>
<td valign="top" width="33%">

### AI & LLM
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=graph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B46C1?style=for-the-badge&logo=llama&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=for-the-badge&logo=ai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

</td>
<td valign="top" width="33%">

### ML/DL & Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

</td>
<td valign="top" width="33%">

### Vector DBs
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00C853?style=for-the-badge&logo=weaviate&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1E0?style=for-the-badge&logo=milvus&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=database&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)

</td>
</tr>
<tr>
<td valign="top" width="33%">

### Web & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

</td>
<td valign="top" width="33%">

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</td>
<td valign="top" width="33%">

### Automation & Tools
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</td>
</tr>
</table>

---

## 🏆 Recognition

| Platform | Achievement | Detail |
|----------|-------------|--------|
| Upwork | **Top-Rated Freelancer** | 100% Job Success Score |
| Kaggle | **Expert** | Active competitions & datasets |
| HackerRank | **Top 98th in Egypt** | Python |
| HackerRank | **#1 at Menoufia University** | Data Structures & Python |
| HackerRank | **#2 at Menoufia University** | Algorithms & C++ |

---

## 💼 Experience

**CTO & Senior AI Engineer** @ NexAI · Riyadh, KSA
Leading the engineering team — system architecture, technical decisions, and end-to-end delivery of enterprise AI products including LLM apps, RAG pipelines, and multi-agent platforms.

**AI Engineering Intern** @ Commercial International Bank (CIB) · Egypt
Built AI agents, RAG pipelines, and vector search systems for banking operations.

**Top-Rated AI Freelancer** @ Upwork · Global
Delivering production AI systems for startups and enterprise teams worldwide.

---

## 📫 Work With Me

**Open to:** AI consulting · RAG system builds · Agentic AI architecture · Senior AI engineering roles

📧 [osamaoabobakr12@gmail.com](mailto:osamaoabobakr12@gmail.com) · 💼 [Upwork](https://www.upwork.com/freelancers/osamaa305) · 🌐 [Portfolio](https://osama-abo-bakr.vercel.app/)

<div align="center">

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Osama-Abo-Bakr.Osama-Abo-Bakr)

</div>
