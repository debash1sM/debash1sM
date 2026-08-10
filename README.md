
# Debashis Mondal

Software Engineer specializing in LLM systems, agentic AI, and applied ML/MLOps. I build production systems that take language models from prototype to reliably serving at scale — fine-tuning, deployment, retrieval, and the infrastructure around them.

Currently a **Software Engineer L2 at Keross Research and Development**, Kolkata, working on production LLM agents, model fine-tuning, and high-throughput inference serving.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/idebashismondal/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:debashis.deep205@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/debash1sM)

## What I work on

- **Agentic AI systems** — designing multi-step agent architectures (plan-execute-verify style) with deterministic verification, moving beyond simple sequential tool-calling loops to handle compound, multi-part requests reliably.
- **LLM fine-tuning & serving** — QLoRA/LoRA fine-tuning on production trace data, GGUF conversion pipelines, and vLLM deployments with hot-swappable adapters for high-throughput, low-latency inference.
- **Retrieval-Augmented Generation** — experience across RAG patterns: standard retrieval, iterative query rewriting, agentic/router-based RAG, web-augmented retrieval, and claim verification pipelines, using vector stores like Qdrant.
- **MLOps** — experiment tracking and model registry with MLflow, dataset versioning with DVC, and observability with Langfuse/LangSmith.
- **Backend & data systems** — FastAPI microservices, advanced SQL/DBMS design, and both relational (MySQL) and NoSQL (Cassandra) systems in production.

## Highlighted work

**Production LLM agent redesign** — Rebuilt a sequential tool-calling agent into a plan-execute-verify architecture with deterministic verification, fixing failures on compound multi-part requests.

**QLoRA fine-tuning at production scale** — Fine-tuned Qwen3-8B via QLoRA (4-bit NF4) on 339 production-trace examples, raising spec accuracy from an 83% prompted baseline to 100%.

**Inference throughput scaling** — Root-caused four bugs in a merge-to-GGUF pipeline that were costing 46 points of accuracy, then redesigned deployment around vLLM with hot-swappable LoRA adapters — roughly a 20x throughput gain (35 to 740 tokens/sec) via continuous batching.

**Autonomous HVAC control system** — Engineered a supervisory Model Predictive Control (MPC) system that set HVAC scheduling and setpoints from real-time occupancy data, cutting chilled water consumption by 35% month-on-month and reducing operating costs by AED 10,000/month.

## Featured projects

**[Papeer — Research Paper Assistant](https://github.com/debash1sM)** — A RAG application for querying academic papers via natural language chat. Built with a LangGraph workflow and an LLM router directing queries across four paths (direct answer, retrieval with iterative rewriting, web search, ArXiv claim verification), session-isolated Qdrant collections, embedding caching, and a DeepEval evaluation pipeline.

**Movie Review Sentiment Analysis** — Sentiment classification system comparing LSTM, GRU, Bidirectional, and Ensemble RNN architectures in a modular MVC-style design, with Keras Tuner (Bayesian optimization) for hyperparameter search and MLflow for experiment tracking, deployed via Streamlit.

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML/DL & Fine-Tuning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT%20(LoRA%2FQLoRA)-4B5563?style=flat-square)
![bitsandbytes](https://img.shields.io/badge/bitsandbytes-4B5563?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-4B5563?style=flat-square)
![Keras Tuner](https://img.shields.io/badge/Keras%20Tuner-D00000?style=flat-square&logo=keras&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

**LLM Serving & Observability**

![vLLM](https://img.shields.io/badge/vLLM-4B5563?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-4B5563?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-4B5563?style=flat-square)

**Agentic AI & RAG**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20API%20Integration-4B5563?style=flat-square)

**MLOps**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![Experiment Tracking](https://img.shields.io/badge/Experiment%20Tracking-4B5563?style=flat-square)
![Model Registry](https://img.shields.io/badge/Model%20Registry-4B5563?style=flat-square)

**Data & Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Advanced SQL/DBMS](https://img.shields.io/badge/Advanced%20SQL%2FDBMS-4B5563?style=flat-square)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![uv](https://img.shields.io/badge/uv-4B5563?style=flat-square)

## Education

Master of Computer Applications (MCA), Academy of Technology, Maulana Abul Kalam Azad University of Technology — CGPA 9.70/10

## Connect

- LinkedIn: [linkedin.com/in/idebashismondal](https://linkedin.com/in/idebashismondal/)
- Email: debashis.deep205@gmail.com
