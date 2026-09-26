# Hi, I'm Haoxuan Jiang (蒋昊轩)

<p align="left">
  <a href="https://www.linkedin.com/in/haoxuan-jiang-b294132a2/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:jhx03050@gmail.com"><img src="https://img.shields.io/badge/Gmail-jhx03050@gmail.com-D14836?style=flat-square&logo=gmail" alt="Gmail"/></a>
  <a href="mailto:2364261713@qq.com"><img src="https://img.shields.io/badge/QQ_Mail-2364261713@qq.com-12B7F5?style=flat-square&logo=tencentqq&logoColor=white" alt="QQ Mail"/></a>
  <img src="https://img.shields.io/badge/HKUST-MSc_AI_%26_Entrepreneurship-003366?style=flat-square" alt="HKUST"/>
  <img src="https://img.shields.io/badge/UESTC_%7C_Glasgow-Dual_BEng_in_EE-1C3D73?style=flat-square" alt="UESTC-Glasgow"/>
</p>

Incoming Master student in **Artificial Intelligence & Entrepreneurship** at **HKUST**.
Dual BEng Graduate from **UESTC** & **University of Glasgow** (Electronics & Information Engineering).

Driven by the intersection of **LLM Alignment & MoE Architectures**, **Multi-Agent Systems**, and **High-Performance AI Systems (CUDA, Cloud-Edge, & Quantization)**.

---

### Core Technical Focus

- **LLM Post-Training & Advanced Architectures**:
- Deep exploration into **SFT, DPO, and RLHF** for domain adaptation and mitigation of hallucinations.
- Parameter-efficient fine-tuning (LoRA/QLoRA), **Mixture of Experts (MoE)** routing, and instruction curation.
- **AI Systems & Hardware-Software Co-Design**:
- **Inference & Serving Optimization**: High-concurrency microservices, 4-bit/8-bit quantization, and low-latency serving.
- **Parallel & Edge Computing**: CUDA acceleration, multi-sensor tight coupling, embedded data acquisition, and ROS cloud-edge pipelines.
- **Agentic Workflows & Multi-Agent Collaboration**:
- Autonomous multi-agent pipelines for quantitative finance, financial NLP, and sub-10ms intent parsing.
- Model Context Protocol (MCP) tool integration and modular context orchestration.

---

### Tech Stack & Engineering Tooling

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <!-- AI / ML Frameworks -->
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <!-- Systems & Deployment -->
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/MATLAB-ED8B00?style=flat-square&logo=mathworks&logoColor=white"/>
</p>

---

### Professional Experience

- **China Electronics Technology Group Corporation (CETC)** | *Algorithm Engineer* `(2025.12 - 2026.05)`
- Spearheaded post-training alignment (SFT / DPO / RLHF) for multimodal foundation models, yielding a **5% benchmark boost** and **8% drift reduction**.
- **TravelSky Technology (中国航信)** | *AI Software Engineer Intern* `(2025.06 - 2025.09)`
- Built production ETL pipelines (50+ temporal features) and deployed predictive ML models via **FastAPI (<200ms latency)**, reducing prediction errors by **18%**.
- **Tsinghua University (LFET Lab)** | *Embedded Systems Engineer Intern* `(2023.06 - 2023.09)`
- Engineered high-precision data acquisition front-ends with precision ADCs and low-noise filters (+20% accuracy); automated dynamic strain field processing in MATLAB (+30% throughput).

---

### Highlighted Systems & Projects

#### 1. [Finance_Helper](https://github.com/justlikethis1/Finance_Helper) — Multi-Agent Financial Research Platform

*High-concurrency Agentic AI system built with FastAPI, Local LLMs, and multi-tier caching.*

- Architected **5 cooperative agents** handling real-time data feeds, fundamental/technical analysis, and summary synthesis.
- Built a cascaded NLP pipeline featuring sub-10ms intent recognition & NER, SQLite conversational state tracking, and local 4-bit quantized deployment.

#### 2. [SlimMCP](https://github.com/justlikethis1/SlimMCP) — Lightweight SLM Fine-Tuning & MCP Integration

*Efficient open-source model alignment and Model Context Protocol (MCP) tool-use harness.*

- Implemented parameter-efficient fine-tuning (PEFT/LoRA) and preference alignment pipelines targeting compact models (e.g., Qwen 2.5 series).
- Engineered standardized Model Context Protocol (MCP) server interfaces for structured tool calling, dynamic context injection, and reduced token consumption.
- Optimized training memory footprints and inference runtime via KV-cache tuning and GPU memory management in PyTorch/CUDA environments.

#### 3. Transformer-MoE Multi-Task Semiconductor Screening (Final Year Project)

*Physics-Informed Deep Learning & AI for Science (UESTC)*

- Formulated a multi-task learning architecture combining **Transformer self-attention and Mixture of Experts (MoE)** for high-throughput semiconductor property prediction.
- Designed a 49-dimensional physics-informed feature pipeline from Materials Project and constraint simulations, boosting raw representation capacity by 3x.
- Achieved **$R^2 > 0.997$** across continuous regression tasks (band gap & formation energy) and **$>99.5\%$ accuracy** across categorical classifications with robust noise resilience.

#### 4. Real-Time Flight Route Planning & Inference Platform

*High-Throughput ML Serving & Production ETL Pipelines (TravelSky)*

- Engineered automated data pipelines extracting 50+ business-critical temporal features, elevating dataset quality by **40%**.
- Containerized and served the architecture as a high-availability **FastAPI microservice**, achieving robust production throughput with **<200ms end-to-end inference latency**.

#### 5. Cloud-Edge Perception & High-Speed SLAM Pipeline

*Autonomous Racing System | Computer Vision & Systems Optimization (UESTC Fury Racing)*

- Developed a distributed perception framework combining **YOLOv5** and **ORB-SLAM3** with LiDAR-camera tight coupling.
- Restructured computation flows using **CUDA parallel computing**, reducing processing latency by **40%** and maintaining **20Hz @ 80km/h** with Kalman filter delay compensation.
- Built cloud-edge messaging using ROS topics to support edge inference and cloud-based online model updates.

---

### Academic Publication & Honors

- **IEEE ICEICT 2024**: *The Optimal Design of Cavity Optomechanical Micro-Hemispherical Gyroscope* (Micro-MEMS & Multiphysics Design & Modeling in COMSOL).
- **National 3rd Prize**: National Mechanical Engineering Innovation Competition ("Ming Shi Cup").
- **Scholarships**: Exemplary Student Scholarship & Academic Excellence Awards (UESTC & Glasgow).

---

### Leadership & Community

- **Executive Committee Member (External Relations)** — *Mainland Students and Scholars Society, HKUST (MSSS)* `(2026.07 - Present)`
  - Driving external partnerships, cross-institutional academic exchanges, and corporate liaison for postgraduates at HKUST.
- **Co-Chair of Management Committee** — *PeerHelp Association (UESTC & Glasgow)* `(2024.07 - 2025.09)`
  - Led a team of nearly 100 peer consultants; established standardized counseling workflows and completed 500+ successful academic matching sessions (>90% satisfaction rate).

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=justlikethis1&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Haoxuan's GitHub Activity Graph" />
</p>

---

 *Always open to discussions on LLM architectures, AI system optimization, or high-performance computing!*
