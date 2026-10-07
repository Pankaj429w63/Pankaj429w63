from reportlab.lib.pagesizes import A4
from reportlab.lib.styles import getSampleStyleSheet, ParagraphStyle
from reportlab.lib.enums import TA_CENTER
from reportlab.platypus import SimpleDocTemplate, Paragraph, Spacer, Preformatted, PageBreak
from reportlab.lib import colors
from reportlab.pdfbase.ttfonts import TTFont
from reportlab.pdfbase import pdfmetrics
from reportlab.lib.units import mm
import os, textwrap

out = "/mnt/data/Pankaj_Yadav_GitHub_README_2026_Copy_Paste.pdf"

readme = r'''<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,50:1d4ed8,100:312e81&height=190&section=header&text=PANKAJ%20YADAV&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%2FML%20ENGINEER%20%7C%20GENAI%20%7C%20MULTIMODAL%20AI%20%7C%20CLOUD%20%26%20MLOPS&descAlignY=62&descSize=17" width="100%"/>

### 👋 AI/ML Engineer | Generative AI | Multimodal AI | Cloud & MLOps

<p>
  <a href="https://www.linkedin.com/in/pankaj-yadav-0172162a2/">
    <img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Pankaj429w63">
    <img src="https://img.shields.io/badge/GITHUB-PANKAJ429W63-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.kaggle.com/pankajyadavbtech2023">
    <img src="https://img.shields.io/badge/KAGGLE-PROFILE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/pankajyadav200/">
    <img src="https://img.shields.io/badge/LEETCODE-PROFILE-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
  </a>
  <a href="https://www.hackerrank.com/profile/pankaj_yadav_bt1">
    <img src="https://img.shields.io/badge/HACKERRANK-PROFILE-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/>
  </a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=Pankaj429w63&label=PROFILE%20VIEWS&color=2563eb&style=for-the-badge" />
</p>

</div>

---

# 👋 About Me

I'm **Pankaj Yadav**, a final-year **B.Tech Artificial Intelligence & Machine Learning student at Symbiosis Institute of Technology, Pune**.

I build intelligent applications across **Machine Learning, Deep Learning, Generative AI, RAG, Multimodal AI, Computer Vision and backend engineering**, with a growing focus on **Cloud, DevOps and MLOps**.

My engineering mindset is:

```text
Problem
   ↓
Data
   ↓
Model
   ↓
Evaluation
   ↓
API
   ↓
RAG / Agents
   ↓
Docker
   ↓
CI/CD
   ↓
Cloud
   ↓
Production
```

### What I'm focused on

- 🤖 Machine Learning & Deep Learning
- 🧠 Generative AI & LLM Applications
- 🔎 Retrieval-Augmented Generation
- 🤝 Agentic AI & AI Workflows
- 🎥 Multimodal AI
- 👁️ Computer Vision
- 📝 NLP & Transformers
- ⚡ Python + FastAPI
- ☁️ Cloud & DevOps
- 🚀 MLOps & AI Deployment
- 🧩 Data Structures & Algorithms
- 🏗️ System Design for AI Applications

> **Career Target:** AI/ML Engineer • GenAI Engineer • ML Engineer • AI Engineer • MLOps Engineer • Cloud/AI Engineer

---

# 🚀 Engineering Focus

<div align="center">

### 🤖 AI / ML

`Machine Learning` `Deep Learning` `PyTorch` `TensorFlow` `Computer Vision` `NLP` `Transformers`

<br/>

### 🧠 Generative AI

`LLMs` `RAG` `Embeddings` `Vector Search` `FAISS` `LangChain` `LlamaIndex` `Ollama` `AI Agents`

<br/>

### ⚡ Backend

`Python` `FastAPI` `REST APIs` `Pydantic` `OpenAPI` `Async APIs`

<br/>

### 🌐 Full Stack

`React` `Vite` `TypeScript` `JavaScript` `API Integration`

<br/>

### ☁️ Cloud / DevOps

`Docker` `GitHub Actions` `Linux` `AWS` `Terraform` `Kubernetes` `CI/CD`

<br/>

### 📊 Data / Infrastructure

`SQL` `MySQL` `PostgreSQL` `Supabase` `Redis` `Kafka` `FAISS`

</div>

---

# 🚀 Pinned Projects

<table>
<tr>
<td width="50%">

## 🧠 Affectra AI

**Multimodal AI Intelligence Platform**

Text + Audio + Video → Fusion → Prediction → RAG → Agents

**Core Engineering**

- Multimodal AI
- PyTorch
- Transformers
- Vision
- Audio
- NLP
- Gated Fusion
- RAG
- FAISS
- AI Agents
- FastAPI
- React
- Docker

**Stack**

`PyTorch` `ViT` `Wav2Vec2` `Transformers` `FAISS` `LangChain` `FastAPI`

🔗 **[View Repository](https://github.com/Pankaj429w63/Affectra-AI)**

</td>

<td width="50%">

## 🌱 TerraMind AI

**Multimodal Agricultural Intelligence**

Plant Vision → Deep Learning → RAG → Agentic Decision Support

**Core Engineering**

- Computer Vision
- EfficientNet
- Transfer Learning
- PyTorch
- Agricultural RAG
- Agentic AI
- FastAPI
- React
- Docker

**Stack**

`PyTorch` `EfficientNet` `CV` `RAG` `LangChain` `Agents` `FastAPI`

🔗 **[View Repository](https://github.com/Pankaj429w63/Terramind-AI)**

</td>
</tr>

<tr>
<td width="50%">

## 💳 Multimodal AI Fraud Detection

**Financial Fraud Intelligence System**

Transactions + Complaints + KYC Images → Multimodal Risk Intelligence

**Architecture**

- Tabular Deep Learning
- NLP
- Computer Vision
- Multimodal Fusion
- Fraud Detection
- Risk Scoring

**Model Direction**

`TabTransformer` `FT-Transformer` `DeBERTa-v3-small` `ViT`

🔗 **[View Repository](https://github.com/Pankaj429w63/MULTIMODAL_AI_FRAUD_DETECTION_SYSTEM)**

</td>

<td width="50%">

## 🧑‍💼 TalentMind AI

**AI-Powered Recruitment Intelligence**

Python-first intelligent recruitment architecture focused on:

- Resume understanding
- Candidate screening
- Semantic matching
- RAG
- Explainable AI
- Agentic workflows
- Production backend
- Cloud / DevOps roadmap

**Stack**

`Python` `FastAPI` `RAG` `LLMs` `Agents` `PostgreSQL`

</td>
</tr>

<tr>
<td width="50%">

## 💰 AI Personal Finance

**Personal Finance & Expense Intelligence**

AI-powered financial analysis system designed to transform financial activity into intelligent insights.

**Focus**

`Python` `FastAPI` `SQL` `AI/ML` `RAG` `Financial Analytics`

🔗 **[View Repository](https://github.com/Pankaj429w63/ai-personal-finance)**

</td>

<td width="50%">

## 🎓 EduPilot Local AI

**On-Device AI Learning Assistant**

Designed around local AI and retrieval:

- Ollama
- Local LLM
- RAG
- FAISS
- Embeddings
- FastAPI
- React / Vite
- PDF Knowledge Base
- AI Chat
- Quiz Generation
- Flashcards

</td>
</tr>
</table>

<div align="center">

### → [Explore All Repositories](https://github.com/Pankaj429w63?tab=repositories)

</div>

---

# 🛠️ Tech Stack

<div align="center">

### Languages & Frameworks

<img src="https://skillicons.dev/icons?i=python,java,c,cpp,js,ts,react,vite,fastapi,flask" />

<br/><br/>

### AI / Machine Learning

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv" />

<br/><br/>

`Scikit-learn` `Pandas` `NumPy` `Transformers` `Hugging Face` `LangChain` `LlamaIndex`

<br/><br/>

### Data & Databases

<img src="https://skillicons.dev/icons?i=mysql,postgres,redis,supabase" />

<br/><br/>

`SQL` `FAISS` `ChromaDB` `Vector Search`

<br/><br/>

### Tools & Infrastructure

<img src="https://skillicons.dev/icons?i=git,github,docker,linux,githubactions,aws,terraform,kubernetes,nginx" />

</div>

---

# 🧠 AI Engineering Toolkit

| Domain | Technologies |
|---|---|
| **Machine Learning** | Regression, Classification, Clustering, KNN, SVM, Decision Trees, Naive Bayes, Ridge, Lasso |
| **Deep Learning** | CNN, Transfer Learning, EfficientNet, Xception, Vision Transformers |
| **NLP** | Transformers, DeBERTa, Sequence Classification, Embeddings |
| **Computer Vision** | OpenCV, Image Classification, KYC Verification, Plant Disease Detection |
| **Generative AI** | LLMs, Prompt Engineering, Embeddings, RAG, Agents |
| **Vector Search** | FAISS, ChromaDB, Semantic Search |
| **Backend** | Python, FastAPI, Flask, REST, Pydantic, OpenAPI |
| **Frontend** | React, Vite, TypeScript, JavaScript |
| **Databases** | MySQL, PostgreSQL, Supabase, Redis |
| **DevOps** | Git, GitHub, Docker, GitHub Actions, Linux |
| **Cloud** | AWS, Vercel, Render |
| **MLOps** | Model Serving, CI/CD, Experiment Tracking, Monitoring |
| **Distributed Systems** | Kafka, Redis, Event-Driven Architecture |

---

# 🏗️ How I Build AI Systems

I don't want my work to stop at:

```python
model.fit(X, y)
```

I am working toward the complete AI engineering lifecycle:

```text
Problem
   ↓
Data Engineering
   ↓
ML / DL / LLM
   ↓
Evaluation
   ↓
FastAPI / Inference
   ↓
RAG / AI Agents
   ↓
Docker
   ↓
CI / CD
   ↓
Cloud / MLOps
   ↓
Production AI System
```

### ☁️ Production AI Architecture

```text
                         👤 USER
                           │
                           ▼
                  ┌─────────────────┐
                  │ React / Web App │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ FastAPI Gateway │
                  └────────┬────────┘
                           │
             ┌─────────────┼─────────────┐
             │             │             │
             ▼             ▼             ▼
        PostgreSQL       Redis         Kafka
         Database        Cache      Event Stream
             │             │             │
             └─────────────┼─────────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │   AI / ML       │
                  │     Workers     │
                  └────────┬────────┘
                           │
                ┌──────────┴──────────┐
                │                     │
                ▼                     ▼
        ┌───────────────┐     ┌───────────────┐
        │ PyTorch / ML  │     │ Vector Search │
        │ Model Serving │     │ FAISS / DB    │
        └───────┬───────┘     └───────┬───────┘
                │                     │
                └──────────┬──────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ AI Response │
                    └──────┬──────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   Observability     │
                │ Prometheus/Grafana  │
                └─────────────────────┘


          GitHub
             │
             ▼
      GitHub Actions
             │
             ▼
          Docker
             │
             ▼
        AWS / Cloud
             │
             ▼
      Terraform / IaC
```

> My goal is to build AI systems that are **reproducible, testable, deployable, observable and scalable**.

---

# 🎓 Currently Learning & Sharpening

<div align="center">

![Generative AI](https://img.shields.io/badge/GENERATIVE_AI-7C3AED?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG_PIPELINES-2563EB?style=for-the-badge)
![Multimodal AI](https://img.shields.io/badge/MULTIMODAL_AI-0891B2?style=for-the-badge)
![Agentic AI](https://img.shields.io/badge/AGENTIC_AI-059669?style=for-the-badge)
![MLOps](https://img.shields.io/badge/MLOPS-DC2626?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS_CLOUD-FF9900?style=for-the-badge&logo=amazonaws&logoColor=black)
![System Design](https://img.shields.io/badge/SYSTEM_DESIGN-7C3AED?style=for-the-badge)

</div>

### Current Roadmap

```text
AI Engineering
      ↓
Generative AI
      ↓
RAG + Agents
      ↓
FastAPI + Backend
      ↓
Docker + CI/CD
      ↓
AWS
      ↓
MLOps
      ↓
Distributed AI Systems
      ↓
Kubernetes + Terraform
```

---

# 🏆 Certifications & Achievements

### Earned

🏅 **Certificate of Distinction — GREEN Olympiad for Youth (GO4Youth)**

### Certification Direction

☁️ AWS Cloud / AI  
🤖 Generative AI / Machine Learning  
⚙️ DevOps / Kubernetes  
🧠 Advanced AI Engineering

> I only list certifications that I have actually earned.

---

# 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Pankaj429w63&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github&theme=github_dark" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pankaj429w63&layout=compact&langs_count=10&hide_border=true&theme=github_dark" height="180"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Pankaj429w63&theme=github-dark-blue&hide_border=true" height="180"/>

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Pankaj429w63&theme=github_dark" width="95%"/>

</div>

---

# 🧩 Competitive Programming

<div align="center">

### 💻 Problem Solving

I use DSA and competitive programming to strengthen:

`Problem Solving` • `Algorithms` • `Complexity Analysis` • `Java` • `Python`

<br/>

<a href="https://leetcode.com/u/pankajyadav200/">
<img src="https://img.shields.io/badge/LEETCODE-PANKAJYADAV200-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>

<a href="https://www.hackerrank.com/profile/pankaj_yadav_bt1">
<img src="https://img.shields.io/badge/HACKERRANK-PANKAJ_YADAV-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/>
</a>

</div>

---

# 📅 Contribution Calendar

<div align="center">

<img src="https://ghchart.rshah.org/2563eb/Pankaj429w63" alt="Pankaj's GitHub Contribution Calendar" width="95%"/>

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Pankaj429w63/Pankaj429w63/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake"/>

</div>

---

# 👀 Visitor Analytics

<div align="center">

<img src="https://komarev.com/ghpvc/?username=Pankaj429w63&label=TOTAL%20PROFILE%20VIEWS&color=2563eb&style=for-the-badge"/>

<br/><br/>

**Thanks for visiting my profile!**

</div>

---

# 💡 Developer Philosophy

<div align="center">

> **Build before claiming.**  
> **Measure before celebrating.**  
> **Test before deploying.**  
> **Secure before exposing.**  
> **Automate before repeating.**  
> **Observe before optimizing.**  
> **Document before scaling.**

</div>

---

# 🤝 Open To

<div align="center">

### 🚀 AI/ML Engineering
### 🧠 Generative AI & LLM Applications
### 🔎 RAG & Agentic AI
### 🎥 Multimodal AI
### 👁️ Computer Vision / NLP
### ⚙️ MLOps & AI Infrastructure
### ☁️ Cloud / DevOps Engineering
### 💻 AI-focused Software Engineering

</div>

---

# 📫 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/pankaj-yadav-0172162a2/">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Pankaj429w63">
<img src="https://img.shields.io/badge/GITHUB-FOLLOW-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.kaggle.com/pankajyadavbtech2023">
<img src="https://img.shields.io/badge/KAGGLE-FOLLOW-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
</a>

<a href="https://leetcode.com/u/pankajyadav200/">
<img src="https://img.shields.io/badge/LEETCODE-PROFILE-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>

<a href="https://www.hackerrank.com/profile/pankaj_yadav_bt1">
<img src="https://img.shields.io/badge/HACKERRANK-PROFILE-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/>
</a>

<a href="https://www.instagram.com/pan_kajyadav2060_/?hl=en">
<img src="https://img.shields.io/badge/INSTAGRAM-FOLLOW-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

</div>

---

<div align="center">

### 🚀 Building intelligent systems from model → API → cloud → production.

**2026 • Learn Deeply • Build Publicly • Ship Consistently**

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:312e81,50:1d4ed8,100:111827&height=120&section=footer" width="100%"/>

</div>
'''

# Register a Unicode font if available; otherwise use a standard monospaced font.
font_path = "/usr/share/fonts/truetype/dejavu/DejaVuSansMono.ttf"
bold_path = "/usr/share/fonts/truetype/dejavu/DejaVuSansMono-Bold.ttf"
if os.path.exists(font_path):
    pdfmetrics.registerFont(TTFont("CodeMono", font_path))
if os.path.exists(bold_path):
    pdfmetrics.registerFont(TTFont("CodeMonoBold", bold_path))

doc = SimpleDocTemplate(
    out,
    pagesize=A4,
    rightMargin=12*mm,
    leftMargin=12*mm,
    topMargin=14*mm,
    bottomMargin=14*mm,
    title="Pankaj Yadav - GitHub README 2026",
    author="Pankaj Yadav",
)

styles = getSampleStyleSheet()
title_style = ParagraphStyle(
    "TitleCustom",
    parent=styles["Title"],
    fontName="Helvetica-Bold",
    fontSize=18,
    leading=22,
    alignment=TA_CENTER,
    textColor=colors.HexColor("#1d4ed8"),
    spaceAfter=8,
)
sub_style = ParagraphStyle(
    "Sub",
    parent=styles["Normal"],
    fontName="Helvetica",
    fontSize=9,
    leading=12,
    alignment=TA_CENTER,
    textColor=colors.HexColor("#444444"),
    spaceAfter=12,
)

story = [
    Paragraph("Pankaj Yadav — GitHub README 2026", title_style),
    Paragraph("Complete copy-paste version • Save as README.md in your profile repository", sub_style),
    Spacer(1, 4),
]

# Preformatted preserves Markdown indentation, code fences, tables, and URLs.
story.append(Preformatted(
    readme,
    ParagraphStyle(
        "Markdown",
        fontName="CodeMono" if os.path.exists(font_path) else "Courier",
        fontSize=5.6,
        leading=7.1,
        textColor=colors.HexColor("#111827"),
        leftIndent=0,
        rightIndent=0,
        spaceAfter=0,
    )
))

def footer(canvas, doc):
    canvas.saveState()
    canvas.setFont("Helvetica", 7)
    canvas.setFillColor(colors.HexColor("#6b7280"))
    canvas.drawCentredString(A4[0]/2, 7*mm, f"Pankaj Yadav • GitHub README 2026 • Page {doc.page}")
    canvas.restoreState()

doc.build(story, onFirstPage=footer, onLaterPages=footer)

print(f"Created: {out}")
