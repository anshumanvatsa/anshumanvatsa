<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b27,100:1e3a5f&height=200&section=header&text=Anshuman%20&fontSize=52&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=ML%20Engineer%20%E2%80%A2%20Full-Stack%20Developer%20%E2%80%A2%20AI%20Builder&descSize=18&descAlignY=60&descColor=8b949e" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&random=false&width=750&lines=Engineering+intelligent+systems+%E2%80%94+idea+to+production+%F0%9F%9B%A0%EF%B8%8F;Bharat+Truth+Lens+%E2%80%94+AI+Fact-Checking+for+India+%F0%9F%87%AE%F0%9F%87%B3;Multi-Platform+Engagement+Predictor+%E2%80%94+F1%3D0.87+%F0%9F%93%8A;ML+Intern+%40+Deuglo+%7C+Final+Year+%40+VIT+Chennai+%F0%9F%8E%93;Turning+research+into+production-ready+products+%F0%9F%92%A1" alt="Typing SVG" />

<br/><br/>

[![Profile Views](https://komarev.com/ghpvc/?username=anshumanvatsa&color=58a6ff&style=flat-square&label=Profile+Views)](https://github.com/anshumanvatsa)
[![GitHub followers](https://img.shields.io/github/followers/anshumanvatsa?style=flat-square&color=58a6ff&label=Followers)](https://github.com/anshumanvatsa?tab=followers)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/anshuman-vatsa-mishra)

</div>

---

## ⚡ About Me

```python
anshuman = {
    "role"      : "ML Intern @ Deuglo | Final Year CS @ VIT Chennai",
    "latest"    : [
        "Bharat Truth Lens — Hybrid NLP fact-checker for Indian democracy 🇮🇳",
        "Multi-Platform Engagement Predictor — LightGBM, F1=0.87, AUC=0.94 📊",
    ],
    "research"  : "Two-Stage Social Media Intelligence System — Target: IEEE Access",
    "interests" : ["LLMs", "MLOps", "Full-Stack AI", "NLP", "Real-time Systems"],
    "reach_me"  : "atulvatsamishra@gmail.com"
}
```

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🇮🇳 [Bharat Truth Lens](https://github.com/anshumanvatsa/bharat-truth-lens)

**AI-powered fake news detection & civic engagement platform for India.**

- 🧠 Fine-tuned **DistilBERT** on 12,836 LIAR dataset samples (6-class)
- 🔗 **4-layer hybrid pipeline**: DistilBERT → Evidence Retrieval (Wikipedia + Tavily) → Semantic Similarity → Credibility Weighting
- 📈 **+7.9% Macro F1** improvement (ablation study on 500 FEVER samples)
- 🗳️ Real **1-person-1-vote** virtual PM election across all 36 states/UTs
- 🤖 **Groq LLaMA-3.1-8B** for cloud AI reasoning
- 🔐 JWT auth + bcrypt + MongoDB Atlas

`FastAPI` `DistilBERT` `Groq LLaMA-3` `React 18` `TypeScript` `MongoDB Atlas`

[![Live Demo](https://img.shields.io/badge/🌐_Live-bharat--truth--lens.vercel.app-22c55e?style=for-the-badge)](https://bharat-truth-lens.vercel.app)
[![API Docs](https://img.shields.io/badge/📖_API_Docs-onrender.com/docs-009688?style=for-the-badge)](https://bharat-truth-lens.onrender.com/docs)

</td>
<td width="50%" valign="top">

### 📊 [Multi-Platform Engagement Predictor](https://github.com/anshumanvatsa/multi-platform-engagement-predictor)

**Social media engagement predictor trained on 800K+ posts.**

- 🚀 **LightGBM** classifier — **F1 = 0.87**, **AUC = 0.94**
- 🌐 Covers **Facebook, TikTok, Twitter & YouTube** in a single model
- 🔍 **SHAP explainability** — per-prediction feature importance
- ⚡ Pre-publication constraints: only features known *before* posting
- 📊 Per-platform bias analysis & calibration curves
- 🔗 FastAPI inference endpoint + React dashboard

`LightGBM` `XGBoost` `SHAP` `FastAPI` `React` `Python` `Scikit-learn`

[![GitHub](https://img.shields.io/badge/🔗_View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/anshumanvatsa/multi-platform-engagement-predictor)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 [CarePredict AI](https://github.com/anshumanvatsa/care-predict-ai-v1)
**Full-stack clinical AI platform** — predicts 90-day patient deterioration risk across 4 chronic conditions using a Multi-Task PyTorch LSTM. Features 5-tab results dashboard with explainability, risk stratification, and CSV export.

`FastAPI` `PyTorch LSTM` `React` `XGBoost` `Supabase` `Render`

[![Live](https://img.shields.io/badge/Live-care--predict--ai.vercel.app-brightgreen?style=flat-square)](https://care-predict-ai.vercel.app)

</td>
<td width="50%" valign="top">

### ☁️ [CloudPilot DevOps](https://github.com/anshumanvatsa/cloudpilot-devops-platform)
**Production DevOps dashboard** — replicating Vercel/Render/AWS functionality with real-time CPU/memory/network metrics via WebSockets, deployment management (build/rollback), log streaming, and severity-based alerts.

`FastAPI` `React` `TypeScript` `Docker` `AWS EC2` `Redis` `PostgreSQL`

[![Live](https://img.shields.io/badge/Live-cloudpilot.sslip.io-brightgreen?style=flat-square)](http://cloudpilot.13.60.57.168.sslip.io)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [AutoStream AI Agent](https://github.com/anshumanvatsa/AutoStream-AI-Agent)
**Conversational AI lead-capture agent** — converts user chats into qualified leads via LangGraph-controlled workflows: intent detection → RAG retrieval → structured lead capture. Supports WhatsApp Business API.

`LangGraph` `Groq LLM` `RAG` `FastAPI` `React` `TypeScript`

</td>
<td width="50%" valign="top">

### 🏗️ [Construction Digital Twin](https://github.com/anshumanvatsa/construction-digital-twin)
**Real-time IoT construction site simulator** — live WebSocket-driven worker movement, hazard zone tracking, safety risk analytics, and a full operations dashboard. 12+ sensor types simulated.

`FastAPI` `WebSockets` `React` `Redis` `PostgreSQL` `TypeScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🫀 [Heart Disease Predictor](https://github.com/anshumanvatsa/Heart-Disease-Predictor)
**ML research pipeline** — compares 4 classifiers (LR, Random Forest, XGBoost, MLP) on the UCI Cleveland dataset with full SHAP explainability. Best model: Random Forest at 82% accuracy, AUC-ROC 0.912.

`scikit-learn` `XGBoost` `SHAP` `Python` `Jupyter`

</td>
<td width="50%" valign="top">

### 🔐 [Selective Encryption](https://github.com/anshumanvatsa/Selective-Encryption)
**Production-grade security system** — AES-256-GCM field-level encryption with JWT auth, Role-Based Access Control, file encryption, full audit logging, Docker orchestration, and CI/CD observability.

`FastAPI` `React` `AES-256-GCM` `JWT` `RBAC` `Docker`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-8A2BE2?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-LLM%20Workflows-00A67E?style=for-the-badge)

**Full-Stack**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=anshumanvatsa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anshumanvatsa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="165" />

<br/>

<img src="https://streak-stats.demolab.com?user=anshumanvatsa&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=anshumanvatsa&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&hide_border=true&area_color=1e3a5f" width="100%"/>

</div>

---

## 🧠 Currently Working On

```
🇮🇳 Bharat Truth Lens (LIVE → bharat-truth-lens.vercel.app)
   └── Hybrid NLP pipeline: DistilBERT → Evidence → Semantic → Credibility
       ├── +7.9% Macro F1 improvement on FEVER benchmark
       ├── Real civic voting system: 36 states/UTs, age-wise breakdown
       └── Groq LLaMA-3.1-8B for cloud inference (no GPU needed)

📊 Multi-Platform Engagement Predictor (LightGBM · F1=0.87 · AUC=0.94)
   └── 800K+ posts across Facebook, TikTok, Twitter, YouTube
       ├── SHAP explainability + per-platform bias analysis
       └── Pre-publication constraints (no data leakage)

📍 ML Intern @ Deuglo — DG-Social Production Platform
   └── Two-Stage Social Media Intelligence System (Target: IEEE Access)
       ├── Stage 1: Pre-publication engagement predictor
       └── Stage 2: TGN-based real-time virality tracker
```

---

## 🏆 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=anshumanvatsa&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=4" />
</div>

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anshuman%20Mishra-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anshuman-vatsa-mishra)
[![GitHub](https://img.shields.io/badge/GitHub-anshumanvatsa-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anshumanvatsa)
[![Email](https://img.shields.io/badge/Email-atulvatsamishra%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atulvatsamishra@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f,50:1a1b27,100:0d1117&height=100&section=footer" width="100%"/>

</div>
