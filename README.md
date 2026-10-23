<p align="center">
  <img src="assets/name-detection.gif" width="1000" alt="Wilbert Andrew Yonathan — animated computer vision detection boxes around my name">
</p>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;size=21&amp;duration=2800&amp;pause=1100&amp;color=3B82F6&amp;center=true&amp;vCenter=true&amp;width=760&amp;height=42&amp;lines=Computer+Vision+%C2%B7+Deep+Learning;Efficient+AI+%C2%B7+Visual+Anomaly+Detection;Generative+AI+%C2%B7+Retrieval-Augmented+Generation;Reinforcement+Learning+%C2%B7+Autonomous+Agents" alt="Computer Vision · Deep Learning · Efficient AI · Visual Anomaly Detection · Generative AI · RAG · Reinforcement Learning">
</p>
<p align="center">
  <strong>Final-year AI Engineering student · Xiamen University Malaysia</strong><br>
  Building practical AI applications through research and engineering.
</p>
<p align="center">
  <a href="https://wilbert-andrew-yonathan.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Visit my portfolio"></a>
  <a href="https://www.linkedin.com/in/wilbert-andrew-yonathan-85562326a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cmVjdCB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHJ4PSIyIiBmaWxsPSIjMEE2NkMyIi8%2BPHRleHQgeD0iMyIgeT0iMTkiIGZpbGw9IndoaXRlIiBmb250LWZhbWlseT0iQXJpYWwsc2Fucy1zZXJpZiIgZm9udC1zaXplPSIyMCIgZm9udC13ZWlnaHQ9ImJvbGQiPmluPC90ZXh0Pjwvc3ZnPg%3D%3D" alt="Connect on LinkedIn"></a>
  <a href="https://huggingface.co/Wizzas"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&amp;logo=huggingface&amp;logoColor=black" alt="Explore my Hugging Face demos"></a>
  <a href="mailto:wilbertyonathan@gmail.com"><img src="https://img.shields.io/badge/Email-2563EB?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email me"></a>
</p>

## About me

I build **computer vision, efficient deep learning, and RAG-powered AI applications**. I enjoy developing and evaluating neural networks, working with visual data, and turning research prototypes into interactive applications using Python, PyTorch, OpenCV, and YOLO.

My work covers **object detection, image classification, visual anomaly inspection, retrieval-augmented generation, and reinforcement learning**. I also work across data preparation, model evaluation, backend integration, and cloud deployment, with an emphasis on reproducible experiments and clear reporting of model limitations.

- **Education:** Bachelor of Engineering in Artificial Intelligence, Xiamen University Malaysia (**September 2023–September 2027, expected**).
- **Academic record:** CGPA **3.77 / 4.00** · Dean’s List for **three consecutive semesters** · XMUM Merit Scholarship for the four-year undergraduate programme (**2023–2027**).
- **Internship availability:** **29 March 2027**, for **3–5 months**.
- **Open to:** AI/ML and Computer Vision internships, plus part-time and project-based collaboration, subject to availability and work authorisation.

## Featured projects

### PaddyLiteX · Paddy disease detection · Final-year thesis

Developed a PyTorch-based YOLOv8n detector using a **DenseLiteX backbone, SPPF and C2PSA** for nine paddy disease and health classes, achieving **81.67% mAP@0.5 on 803 test images**.

Compared with the **initial YOLOv8n-DenseNet121 proposal**, the final architecture reduced parameters by **68.01%** and GFLOPs by **72.59%**. I conducted ablation studies and deployed a three-model interactive comparison demo.

Python · PyTorch · Ultralytics YOLO · OpenCV<br>
[Repository](https://github.com/WAYTECHG/PaddyLiteX) · [Live demo](https://paddylitex.onrender.com/)

### DefectRAG · Visual anomaly inspection & evidence-grounded RAG

Built a visual inspection application for **12 VisA product categories** using a frozen **DINOv2** encoder, normal-reference comparisons, calibrated anomaly scores, and heatmaps. The project reports **95.13% mean image AUROC** in a *retrospective development evaluation*, not an independent external validation.

Integrated **BGE embeddings, LangChain, LangGraph, and Qwen** for cited RAG explanations. Developed a **React.js/FastAPI dashboard** for inspection history, reports and review workflows, using **Supabase (PostgreSQL)** for cloud collaboration, **SQLite** locally, and **Hugging Face ZeroGPU** for queued cloud inference.

Python · PyTorch · DINOv2 · LangChain · LangGraph · Qwen · React.js · FastAPI · Supabase · SQLite<br>
[Repository](https://github.com/WAYTECHG/DefectRAG) · [Live demo (Hugging Face Spaces)](https://huggingface.co/spaces/Wizzas/DefectRAG)

### MarineLite · Marine organism detection

Integrated **GhostConv and SimSPPF into DU-MobileYOLO** on URPC2020, increasing mAP@0.5 from **74.23% to 75.36%** while reducing parameters from **4.70M to 4.37M**.

I evaluated accuracy–complexity trade-offs through baseline and ablation experiments and deployed an interactive demo with bounding-box visualisation and model comparisons. The repository credits the original DU-MobileYOLO work.

Python · PyTorch · YOLO · OpenCV<br>
[Repository](https://github.com/WAYTECHG/GhostConv-and-SimSPPF-Integration-for-Marine-Organism-Detection) · [Live demo](https://marine-object-detection.onrender.com/)

### dPickleball · Autonomous reinforcement learning agent

Trained **Proximal Policy Optimization (PPO)** agents in Unity ML-Agents using a two-stage pipeline combining a six-level wall-training curriculum with league self-play. I experimented with reward and penalty configurations to develop movement, paddle rotation and ball-return behaviour.

Contributed candidate policies and round-robin evaluation to a **six-member team that placed 2nd among 13 teams in the final class competition**. The project builds on the [original dPickleBall environment](https://github.com/dPickleball/dPickleBallEnv).

Python · PyTorch · Unity ML-Agents · PPO<br>
[Repository](https://github.com/WAYTECHG/dpickleball-reinforcement-learning-agent) · [Watch the competition on YouTube](https://www.youtube.com/live/CitFn9FK12s)

### FER2013 · Facial expression recognition

Contributed **custom CNN development and evaluation, VGG16 fine-tuning and evaluation, and the main application code** to a team project classifying seven facial expressions. The custom CNN achieved **66.00% reported test accuracy** in the project evaluation.

The project also includes a browser demo for image uploads and webcam inference, with face detection, confidence scores and model switching.

Python · TensorFlow/Keras · OpenCV · scikit-learn · ONNX Runtime Web<br>
[Repository](https://github.com/WAYTECHG/FER2013-Project) · [Live demo](https://fer2013-project.onrender.com/)

## Technical skills

- **Programming:** Python, C, C++, SQL
- **Machine learning & data:** PyTorch, TensorFlow/Keras, scikit-learn, NumPy, pandas, OpenCV, LightGBM
- **Generative AI & NLP:** Natural Language Processing (NLP), Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), LangChain, LangGraph, Hugging Face Transformers
- **Web & APIs:** FastAPI, Flask, React (React.js), Gradio, Streamlit, REST APIs
- **Databases:** SQLite, Supabase (PostgreSQL)
- **Development & deployment:** Git, Docker, Render, Vercel, Hugging Face Spaces / ZeroGPU
- **Application services:** Resend
- **Reinforcement learning:** Unity ML-Agents, PPO, curriculum learning, reward shaping, league self-play

**Evaluation:** Dataset preparation, baseline comparisons, ablation studies, image AUROC, precision/recall and mAP.

## GitHub activity

<p align="center">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=WAYTECHG&amp;show_icons=true&amp;hide_rank=true&amp;hide_border=true&amp;bg_color=0B1323&amp;title_color=60A5FA&amp;icon_color=38BDF8&amp;text_color=CBD5E1&amp;custom_title=GitHub+Activity" alt="WAYTECHG GitHub activity statistics">
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=WAYTECHG&amp;layout=compact&amp;langs_count=6&amp;hide_border=true&amp;bg_color=0B1323&amp;title_color=60A5FA&amp;text_color=CBD5E1" alt="Most used languages in WAYTECHG's public repositories">
</p>
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

## Experience & leadership

- **Student Registration & Operations Assistant, Xiamen University Malaysia (April 2025):** Supported registration and event logistics with a team serving **800+ students**.
- **Head of Photography & Videography, Love in Action (February–March 2026):** Coordinated media coverage and edited outreach materials.
- **Head of General Affairs, XMUM AI Club (April–October 2025):** Coordinated logistics and external partners for a national-level AI event.

**Languages:** English, Mandarin, Indonesian, Malay and Hokkien.

## Let’s connect

Looking for someone to contribute to **computer vision, efficient deep learning, or RAG-powered AI applications**? Explore my [portfolio](https://wilbert-andrew-yonathan.vercel.app/), connect on [LinkedIn](https://www.linkedin.com/in/wilbert-andrew-yonathan-85562326a/), or [email me](mailto:wilbertyonathan@gmail.com).
