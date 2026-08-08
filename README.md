# Hi, I'm Stefano 👋

Data/AI Engineer in training, focused on turning raw data and AI services into working, production-shaped systems. I build end-to-end integrations — not just notebooks.

Lately: **retrieval-augmented systems that have to be right, not just fluent** — grounded answers with checkable citations, refusal when the data doesn't support an answer, and measured cost.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure AI](https://img.shields.io/badge/Azure%20AI-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![mypy](https://img.shields.io/badge/mypy%20--strict-1E4B7A?style=for-the-badge&logo=python&logoColor=white)

## 🔎 What I work on

**RAG & retrieval** — hybrid BM25 + dense vector search with reciprocal rank fusion, chunking strategies for mixed structured/unstructured corpora, entity resolution, recall measured against a gold set rather than assumed.

**LLM engineering** — constrained decoding and forced tool use for reliable routing, prompt design as a last resort rather than a first one, running the same application against a local open-source model *and* a hosted one behind a single interface.

**Trustworthy output** — citation validation, deterministic conflict detection between disagreeing sources, prompt-injection containment, and refusal behaviour enforced in code, because a control the model can decline to apply is not a control.

**Evaluation & cost** — answer-level harnesses that score structural properties instead of prose, and enforced spend ceilings checked before the call rather than reported after it.

## 📊 Currently working on

- [**local-aws-crm-assistant**](https://github.com/stegossauro/local-aws-crm-assistant) — grounded RAG assistant over CRM data, running on **a local Qwen2.5-7B or Claude Haiku 4.5 on AWS Bedrock** from one codebase. Hybrid BM25+FAISS retrieval (90% recall@8), deterministic conflict detection and injection containment, enforced spend ceiling, 178 tests, answer-level evaluation across 9 question categories. **€0.37 of AWS to build and evaluate the whole thing.**
- [**multiagent-online-store-manager**](https://github.com/stegossauro/multiagent-online-store-manager) — multi-agent online store on Azure AI Foundry: shop assistant with 13 connected agents plus a 6-agent marketing campaign pipeline
- [**intelligent-order-intake-pipeline**](https://github.com/stegossauro/intelligent-order-intake-pipeline) — document intelligence and hybrid multi-agent order processing
- [**id-document-webcam-recognition**](https://github.com/stegossauro/id-document-webcam-recognition) — real-time identity verification pipeline (face detection + OCR/Document Intelligence + voice confirmation)
- [**ai-content-moderation-sartoria**](https://github.com/stegossauro/ai-content-moderation-sartoria) — multilingual chatbot with dual-layer LLM + Azure content moderation
- [**agent-games-foundry**](https://github.com/stegossauro/agent-games-foundry) — Azure AI Foundry agent with structured JSON-Lines output for agent-to-agent piping
- [**Economic Growth Through the Lens of Data Science**](#) — *(bachelor's thesis — publish this repo before linking it live)*

## 🎓 Background

Statistical modeling & ML (numpy, pandas, scikit-learn, statsmodels) applied to economic forecasting, now moving into applied AI engineering across the Azure and AWS AI stacks.

## 📫 Connect

[LinkedIn](https://www.linkedin.com/in/stefanocaronti)
