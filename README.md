<h1 align="center">Mostafa Aly Sayed</h1>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2E75B6&center=true&vCenter=true&width=900&lines=AI+%26+ML+Engineer+%7C+Cairo+University+%7C+B.Sc.+Artificial+Intelligence;Computer+Vision+%C2%B7+Deep+Learning+%C2%B7+NLP+%C2%B7+LLMs;Building+End-to-End+AI+Systems+That+Ship" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mostafa-aly-sayed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:moustafaalyyy@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <a href="https://drive.google.com/drive/folders/1wAAdZH3Wto0IIRbpQ21AvB3iswFU4ZX-"><img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white"/></a>
</p>

---

## About Me

AI/ML Engineer with a B.Sc. in Artificial Intelligence from Cairo University, specializing in **computer vision**, **deep learning**, and **NLP**. I build and deploy production-ready AI systems — from multimodal sign language recognition and real-time object detection, to darknet threat intelligence and automatic speech recognition.

Currently working as a **Freelance AI Solutions Developer** for international clients (Happy Software, Saudi Arabia), delivering end-to-end ML applications. I'm passionate about closing the gap between research and real-world impact.

---

## Featured Project — Graduation Project (Grade: A+)

### NeoSilk — AI-Enhanced Dark Web Monitoring Framework

> An AI-driven darknet intelligence framework combining Tor-based scraping, fine-tuned transformer models, and explainability tools for cybersecurity threat analysis.

- Fine-tuned **BERT, DarkBERT, and RoBERTa** across **3 NLP classification tasks** on darknet-sourced text
- Integrated **SHAP explainability** and **RAG-based QA systems** for interpretable outputs
- Built **Power BI dashboards** visualizing threat patterns across **5+ darknet categories**

`Python` `Hugging Face Transformers` `BERT` `RoBERTa` `RAG` `SHAP` `Power BI` `Tor Network`

[![NeoSilk](https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=NeoSilk&theme=tokyonight)](https://github.com/mostafa-aly-sayed/NeoSilk)

---

## Projects

### Multimodal ASL Recognition System — Speech2Text + Video2Text

> A two-phase multimodal deep learning pipeline for American Sign Language recognition — classifying signs from both spoken audio and sign-language video — served as two independent REST APIs.

**Phase 1 — Speech Recognition (Audio → Word Category)**
- Trained a **1D-CNN** on **10,000 `.wav` files** across **10 semantic word categories** (Health, Travel, Food, etc.)
- Extracted **13-coefficient MFCCs** at 16 kHz; normalized + padded to **23 frames** with `StandardScaler`
- Deployed as a **Flask REST API** (POST `/predict`) via ngrok — returns predicted category + confidence

**Phase 2 — Sign Language Video Recognition (Video → ASL Gloss)**
- Built on the **WLASL dataset**: **807 videos**, **115 ASL gloss classes**, stratified splits
- Designed a **MediaPipe keypoint extraction pipeline** — **225-dimensional** skeletal features per frame (33 pose + 21 × 2 hand landmarks), replacing raw video with compact representations (~100× dimensionality reduction)
- Architected a **Transformer Encoder** (d_model=128, 4 attention heads, 3 stacked blocks) trained over **80 epochs** with EarlyStopping + ReduceLROnPlateau
- Deployed as a second **Flask REST API** — end-to-end: `.mp4` upload → keypoint extraction → inference → JSON response

`Python` `TensorFlow/Keras` `MediaPipe` `Librosa` `OpenCV` `Flask` `Ngrok` `Scikit-learn`

---

### Real-Time Traffic Sign Detection System

[![Traffic Sign Detection](https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=traffic-sign-detection&theme=tokyonight)](https://github.com/mostafa-aly-sayed/traffic-sign-detection)

- Engineered a **real-time computer vision pipeline** using **YOLOv8** achieving **30+ FPS** on live video streams
- Covers **10+ traffic sign classes** with a custom annotated dataset built via **Roboflow**
- Applied preprocessing and augmentation techniques to improve generalization

`Python` `YOLOv8` `OpenCV` `Roboflow`

---

### Speech2Text — Automatic Speech Recognition

[![Speech2Text](https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=Speech2Text&theme=tokyonight)](https://github.com/mostafa-aly-sayed/Speech2Text)

- End-to-end ASR pipeline transcribing spoken audio to text using deep learning
- Engineered audio features: **MFCCs**, spectrograms, and noise reduction for robust transcription

`Python` `TensorFlow` `Librosa` `SpeechRecognition`

---

### CodeAlpha Internship Projects

<p align="left">
  <a href="https://github.com/mostafa-aly-sayed/CodeAlpha_SpeechEmotionRecognition">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=CodeAlpha_SpeechEmotionRecognition&theme=tokyonight" />
  </a>
  &nbsp;
  <a href="https://github.com/mostafa-aly-sayed/CodeAlpha_HandwrittenCharacterRecognition">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=CodeAlpha_HandwrittenCharacterRecognition&theme=tokyonight" />
  </a>
  &nbsp;
  <a href="https://github.com/mostafa-aly-sayed/CodeAlpha_DiseasePredection">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=CodeAlpha_DiseasePredection&theme=tokyonight" />
  </a>
</p>

---

### Flutter Projects

<p align="left">
  <a href="https://github.com/mostafa-aly-sayed/tourism-gallery-app">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=NewsApp&theme=tokyonight" />
  </a>
  &nbsp;
  <a href="https://github.com/mostafa-aly-sayed/WeatherApp">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mostafa-aly-sayed&repo=WeatherApp&theme=tokyonight" />
  </a>
</p>

---

## Tech Stack

### Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

### AI / ML / DL
<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-00897B?style=for-the-badge&logo=google&logoColor=white"/>
</p>

### Data & Visualization
<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-003B57?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
</p>

### APIs, Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
</p>

---

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| Deep Learning Specialization | DeepLearning.AI | March 2026 |
| Machine Learning Specialization | DeepLearning.AI | August 2024 |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mostafa-aly-sayed&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mostafa-aly-sayed&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

<p align="center">
  <sub>Open to collaborations, research projects, and freelance AI work · <a href="mailto:moustafaalyyy@gmail.com">moustafaalyyy@gmail.com</a></sub>
</p>
