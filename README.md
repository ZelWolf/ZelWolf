
# Hi, I'm Ananay  👋

**AI/ML Engineer** · LLM security, RAG pipelines, and transformer models

I build AI systems that are measurable and production-minded: services with clear architecture, reproducible benchmarks, and honest error analysis.

---

## Featured Project


### [AI Trust Gateway (Sentinel)](https://github.com/ZelWolf/ai-trust-gateway)
*A policy-aware security gateway that inspects, redacts, and blocks risky prompts before they reach an LLM.*


A dual-layer middleware between applications and LLM providers:

- **Layer 1, deterministic:** PII detection (Microsoft Presidio) and regex-based secret detection, with redaction or early blocking. Average latency **17.9 ms**.
- **Layer 2, semantic:** intent classification, policy retrieval from a ChromaDB knowledge base (RAG), and a LangGraph workflow with an LLM-as-a-Judge (Groq). Malicious requests are stopped at the gateway, so no downstream LLM tokens are spent.
- **Observability:** Streamlit SOC dashboard with audit logs, P50/P95 latency, and "LLM calls avoided" metrics.
- **Benchmarked** against PromptGuard2 and OSS Safeguard in a built-in comparison arena.

**Results on a 150-case adversarial suite** (114 attacks, 36 benign):

| Metric | Value |
|--------|-------|
| Decision accuracy | 96.67% |
| Threat block rate | 97.37% (111/114) |
| False positive rate | 5.56% (2/36) |
| False negative rate | 2.63% (3/114) |

**Stack:** Python · FastAPI · Pydantic · LangChain · LangGraph · ChromaDB · FastEmbed · Presidio · spaCy · Groq · Streamlit · SQLAlchemy · Docker

---

## Secondary Project

### [SentimentScope](https://github.com/ZelWolf/movie_sentiment_analysis)
*A transformer built from scratch in PyTorch for sentiment classification.*

- Implemented attention heads, multi-head attention, feed-forward layers, and transformer blocks from first principles
- Adapted a GPT-style architecture for classification with mean pooling and a linear head; BERT subword tokenizer
- **75.90% test accuracy** on 25,000 IMDB reviews (~4.7M parameters, 3 epochs)

**Stack:** Python · PyTorch · Hugging Face Transformers · Pandas

---

## Technical Skills

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
