# Debashis Mondal

Software Engineer specializing in LLM systems, agentic AI, and applied ML/MLOps — building production systems that take language models from prototype to reliable, high-throughput serving.

**Software Engineer L2 at Keross Research and Development**, Kolkata — production LLM agents, fine-tuning, and inference serving.

<p align="center">
  <a href="https://linkedin.com/in/idebashismondal/"><img src="https://cdn.simpleicons.org/linkedin/0A66C2" width="48" height="48" alt="LinkedIn" /></a>&nbsp;&nbsp;
  <a href="mailto:debashismondal205@outlook.com"><img src="https://cdn.simpleicons.org/microsoftoutlook/0078D4" width="48" height="48" alt="Outlook" /></a>&nbsp;&nbsp;
  <a href="https://github.com/debash1sM"><img src="https://cdn.simpleicons.org/github/181717" width="48" height="48" alt="GitHub" /></a>
</p>

## What I work on

- **Agentic AI** — multi-step agent architectures (plan-execute-verify) with deterministic verification for compound, multi-part requests.
- **LLM fine-tuning & serving** — QLoRA/LoRA fine-tuning and vLLM deployments with hot-swappable adapters for high-throughput inference.
- **RAG** — standard, iterative-rewrite, agentic/router-based, web-augmented, and self-verifying RAG pipelines with vector stores like Qdrant.
- **MLOps & backend** — MLflow/DVC pipelines, FastAPI microservices, and advanced SQL/DBMS across MySQL and Cassandra.

## Highlighted work

**Production LLM agent redesign** — Rebuilt a sequential tool-calling agent into a plan-execute-verify architecture, then root-caused four bugs in the merge-to-GGUF pipeline and moved deployment to vLLM with hot-swappable LoRA adapters — roughly a 20x throughput gain (35 to 740 tokens/sec).

**QLoRA fine-tuning at production scale** — Fine-tuned Qwen3-8B via QLoRA (4-bit NF4) on 339 production-trace examples, raising spec accuracy from an 83% prompted baseline to 100%.

**Autonomous HVAC control system** — Built a supervisory MPC system setting HVAC scheduling and setpoints from real-time occupancy data, cutting chilled water consumption 35% month-on-month and costs by AED 10,000/month.

## Featured projects

**[Clarity — Self-Verifying RAG Chatbot](https://github.com/debash1sM/clarity-self-rag)** — A self-RAG chatbot (FastAPI + LangGraph) that answers from uploaded PDFs, checks its own answers for grounding and usefulness, revises or retries when they fall short, and falls back to live web search only when the documents lack the answer. Includes a live pipeline trace UI and PDF upload/re-indexing.

**[Papeer — Research Paper Assistant](https://github.com/debash1sM)** — A RAG application for querying academic papers via chat, with a LangGraph router directing queries across four paths (direct answer, retrieval with iterative rewriting, web search, ArXiv claim verification), session-isolated Qdrant collections, and a DeepEval evaluation pipeline.

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML/DL, Fine-Tuning & Serving**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT%20(LoRA%2FQLoRA)-4B5563?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-4B5563?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-4B5563?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Agentic AI & RAG**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-4B5563?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-4B5563?style=flat-square)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**MLOps**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)

**Data & Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![uv](https://img.shields.io/badge/uv-4B5563?style=flat-square)

## Education

MCA, Academy of Technology, Maulana Abul Kalam Azad University of Technology — CGPA 9.70/10
