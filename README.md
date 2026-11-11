<p align="center">
  <img src="assets/banner.svg" width="900" alt="Wilbert Andrew Yonathan. Final-year AI Engineering student at Xiamen University Malaysia. Computer vision, generative AI and efficient deep learning. Open to internships from 29 March 2027.">
</p>

<p align="center">
  <a href="https://wilbert-andrew-yonathan.vercel.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/wilbert-andrew-yonathan/">LinkedIn</a> ·
  <a href="https://huggingface.co/Wizzas">Hugging Face</a> ·
  <a href="mailto:wilbertyonathan@gmail.com">Email</a>
</p>

---

## Hi, I'm Wilbert

I'm a final-year AI Engineering student at Xiamen University Malaysia. I build **computer vision, generative AI and efficient deep learning** systems end to end: train and evaluate the model, then ship it behind an API with a working UI, tests and CI.

**What I'm exploring**

- **Efficient detection:** lightweight YOLO variants that keep accuracy while cutting parameters and compute.
- **Visual anomaly detection:** finding defects from normal images only, with frozen or lightly fine-tuned foundation-model features.
- **Grounded LLM applications:** retrieval-augmented generation with citations and small fine-tuned models (QLoRA on an 8 GB GPU).
- **Reinforcement learning:** PPO, curriculum learning and self-play in Unity ML-Agents.

I care about reproducible experiments and reporting model limitations honestly.

## Projects

### [DefectRAG](https://github.com/WAYTECHG/DefectRAG): visual anomaly inspection with a cited assistant
Detects unusual products across 12 VisA categories without labelled defect images, shows heatmaps, and explains findings with a RAG assistant that quotes its sources.

- Detector: DINOv2 with its last 4 of 12 blocks fine-tuned on synthetic defects plus a coreset memory of normal patches. **0.971 mean image AUROC on VisA** (0.950 before fine-tuning and coreset memory) and **0.992 on MVTec AD**. VisA figures are descriptive, not independent validation.
- Assistant: BGE retrieval, LangChain and LangGraph, with Qwen2.5-3B fine-tuned using QLoRA. Correct quoted sources rose **from 42% to 89%** on 100 held-out questions (80 answerable, 20 not).
- Product: React and FastAPI dashboard, Supabase auth with TOTP MFA and row-level security, n8n corrective-action emails on AWS Lightsail, **500+ automated tests** in GitHub Actions CI with an approval-gated release.

`Python` `PyTorch` `DINOv2` `QLoRA` `LangChain` `LangGraph` `React` `FastAPI` `Supabase` `n8n` `Docker` `AWS` `GitHub Actions` · [Code](https://github.com/WAYTECHG/DefectRAG) · [Live demo](https://huggingface.co/spaces/Wizzas/DefectRAG)

### [PaddyLiteX](https://github.com/WAYTECHG/paddylitex-disease-detection): lightweight paddy disease detector (final-year thesis)
A YOLOv8n variant with a DenseLiteX backbone, SPPF and C2PSA for 9 paddy disease classes.

- **81.67% mAP@0.5** on 803 test images, with **68.01% fewer parameters and 72.59% fewer GFLOPs** than the initial YOLOv8n-DenseNet121 proposal.
- Ablation studies and an interactive three-model comparison demo.

`Python` `PyTorch` `Ultralytics YOLO` `OpenCV` · [Code](https://github.com/WAYTECHG/paddylitex-disease-detection) · [Demo](https://paddylitex.onrender.com/) · [Hugging Face Space](https://huggingface.co/spaces/Wizzas/PaddyLiteX)

### [MarineLite](https://github.com/WAYTECHG/marinelite-organism-detection): underwater organism detection
GhostConv and SimSPPF integrated into DU-MobileYOLO and evaluated on URPC2020: mAP@0.5 **74.23% → 75.36%** while parameters fall **4.70M → 4.37M**. Credits the original DU-MobileYOLO work.

`Python` `PyTorch` `YOLO` `OpenCV` · [Code](https://github.com/WAYTECHG/marinelite-organism-detection) · [Demo](https://marine-object-detection.onrender.com/)

### [dPickleball](https://github.com/WAYTECHG/dpickleball-rl-agent): reinforcement learning in Unity ML-Agents
Team project on the [dPickleBall environment](https://github.com/dPickleball/dPickleBallEnv): a 6-level wall-training curriculum followed by league self-play. My part was an independent PPO agent with tested reward and penalty settings (about 90 minutes per run, 4 checkpoints delivered); it reached the top 4 of the team's round-robin, and the team placed 2nd of 13.

`Python` `PyTorch` `Unity ML-Agents` `PPO` · [Code](https://github.com/WAYTECHG/dpickleball-rl-agent) · [Video](https://www.youtube.com/live/CitFn9FK12s)

*Render-hosted demos can take about a minute to wake on first load.*

## Tech stack

| | |
|---|---|
| **Languages** | <img src="https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=3776AB" alt="Python"> <img src="https://img.shields.io/badge/C-0F172A?style=flat-square&logo=c&logoColor=A8B9CC" alt="C"> <img src="https://img.shields.io/badge/C++-0F172A?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++"> <img src="https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/SQL-0F172A?style=flat-square" alt="SQL"> |
| **ML & Computer vision** | <img src="https://img.shields.io/badge/PyTorch-0F172A?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"> <img src="https://img.shields.io/badge/TensorFlow/Keras-0F172A?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow/Keras"> <img src="https://img.shields.io/badge/scikit--learn-0F172A?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn"> <img src="https://img.shields.io/badge/OpenCV-0F172A?style=flat-square&logo=opencv&logoColor=5C3EE8" alt="OpenCV"> <img src="https://img.shields.io/badge/YOLOv8-0F172A?style=flat-square" alt="YOLOv8"> <img src="https://img.shields.io/badge/DINOv2-0F172A?style=flat-square" alt="DINOv2"> |
| **GenAI & NLP** | <img src="https://img.shields.io/badge/LLMs_(Qwen)-0F172A?style=flat-square" alt="LLMs (Qwen)"> <img src="https://img.shields.io/badge/RAG-0F172A?style=flat-square" alt="RAG"> <img src="https://img.shields.io/badge/LangChain-0F172A?style=flat-square&logo=langchain&logoColor=2DD4BF" alt="LangChain"> <img src="https://img.shields.io/badge/LangGraph-0F172A?style=flat-square" alt="LangGraph"> <img src="https://img.shields.io/badge/LoRA/QLoRA-0F172A?style=flat-square" alt="LoRA/QLoRA"> <img src="https://img.shields.io/badge/Hugging_Face-0F172A?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face Transformers"> |
| **Data** | <img src="https://img.shields.io/badge/NumPy-0F172A?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy"> <img src="https://img.shields.io/badge/pandas-0F172A?style=flat-square&logo=pandas&logoColor=8B7CF6" alt="pandas"> <img src="https://img.shields.io/badge/SQLite-0F172A?style=flat-square&logo=sqlite&logoColor=38BDF8" alt="SQLite"> <img src="https://img.shields.io/badge/Supabase_(PostgreSQL,_Auth,_RLS)-0F172A?style=flat-square&logo=supabase&logoColor=3ECF8E" alt="Supabase (PostgreSQL, Auth, RLS)"> |
| **Web & APIs** | <img src="https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/FastAPI-0F172A?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI"> <img src="https://img.shields.io/badge/Gradio-0F172A?style=flat-square&logo=gradio&logoColor=FF7C00" alt="Gradio"> <img src="https://img.shields.io/badge/Streamlit-0F172A?style=flat-square" alt="Streamlit"> <img src="https://img.shields.io/badge/REST_APIs-0F172A?style=flat-square" alt="REST APIs"> <img src="https://img.shields.io/badge/HTML/CSS-0F172A?style=flat-square&logo=html5&logoColor=E34F26" alt="HTML/CSS"> |
| **Cloud & Deployment** | <img src="https://img.shields.io/badge/AWS_(Lambda,_Lightsail,_CloudWatch,_SNS,_IAM,_Budgets)-0F172A?style=flat-square" alt="AWS (Lambda, Lightsail, CloudWatch, SNS, IAM, Budgets)"> <img src="https://img.shields.io/badge/Docker-0F172A?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"> <img src="https://img.shields.io/badge/Docker_Compose-0F172A?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker Compose"> <img src="https://img.shields.io/badge/GitHub_Actions_(CI/CD)-0F172A?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions (CI/CD)"> <img src="https://img.shields.io/badge/Linux_(Ubuntu)-0F172A?style=flat-square&logo=ubuntu&logoColor=E95420" alt="Linux (Ubuntu)"> <img src="https://img.shields.io/badge/Hugging_Face_Spaces_(ZeroGPU)-0F172A?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face Spaces (ZeroGPU)"> <img src="https://img.shields.io/badge/Caddy-0F172A?style=flat-square&logo=caddy&logoColor=1F88C0" alt="Caddy"> <img src="https://img.shields.io/badge/Render-0F172A?style=flat-square&logo=render&logoColor=white" alt="Render"> <img src="https://img.shields.io/badge/Vercel-0F172A?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"> |
| **Tools & Automation** | <img src="https://img.shields.io/badge/Git-0F172A?style=flat-square&logo=git&logoColor=F05032" alt="Git"> <img src="https://img.shields.io/badge/pytest-0F172A?style=flat-square&logo=pytest&logoColor=0A9EDC" alt="pytest"> <img src="https://img.shields.io/badge/n8n-0F172A?style=flat-square&logo=n8n&logoColor=EA4B71" alt="n8n"> <img src="https://img.shields.io/badge/Webhooks-0F172A?style=flat-square" alt="Webhooks"> <img src="https://img.shields.io/badge/Resend-0F172A?style=flat-square&logo=resend&logoColor=white" alt="Resend"> |

<p align="center">
  <img src="https://raw.githubusercontent.com/WAYTECHG/WAYTECHG/output/streak.svg" alt="WAYTECHG's total contributions, current streak, and longest streak">
</p>
<!-- Generated from my contributions by .github/workflows/snake.yml. -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/WAYTECHG/WAYTECHG/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/WAYTECHG/WAYTECHG/output/github-snake.svg">
    <img src="https://raw.githubusercontent.com/WAYTECHG/WAYTECHG/output/github-snake.svg" alt="Animated snake following my GitHub contribution graph">
  </picture>
</p>

## Get in touch

Open to internships and project collaboration in computer vision, generative AI and efficient deep learning: [wilbertyonathan@gmail.com](mailto:wilbertyonathan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/wilbert-andrew-yonathan/) · [Portfolio](https://wilbert-andrew-yonathan.vercel.app/)
