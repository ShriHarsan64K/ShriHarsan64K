<div align="center">

# Shri Harsan M

**Computer Vision · Data Science · Multi-Agent Systems**

M.Tech Data Science @ SRM IST Chennai · Perplexity Campus Partner

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shriharsan)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/KptbBoLr4X/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shriharsang@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-202B45?style=for-the-badge&logo=googlechrome&logoColor=white)](https://shriharsan64k.github.io)

</div>

---

## About

Mechanical engineering background, now working across computer vision, physics-informed ML, and LLM-based systems. Currently a Graduate Technical Intern at Medtronic, alongside an M.Tech in Data Science.

- Research intern at **IIT Kanpur's VIMS Lab** — built GrOUND, a training-free object discovery pipeline that beat a published baseline (TokenCut) by 15+ IoU points on identical features
- **1st place, StudAI 2026** (CampusOS) · Top 5, TANFINET 2026 · Top 10, Schneider Electric 2026
- Currently exploring: physics-informed neural networks, multi-agent LLM systems

---

## Experience

**Medtronic** — Graduate Technical Intern
*2026 – Present*

**IIT Kanpur, VIMS Lab** — Research Intern, Dept. of Electrical Engineering
*May 2026 – Jul 2026*
- Built GrOUND, a training-free object discovery pipeline on frozen DINOv3 ViT-L/16 features — adaptive-threshold affinity graph cut, refined with FastSAM and a YOLOv8 rescue stage, no labels or fine-tuning
- Reached 71.6% IoU across ECSSD, DUTS-TE, and DUT-OMRON — beat TokenCut's algorithm outright by 15.1 IoU points on identical features
- Traced a resolution-driven failure mode in small-object detection to patch stride, not the algorithm, via per-object-size ablation

**Devvit** (early-stage startup) — Founding Team, Technical Lead & Community
*Apr 2026 – Jun 2026*
- Built and deployed the company website from scratch (React, Vercel)
- Organized and hosted a student hackathon with 30+ participants
- Led technical development and community strategy alongside the founders

**AICTE-EduSkills & AWS Academy** — Gen AI Virtual Intern
*Jan 2026 – Mar 2026*
- Completed a 10-week Gen AI curriculum: transformer architectures, prompt engineering, AWS AI services
- Built RAG pipelines and fine-tuned LLM applications on AWS infrastructure

**Motherson Group of Companies** — Process Automation & Analytics Intern
*Mar 2025 – May 2025*
- Engineered Python automation for 1,000+ records, a 30% efficiency gain through workflow optimization
- Led process re-engineering across 10 teams — eliminated 75% of paperwork, saved 120+ hours monthly
- Deployed analytics dashboards tracking manufacturing KPIs

**Top Engineers, Chennai** — AI Intern
*Jun 2022*
- Built ML models integrated with IoT sensors for industrial automation

---

## Hackathon Projects

### 🥇 CampusOS — StudAI Hackathon 2026 · 1st Place (₹50,000) · [GitHub](https://github.com/ShriHarsan64K/CampusOS)
Autonomous campus AI agent for event registration, grievance filing, and research retrieval — under 3 seconds per task.
- 91.4% intent accuracy, zero false registrations across 47 real student pilot interactions
- Cut task completion time 85% through autonomous workflows
- Went from a 76/100 review score to 1st place by fixing every concern raised: idempotency, audit trail, live monitoring

`Python` `Multi-Agent Systems` `LangChain` `RAG`

### NetFault-AI — TANFINET Hackathon 2026 · Top 5 · [GitHub](https://github.com/ShriHarsan64K/NetFault-AI)
AI-powered network fault isolation for BharatNet — cuts fault detection from 2–6 hours to under 60 seconds.
- Analyzes a 106-node topology in real-time, detects 6 fault types across OSI layers using NLP + anomaly detection
- GIS mapping with real GPS coordinates for 99 villages, plus a live Mininet digital twin for fault injection testing

`Python` `distilBERT` `Isolation Forest` `NetworkX` `Streamlit` `Folium`

### ResearchMind — AMD Slingshot 2026 (Team NextStrike) · [GitHub](https://github.com/ShriHarsan64K/ResearchMind)
Offline AI research assistant — analyzes PDFs and extracts insights in under 60 seconds using LLaMA 3 on an AMD Ryzen AI NPU.
- Zero cloud dependency, no API keys — runs fully offline
- Local ChromaDB vector store for research library management

`Python` `LLaMA 3` `Ollama` `ChromaDB` `Streamlit` `PyMuPDF`

### AI Code Reviewer — Schneider Electric Innovation Hackathon 2026 · Top 10 · [GitHub](https://github.com/ShriHarsan64K/Schneider-AI-Code-Reviewer)
VSCode extension analyzing code against 558 Schneider Electric standards across 7 languages, with one-click auto-fix.
- 99.9% faster reviews (hours → under 10 seconds), 91% quality improvement (35→91/100)
- Triple AI fallback: GPT-4 → Gemini → Ollama

`Python` `Flask` `TypeScript` `VSCode API` `GPT-4` `Gemini 2.0`

### AgentReady-Score — SAP × Great Lakes Hackathon 2026 · [GitHub](https://github.com/ShriHarsan64K/AgentReady-Score)
Real-time scoring tool measuring how well e-commerce platforms are optimized for AI shopping agents.

`Python` `Streamlit` `API Integration`

---

## Research Projects

### Marine Biodiversity — M.Tech Thesis · [GitHub](https://github.com/ShriHarsan64K/Marine-Biodiversity)
Automated underwater species detection and tracking for ecological monitoring.
- 95.1% mAP@0.5 at 59.3 FPS on a consumer GPU (RTX 3050), YOLOv8 + ByteTrack
- Built a 5,201-image self-curated dataset with underwater-aware augmentation, 93.8% precision
- Cut manual ecological survey time by 80% via an automated Marine Health Index score

`Python` `YOLOv8` `ByteTrack` `PyTorch` `OpenCV`

### Cyclone-PINN — Physics-Informed Neural Networks · [GitHub](https://github.com/ShriHarsan64K/Cyclone-PINN)
Reconstructing tropical cyclone wind fields from sparse ERA5 satellite data (Hurricane Ida case study).
- Improved trajectory prediction 15% over pure ML via Navier-Stokes integration
- Cut training time 40% through physics-informed loss functions while maintaining 92% accuracy
- Validated on 100+ historical cyclone cases

`Python` `PyTorch` `SciPy` `ERA5` `Differential Equations`

---

## Tech Stack

**AI & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**LLM & Gen AI**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ai&logoColor=white)

**Data & Infra**
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**Visualization**
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## Achievements

| | Result | Event | Year |
|---|---|---|---|
| 🥇 | 1st Place, ₹50K | StudAI Hackathon (CampusOS) | 2026 |
| 🏅 | Top 5 | TANFINET Hackathon (NetFault-AI) | 2026 |
| 🏅 | Top 10 | Schneider Electric Innovation Hackathon | 2026 |
| 🎯 | Participant | AMD Slingshot (ResearchMind — Team NextStrike) | 2026 |
| 🎯 | Participant | Appian AI Challenge, IIT Madras Shaastra | 2026 |
| 🥈 | 2nd Place | National Technical Design Competition, SRM | 2025 |
| 🥉 | 3rd Place | FAME Paper Presentation, Hybrid Vehicles | 2024 |
| 🥇 | 1st Place | SAE India Paper Presentation, AIoT & Smart Systems | 2023 |

## Certifications

`AWS AI Practitioner` `AWS Cloud Practitioner` `AWS Academy — ML Foundations` `AWS Academy — ML for NLP` `AWS Academy — Generative AI Foundations` `Google & Kaggle — AI Agents Intensive` `Google — Crash Course on Python` `IBM — Python for Data Science, AI & Dev` `IIT NPTEL — Fundamentals of AI` `Coursera — EDA for ML` `Coursera — MySQL`

## Languages

English, Tamil — fluent · French — conversational · Hindi, Telugu, German (B1) — learning

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=ShriHarsan64K&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ShriHarsan64K&layout=compact&theme=tokyonight&hide_border=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=ShriHarsan64K&theme=tokyonight&hide_border=true)

</div>

---

## Get in touch

Open to conversations about computer vision, multi-agent systems, or scientific ML.

📧 [shriharsang@gmail.com](mailto:shriharsang@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/shriharsan) · 💻 [LeetCode](https://leetcode.com/u/KptbBoLr4X/) · 🌐 [Portfolio](https://shriharsan64k.github.io)
