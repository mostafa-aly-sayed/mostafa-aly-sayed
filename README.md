<div align="center">

```
███╗   ███╗ ██████╗ ███████╗████████╗ █████╗ ███████╗ █████╗
████╗ ████║██╔═══██╗██╔════╝╚══██╔══╝██╔══██╗██╔════╝██╔══██╗
██╔████╔██║██║   ██║███████╗   ██║   ███████║█████╗  ███████║
██║╚██╔╝██║██║   ██║╚════██║   ██║   ██╔══██║██╔══╝  ██╔══██║
██║ ╚═╝ ██║╚██████╔╝███████║   ██║   ██║  ██║██║     ██║  ██║
╚═╝     ╚═╝ ╚═════╝ ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝
```

**AI & Automation Engineer · Cairo University, B.Sc. Artificial Intelligence**

*Building ERP systems, LLM agents, and automations that run real business operations.*

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-moustafaasayed.netlify.app-2E75B6?style=for-the-badge)](https://moustafaasayed.netlify.app/)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mostafa-aly-sayed/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:moustafaalyyy@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1wAAdZH3Wto0IIRbpQ21AvB3iswFU4ZX-)

</div>

---

## What I Build

I design ERP systems and build the automation around them — LLM-powered agents, RAG assistants, and human-in-the-loop workflows built to run business operations reliably. My background in ML research (NLP, computer vision, explainability) shapes how I ship AI: tested, observable, and with a human in control where it matters.

Currently **AI & Automation Engineer at naturesta** (Giza, Egypt), building the company's Odoo ERP from scratch and the AI-driven sales and operations workflows on top of it.

---

## Experience

### AI & Automation Engineer — naturesta
*Giza, Egypt · Jun 2026 – Present*

- Designing and building the company's **Odoo ERP** from scratch, including the complete sales workflow (quotation → delivery → invoicing) the business runs on
- Built **Order Desk**, an external automation that turns order and return emails into Odoo records and feeds live daily sales analysis to management
- Building the B2C sales pipeline — AI chatbots, WhatsApp bots, inventory sync, order routing — and connected **Claude to live Odoo via MCP** for plain-language ERP queries

### AI Automation Intern — Splash-CFD Ltd
*United Kingdom (Remote) · Jul 2026 – Sep 2026*

- Built an offline **LLM agent for support-inbox triage and reply drafting** plus a **RAG FAQ assistant**, with human approval before any send enforced by 57 automated tests, not prompts
- Built the sales automation foundations: a Flask licence-issuing REST service and CRM lead scoring, with every integration behind provider-agnostic interfaces

### Data Analyst Intern — Digital Egypt Pioneers Program (MCIT)
*Apr 2024 – Oct 2024*

- Analyzed business datasets with Python, SQL, and Excel and built interactive Power BI dashboards

---

## Flagship Projects

### ① NeoSilk — AI-Powered Dark Web Monitoring Framework

> *Graduation Project · Grade: A+*

**[🌐 Live Demo](https://neosilk.netlify.app/)** · [GitHub](https://github.com/mostafa-aly-sayed/NeoSilk)

An intelligence framework for cybersecurity analysts that scrapes, classifies, and explains darknet threats using fine-tuned transformer models.

| What | How |
|---|---|
| NLP Classification | Fine-tuned BERT, DarkBERT, RoBERTa across 3 threat-classification tasks |
| Explainability | SHAP-powered interpretability layer for analyst trust |
| Knowledge Retrieval | RAG-based QA system over darknet corpora |
| Intelligence Dashboards | Power BI visualizations across 5+ darknet categories |
| Data Collection | Custom Tor-based scraping pipeline |

`Python` `Hugging Face` `BERT` `RoBERTa` `RAG` `SHAP` `Power BI` `Tor Network`

---

### ② Multimodal ASL Recognition — Speech & Video to Text

A two-phase deep learning pipeline that understands American Sign Language from both audio and video inputs, served as independent REST APIs.

**Phase 1 — Audio → Word Category**
- 1D-CNN trained on 10,000 `.wav` files across 10 semantic categories
- 13-coefficient MFCCs at 16 kHz, normalized + padded to 23 frames
- Deployed via Flask + ngrok: POST `/predict` → category + confidence

**Phase 2 — Video → ASL Gloss**
- WLASL dataset: 807 videos, 115 ASL gloss classes
- MediaPipe keypoint pipeline: 225-dimensional skeletal features per frame (33 pose + 21×2 hand landmarks) — ~100× dimensionality reduction vs. raw video
- Custom Transformer Encoder (d_model=128, 4 heads, 3 blocks) — 80 epochs with EarlyStopping + ReduceLROnPlateau
- End-to-end API: `.mp4` upload → keypoints → inference → JSON

`TensorFlow/Keras` `MediaPipe` `Librosa` `OpenCV` `Flask`

---

### ③ Real-Time Traffic Sign Detection

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mostafa-aly-sayed/traffic-sign-detection)

YOLOv8-powered detection pipeline achieving **30+ FPS** on live video. Custom-annotated dataset via Roboflow covering 10+ sign classes, with augmentation pipeline for real-world generalization.

`YOLOv8` `OpenCV` `Roboflow` `Python`

---

### ④ Speech2Text — End-to-End ASR

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mostafa-aly-sayed/Speech2Text)

Automatic speech recognition pipeline with engineered audio features — MFCCs, spectrograms, and noise reduction — for robust transcription under real-world conditions.

`TensorFlow` `Librosa` `SpeechRecognition`

---

## Other Work

<details>
<summary><b>CodeAlpha Internship Projects</b></summary>
<br>

| Project | Description |
|---|---|
| [Speech Emotion Recognition](https://github.com/mostafa-aly-sayed/CodeAlpha_SpeechEmotionRecognition) | Classifying emotional state from audio signals |
| [Handwritten Character Recognition](https://github.com/mostafa-aly-sayed/CodeAlpha_HandwrittenCharacterRecognition) | CNN-based OCR for handwritten characters |
| [Disease Prediction](https://github.com/mostafa-aly-sayed/CodeAlpha_DiseasePredection) | ML classifier for symptom-based disease prediction |

</details>

<details>
<summary><b>Flutter / Mobile Projects</b></summary>
<br>

| Project | Description |
|---|---|
| [Bookly App](https://github.com/mostafa-aly-sayed) | Google Books API · 40M+ titles · Clean Architecture · Bloc/Cubit |
| [NewsCloud App](https://github.com/mostafa-aly-sayed/NewsApp) | Real-time news reader · NewsAPI · Responsive layouts |
| [Real-Time Chat App](https://github.com/mostafa-aly-sayed) | Firebase Auth · Firestore · Bloc/Cubit · Live messaging |
| [Weather App](https://github.com/mostafa-aly-sayed/WeatherApp) | Live weather data with location support |

</details>

---

## Tech Stack

### ERP & Business Automation
<p>
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/WhatsApp_Bots-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</p>

### AI & LLM Engineering
<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multi--Agent_Systems-3C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tool_Calling-1F6FEB?style=for-the-badge"/>
</p>

### Machine Learning
<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-00897B?style=for-the-badge&logo=google&logoColor=white"/>
</p>

### Programming & Backend
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

### Data & Visualization
<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-003B57?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
</p>

### Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/ngrok-1F1E37?style=for-the-badge&logo=ngrok&logoColor=white"/>
  <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
</p>

---

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| [Deep Learning Specialization](https://coursera.org/share/72c503939987fca5e1f72c8365c44ba8) | DeepLearning.AI (5 courses) | Mar 2026 |
| [Machine Learning Specialization](https://coursera.org/share/60a3122277a3394508b580c5b2652234) | DeepLearning.AI (3 courses) | Aug 2024 |

---

## Languages

**Arabic** — Native · **English** — Professional Working · **Turkish** — Professional Working

---

<div align="center">

**Open to AI & automation collaborations, research, and freelance work**

[moustafaalyyy@gmail.com](mailto:moustafaalyyy@gmail.com) · [moustafaasayed.netlify.app](https://moustafaasayed.netlify.app/)

</div>
