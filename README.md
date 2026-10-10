
# Hi, I'm **Ananay**👋 

```bash
Online alias: ZelWolf
Zeal in pursuit, a wolf by nature.
```
**AI/ML Engineer** · LLM security, RAG pipelines, and transformer models

I build AI systems that are measurable and production-minded: services with clear architecture, reproducible benchmarks, and honest error analysis.

---

## Featured Project


### [Sentinel AI Trust Gateway](https://github.com/ZelWolf/ai-trust-gateway)
*A policy-aware security gateway that inspects, redacts, and blocks risky prompts before they reach an LLM.*


A dual-layer middleware between applications and LLM providers:

- **Layer 1, deterministic:** PII detection (Microsoft Presidio) and regex-based secret detection, with redaction or early blocking.
- **Layer 2, semantic:** intent classification, policy retrieval from a ChromaDB knowledge base (RAG), and a LangGraph workflow with an LLM-as-a-Judge. Malicious requests are stopped at the gateway, so no downstream LLM tokens are spent.
- **Observability:** Streamlit SOC dashboard with audit logs, P50/P95 latency, and "LLM calls avoided" metrics.

**Stack:** Python · FastAPI · Pydantic · LangChain · LangGraph · ChromaDB · FastEmbed · Presidio · spaCy · Groq · Streamlit · SQLAlchemy · Docker

---

## Secondary Project

### [SentimentScope](https://github.com/ZelWolf/movie_sentiment_analysis)
*A transformer built from scratch in PyTorch for sentiment classification.*

- Implemented attention heads, multi-head attention, feed-forward layers, and transformer blocks from first principles
- Adapted a GPT-style architecture for classification with mean pooling and a linear head; BERT subword tokenizer

**Stack:** Python · PyTorch · Hugging Face Transformers · Pandas

---

## What I work with ?

| Area | Tools |
|------|-------|
| Language | Python, SQL, Bash |
| LLM & RAG | LangChain, LangGraph, ChromaDB, FastEmbed, Groq API |
| Deep Learning | PyTorch, Hugging Face Transformers |
| Backend & Deployment | FastAPI, Pydantic, Uvicorn, Docker, SQLAlchemy |
| Security & NLP | Microsoft Presidio, spaCy |
| Data & Dashboards | Pandas, NumPy, Streamlit, Altair |
| Cloud | Microsoft Azure
## Connect

- LinkedIn: [in/ananaychaudhry](https://www.linkedin.com/in/ananaychaudhry)
- GitHub: [@ZelWolf](https://github.com/ZelWolf)
