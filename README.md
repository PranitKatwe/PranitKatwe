<p align="center">
  <img src="assets/header.svg" alt="Pranit Katwe — Data Science × AI Engineer. Noise in, signal out." width="100%" />
</p>

<p align="center">
  <a href="https://pranitkatwe.vercel.app/"><code>portfolio</code></a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/pranit-katwe"><code>linkedin</code></a>
  &nbsp;·&nbsp;
  <a href="mailto:pranitskatwe@gmail.com"><code>email</code></a>
</p>

## 📋 Model Card

| | |
|---|---|
| **Base architecture** | Human · MS in Data Science, University of Colorado Boulder |
| **Current deployment** | AI Intern @ ExodusPoint Capital Management · New York, NY |
| **Fine-tuning history** | Goodie Bag Food Co. (production multi-agent systems) · mHealth Impact Lab (health data platforms) · CU Boulder (Head TA, 4 grad ML/NLP courses) |
| **Pretraining corpus** | 2+ years of ML systems, financial ETL pipelines, and AI agents |
| **Currently training on** | AI agents · MCP · A2A · AWS infrastructure |
| **Intended use** | Full-time Data Science / ML / AI Engineering roles |

## 🛠️ Capabilities

```yaml
tool_use:
  agents:      [LangGraph, CrewAI, MCP, LangChain, RAG + FAISS, LangSmith, Bedrock, Vertex AI]
  ml:          [PyTorch, TensorFlow, XGBoost, LightGBM, scikit-learn, TabTransformer]
  data:        [Snowflake, Kafka, Spark, Airflow, PostgreSQL, MongoDB, Redis, pandas]
  backend:     [FastAPI, Flask, Django, Docker, Kubernetes, AWS, GCP]
  statistics:  [hypothesis testing, A/B testing, causal inference, time series, ANOVA]
  languages:   [Python, SQL, R, JavaScript]
```

## 📊 Evals

*All benchmarks verified on real production workloads — no synthetic data.*

| Benchmark | Score |
|---|---|
| Vendor replaced with in-house pipeline | **~$120K/yr saved** |
| Vendor Excel formats parsed into one Snowflake schema | **68 formats, 20+ institutions** |
| Multi-agent system shipped to production | **5 domain agents, 25% token savings** via MoE intent router |
| Duplicates after 3-level dedup design (SHA-256 + Message ID + 7-column key) | **0** |
| SBA loan stacked-ensemble accuracy | **87%** across 4 loan types |
| Grad students survived my grading | **200+ mentored** |

## 🚀 Deployed Instances

| Instance | Description | Stack |
|---|---|---|
| **[Filing-Delta Event Signal](https://github.com/PranitKatwe/equity-filing-delta)** · [live](https://equity-filing-delta.vercel.app/) | Point-in-time event study: do changes in SEC 10-K risk-factor text predict abnormal returns? 480 S&P 500 companies, 4,705 filings, strict no-lookahead design, grounded LLM narrator. Honest verdict: real but weak, dies after costs. *"The chart goes nowhere. That's the point."* | Python · statsmodels · SEC EDGAR · Claude API · Vercel |
| **[Repo Oracle](https://github.com/PranitKatwe/repo-oracle)** | 6-tool MCP server letting LLMs query GitHub repos inside Cursor IDE — PR risk detection, recursive tree scanner, ~40% fewer redundant API calls. Built at Cursor Hackathon Denver 2025. | Python · FastMCP · GitHub API |
| **[DocSumAI](https://github.com/PranitKatwe/DocSumAI-LLM-Powered-Summary)** | Cloud LLM document summarization — PDF/DOCX/TXT, 10K+ word docs via token-safe chunking, response time cut 10s → 6s. | Flask · GCP Pub/Sub · BART · GPT-4o · Docker |
| **[SBA Loan Eligibility](https://github.com/PranitKatwe/ai-driven-sba-loan-eligibility-system)** | Stacked ensemble with 30%+ minority-class recall improvement and SHAP/LIME explainability. | XGBoost · LightGBM · TabTransformer · SHAP |
| **[Ray — open source contrib](https://github.com/PranitKatwe/ray)** | Resolved `ArrowNotImplementedError` enabling PyArrow compatibility in Ray Datasets; duplicate-removal API used in large-scale ML preprocessing. | Python · PyArrow · Distributed Computing |

<details>
<summary>Earlier checkpoints</summary>
<br/>

- **[UniPredict — Admission Analytics](https://github.com/PranitKatwe/UniPredict-Admission-Analytics)** — 7 GLMs compared via MSPE (R²=0.80); CGPA (r=0.72) and LOR top predictors
- **[ShopTalk — E-commerce Sentiment](https://github.com/PranitKatwe/ShopTalk-E-commerce-Sentiment-Analysis)** — 23K+ reviews, LR vs SVM benchmark, 95% accuracy
- **[Breast Cancer Neural Classifier](https://github.com/PranitKatwe/Breast-Cancer-Neural-Classifier)** — neural classification on diagnostic data
- **[SteamPlay Recommender](https://github.com/PranitKatwe/ML-Project)** — game recommendation system
- **[ElectroMobility Dashboard](https://github.com/PranitKatwe/ElectroMobility-Dashboard-)** — Power BI, 7 years of EV adoption across 300+ U.S. counties

</details>

## ⚠️ Known Limitations

- Replies too fast. It's a problem.
- Will replace your $10K/month vendor with a Python script if left unsupervised.
- Once ran 3 training jobs in parallel — GPU at 100%, VRAM exhausted, no regrets.
- Runs exclusively on black coffee, no sugar. This parameter is frozen.

## 🔌 API Access

**Endpoint:** [pranitskatwe@gmail.com](mailto:pranitskatwe@gmail.com) · **Docs:** [pranitkatwe.vercel.app](https://pranitkatwe.vercel.app/) · **Changelog:** [My Learning Vault](https://sites.google.com/view/pranit-katwe/professional-background) · **Archived talks:** [@nerdcast_nerdcasm](https://www.youtube.com/@nerdcast_nerdcasm)

*Rate limits: none. Latency: low. See Known Limitations.*
