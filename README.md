<div align="center">

```
███╗   ███╗ ██████╗ ███████╗████████╗ █████╗ ███████╗ █████╗
████╗ ████║██╔═══██╗██╔════╝╚══██╔══╝██╔══██╗██╔════╝██╔══██╗
██╔████╔██║██║   ██║███████╗   ██║   ███████║█████╗  ███████║
██║╚██╔╝██║██║   ██║╚════██║   ██║   ██╔══██║██╔══╝  ██╔══██║
██║ ╚═╝ ██║╚██████╔╝███████║   ██║   ██║  ██║██║     ██║  ██║
╚═╝     ╚═╝ ╚═════╝ ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝
```

**AI/ML Engineer · Cairo University, B.Sc. Artificial Intelligence**

*Building production AI systems at the edge of research and reality.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mostafa-aly-sayed/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:moustafaalyyy@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1wAAdZH3Wto0IIRbpQ21AvB3iswFU4ZX-)

</div>

---

## What I Build

I specialize in shipping AI that works outside the notebook — multimodal systems, NLP pipelines, and computer vision deployments. From darknet threat intelligence to real-time sign language recognition, my focus is on systems that close the gap between research and real-world use.

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
| [Weather App](https://github.com/mostafa-aly-sayed/WeatherApp) | Live weather data with location support |
| [News App](https://github.com/mostafa-aly-sayed/NewsApp) | Category-filtered news reader |

</details>

---

## Core Stack

```
Vision        →  YOLOv8 · OpenCV · MediaPipe
NLP / LLMs    →  Hugging Face · BERT · RoBERTa · RAG · SHAP
Audio         →  Librosa · MFCCs · 1D-CNN · Whisper-style ASR
Frameworks    →  TensorFlow · PyTorch · Keras · Scikit-learn
APIs          →  Flask · FastAPI · Django
Data          →  Pandas · NumPy · Power BI · Tableau
Languages     →  Python · C++ · SQL · Dart
```

---

<div align="center">

**Open to AI collaborations, research, and freelance work**
[moustafaalyyy@gmail.com](mailto:moustafaalyyy@gmail.com)

</div>
