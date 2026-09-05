# Karnav Bhattacharya

Undergraduate @ IIT Patna  
Machine Learning Engineer focused on building real-world ML systems

---

## About Me

I build and deploy machine learning systems with a focus on **inference, multimodal pipelines, and real-world applications**.

My work sits at the intersection of:
- Computer Vision
- Multimodal AI
- Model Serving & Inference Optimization
- Agent-based Systems

I’m particularly interested in treating ML as an **engineering discipline** — optimizing systems for latency, scalability, and reliability rather than just training models.

---

## Selected Work

### 🔍 Multimodal Search Engine — Image Retrieval with Cross-Encoder Reranking

- Built a multimodal image retrieval system searching 400K Amazon product images using text or image queries, with cross-encoder reranking to improve retrieval quality
- Designed a TREC-style pooled evaluation pipeline with automated graded relevance judging, benchmarked across 1,270 queries using MAP, MRR, Precision@K, and nDCG
- Improved retrieval quality over the CLIP baseline by **+0.040 MAP**, **+0.042 MRR**, and **+0.070 nDCG@5**
- Benchmarked the accuracy–latency trade-off introduced by cross-encoder reranking

👉 Repo: <https://github.com/Karnav-Bhattacharya/Multimodal-Image-Retrieval-with-Cross-Encoder-Reranking>

---

### 🔍 Eagleye: InterIIT Tech 14th Edition Project
- Built an end-to-end pipeline combining **Gemma-3-27B (VLM) + YOLO + BLIP**
- Designed for **remote sensing / satellite imagery**
- Implemented **LangGraph-based orchestration**
- Deployed using **FastAPI**
- Focus: model routing, multimodal reasoning, inference coordination

👉 Repo: <https://github.com/Karnav-Bhattacharya/eagleye_backend>

---

### 📊 InSightAI — Agentic KPI Investigation & Recommendation Engine

- Built a multi-stage agentic pipeline that detects commercially material KPI movements, investigates root causes across structured and unstructured data, and generates evidence-grounded recommendations
- Designed a deterministic anomaly-detection layer (rolling z-scores + revenue-materiality thresholds) to keep the "is this actually wrong" decision fully auditable and LLM-free
- Fine-tuned SLM **Gemma-2-2B** for batched, record-level signal extraction from unstructured business text (tickets, reviews, social)
- Orchestrated an **Investigation Agent + Recommendation Agent** (Qwen3-4B) with deterministic evidence retrieval and strict JSON-schema validation at every stage
- Deployed the whole solution using python-fastapi backend on netlify
- Evaluated against a synthetic dataset with 8 engineered ground-truth causal scenarios to test hypothesis accuracy and abstention behavior

👉 Repo: <https://github.com/Karnav-Bhattacharya/InSightAI>

---

## Technical Interests

- ⚙️ Model Serving & Inference Optimization
- 📦 Quantization (4-bit, FP8, etc.)
- 🚀 Low-latency ML systems
- 🧠 Multimodal reasoning systems
- 🔗 Agent systems

---

## Tech Stack

**Languages:** Python, SQL  
**ML:** PyTorch, Transformers, Computer Vision, Generative Models  
---

## Contact

- 📧 bhattacharyakarnav@gmail.com  
- 🔗 www.linkedin.com/in/karnav-bhattacharya-5b2459288 
- 💻 [https://github.com/Karnav-Bhattacharya](https://github.com/Karnav-Bhattacharya/)
