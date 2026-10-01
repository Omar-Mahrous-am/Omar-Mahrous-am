<div align="center">

### AI/ML Engineer — LLM Applications, Agentic AI & Production ML Systems

Final-year AI Engineering student building deployed, end-to-end AI systems — from LangGraph agents and RAG pipelines to computer vision, containerized and CI/CD-driven for production.

[![Email](https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omer.mohamed.mahrous@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-mahrous-787b76305/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://omar-mahrous-am.github.io/omar_mahrous/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/omar-mahrous-am)

</div>

---

### About

I'm an AI Engineering student at Mansoura University (expected graduation: Feb 2027) focused on building AI systems that actually run — not just notebooks with accuracy scores. My work spans production-grade LLM applications, advanced RAG, multi-agent workflows, and computer vision, with containerized services, CI/CD pipelines, and observability as part of how I build, not an afterthought. I'm seeking an entry-level AI/ML role.

### Currently Exploring

- Multi-agent systems and advanced agentic workflows (LangGraph)
- Advanced RAG architectures and LLM fine-tuning (LoRA/PEFT)
- Deepening MLOps practices — automated retraining, model monitoring

---

### Featured Projects

**[Analyst Agent — Intelligent SQL Agent with Human-in-the-Loop](#)**
Natural-language-to-SQL agent built as an 8-node LangGraph state machine with cyclic self-correction loops and persistent SQLite checkpointing, converting questions into verified SQL queries.
- 3-layer SQL sanitization and extraction to ensure execution safety
- Async FastAPI backend with real-time Server-Sent Events (SSE) streaming of live node-by-node state transitions
- Human-in-the-Loop interrupt gate with 3 distinct decision paths for review and oversight
- Multi-provider LLM support via AISuite (OpenAI, Cohere, Anthropic), intent classification, Tavily web-search fallback, and pandas analytics pipelines

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**[SmartDesk AI — AI-Powered Customer Support Platform](#)**
Enterprise-grade customer support platform on FastAPI with 10 documented REST endpoints and hot-swappable vector database backends (Qdrant & pgvector).
- Multi-stage RAG pipeline and stateful conversation engine with JSONB-backed message persistence
- Multi-provider LLMs (OpenAI & Cohere) integrated through a factory pattern
- 9-container Docker Compose architecture with Nginx reverse proxy, custom Prometheus metrics, Grafana dashboards, and non-blocking async SMTP ticket dispatch

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**[Essay Writer Agent — Autonomous Essay Generation with Self-Critique](#)**
Cyclic LangGraph state machine that plans a hierarchical outline, runs dynamic Tavily web search, and iterates through adversarial self-reflection loops to synthesize structured academic essays.
- Async FastAPI backend with thread-isolated memory checkpointing via LangGraph `MemorySaver`
- Zero-dependency web interface

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**[Sentry Vision — Real-Time AI Security Platform](#)**
Modular multi-model CV platform integrating 5 optimized deep learning models (YOLOv8/YOLO11 weapon detection, MobileNetV2 fire & smoke classification, and a 3-stage cascade LPR pipeline for Egyptian Arabic plates) with a total weight footprint under 48.2 MB.
- 94.90% validation accuracy for fire/smoke detection; 92.4%–96.8% mAP across weapon localization and cascaded plate recognition
- Async FastAPI backend with 11 production REST endpoints; processes video files up to 500 MB at >4.2x real-time speed (1080p @ 30 FPS, `frame_skip=5`)
- Sub-millisecond SQLite watchlist lookups (<1.2 ms), LPR syntax parsing across all 27 Egyptian Governorates, and non-blocking audio alerts (<50 ms trigger delay)
- Full MLOps lifecycle: Docker Compose multi-service deployment, 4 GitHub Actions workflows (lint, test, deploy, daily eval) + CircleCI, and automated weekly retraining and evaluation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**[CineMatch — Movie Recommender System](#)**
Content-based recommendation engine using TF-IDF vectorization and cosine similarity across 4,800+ films, with a FastAPI backend and React SPA frontend.
- REST endpoints (`/predict`, `/quiz-recommend`) serving real-time recommendations
- Single Docker image containerizing the full stack, deployed live on AWS EC2
- End-to-end ownership: model training → API → frontend → cloud deployment

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20EC2-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**[Credit Fraud Detection — End-to-End ML Pipeline](#)**
Classification pipeline with preprocessing, feature engineering, and SMOTE-based imbalance handling, achieving 0.97 AUC-ROC with full precision/recall/F1 evaluation.
- Streamlit interface for real-time transaction inference
- Complete model-to-production lifecycle, from raw data to deployed inference

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

> Repository links above are placeholders — replace `#` with your actual GitHub repo URLs.

---

### Technical Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,docker,mysql,sqlite,postgres,mongodb,aws,linux,git,github" />
</div>

<br />

**Agentic AI & Generative AI**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

`Autonomous Agentic Workflows` `Tool Integration` `Human-in-the-Loop` `RAG System Design` `LLM Fine-Tuning (LoRA/PEFT)` `Prompt Engineering` `Multi-model LLM Orchestration`

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

`CNNs` `RNNs` `Transformers` `YOLOv8/YOLO11` `MobileNetV2` `Transfer Learning` `Real-time Inference Optimization` `End-to-End ML Pipelines` `Feature Engineering` `Model Evaluation`

**Backend & MLOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=for-the-badge&logo=circleci&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Databases, Data & Cloud**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

### Education & Certifications

- **B.Eng. in AI Engineering** — Mansoura University (2022 – Expected Feb 2027), GPA 3.61/4.0
- **ALX Data Science Program** (Explore AI) — 13-month intensive training, 2024–2025
- **Deep Learning Specialization** — Coursera, Andrew Ng
- **Digital Egypt Pioneers Initiative (DEPI)** — 4-month intensive AI & ML training
- **McKinsey Forward Program** — Leadership & Problem-Solving, McKinsey & Company

---

<div align="center">

📫 [Email](mailto:omer.mohamed.mahrous@gmail.com) · [LinkedIn](https://www.linkedin.com/in/omar-mahrous-787b76305/) · [Portfolio](https://omar-mahrous-am.github.io/omar_mahrous/)

</div>
