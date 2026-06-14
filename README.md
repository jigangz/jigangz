# Jigang (Harry) Zhou

**Backend Software Engineer — LLM / ML systems.**
I build production backends and ML/RAG systems — and I contribute to the open-source **LLM infrastructure that other teams run in production**.

📍 Vancouver, BC · open to Backend / ML / AI-infra SWE roles
🔗 [LinkedIn](https://www.linkedin.com/in/jigangzhou/) · ✉️ zjg0907008@gmail.com

---

## 🛠️ Merged into the LLM stack the industry runs on

Real fixes — reviewed and merged by maintainers — in repos teams run in production:

| Project | PR | What it fixed |
|---|---|---|
| **vLLM** ⭐50k | [#39780](https://github.com/vllm-project/vllm/pull/39780) | Empty `tools` array silently returned HTTP&nbsp;200 → now **400 per OpenAI spec**, so callers catch malformed requests before they reach the model |
| **Microsoft / markitdown** | [#1644](https://github.com/microsoft/markitdown/pull/1644) | **Silent data corruption** in the HTML→Markdown converter used for LLM ingestion — deeply-nested inputs (e.g. SEC EDGAR) returned raw HTML, poisoning downstream context |
| **Dify** | [#34221](https://github.com/langgenius/dify/pull/34221) | Service-API `null` summaries **+ an N+1 query**, fixed with a batch-query helper |
| **dataelement / Clawith** | [#212](https://github.com/dataelement/Clawith/pull/212) | Malformed-LLM-JSON recovery so `write_file` tool calls no longer fail silently |
| **WordPress / Gutenberg** ⭐65k | [#76888](https://github.com/WordPress/gutenberg/pull/76888) | MediaControl blank-label fallback |

…plus merged fixes to **Nautobot**, **astronomer-cosmos**, and **icalendar** — **15+ merged PRs** total.

---

## 🚀 What I build

### [Quant AI](https://github.com/jigangz/quant-ai) · [**live demo →**](https://quant-ai-ui.vercel.app)
A multi-task **financial-ML platform**: direction + volatility + meta-labeling (López de Prado) + cross-sectional learning-to-rank stock selection. 6 model types, Optuna + SHAP, **59 REST endpoints**, distributed on **Kafka + Kubernetes**, 470+ tests. Reports **honest** metrics (Rank IC ~0.05 — "relative ranking has edge where absolute prediction doesn't"), not inflated ones.

### [TrustRAG](https://github.com/jigangz/TrustRAG)
A **trust-scored RAG** system: hybrid retrieval (pgvector + BM25 + RRF), a **LangGraph** multi-hop agent with a trust budget, an **MCP server** (Claude Desktop compatible), and **3 published PyPI packages**.

---

## ⚙️ Stack

`Python` · `TypeScript` · `FastAPI` · `PyTorch` · `XGBoost` · `LangChain` / `LangGraph` · `MCP` · `RAG` · `pgvector` · `Kafka` · `Kubernetes` · `AWS` · `Docker`
