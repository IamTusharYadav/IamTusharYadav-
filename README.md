# Hi, I'm Tushar 👋

**I build agentic LLM and ML systems that are measured, deployed, and cost-guarded in production.**

🎓 M.Sc. Data Science @ Hochschule Fulda (graduating 2027) · TA for Big Data Technologies
🛠️ Previously 3+ years building production Python automation at eClerx (Trainee → Senior Analyst)
📍 Frankfurt region · open to remote across Germany
🔎 **Looking for a Werkstudent role in AI/ML Engineering**

---

## Featured work

### 🗺️ [arxiv-atlas](https://github.com/IamTusharYadav/arxiv-atlas) — **[live](https://atlas.tusharyadav.dev)**
*A living map of AI research, drawn nightly by agents.*
Autonomous multi-agent system on **AWS Bedrock**: nightly ingestion embeds new arXiv papers into a semantic graph (Qdrant); a framework-free agent loop turns them into cited research briefs and interactive topic landscapes.
Serverless (Lambda · API Gateway · DynamoDB) · fail-closed budget guard · golden-set **LLM-judge evals gating CI** · immutable deploys with auto-rollback.

### 🔗 [cross-repo-rag](https://github.com/IamTusharYadav/cross-repo-rag) — **[live](https://crossrepo.tusharyadav.dev)**
Deployed RAG over **two codebases at once** (FastAPI + Qdrant client): hybrid dense+BM25 retrieval, embeddings chosen by A/B test (+19% MRR), 27 tests, CI, Docker on Hetzner.
*Built a reranker, benchmarked it, removed it — the numbers said no.*

### 🏭 [laser-trimming](https://github.com/IamTusharYadav/laser-trimming) — Trustworthy Industrial AI
End-to-end ML on real sensor-manufacturing data per **VDE SPEC 90012**: leakage-guarded pipelines, temporal validation vs honest baselines, audit-logged predictions, model cards & EU AI Act self-assessment. *(University team project — my role in the repo README.)*

---

## How I work

Every project ships with an evaluation harness, documented architecture decisions, and a reproducible setup. If a feature can't justify itself in a benchmark, it doesn't ship.

**Stack:** Python · AWS (Bedrock · Lambda · DynamoDB · SAM) · FastAPI · LangChain · Qdrant / ChromaDB · sentence-transformers · LightGBM · scikit-learn · pandas · PostgreSQL · MongoDB · Docker · GitHub Actions · pytest · Streamlit · TypeScript/React · ONNX

📫 iamtushary@gmail.com · [LinkedIn](https://linkedin.com/in/i-am-tushar-yadav) · [Live demo](https://crossrepo.tusharyadav.dev) · [Live demo](https://atlas.tusharyadav.dev/) 
