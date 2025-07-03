# BioMARS

🔬 **BioMARS (Biological Multi-Agent Robotic System)** is an intelligent platform integrating Large Language Models (LLMs), Vision–Language Models (VLMs), and modular robotics to enable autonomous design, planning, and execution of biological experiments.

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

https://github.com/user-attachments/assets/c06b4494-ccc1-4506-b199-57fe7158a267

https://github.com/user-attachments/assets/26c25e95-a553-4024-b751-72de582e23cb

https://github.com/user-attachments/assets/5a1197a2-24e6-40b3-bcf2-ab2bedee73a8







