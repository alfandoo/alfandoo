<div align="center">

# Hi, I'm Alfando 👋

### 🤖 IBM-Certified AI Engineer | Generative AI & Multi-Agent Systems
**Specialized in Production-Ready RAG, Agentic Workflows (LangGraph), and LLM Evaluation Pipelines**

Pekanbaru, Riau, Indonesia • [LinkedIn](https://www.linkedin.com/in/alfando1306/) • [Hugging Face](https://huggingface.co/alfando) • [Email](mailto:alfandooo@gmail.com)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alfando1306/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-yellow?style=for-the-badge)](https://huggingface.co/alfando)
[![Email](https://img.shields.io/badge/Email-alfandooo%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alfandooo@gmail.com)
[![Portfolio Live](https://img.shields.io/badge/Live%20Projects-StratAgent-10B981?style=for-the-badge)](https://stratagent.my.id/)

</div>

---

### 🚀 About Me

I am an **IBM-certified AI Engineer** with a strong foundation in building and deploying production-ready Generative AI and end-to-end machine learning applications.

- 🧠 **GenAI & Agents:** Architecting multi-agent workflows using **LangGraph StateGraph**, reflection loops, tool-calling, and closed-loop self-correction.
- 🔍 **Advanced RAG:** Designing hybrid search pipelines (**BM25 + Dense Embeddings**) with **Cross-Encoder reranking**, claim verification, and strict hallucination guardrails.
- ⚙️ **Production & MLOps:** Bridging AI models with resilient backend infrastructure using **FastAPI**, **Docker**, **PostgreSQL**, **Redis**, **Celery**, and LLM observability via **Langfuse**.
- 📊 **Model Explainability & Monitoring:** Calibrated ML models with real-time **SHAP** attributions and feature/prediction drift monitoring.

---

### 🛠️ Technical Arsenal

<table width="100%">
  <tr>
    <td width="25%" valign="top"><b>Generative AI & LLMs</b></td>
    <td>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=chainlink&logoColor=white" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white" />
      <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
      <img src="https://img.shields.io/badge/RAG_Hybrid_Search-4285F4?style=flat-square" />
      <img src="https://img.shields.io/badge/Cross--Encoder_Reranking-00A86B?style=flat-square" />
      <img src="https://img.shields.io/badge/LoRA_Fine--Tuning-8A2BE2?style=flat-square" />
      <img src="https://img.shields.io/badge/Guardrails_%26_Eval-FF5722?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="25%" valign="top"><b>Machine Learning & DL</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
      <img src="https://img.shields.io/badge/XGBoost-15B8A6?style=flat-square" />
      <img src="https://img.shields.io/badge/SHAP_(XAI)-9333EA?style=flat-square" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="25%" valign="top"><b>Backend & Vector DBs</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square" />
      <img src="https://img.shields.io/badge/Upstash_Vector-00E599?style=flat-square&logo=upstash&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="25%" valign="top"><b>MLOps & Observability</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
      <img src="https://img.shields.io/badge/Langfuse_(LLM_Tracing)-0284C7?style=flat-square" />
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
      <img src="https://img.shields.io/badge/Drift_Monitoring-E11D48?style=flat-square" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
</table>

---

### 🌟 Featured AI Engineering Projects

| Project | Highlights & Architecture | Links |
| :--- | :--- | :---: |
| **StratAgent**<br/>*Autonomous Multi-Agent Market Research* | • Orchestrated 4 specialized agents (Planner, Researcher, Fact-Checker, Writer) using **LangGraph StateGraph**.<br/>• Closed-loop self-correction scoring evidence confidence, triggering re-queries when scores fall below 80%.<br/>• Multi-provider search fallback (Google Grounding → Tavily → DuckDuckGo) + ChromaDB vector store.<br/>• FastAPI SSE real-time streaming, topic guardrails, and self-hosted **Langfuse** tracing. | [🌐 Live Demo](https://stratagent.my.id/)<br/>[💻 GitHub](https://github.com/alfandoo/rag-agentic-ai) |
| **KerjaPedia AI**<br/>*Production RAG for Labor Regulations* | • Enterprise RAG assistant for Indonesian labor laws with **Hybrid Retrieval (BM25 + Dense)** and **Cross-Encoder reranking**.<br/>• Automated RAG evaluation & guardrails: claim-support verification, refusal handling, and exact article citations.<br/>• Asynchronous ingestion pipeline via FastAPI, Redis, and Celery backed by Upstash Vector & PostgreSQL.<br/>• CI/CD testing via GitHub Actions & Pytest with model latency and token monitoring. | [🌐 Live Demo](https://kerjapedia-ai.vercel.app/)<br/>[💻 GitHub](https://github.com/alfandoo/kerjapedia-ai) |
| **Attrition Prediction Intelligence**<br/>*Real-Time ML Service & Monitoring* | • End-to-end ML inference service deployed on **Hugging Face Spaces** with interactive React UI.<br/>• Calibrated classification model (ROC-AUC **0.825**, Recall **0.70**) tuned to minimize false negatives on high-risk employee departures.<br/>• Integrated **SHAP (Explainable AI)** for real-time local/global feature attributions.<br/>• Baseline drift monitoring to detect feature/prediction distribution shifts post-deployment. | [🤗 Space](https://huggingface.co/spaces/alfando/attrition-prediction-intelligence)<br/>[💻 GitHub](https://github.com/alfandoo/attrition-prediction-intelligence) |

---

### 📜 Certifications & Education

- 🎓 **IBM AI Engineering Professional Certificate** — IBM / Coursera
  - 13-course specialization covering Machine Learning, Deep Learning (PyTorch, TensorFlow), Generative AI, LLM Fine-Tuning (LoRA), RAG, and AI Agents with LangChain.
- 🎓 **Bachelor of Computer Science (S.Kom) - Informatics Engineering** — Universitas Muhammadiyah Riau (Graduated Mar 2024)
  - Major GPA: **3.62 / 4.00**
  - Thesis: *Deep Learning for Multi-Label Classification*

---

<div align="center">
  <sub>Designed & engineered with precision by Alfando. Open for full-time AI Engineer & LLM Engineer roles.</sub>
</div>
