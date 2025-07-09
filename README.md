# BioMARS
[![Static Badge](https://img.shields.io/badge/Project-Page-a)](https://alexandreq27.github.io/BioMARS-site/)

🔬 **BioMARS (Biological Multi-Agent Robotic System)** is an intelligent platform integrating Large Language Models (LLMs), Vision–Language Models (VLMs), and modular robotics to enable autonomous design, planning, and execution of biological experiments.

![structure(1)](https://github.com/user-attachments/assets/25eb2092-411d-4605-a4d1-42a6c696c4f1)

---

## Table of Contents
- [📄 Paper](#-paper)
- [📌 Abstract](#-abstract)
- [🧠 System Architecture](#-system-architecture)
- [🤖 Key Features](#-key-features)
- [🎥 Demo](#-demo)

---

## 📄 Paper

✒️ Yibo Qiu, Zan Huang, Zhiyu Wang, Handi Liu, Yiling Qiao, Yifeng Hu, Shu'ang Sun, Hangke Peng, Ronald X Xu, Mingzhai Sun

🔥 https://arxiv.org/abs/2507.01485

---

## 📌 Abstract

Large language models (LLMs) and vision–language models (VLMs) hold transformative potential for biological research by enabling autonomous experimentation. However, their application is hindered by rigid protocol design, limited adaptability to dynamic lab conditions, inadequate error handling, and high operational complexity. We introduce **BioMARS**, a multi-agent system combining LLMs, VLMs, and modular robotics to autonomously design and execute biological experiments.

BioMARS employs a hierarchical architecture:
- **Biologist Agent**: Synthesizes experimental protocols via retrieval-augmented generation.
- **Technician Agent**: Translates protocols into executable robotic pseudo-code.
- **Inspector Agent**: Ensures procedural integrity through multimodal perception and anomaly detection.

The system autonomously performs cell passaging and culture tasks, achieving or exceeding manual performance in viability, consistency, and morphological integrity. It also supports context-aware optimization, outperforming conventional strategies in differentiating retinal pigment epithelial cells. A web interface enables real-time human-AI collaboration, while a modular backend allows scalable integration with laboratory hardware. These results demonstrate the feasibility of generalizable, AI-driven laboratory automation and the transformative role of language-based reasoning in biological research.

---

## 🧠 System Architecture

### Agents Overview

| Agent            | Function                                                                 |
|------------------|--------------------------------------------------------------------------|
| Biologist Agent  | Generates experimental protocols using retrieval-augmented generation (RAG) |
| Technician Agent | Converts natural language protocols into robotic pseudo-code              |
| Inspector Agent  | Monitors processes and detects anomalies via multimodal perception      |

---

## 🤖 Key Features

- **Autonomous Experiment Design & Execution**
- **Multimodal Perception & Anomaly Detection**
- **Automated Cell Culture & Passaging**
- **Context-Aware Optimization**
- **Modular Hardware/Software Integration**

---

## 🎥 Demo
Real-world robot experiments.


https://github.com/user-attachments/assets/ea469a13-d455-48d0-ab5d-f2b5bd704555


https://github.com/user-attachments/assets/f134ed1c-4727-4379-83e4-ce3af4dedff3


https://github.com/user-attachments/assets/609dffaf-0cc4-4119-b23c-3efd48e5098e

## 📝 Citation

If you find our research valuable and would like to cite it in your work, please use the following references:

```bibtex
@article{qiu2025biomars,
  title={BioMARS: A Multi-Agent Robotic System for Autonomous Biological Experiments},
  author={Qiu, Yibo and Huang, Zan and Wang, Zhiyu and Liu, Handi and Qiao, Yiling and Hu, Yifeng and Sun, Shu'ang and Peng, Hangke and Xu, Ronald X and Sun, Mingzhai},
  journal={arXiv preprint arXiv:2507.01485},
  year={2025}
}
```










