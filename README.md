<h1 align="center">Hi 👋, I'm Malik Muhammad Kashif Saeed</h1>
<h3 align="center">AI Engineer | Multi-Agent Systems (LangGraph) · RAG & Vector Search · LLMOps · AWS</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=AI+Engineer+%7C+3%2B+Years+Building+Production+LLM+Systems;LangGraph+Multi-Agent+Orchestration+%7C+RAG+Architectures;AWS+%7C+FastAPI+%7C+LangChain+%7C+Vector+Search" alt="Typing SVG" />
</p>

---

### 🚀 About Me

I'm an **AI Engineer** based in Rawalpindi, Pakistan, with **3+ years** of experience designing, building, and deploying production-grade LLM systems — from agentic multi-agent orchestration pipelines to retrieval-augmented generation (RAG) architectures and scalable AWS infrastructure for enterprise clients.

- 🔭 Most recently led architecture & engineering of **GovHub** — a production AI platform ingesting thousands of SAM.gov federal contracting opportunities daily through a **LangGraph multi-agent pipeline** with automated compliance checking, scoring, and executive summary generation.
- 🧠 Deep expertise across the full AI stack: multi-agent system design with **LangGraph StateGraphs**, tool/function calling, hybrid vector search, LLM observability with **Langfuse**, prompt engineering, and end-to-end AWS deployment.
- 👯 Looking to collaborate on **AI agents, RAG systems, and intelligent automation platforms**.
- 💬 Ask me about **LangGraph, RAG pipelines, FastAPI, vector search, and LLM deployment on AWS**.
- 📫 Reach me at **malikmuhammadkashif414@gmail.com**

---

### 🛠️ Featured Work

**GovHub — AI Government Contracting Intelligence Platform** *(Lead AI Engineer, Marsons Media)*
> Production SaaS platform ingesting thousands of SAM.gov opportunities daily via a 6-agent LangGraph pipeline (`llm_match`, `document_parser`, `compliance_checker`, `score_calculator`, `opportunity_orchestrator`, `company_match`), delivering ranked opportunities with compliance reports and win-probability scores. Deployed on ECS Fargate, Lambda, RDS, and S3 with full GitHub Actions CI/CD.

**Intella Part AI — Industrial RAG System** *(Codeaza Technologies)*
> Production RAG system adopted across 30+ industrial brands, indexing 5,000+ technical manuals with Voyage AI embeddings and Elasticsearch, delivering sub-second p95 query latency.

**Real Estate Property QA Chatbot** *(Codeaza Technologies)*
> Hybrid retrieval architecture (Qdrant + BM25 + reranking) achieving ~50% improvement in search relevance, served via a FastAPI backend with <200ms p95 response time.

---

### 💼 What I've Built

<details open>
<summary><b>🟢 GovHub — AI Government Contracting Intelligence Platform</b></summary>
<br>

- Led full architecture & engineering of a production AI SaaS platform ingesting **thousands of SAM.gov opportunities daily**, running a multi-stage LangGraph pipeline with compliance reports and win-probability scores.
- Designed a **6-agent LangGraph StateGraph** orchestration system (`llm_match`, `document_parser`, `compliance_checker`, `score_calculator`, `opportunity_orchestrator`, `company_match`) via an agent registry pattern with runtime dependency injection.
- Built a two-stage AI pipeline: real-time GPT-4.1-mini quick-match scoring, plus on-demand full RFP/SOW parsing and BLUF summary generation via Claude's 200K context window.
- Engineered the SAM.gov ingestion pipeline (paginated fetch → PostgreSQL upsert → async S3 streaming → Lambda → ECS Fargate dispatch) and a multi-format document intelligence layer (PDF, Word, Excel, HTML).
- Integrated **Langfuse** for full LLM observability — traces, token cost, and latency across all agents.
- Deployed on **AWS** (ECS Fargate, Lambda, RDS, S3, ECR, Secrets Manager, private-subnet VPC) with a GitHub Actions CI/CD pipeline for zero-downtime rolling updates.
</details>

<details>
<summary><b>🔵 Intella Part AI — Industrial RAG System (30+ Brands, 4,000+ Manuals)</b></summary>
<br>

- Architected and shipped a production RAG system adopted across **30+ industrial brands** for natural-language Q&A over technical documentation.
- Built an ingestion pipeline for **5,000+ manuals** using Voyage AI embeddings and Elasticsearch, hitting sub-second p95 query latency.
</details>

<details>
<summary><b>🟣 Real Estate Property QA Chatbot</b></summary>
<br>

- Designed a hybrid retrieval architecture (Qdrant + BM25 + reranking), improving search relevance by **~50%** over baseline keyword search.
- Built a FastAPI backend with **<200ms p95** response time; owned the project end-to-end from discovery to AWS deployment.
</details>

<details>
<summary><b>🟠 Sentimantle — ML Sentiment Analysis Platform</b></summary>
<br>

- Maintained production ML inference pipelines on AWS ECS, sustaining **99%+ uptime**.
- Cut API response times by **40%** through MySQL query rewriting and index tuning.
</details>

<details>
<summary><b>🔴 Document QA Chatbot & LLM Benchmarking Tools</b></summary>
<br>

- Built a **LlamaIndex-based RAG chatbot** for semantic Q&A over uploaded documents.
- Developed **LLM Wars**, a GPT vs. Gemini output-quality benchmarking framework.
- Built **Echo App**, a Node.js backend integrating an AI image model for automated social content generation.
</details>

<br>

🎓 **B.E. Computer Software Engineering** — National University of Sciences and Technology (NUST), Islamabad

---

### 🧰 Tech Stack

**AI / Agents**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

**RAG & Vector Search**
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

**Frontend**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next.js](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

**ML / Data**
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=kashif-saeed1122&show_icons=true&theme=dark&hide_border=false&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kashif-saeed1122&layout=compact&theme=dark&hide_border=false" />
</p>

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=kashif-saeed1122&theme=dark&hide_border=false" alt="GitHub Streak" />
</p>

---

### 🌐 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/malik-muhammad-kashif-saeed/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://medium.com/@malikmuhammadkashif414" target="_blank">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
  <a href="mailto:malikmuhammadkashif414@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://visitcount.itsvg.in/api?id=kashif-saeed1122&icon=0&color=0" alt="Profile Views" />
</p>
