# Quinn Hasse

CS student. Building in AI and ML — models, pipelines, and tools that actually run.

Current focus: deep learning fundamentals and applied NLP. Training transformers from scratch, building computer vision systems, shipping full-stack AI products.

---

## Projects

### [Attention Is All You Need](https://github.com/quinnhasse-test/AttentionIsAllYouNeed)
PyTorch implementation of the transformer architecture (Vaswani et al., 2017) built without `nn.Transformer`. Every component hand-coded: scaled dot-product attention, sinusoidal positional encoding, multi-head attention, Noam LR warmup, label-smoothing cross-entropy, beam search with length normalization. Trained on Multi30k EN-DE. **BLEU 33.8** on test set.

### [RealTimeASLTranslator](https://github.com/quinnhasse-test/RealTimeASLTranslator)
Real-time American Sign Language hand gesture classifier. OpenCV captures frames at 30 fps; a CNN classifies each frame and renders the predicted letter as a live overlay. Built with TensorFlow.

### [LexonAI](https://github.com/quinnhasse-test/LexonAI)
Transparent AI answer system built at MadHacks 2025. Constrains GPT-4o-mini to retrieved sources only (via Exa neural search), then constructs a 4-layer evidence graph linking every claim back to its source. Interactive 3D visualization built with React Three Fiber. Live at [lexon-ai.vercel.app](https://lexon-ai.vercel.app/).

### [echo-ridge-scoring](https://github.com/quinnhasse-test/echo-ridge-scoring)
FastAPI REST service for deterministic DOIMB scoring (0–100) and risk/feasibility assessment in agentic pipelines. Configurable score blending with full test coverage. Runs behind a clean OpenAPI spec.

### [AutoTest](https://github.com/quinnhasse-test/AutoTest)
Agentic developer assistant. Takes a natural language prompt, generates the code via GPT, and commits it directly to a configured GitHub repository. Streamlit frontend, PyGithub backend, research agent for library lookups.

---

## Stack

**ML/DL:** PyTorch, TensorFlow, scikit-learn, NumPy, pandas  
**CV:** OpenCV  
**APIs:** FastAPI, Express, OpenAI, Exa  
**Frontend:** React, TypeScript, Vite, Three.js  
**Tooling:** pytest, W&B, Docker, GitHub Actions
