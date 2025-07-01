# BioMARS

🔬 **BioMARS (Biological Multi-Agent Robotic System)** is an intelligent platform integrating Large Language Models (LLMs), Vision–Language Models (VLMs), and modular robotics to enable autonomous design, planning, and execution of biological experiments.

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
