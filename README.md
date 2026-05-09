# Andrea Yanez Soto

**Junior CS @ NJIT** | NASA-Funded ML Researcher | GPU Computing & Deep Learning

Building production-grade ML systems from CUDA kernels to transformer architectures.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andreayanezsoto-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/andreayanezsoto)
[![GitHub](https://img.shields.io/github/followers/andreay99?label=Follow&style=flat&logo=github)](https://github.com/andreay99)

---

## Current Work

**NASA MIRO Research Fellow** | Dec 2025 - Present  
Training multimodal transformer models on decades of NASA/SDO and SOHO solar data to predict eruption events. Achieved 20% forecast accuracy improvement through systematic experiment tracking and Physics-Informed Neural Network integration with YOLO-based feature extraction.

**Open Source**  
Contributing to [Hugging Face Transformers](https://github.com/huggingface/transformers) — PyTorch CUDA backend API migrations ([PR #45856](https://github.com/huggingface/transformers/pull/45856))

---

## Projects

### [CUDA Flash Attention](https://github.com/andreay99/cuda-flash-attention)
Implemented Flash Attention (Dao et al. 2022) forward and backward passes from scratch in raw CUDA C++.

**Performance:**
- 22.9× softmax speedup (4.8 → 110 GB/s) via shared memory and warp-shuffle reductions
- 86× HBM traffic reduction at seq_len=4096
- Verified all gradients (dQ, dK, dV) against PyTorch autograd with max error <4e-7

**Techniques:** Shared memory tiling, warp-level primitives, online softmax, gradient recomputation

[Technical blog post](https://medium.com/@andreayanez) | [Benchmark results](https://github.com/andreay99/cuda-flash-attention#benchmark-results)

---

### [Recall](https://github.com/Christinetrr/recall) — Edge-Deployed Facial Recognition
**Winner: Best Use of Grok (XAI) & Best Use of Arm** | HackPrinceton 2025

Edge-deployable face recognition pipeline built in PyTorch and OpenCV for Raspberry Pi.

- <200ms on-device inference latency
- 94% precision with <2% false positives
- Streaming REST API with OpenAPI docs

**Stack:** Python, PyTorch, OpenCV, FastAPI, Raspberry Pi

---

### [ROM-COM](https://github.com/andreay99/rom-com) — Stroke Rehabilitation System
**HackPrinceton Spring 2026**

Real-time gesture recognition for physical therapy assessment.

- 96%+ CV accuracy using MediaPipe and Random Forest
- Live FMA-UE clinical scoring from joint kinematics
- 14+ FPS WebSocket streaming with sub-50ms latency

**Stack:** Python, MediaPipe, scikit-learn, FastAPI, React

---

## Technical Stack

**AI/ML:** PyTorch, TensorFlow, Hugging Face, OpenCV, CUDA, cuDNN  
**Languages:** Python, C++, CUDA C, JavaScript/TypeScript, Java, SQL  
**Tools:** Docker, Git, FastAPI, Flask, AWS, Azure, MongoDB

---

## Recognition

- **HackPrinceton 2025** — Best Use of Grok (XAI) & Best Use of Arm (MLH)
- **NASA MIRO Fellow** — Competitive research fellowship for ML in heliophysics
- **Apple Technical Specialist** — Top 5% nationally for quality and efficiency

---

## Connect

**LinkedIn:** [andreayanezsoto](https://linkedin.com/in/andreayanezsoto)  
**Website:** [andreasoto.dev](https://www.andreasoto.dev)  
**Email:** andreayanez11@outlook.com

Open to ML research collaborations and open source contributions.
