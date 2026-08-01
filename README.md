<h1 align="center">Muhammad Nouman Amjad</h1>
<h3 align="center">AI Engineer</h3>

<p align="center">
I design and deploy end-to-end intelligent systems: LLM and RAG pipelines, agentic AI, MLOps, and computer vision. I take products from architecture to production on AWS and GCP using Python, LangChain, LangGraph, FastAPI, and Docker.
</p>

---

### About Me

- I architect backend AI systems for data ingestion, processing, and retrieval across enterprise use cases.
- I build RAG pipelines with a focus on contextual retrieval, prompt engineering, and response grounding.
- I deploy production infrastructure on AWS and GCP with CI/CD, containerization, and observability.
- I work across the stack: LLMs (OpenAI, Anthropic Claude), agentic orchestration, vector search, and computer vision.

Most of my recent work lives in private company repositories, so the highlights below describe what I have built rather than link to source.

---

### Featured Work

**FedBid Intelligence Platform**
AI-powered federal contracting intelligence platform on AWS. Orchestrated LangGraph agents with OpenAI and Anthropic Claude to automate opportunity discovery, document parsing (PDF, DOCX, XLSX), compliance checking, and multi-factor bid/no-bid scoring across 10,000+ government contract opportunities.
- Built a semantic relevance matching engine using OpenAI text-embedding-3-small (1536-dim) with pgvector on PostgreSQL, scoring opportunity-to-company fit with a weighted formula across capability, past performance, competitiveness, and size fit.
- Engineered an event-driven ingestion pipeline (AWS Step Functions, Lambda, SQS, ECS Fargate) pulling federal data from SAM.gov, FPDS, USAspending, and GSA CALC+ on a 4-hour refresh cycle with idempotent upserts and S3-backed storage.
- Shipped MLOps pipelines with GitHub Actions CI/CD, Docker multi-platform builds to AWS ECR, and automated ECS Fargate deployments; a centralized agent registry enables independent deployment of 7+ AI agents.
- Ran production infrastructure (ECS Fargate, ALB, RDS PostgreSQL, S3, WAF, Route 53) with auto-scaling, RBAC, async DB access, and Langfuse tracing, keeping LLM costs under $165 per month.
<br>Stack: Python, LangGraph, OpenAI, Anthropic Claude, pgvector, PostgreSQL, AWS, Docker, Langfuse

**Enterprise Insight Engine**
High-performance platform for enterprise data search and contextual AI. Integrated data from Snowflake and Populi, using MCP agents and LLM-based prompt expansion with MongoDB schema awareness to sharpen query intent and retrieval quality. Optimized context filtering for token efficiency in high-throughput search scenarios.
<br>Stack: Python, LLMs, MongoDB, Snowflake, MCP

**Agenda Architect**
FastAPI backend integrated with MongoDB and Qdrant for persistence and semantic vector search. Deployed LLMs locally via NVIDIA NIM to cut latency and cost versus cloud inference, with a LangChain RAG pipeline that generates structured multi-section agendas from user input. Orchestrated backend, database, vector store, and local LLM services with Docker Compose.
<br>Stack: FastAPI, LangChain, Qdrant, MongoDB, NVIDIA NIM, Docker

**CreatorMatch Engine**
Built an ETL pipeline on GCP to ingest and transform complex JSON data into BigQuery. Developed a Health Score algorithm from engagement and credibility metrics, plus a recommender engine to support marketing sponsorship decisions.
<br>Stack: GCP, BigQuery, Python

**RoadVision GeoLocator**
Deep learning system to geolocate US roadway assets from 2D images and vehicle-mounted footage. Fused Vision Transformer features with metadata and depth maps, improving geolocation accuracy by over 50 percent, from 17ft error to under 7ft, through model fine-tuning and depth estimation.
<br>Stack: PyTorch, Vision Transformers, OpenCV

---

### Experience

- AI Engineer and Team Lead, Marsons Media
- Machine Learning Engineer, VannGuard AI
- Machine Learning Engineer, iENGINEERING

---

### Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white)

**AI and Machine Learning**
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=TensorFlow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-%23white.svg?style=flat&logo=opencv&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat&logo=dvc&logoColor=white)

**Data and Vector Stores**
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**MLOps and Cloud**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=flat&logo=google-cloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=flat&logo=jenkins&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=Prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white) ![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat&logo=langfuse&logoColor=white)

**Web**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=flat&logo=flask&logoColor=white)

---

### GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Nouman-Amjad&theme=calm&hide_border=false&include_all_commits=true&count_private=true&show_icons=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nouman-Amjad&theme=calm&hide_border=false&include_all_commits=true&count_private=true&layout=compact"/>
</p>

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=Nouman-Amjad&theme=calm&hide_border=false"/>
</p>
