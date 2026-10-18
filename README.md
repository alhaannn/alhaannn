<div align="center">

# Mohammad Alhan Bellary
### Agentic AI • Backend Systems • MLOps Engineer

<p align="center">
  <a href="https://www.alhan.me/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=1000&color=10B981&center=true&vCenter=true&width=650&lines=GenAI+%26+Agentic+AI+Engineer;Resilient+Backend+Pipelines+%26+APIs;Production+MLOps+%26+Telemetry;IIT+Dharwad+NSQF+L5.0+AI+Scholar" alt="Typing SVG" />
  </a>
</p>

[![Portfolio](https://img.shields.io/badge/Portfolio-alhan.me-10B981?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.alhan.me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alhan_Bellary-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alhan-bellary)
[![LeetCode](https://img.shields.io/badge/LeetCode-alhaannn-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/alhaannn/)
[![Email](https://img.shields.io/badge/Email-alhanbellary123%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alhanbellary123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-alhaannn-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alhaannn)
[![Location](https://img.shields.io/badge/Location-Bengaluru%2C_India-6366F1?style=for-the-badge&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Bengaluru)

<br/>

> *"Systems should be **legible under load** — every state typed, every failure path named."*  
> **$\mathcal{O}(\text{clarity}) > \mathcal{O}(\text{cleverness})$** • *Built from first principles.*

</div>

---

## 📌 Executive Summary

I am an early-career **Software & AI Systems Engineer** based in Bengaluru, India. I treat AI systems as **measurable distributed systems**, not simple API wrappers. My work focuses on stateful multi-agent workflows, resilient asynchronous Python backends, production MLOps pipelines with drift telemetry, and edge-optimized computer vision.

- 🎓 **IIT Dharwad**: Pursuing full-time Artificial Intelligence in the **NSQF Level 5.0 "A.I – Technocrat"** program (Cohort 2026–2027) with 120 hours of mandatory deployment-focused OJT.
- 💼 **Production Experience**: Former Junior Software Developer Intern at **Heagl Technologies Pvt Ltd**, shipping 5 features across 2 production Django codebases and resolving 15+ issues with ~25% faster turnaround.
- 🏅 **Certified Professional**: Oracle Cloud Infrastructure 2025 Certified Data Science Professional & IBM SkillsBuild AI Literacy certified.
- 🎯 **Target Roles**: GenAI / Agentic AI Engineer • Software Engineer (Backend) • MLOps Engineer • AI/ML Engineer.

---

## 🧭 Engineering Focus & Capabilities

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 GenAI / Agentic AI Engineering</h3>
      <ul>
        <li><strong>Stateful Orchestration:</strong> Cyclic workflows with LangGraph (Planner, Retriever, Fact-Checker, and Correction loops).</li>
        <li><strong>Grounding & Retrieval:</strong> Hybrid search combining Qdrant / Chroma vector layers with BM25 keyword search and vectorless SQL fallbacks.</li>
        <li><strong>Guardrails & Safety:</strong> Strict Pydantic v2 schemas, PII redaction callbacks, and prompt-injection filtering.</li>
        <li><strong>Evaluation:</strong> Regression gates with Ragas / DeepEval measuring faithfulness, relevancy, and context recall.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Backend & Distributed Systems</h3>
      <ul>
        <li><strong>High-Throughput Services:</strong> Asynchronous REST APIs with FastAPI, Pydantic v2, and SSE streaming.</li>
        <li><strong>Background Processing:</strong> Decoupled worker queues using Celery and Redis to offload heavy workloads from the web path.</li>
        <li><strong>Traffic & Resilience:</strong> Token-bucket rate limiters, LRU semantic caching, and LiteLLM automated provider fallbacks.</li>
        <li><strong>Data Layer:</strong> Relational schemas, migrations, and audit logs with PostgreSQL, SQLAlchemy, and Alembic.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔄 MLOps & Production Telemetry</h3>
      <ul>
        <li><strong>Reproducibility:</strong> Dataset versioning via DVC and experiment tracking with MLflow model registry.</li>
        <li><strong>Container Delivery:</strong> Docker packaging and Kubernetes deployments with Horizontal Pod Autoscaling (HPA).</li>
        <li><strong>Operational Health:</strong> Prometheus metrics, Grafana dashboards, and telemetry-triggered rollback mechanisms.</li>
        <li><strong>Data & Model Drift:</strong> Continuous distribution tracking and quality monitoring with Evidently AI.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>👁️ Applied ML & Computer Vision</h3>
      <ul>
        <li><strong>Model Training:</strong> Fine-tuning YOLOv8, MobileNet, and Scikit-learn / XGBoost tabular baselines.</li>
        <li><strong>Multimodal Fusion:</strong> Combining visual features with structured operational and sensor metadata.</li>
        <li><strong>Edge Optimization:</strong> Model quantization via ONNX Runtime and TFLite for low-latency CPU inference.</li>
        <li><strong>Traceability:</strong> Typed detection APIs and SQL-backed anomaly audit records for historical review.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Featured Flagship Systems (From [alhan.me](https://www.alhan.me/))

### 01. Enterprise Multi-Agent Knowledge & Research Assistant
> **Domain:** Agentic AI & LLMOps | **Status:** In Progress
- **Problem:** Vanilla RAG pipelines suffer from context hallucination on multi-hop questions requiring cross-source synthesis and rigorous source verification.
- **Architecture:** Cyclic team of agents orchestrated via **LangGraph** (Planner, Retriever, Fact-Checker). Implements hybrid retrieval using **Qdrant** vector search + **BM25**, supported by structured SQL fallback, PII redaction, prompt injection defense, and **FastAPI SSE** streaming.
- **Key Metrics & Targets:** Target **34% lower context hallucination**; continuous regression testing via **Ragas** and **DeepEval** for faithfulness, relevancy, and context recall.
- **Stack:** `LangGraph` · `FastAPI SSE` · `Qdrant` · `BM25` · `Pydantic v2` · `Ragas` · `Docker`

---

### 02. High-Throughput Asynchronous AI Gateway & Task Engine
> **Domain:** Distributed Backend Systems | **Status:** In Progress
- **Problem:** Direct LLM API invocations block server threads, timeout during peak load, lack rate limiting, and risk single-provider downtime.
- **Architecture:** Asynchronous gateway built with **FastAPI** and **Pydantic v2**. Enforces token-bucket rate limits and LRU semantic deduplication. Automatically routes inference requests through **LiteLLM** with Groq as primary and OpenAI as fallback. Background tasks run on **Celery + Redis**, persisting latency and token usage metrics in **PostgreSQL**.
- **Key Metrics & Targets:** Target **250+ concurrent requests**, **sub-50ms queue latency**, and **>80% test coverage** via Pytest and GitHub Actions CI/CD.
- **Stack:** `FastAPI` · `Celery` · `Redis` · `PostgreSQL` · `SQLAlchemy` · `LiteLLM` · `GitHub Actions`

---

### 03. Production MLOps Anomaly Detection & Deployment System
> **Domain:** MLOps & Telemetry | **Status:** In Progress
- **Problem:** Offline ML models silently degrade in production due to unmonitored feature drift, manual deployments, and lack of rollback safety.
- **Architecture:** Complete lifecycle pipeline: versions IoT and security telemetry datasets with **DVC**, logs training runs and registers Isolation Forest / XGBoost models with **MLflow**, containerizes serving with **Docker**, and orchestrates deployments with **Kubernetes HPA** and **Prometheus / Grafana / Evidently AI** monitoring.
- **Key Metrics & Targets:** Real-time **automated drift visibility** and **zero-downtime rolling updates with telemetry-triggered rollback**.
- **Stack:** `PyTorch` · `XGBoost` · `MLflow` · `DVC` · `Docker` · `Kubernetes` · `Prometheus` · `Grafana` · `Evidently AI`

---

### 04. Multimodal Defect & Threat Inspection System
> **Domain:** Computer Vision & Edge AI | **Status:** In Progress
- **Problem:** Industrial quality control and threat inspection require fusing image data with operational and environmental telemetry.
- **Architecture:** Dual-stream pipeline fine-tuning **YOLOv8** on defect imagery with **PyTorch** and **OpenCV**, fusing visual embeddings with tabular sensor metadata, and quantizing models with **ONNX Runtime** for high-efficiency CPU edge serving through **FastAPI**.
- **Key Metrics & Targets:** Target **42 FPS edge inference** and **94.2% mAP** across 5 defect categories with structured SQL audit logging.
- **Stack:** `PyTorch` · `YOLOv8` · `OpenCV` · `ONNX Runtime` · `FastAPI` · `PostgreSQL`

---

### 05. Self-Healing BI & SQL Analytics Agent
> **Domain:** Applied AI & Analytics | **Status:** In Progress
- **Problem:** Traditional text-to-SQL prompts frequently fail on complex joins, hallucinate non-existent table schemas, or risk destructive write operations.
- **Architecture:** An interactive analytics agent that first runs a Schema Inspector to ground generation in active tables and constraints. Validates and executes queries strictly against a **read-only database replica**. If execution errors occur, an automated self-correction loop catches syntax/database errors and retries up to 3 times before routing ambiguous requests to human review. Generates interactive **Plotly** visualizations.
- **Key Metrics & Targets:** Target **bounded self-correction within 3 retries**; **100% read-only safe execution**.
- **Stack:** `LangGraph` · `PostgreSQL` · `Pydantic v2` · `Pandas` · `Plotly` · `FastAPI`

---

## 🛠️ Other Notable Builds & Open-Source Repositories

- 🤖 **[gary-bot](https://github.com/alhaannn/gary-bot)**: Automated algorithmic trading system that ingests signals from Telegram channels, classifies trade parameters using Groq (LLaMA), and executes orders on MetaTrader5 asynchronously.  
  *Stack: Python · Groq API · MetaTrader5 · Telethon · asyncio*

- 🌾 **[Agricultural Market Price Intelligence](https://github.com/alhaannn/Agricultural-Market-Price-Intelligence)**: Web application for commodity price tracking and ML-powered forecasting to empower agricultural market decisions.  
  *Stack: Python · Django · scikit-learn · Chart.js · SQLite*

- 🧩 **NeetCode 150 Daily Algorithmic Practice**: Consistent daily problem solving in Python 3.13 focusing on trees, graphs, dynamic programming, and systems algorithms with clean Big-O time and space documentation.

---

## 💼 Experience & Education

```
2026 – 2027   [Scholastic]   IIT Dharwad — A.I – Technocrat, NSQF Level 5.0
                             120-hour deployment OJT: Docker, K8s, CI/CD telemetry, Grafana

Feb–May 2026  [Commercial]   Heagl Technologies Pvt Ltd — Junior Software Developer Intern
                             Shipped 5 production Django features, fixed 15+ bugs, ~25% faster turnaround

2023 – 2026   [Academic]     IBMR Business School — BCA in Information Technology (CGPA: 7.66 / 10)
                             Coursework: Data Structures, DBMS, Web Tech, Software Engineering, OOP
```

---

## 🏅 Verified Certifications & Honors

- 📜 **[Oracle Cloud Infrastructure 2025 Certified Data Science Professional](https://catalog-education.oracle.com/ords/certview/sharebadge?id=49DC8CE41692A4C593AF0370F1D381193469FFF790D8B63C4B33B5E3FC7E7F39)** — Oracle
- 📜 **[IBM SkillsBuild AI Literacy (2025)](https://www.credly.com/badges/a78e9b34-62ac-4974-8e3c-7e1c10acb504/public_url)** — IBM
- 📜 **[Certified Product Manager (CPM)](https://www.geeksforgeeks.org/certificate/cc225bc4e1875b8ad97cd09834ffd50b)** — GeeksforGeeks
- 🏆 **1st Place Winner** — CheTech Hackathon (2026), Chetan College
- 🎯 **Participant** — Empathy Encryption Hackathon (2025), UnsaidTalks

---

## 🧰 Technical Arsenal

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages & Package Mgmt** | ![Python](https://img.shields.io/badge/Python_3.13-3776AB?style=flat-square&logo=python&logoColor=white) ![uv](https://img.shields.io/badge/uv-Package_Manager-DE5B43?style=flat-square) ![SQL](https://img.shields.io/badge/SQL-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Agentic AI & LLMs** | ![LangGraph](https://img.shields.io/badge/LangGraph-Stateful_Agents-FF6B6B?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-v1-1C3C3C?style=flat-square) ![LiteLLM](https://img.shields.io/badge/LiteLLM-Routing_%26_Fallback-4B32C3?style=flat-square) ![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC2626?style=flat-square) ![Chroma](https://img.shields.io/badge/Chroma-Vector_DB-orange?style=flat-square) ![Ragas](https://img.shields.io/badge/Ragas-LLM_Eval-purple?style=flat-square) |
| **Backend & Distributed** | ![FastAPI](https://img.shields.io/badge/FastAPI-Async_APIs-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-Production-092E20?style=flat-square&logo=django&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-Distributed_Workers-37814A?style=flat-square&logo=celery&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-Caching_%26_Queues-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Relational_DB-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-D71F00?style=flat-square) |
| **MLOps & Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-HPA_%26_Rolling_Updates-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-Registry-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-Data_Versioning-945DD6?style=flat-square&logo=dvc&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-Telemetry-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Machine Learning & CV** | ![PyTorch](https://img.shields.io/badge/PyTorch-Deep_Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-Computer_Vision-00FFFF?style=flat-square&logoColor=black) ![OpenCV](https://img.shields.io/badge/OpenCV-Image_Processing-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX_Runtime-Edge_Quantization-005CED?style=flat-square) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-Gradient_Boosting-2D6CA2?style=flat-square) |

</div>

---

## 📊 Telemetry & Activity

### ⚡ GitHub Contribution Telemetry

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=alhaannn&theme=tokyonight&border=10B981&background=0D1117&ring=10B981&fire=10B981&currStreakLabel=10B981" alt="GitHub Streak" width="95%" />
</div>

<br/>

### 🧩 LeetCode Problem-Solving Telemetry

<div align="center">
  <a href="https://leetcode.com/u/alhaannn/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/alhaannn?theme=tokyonight&font=Fira%20Code" alt="Alhan's LeetCode Stats" width="60%" />
  </a>
</div>

---

## 🤝 Let's Connect & Build

I am always interested in discussing scalable architectures, agentic systems, MLOps telemetry, and collaborative engineering opportunities.

- 🌐 **Interactive Portfolio**: [https://www.alhan.me](https://www.alhan.me)
- 💼 **LinkedIn**: [linkedin.com/in/alhan-bellary](https://www.linkedin.com/in/alhan-bellary)
- 🧩 **LeetCode**: [leetcode.com/u/alhaannn](https://leetcode.com/u/alhaannn/)
- 📧 **Email**: [alhanbellary123@gmail.com](mailto:alhanbellary123@gmail.com)
- 🐙 **GitHub**: [@alhaannn](https://github.com/alhaannn)
- 📸 **Instagram**: [@alhaaannnn](https://www.instagram.com/alhaaannnn)

---

<div align="center">
  <sub>Designed with precision to match <a href="https://www.alhan.me">alhan.me</a> • © 2026 Mohammad Alhan Bellary</sub>
</div>
