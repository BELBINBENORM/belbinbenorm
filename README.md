<div align="center">

# Hi, I'm Belbin Beno R M 👋

### AI / ML Engineer · Generative AI · Data Engineering

**Python · Machine Learning · Generative AI · RAG · LLM Agents · FastAPI · PostgreSQL**

<a href="https://belbin-beno-rm-portfolio.vercel.app/">
  <img src="https://img.shields.io/badge/PORTFOLIO-111111?style=for-the-badge" />
</a>
<a href="https://www.linkedin.com/in/belbino/">
  <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://www.kaggle.com/belbino">
  <img src="https://img.shields.io/badge/KAGGLE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
</a>
<a href="mailto:belbin.datascientist@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

## About Me

I build **AI/ML systems across the full pipeline**, from data preparation and feature engineering to model training, hyperparameter tuning, evaluation, and deployment.

My work spans **classical machine learning, ensemble modeling, Kaggle competitions and datasets, Generative AI, RAG, LLM agents, backend engineering, and data pipelines**.

My recent projects focus on turning experimentation into **reproducible, testable, production-oriented systems** using Python, FastAPI, PostgreSQL, vector search, MCP, Redis, Docker, and cloud deployment.

---

# 🚀 Featured Project: AegisAI

**[AegisAI](https://github.com/BELBINBENORM/aegisai)** is a **production-oriented single-agent AI platform** for document-grounded reasoning and tool-using AI.

Instead of multiple autonomous agents, AegisAI uses **one Main Agent** responsible for planning, tool selection, reasoning, clarification, and final synthesis.

### Core Architecture

```text
┌──────┐     ┌─────────────┐     ┌────────────┐     ┌─────┐
│ User │ ──► │   FastAPI   │ ──► │ Main Agent │ ──► │ MCP │
└──────┘     │  Auth / API │     │ Planning,  │     └──┬──┘
             └─────────────┘     │ Reasoning, │        │                                            ┌────────┐
                                 │ Tool Use   │        ├─► [ RAG ] ────────┐   ┌──────────────┐     │ Final  │
                                 └────────────┘        ├─► [ Memory ] ─────┼─► │ Verification │ ──► │ Answer │
                                                       └─► [ Web Search ] ─┘   └──────────────┘     └────────┘
```

### Engineering Highlights

* Single Main Agent architecture
* Advanced RAG with vector and keyword retrieval
* MCP-based tool boundary
* Document ingestion pipeline
* Semantic memory and conversation history
* Agent planning and verification
* Agent clarification with nested interaction
* Prompt injection and security controls
* Redis caching and rate limiting
* Background document-processing jobs
* Streaming responses
* PostgreSQL + pgvector
* Authentication and authorization
* Observability and evaluation
* Automated testing and CI/CD
* Dockerized deployment

### Infrastructure

```text
Render
 ├── FastAPI
 └── Background Worker
        │
        ├── Neon PostgreSQL + pgvector
        └── Redis
             ├── Cache
             ├── Rate Limiting
             └── Job Queue
```

**Live API Docs:** https://aegisai-x721.onrender.com/docs

---

# 🧠 RAGForge

**[RAGForge](https://github.com/BELBINBENORM/ragforge)** is an **Agentic RAG platform** combining document ingestion, semantic search, conversational memory, LLM agents, and MCP.

```text
Documents
    │
    ▼
Embeddings + pgvector
    │
    ▼
User → FastAPI → Gemini Agent → MCP
                              │
                     ┌────────┴────────┐
                     ▼                 ▼
               Document Search    Conversation History
                     │                 │
                     └────────┬────────┘
                              ▼
                       Grounded Answer
```

RAGForge represents the RAG and agent foundations that evolved into the broader AegisAI architecture.

**Live API Docs:** https://ragforge-htnl.onrender.com/docs

---

# 🤖 AI & Generative AI

| Project                                                                                          | Focus                                                                                                                 |
| ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| **[AegisAI](https://github.com/BELBINBENORM/aegisai)**                                           | Single-agent AI platform, Advanced RAG, MCP, memory, verification, security, evaluation and production infrastructure |
| **[RAGForge](https://github.com/BELBINBENORM/ragforge)**                                         | Agentic RAG, MCP, semantic search and conversational memory                                                           |
| **[ai_document_intelligence](https://github.com/BELBINBENORM/ai_document_intelligence)**         | AI-powered document intelligence                                                                                      |
| **[ai_customer_support_platform](https://github.com/BELBINBENORM/ai_customer_support_platform)** | AI-powered customer-support platform                                                                                  |

---

# 📊 Machine Learning

My ML work covers **data preparation, feature engineering, model training, hyperparameter tuning, cross-validation, ensemble learning, evaluation, experiment management, and resource-aware model training**.

I also work with **Kaggle datasets and competition-style workflows**, including experimentation across multiple algorithms and evaluation strategies.

| Project                                                                                      | Focus                                                                  |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| **[evaluate-classification-ml](https://github.com/BELBINBENORM/evaluate-classification-ml)** | Automated training and evaluation across 30+ classification algorithms |
| **[evaluate-regression-ml](https://github.com/BELBINBENORM/evaluate-regression-ml)**         | Automated regression training, evaluation and model persistence        |
| **[safe-stack-ml](https://github.com/BELBINBENORM/safe-stack-ml)**                           | Stacking ensembles, OOF predictions and resource-aware training        |
| **[vortex-kfold-engine](https://github.com/BELBINBENORM/vortex-kfold-engine)**               | Cross-validation and experiment persistence                            |
| **[vortex-intelligence-suite](https://github.com/BELBINBENORM/vortex-intelligence-suite)**   | Feature profiling and model-based feature analysis                     |
| **[mission-control-ml](https://github.com/BELBINBENORM/mission-control-ml)**                 | ML training, Optuna optimization, ETL and long-running task execution  |
| **[modelblocks-ml-mvp-](https://github.com/BELBINBENORM/modelblocks-ml-mvp-)**               | Modular ML platform with FastAPI and trainer plugins                   |


---

# 🌍 Data Engineering & Datasets

I build **automated data pipelines and continuously updated datasets**, including data collection, transformation, validation, publishing, and scheduled updates.

| Project                                                                                                                                  | Focus                                                                           |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **[Scraper-Global-Mental-Health-Crisis-Tracker](https://github.com/BELBINBENORM/Scraper-Global-Mental-Health-Crisis-Tracker)**           | Longitudinal cross-country dataset with automated updates and Kaggle publishing |
| **[Scraper-Global-Sovereign-Debt-Crisis-Monitor](https://github.com/BELBINBENORM/Scraper-Global-Sovereign-Debt-Crisis-Monitor)**         | Automated sovereign-debt data tracking                                          |
| **[Scraper-BRICS-Expansion-De-Dollarization-Tracker](https://github.com/BELBINBENORM/Scraper-BRICS-Expansion-De-Dollarization-Tracker)** | Automated BRICS and de-dollarization data tracking                              |
| **[food-price-dataset](https://github.com/BELBINBENORM/food-price-dataset)**                                                             | Auto-updating food-security dataset using public economic and agricultural data |

---

# 🛠️ Technical Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,postgres,docker,git,github" />

### Machine Learning

`Scikit-learn` · `XGBoost` · `LightGBM` · `CatBoost` · `Optuna` · `SHAP`

### Generative AI

`RAG` · `pgvector` · `Embeddings` · `LLM Agents` · `MCP` · `Google Gemini`

### Backend & Data

`FastAPI` · `PostgreSQL` · `Redis` · `Pandas` · `NumPy`

### Data & Analytics

`ETL` · `Data Pipelines` · `Kaggle` · `Power BI` · `Tableau`

### Engineering

`Docker` · `Git` · `GitHub Actions` · `Pytest` · `CI/CD`

</div>

---

# 🎓 Background

### B.E. Computer Science & Engineering

**Anna University** · CGPA 8.53

### PGP Data Analytics & Data Science

**Skill-Lync**

### Quantitative Analyst

**Adroit Design India Pvt Ltd**

Resource planning, cost estimation, and KPI reporting.

---

# 📌 What I Work On

```text
Machine Learning
    ├── Model Training
    ├── Hyperparameter Tuning
    ├── Ensemble Learning
    ├── Cross-Validation
    └── Model Evaluation

Generative AI
    ├── RAG
    ├── LLM Agents
    ├── MCP
    ├── Memory
    └── AI Security

Data Engineering
    ├── Data Collection
    ├── ETL Pipelines
    ├── Dataset Automation
    └── Data Publishing

Software Engineering
    ├── FastAPI
    ├── PostgreSQL
    ├── Redis
    ├── Docker
    ├── Testing
    └── CI/CD
```

---

<div align="center">

### Let's Connect

**[Portfolio](https://belbin-beno-rm-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/belbino/) · [Kaggle](https://www.kaggle.com/belbino) · [LeetCode](https://leetcode.com/u/belbinbenorm2002/) · [HackerRank](https://www.hackerrank.com/profile/belbinbenorm2002/)**

</div>
