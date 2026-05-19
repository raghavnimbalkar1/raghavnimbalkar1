# Raghav Nimbalkar

**Systems · AI Research · Game Engineering**

I build things at the intersection of low-level systems and applied intelligence — from real-time shader pipelines to agentic graph-based reasoning systems. Currently pursuing M.Tech in Data Science.

---

## Work

**Agentic GraphRAG for Root Cause Analysis** &nbsp;·&nbsp; *In Progress*  
Graph-structured retrieval and skill-graph reasoning over cascading failure traces in large-scale cloud microservices. Built on LangChain and LangGraph. Targeting autonomous, explainable RCA without human-in-the-loop triage.

**[Screenplay GPT-2 Fine-Tuning Study](https://github.com/raghavnimbalkar1/screenplay-gpt2-finetuning-study)**  
Comparative study of full-parameter fine-tuning vs. LoRA adaptation for structured creative text generation using GPT-2 Small (124M). Trained across AMD DirectML, Apple Silicon, and NVIDIA T4 (CUDA) backends. Includes a stateful checkpoint recovery from a mid-run hardware preemption at step 5,600/9,272 — resumed with zero loss discontinuity. Both fine-tuned model weights published to Hugging Face Hub. Final validation loss: **1.3194**.

**StudyBuddy — Local RAG Assistant**  
Fully offline retrieval-augmented generation over personal document corpora (PDF/PPT). SentenceTransformers for embeddings, FAISS for vector search, Llama 8B via LM Studio for inference. Zero cloud dependency; citation-grounded answers with source chunk attribution.

**Multi-Class News Classification**  
End-to-end NLP pipeline classifying articles across 42 categories (LinearSVC) and 13 consolidated super-categories (LinearSVC + XGBoost). Modular 4-stage architecture: scraping → preprocessing → training → analytics. Ships with an interactive Streamlit dashboard supporting live URL scraping, batch CSV processing, and per-category confusion matrix visualization.

**Live Win Probability Engine**  
Real-time Bundesliga match prediction via Monte Carlo simulation over Poisson-distributed Elo ratings. FastAPI backend with WebSocket delivery of mid-match probability updates. MySQL persistence, Redis caching with mock fallback, and full SQLAlchemy ORM layer.

---

## Technical Profile

```
Languages        C · C++ · C# · Python · GLSL
Graphics         OpenGL · GLSL Shader Development · Pixel Art Pipeline
AI / ML          LangChain · LangGraph · FAISS · HuggingFace Transformers
                 Fine-tuning (Full + LoRA/PEFT) · RAG · Graph Neural Reasoning
ML Ops           Checkpoint Recovery · Mixed Precision (FP16) · Multi-backend Training
Backend          FastAPI · WebSockets · SQLAlchemy · Redis · MySQL
```

---

## Published

Two fine-tuned models on Hugging Face — GPT-2 Small adapted for screenplay generation, trained across multiple hardware backends with full training telemetry documented.  
→ [huggingface.co/raghavnimbalkar1](https://huggingface.co/raghavnimbalkar)

---

## Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=raghavnimbalkar1&show_icons=true&hide_title=true&hide_border=true&count_private=true&theme=default&hide=stars)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=raghavnimbalkar1&layout=compact&hide_border=true&theme=default&langs_count=6)

---

## Currently

Designing procedural shaders and pixel art pipelines for a retro-aesthetic game project &nbsp;·&nbsp; Researching agentic graph traversal for fault localization in distributed systems &nbsp;·&nbsp; Learning OpenGL internals at the pipeline level

---

[LinkedIn](https://linkedin.com/in/raghavnimbalkar) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/raghavnimbalkar) &nbsp;·&nbsp; [Email](mailto:raghav.nimbalkar1010@gmail.com)
