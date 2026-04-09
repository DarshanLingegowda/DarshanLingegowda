# Darshan Linge Gowda

### AI/ML Engineer · Agentic Systems · LLMOps · RAG & Retrieval · Production ML

I build production-grade LLM-powered agents, multi-agent pipelines, and RAG systems — deployed on cloud infrastructure, evaluated rigorously, and built to hold up under real conditions.

Four years of deliberate investment in applied AI: freelance production work, structured academic programmes (MIT-IDSS, HarvardX, DataCamp), and competitive hackathon builds — bridging enterprise engineering discipline from Germany with frontier AI research.

M.Sc. thesis on large-scale geospatial data processing adopted into **live production at FusionSystems GmbH for the Galileo Map Service**.

---

## Core Skills

**Agentic AI** — Multi-agent orchestration · Tool-use · ReAct pattern · Stateful agents · LangChain · Conversational AI  
**LLMs & GenAI** — OpenAI API · Gemini 2.5 Flash · Prompt engineering · LLMOps · Evaluation design · Fine-tuning concepts  
**RAG & Retrieval** — Semantic search · Vector DBs (Pinecone, FAISS) · Embeddings · Chunking · Hallucination grounding  
**MLOps & Cloud** — GCP · Vertex AI · Cloud Run · Docker · Kubernetes · Cloud Build CI/CD · Datadog · MLflow · AWS · Azure  
**Languages** — Python · C# · ASP.NET Core · Node.js · FastAPI · SQL · JavaScript · PHP · Bash  
**Data & Databases** — MS SQL Server · MongoDB · ETL pipelines · XML schema design · Geospatial data processing  

---

## Hackathons & Competitions

### 🥇 AI Invoice Agent — Conversational Multi-Agent System
**Google Gen AI Academy APAC · Track 1 · 2026**

Full-stack production multi-agent system built end-to-end during the Google Gen AI Academy APAC programme.

- **Agentic pipeline**: React + Vite → Node.js Express orchestration → Gemini 2.5 Flash reasoning layer → persistent storage
- **Multi-agent orchestration**: Invoice creation, payment tracking, and real-time financial analytics via stateful tool calls and session memory
- **LLM reliability engineering**: Diagnosed and resolved a silent model/API version mismatch causing production failures — no crash, just wrong outputs. Traced to orchestration layer, resolved under live load
- **Deployment**: Containerised with Docker · Google Cloud Run · Cloud Build CI/CD
- **Impact**: ~70% faster invoice workflows

---

### 🏆 WorkflowEnv — AI-Powered Workflow Automation Agent
**Scalar Hackathon · 2026**

Agentic workflow engine that interprets natural language intent and autonomously orchestrates multi-step workflows across tools and environments.

- **NL-to-action**: Agent decomposes free-form user instructions into structured multi-step tool call sequences
- **Robust execution**: Maintains environment state · detects tool failures · classifies failure type · retries with corrected parameters
- **Modular design**: Tool registry allows new integrations without modifying core agent logic
- **Reliability pattern**: Production-grade recovery logic — the hardest part isn't the happy path, it's knowing when to retry vs when to stop

---

### AI SRE Copilot — Multimodal LLM Observability
**DEVPOST Hackathon · 2025**

Multimodal agentic system for automated root-cause analysis of production incidents.

- Integrated Datadog metrics, logs, and dashboard screenshots with Vertex AI (Gemini) for AI-driven incident diagnosis
- Designed evaluation metrics to measure AI diagnostic accuracy against ground-truth incidents
- FastAPI service deployed on Cloud Run (serverless)
- Structured AI insights significantly reduced incident investigation time

---

## Projects

### Generative AI Search Agent
*Personal Research Project · 2023–25*

LLM-powered semantic retrieval agent with prompt chaining and contextual memory.

- Embeddings + vector DB for semantic retrieval
- ~40% faster resolution vs keyword search
- Containerised via Docker/CI-CD — production-ready pattern

---

### 3D Elevation Mapping for Digital Maps
*M.Sc. Thesis → Live Production Deployment · TU Chemnitz & FusionSystems GmbH · 2016–17*

Research combining OpenStreetMap and NASA SRTM satellite data via spatial interpolation (IDW) to build a queryable 3D geospatial database — adopted into live production at FusionSystems GmbH for the Galileo Map Service.

- **Pipeline**: OSM PBF + SRTM DEM ingestion → PostgreSQL/PostGIS → IDW spatial interpolation → 3D geometry (LineStringZ, PolygonZ) → GeoServer rendering with custom SLD map tiles
- Full ML lifecycle: data processing → modelling → deployment → monitoring at scale

---

## Professional Background

**Freelance AI/ML Engineer & Researcher** — Independent · Apr 2022–Apr 2026  
AI/ML and data engineering solutions for European clients · RAG systems · Semantic search agents · Multi-agent pipelines

**Full Stack Software Developer** — PICA GmbH · Munich, Germany · 2018–2021  
Enterprise software for BMW (SAP invoice automation · 80% accuracy improvement), Otto Bock (orthopaedic caretaker app), and the Bavarian State Medical Association (nursing training platform)

**Software Developer (Contract)** — AMAN Media GmbH / AAM IT GmbH · Munich · 2018  
Thermomix backend platform for Vorwerk Switzerland · large-scale DB migration · ETL automation · anomaly detection

---

## Education & Certifications

**M.Sc. Information & Communication Systems** — TU Chemnitz, Germany · 2013–2017  
**B.E. Electronics & Communication Engineering** — Visvesvaraya Technological University, India · 2009–2013

| Programme | Year |
|---|---|
| DataCamp — Associate AI Engineer for Developers (LLMOps · OpenAI API · LangChain · Pinecone) | 2025 |
| DataCamp — Developing AI Applications · OpenAI Fundamentals | 2025 |
| HarvardX — CS50 Python | 2024–25 |
| MIT-IDSS — Data Science & Machine Learning | 2022 |
| Kaggle — Generative AI & AI Agents Intensive | 2026 |

---

## Engineering Philosophy

- **Reliability over hype** — production systems fail in ways demos never do
- **Evaluation-first** — if you cannot measure it, you cannot improve it
- **Research to production** — every project runs the full lifecycle
- **Fail fast, recover smarter** — the recovery logic is the hardest and most important part

---

📍 Bangalore, India · Open to relocation  
📫 darshanl1711@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/darshan-linge-gowda)
