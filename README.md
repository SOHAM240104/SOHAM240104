<div align="center">

# hey, I'm Soham

**Software & AI Engineer** · building systems that see, listen, and reason

I work on **multi-modal AI**, **agentic workflows**, and **backends that stay fast under real load**.  
Most days I'm wiring models into products people can actually trust — deepfake forensics, disaster response, voice interfaces.

*Anna University (CEG) · building in the open @ [SOHAM240104](https://github.com/SOHAM240104)*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_HANDLE)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/YOUR_HANDLE)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=safari&logoColor=white)](https://YOUR_PORTFOLIO_URL)

</div>

---

### what I care about

I like problems where **perception meets judgment** — when a model has to look at a video, hear a clip, read a claim, and still leave a human with evidence they can act on.  
I also care about the unglamorous half: clean APIs, honest latency, and pipelines that don't fall apart outside the demo.

---

### stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
</p>

---

### featured work

<br/>

#### 01 · Multimodal Disinformation & Scam Verification Engine
> *When a clip looks real and a message feels urgent — I want the system to leave receipts, not vibes.*

Built a verification stack that fuses **audio-only** and **audio-visual** deepfake signals (NOMA + AVH-Align / AV-HuBERT), then layers in scam / claim checking for text and screenshots. Scores are calibrated and fused with reliability weighting; optional **Grad-CAM** mouth-ROI overlays and an **evidence bundle** (hashes, extracted audio, ROI video, predictions) make outputs reviewable — not just a red/green badge.

**Architecture highlights**
- Dual detectors → reliability-weighted fusion → optional corroboration path  
- Spatial pre-crop + mouth ROI for messy vertical / UI-heavy video  
- OCR + fact-check tooling for message / screenshot scam flows  
- Exportable forensic bundle for audits and downstream review

`PyTorch` · `OpenCV` · `AV-HuBERT` · `Streamlit` · `calibration & metrics`

🔗 [fake_detection_mads](https://github.com/SOHAM240104/fake_detection_mads) · [AVH](https://github.com/SOHAM240104/AVH)

<br/>

#### 02 · YOLOv8 Real-time Disaster Response & Pathfinding System
> *Detect first. Route second. Seconds matter when the map is changing.*

Computer-vision pipeline for on-the-ground disaster scenes: **YOLOv8** for real-time hazard / victim / obstacle detection, paired with graph-based **pathfinding** so responders get actionable routes — not just bounding boxes. Informed by geospatial risk work (multi-source landslide assessment) and earlier campus navigation graphs in C++.

**Architecture highlights**
- Live detection loop optimized for field latency  
- Scene graph → shortest / safest path under changing constraints  
- Bridges perception (CV) with planning (routing) in one decision path  
- Designed for operators who need a clear next step under pressure

`YOLOv8` · `OpenCV` · `Python` · `C++` · `geospatial / routing`

🔗 [landslide-risk-assessment](https://github.com/SOHAM240104/landslide-risk-assessment-) · [CEG campus navigation](https://github.com/SOHAM240104/CEG-campus-navigation-system)

<br/>

#### 03 · LLM-Enhanced Voice Interface with Fine-Tuned Whisper
> *Voice should feel like talking to a patient friend — not fighting an IVR.*

End-to-end voice layer on top of an agentic assistant: **fine-tuned Whisper** for robust ASR, then LLM + tool-calling for intent, retrieval, and calm replies. Same spirit as the Saksham / Care work — short sentences, mode-aware routing (support vs scam), and tools preferred over guessing.

**Architecture highlights**
- Fine-tuned Whisper ASR → structured intent → tool-using LLM  
- Hybrid retrieval (vector + BM25) with reranking for grounded answers  
- Mode-aware agent (tech support ↔ scam verification) with injection-safe OCR handling  
- Built for real users: elderly-friendly tone, multilingual when natural

`Whisper` · `LangChain` · `FAISS` · `FastAPI` · `OpenAI / local SLM path`

🔗 [saksham-mvp](https://github.com/SOHAM240104/saksham-mvp) · [slm](https://github.com/SOHAM240104/slm)

---

### github at a glance

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SOHAM240104&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="GitHub Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SOHAM240104&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=SOHAM240104&theme=dark&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub Streak"/>
</div>

---

### currently exploring

agent orchestration · local privacy gates for LLMs · MCP tooling · search / retrieval products that feel conversational without inventing facts

---

<div align="center">

**if you're building something hard in AI systems — I'd love to talk.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_HANDLE)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/YOUR_HANDLE)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=safari&logoColor=white)](https://YOUR_PORTFOLIO_URL)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SOHAM240104)

<br/>

<sub>thanks for stopping by — ship carefully, measure twice.</sub>

</div>
