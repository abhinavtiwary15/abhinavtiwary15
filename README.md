# 💫 About Me

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3000&color=00D2FF&center=true&vCenter=true&width=800&lines=Hello+World!+👋;I'm+Abhinav+Tiwary;AI+%2F+ML+Engineer;Focusing+on+Leakage-Free+Pipelines;Building+Production+LLM+%26+RAG+Systems)](https://github.com/abhinavtiwary15)

</div>

<img align="right" alt="Coding" width="380" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif">

## 👋 Hi there! I'm Abhinav Tiwary

I'm a **B.Tech CS (AI & ML) student** at **Arka Jain University** and an **AI/ML Engineer**. 

I care more about checking for target leakage and calculating the right economic threshold than chasing inflated benchmark scores. Experienced across the end-to-end ML lifecycle: preprocessing raw, messy real-world datasets strictly inside cross-validation folds, solving extreme class imbalance, and deploying agentic LLM workflows with deterministic safety gates.

- 🎓 **Microsoft Learn Student Ambassador (MLSA)**
- 💼 Former **AI/ML Engineer Intern** at **Venturing Digitally**
- 🏆 **Top 78** out of hundreds of teams across Asia at **Google Cloud's APAC GenAI Hackathon**
- 🛠️ Creator of **Students for Startups**

---

## 🎯 Current Focus
- 🛡️ **Leakage-Free ML**: Structuring production scikit-learn & `imblearn` pipelines to eliminate train/test contamination.
- 📉 **Cost-Sensitive Learning**: Deriving classification thresholds from actual asymmetric business risk instead of defaulting to 0.5.
- 🤖 **Reliable LLM Orchestration**: Building RAG systems with hard state gates, deterministic safety guards, and tool calling.
- 🚢 **Ship-Ready Inference**: Serving modular pipelines via **FastAPI**, **Docker**, and interactive **Streamlit** applications.

---

## 🌐 Connect With Me

<div align="left">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhinav-tiwary-ai)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhinavtiwary15)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/abhinavtiwary)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhinavtiwary498@gmail.com)

</div>

---

## 💻 Tech Stack

### **Machine Learning & Data Science**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB3C00?style=for-the-badge&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-4479A1?style=for-the-badge&logo=sparkpost&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### **LLM, Agents & NLP**
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### **Deployment, Databases & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

---

## 🚀 Featured Engineering Systems

### 🧠 Mitra AI — NLP Intervention & Human Reconnection Pipeline
**Tech:** `FastAPI` $\cdot$ `spaCy` $\cdot$ `PostgreSQL` $\cdot$ `Streamlit` $\cdot$ `Docker`  
A rule-based + LLM architecture featuring an **anti-engagement gate** that locks chat sessions until real-world social outreach actions are reported.
* 🛡️ **Deterministic Gating:** Crisis detection and priority ranking run completely independent of LLM calls.
* ⚙️ Swappable provider abstraction (Groq / Gemini / Mistral) with JSON output schemas and 34 automated unit tests.

### 💳 Credit Card Fraud Detection — Imbalance-Calibrated Classifier
**Tech:** `scikit-learn` $\cdot$ `XGBoost` $\cdot$ `imbalanced-learn (SMOTE)` $\cdot$ `Streamlit`  
An end-to-end classification pipeline built for extreme class imbalance (0.17% fraud rate across 284k+ transactions).
* 🔒 **Zero Leakage:** Enforced `SMOTE` and cyclical hour-of-day scaling strictly within CV folds via `imblearn.pipeline`.
* 🎯 **Threshold Tuning:** Shifted the classification threshold across the PR curve to 0.9793, jumping precision from 36.1% to **87.5%** while retaining 78.6% recall.

### 📉 Customer Churn Prediction — Cost-Optimized Classification
**Tech:** `scikit-learn` $\cdot$ `XGBoost` $\cdot$ `LightGBM` $\cdot$ `Streamlit`  
Framed churn detection around asymmetric business loss ($1,000 missed-churn cost vs. $50 retention offer) instead of accuracy.
* 💰 **Economic Thresholding:** Derived $\tau^* = 0.09$, boosting recall from 56.1% to **95.7%** (catching 358 of 374 churners).
* 📉 Prevented ~$45,000 in expected cost on the holdout split; includes an interactive Streamlit ROI simulator.

### 🏠 Bengaluru House Price Prediction — Leakage Identification & Fix
**Tech:** `scikit-learn` $\cdot$ `XGBoost` $\cdot$ `pandas` $\cdot$ `joblib`  
Diagnosed a pipeline defect where test $R^2$ (0.832) implausibly beat CV $R^2$ (0.696) due to global target-derived filtering.
* 🔬 Computed outlier bounds strictly inside training splits; verified the fix when cross-validation and test scores converged (0.543 vs 0.561).
* 📊 Applied log-target regression with price-quartile residual diagnostics to audit luxury tier error distribution.

---

## 📊 GitHub Analytics

<div align="center">

[![Abhinav's GitHub Stats](https://github-readme-stats.vercel.app/api?username=abhinavtiwary15&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/abhinavtiwary15)
[![Abhinav's Streak](https://github-readme-streak-stats.herokuapp.com/?user=abhinavtiwary15&theme=tokyonight&hide_border=true)](https://github.com/abhinavtiwary15)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=abhinavtiwary15&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/abhinavtiwary15)

[![Abhinav's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=abhinavtiwary15&theme=tokyo-night&hide_border=true)](https://github.com/abhinavtiwary15)

</div>

---

## 🏆 Certifications & Milestones
- 🌐 **Microsoft:** Certified Azure AI Fundamentals
- 💼 **IBM:** AI Engineering Professional Certificate
- ☁️ **Google Cloud:** Generative AI Leader
- 🦜 **DeepLearning.AI:** LangChain for LLM Application Development
- 🥇 **Google Cloud APAC Gen AI Hackathon:** Rank 78 across Asia

---

<div align="center">

**Built with precision, cross-validated with care.** *© Abhinav Tiwary*

</div>
