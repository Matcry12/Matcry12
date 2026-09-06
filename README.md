<h1 align="center">Hi there, I'm Triet 👋</h1>
<p align="center">
  <b>AI/ML Engineer · LLM Applications & Backend · Competitive Programmer</b><br/>
  <i>I build end-to-end LLM systems — and rigorously benchmark them.</i><br/>
  <sub>Hanoi University of Science and Technology — IT-E7 (Global ICT)</sub>
</p>

---

## 🧠 About Me

I'm an IT student at **HUST** focused on **AI Engineering** — I build end-to-end LLM applications (agentic RAG, multi-stage orchestration, transformer fine-tuning) and back them with **real evaluation**: public benchmarks, ablations, and honest failure analysis, not just demos.

- 🔴 **Live demo:** [Rabbook — Agentic RAG](https://huggingface.co/spaces/Matcry/Rabbook) — try it in your browser
- 🧪 **What sets my work apart:** I measure it — e.g. benchmarking Rabbook on HotpotQA + SQuAD v2 with a human-calibrated LLM judge
- 🌱 **Currently exploring:** multi-agent LLM systems and evaluation harnesses
- 🏆 2nd Place — Provincial Science & Engineering Competition
- 🏅 2nd & 3rd Place — Provincial Algorithmic Programming Competition
- 📄 IELTS 6.0 · Coursework: ML, Deep Learning, DSA, Linear Algebra, Probability

---

## 🚀 Featured Projects

### 📚 [Rabbook — Agentic RAG System](https://github.com/Matcry12/Rabbook) · [🔴 Live Demo](https://huggingface.co/spaces/Matcry/Rabbook)

A production-style **agentic RAG** system: a real tool-use agent loop where the LLM selects tools each turn, plus a deterministic LangGraph variant with grounding gates that block low-evidence answers. A 7-stage retrieval pipeline combines hybrid dense (Chroma) + BM25, Reciprocal Rank Fusion, cross-encoder reranking, and context expansion, and a **self-expanding knowledge base** auto-embeds fetched web pages back into the vector store.

**What sets it apart — it's measured.** Benchmarked on 100 public cases (multi-hop HotpotQA + unanswerable SQuAD v2) via a 3-layer eval suite with a human-calibrated LLM judge; diagnosed bottlenecks and raised multi-hop answer accuracy **64% → 71%** and gold-chunk retrieval **54% → 89%**, while halving hallucination (**~20% → ~10%**) — all on a free local 4.6B model at **$0 inference cost**. 57 mock-based unit tests, Dockerized.

`Python` `FastAPI` `LangGraph` `LangChain` `ChromaDB` `rank-bm25` `Cross-Encoder` `Docker`

### 🎬 [Video Maker — LLM-Orchestrated Generation Pipeline](https://github.com/Matcry12/Video-Maker)

A multi-stage **LLM orchestration** pipeline (plan → research → script → quality gate → render) running end-to-end from a single prompt, with a quality gate that validates each stage before the next proceeds. Features **multi-provider routing** across Groq and Gemini — per-stage model selection with automatic failover/retry on rate limits and no hardcoded model names — a **multi-source RAG research stage** (Crawl4AI + SearXNG / DuckDuckGo / Wikipedia with per-page LLM extraction, BM25 scoring, dedup) reaching 67–100% passage relevance, and a **SigLIP** cross-modal reranker that matches visuals to each narration segment. *(Rendering layer optimized 27.5× via PIL pre-compose over FFmpeg.)*

`Python` `Groq` `Gemini` `SigLIP` `Hugging Face` `Crawl4AI` `SearXNG` `rank-bm25` `FFmpeg`

### 🗣️ [PhoSenti — Vietnamese Sentiment Analysis](https://github.com/Matcry12/PhoSenti)

Fine-tuned **PhoBERT** on the UIT-VSFC dataset (16,175 Vietnamese student-feedback samples) for 3-class sentiment classification — **93.3% accuracy**, **0.84 macro F1** on 3,166 test examples. Served via a FastAPI endpoint with a web UI returning label, confidence, and per-class probabilities.

`Python` `PyTorch` `PhoBERT` `Hugging Face Transformers` `FastAPI`

### 🌿 [Plant Disease Classification (CNN + FastAPI)](https://github.com/Matcry12/Tomato-Disease-Classification)

ResNet18 transfer-learning model for tomato-leaf disease detection (10 classes) — **98.8% accuracy**, **0.9867 macro F1** on 2,400+ test images. Real-time FastAPI inference returning predicted class, confidence, and top-3 predictions.

`PyTorch` `ResNet18` `FastAPI` `Transfer Learning`

### 🏨 [Tuyen Quang Explorer](https://github.com/Matcry12/Tuyen-Quang-Explorer)

Full-stack hotel booking & management web app (Django, MVC) — user auth, hotel browsing, a full booking workflow, and reviews over models for users, hotels, rooms, and bookings. **2nd Place, provincial competition.**

`Django` `Python` `MySQL`

---

## 🛠️ Tech Stack

**Languages:** Python (OOP) · C++

**LLM / NLP:** RAG Systems · Agentic & Tool-Use Pipelines · LLM Orchestration · LangGraph · LangChain · Hybrid Retrieval · Reranking · Embeddings & Semantic Search · Transformer Fine-tuning (PhoBERT) · Structured Output

**Evaluation:** RAGAS · LLM-as-Judge (human-calibrated) · Retrieval Metrics (Hit@k / Recall@k / MRR) · Ablation Studies · Benchmark Design

**Machine / Deep Learning:** Classification · Regression · Random Forest · XGBoost · CNN · RNN · Transfer Learning · ResNet · EfficientNet · SigLIP · Cross-Encoders

**Backend & Deployment:** FastAPI · Django · Flask · Docker · Hugging Face Spaces

**Libraries:** PyTorch · Hugging Face Transformers · Scikit-learn · Pandas · NumPy · ChromaDB · rank-bm25

**Databases & Tools:** MySQL · SQLite · Git · Jupyter

---

## 📊 GitHub Activity

[![Triet's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Matcry12&theme=dracula)](https://github.com/Matcry12)

---

## 📬 Connect With Me

<p>
  <a href="mailto:nguyenanhtriet702@gmail.com">📧 nguyenanhtriet702@gmail.com</a> &nbsp;|&nbsp;
  <a href="https://linkedin.com/in/triết-nguyễn-anh-882688391">💼 LinkedIn</a> &nbsp;|&nbsp;
  <a href="https://github.com/Matcry12">🐙 GitHub</a>
</p>

---

<p align="center"><i>"Build things. Break things. Learn fast."</i></p>
