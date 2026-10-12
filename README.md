<p align="center">
  <img src="assets/name-detection.gif" width="1000" alt="Wilbert Andrew Yonathan — animated computer vision detection boxes around my name">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;size=21&amp;duration=2800&amp;pause=1100&amp;color=3B82F6&amp;center=true&amp;vCenter=true&amp;width=760&amp;height=42&amp;lines=Computer+Vision+%C2%B7+Deep+Learning;Lightweight+Models+%C2%B7+Efficient+AI;Reinforcement+Learning+%C2%B7+Autonomous+Agents" alt="Computer Vision · Deep Learning · Lightweight Models · Efficient AI · Reinforcement Learning · Autonomous Agents">
</p>

<p align="center">
  <strong>Final-year AI Engineering student · Xiamen University Malaysia</strong><br>
  Building practical AI applications through research and engineering.
</p>

<p align="center">
  <a href="https://wilbert-andrew-yonathan.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Visit my portfolio"></a>
  <a href="https://www.linkedin.com/in/wilbert-andrew-yonathan-85562326a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cmVjdCB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHJ4PSIyIiBmaWxsPSIjMEE2NkMyIi8%2BPHRleHQgeD0iMyIgeT0iMTkiIGZpbGw9IndoaXRlIiBmb250LWZhbWlseT0iQXJpYWwsc2Fucy1zZXJpZiIgZm9udC1zaXplPSIyMCIgZm9udC13ZWlnaHQ9ImJvbGQiPmluPC90ZXh0Pjwvc3ZnPg%3D%3D" alt="Connect on LinkedIn"></a>
  <a href="https://huggingface.co/Wizzas"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&amp;logo=huggingface&amp;logoColor=black" alt="Explore my Hugging Face demos"></a>
  <a href="mailto:30587wilbertandrewyonathan@gmail.com"><img src="https://img.shields.io/badge/Email-2563EB?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email me"></a>
</p>

## About me

I build **computer vision pipelines and interactive AI applications** using Python, PyTorch, OpenCV, and YOLO. My projects focus on efficient object detection, facial expression recognition, and autonomous reinforcement learning agents.

I work across dataset preparation, model development, training, evaluation, and application deployment, with an emphasis on **reproducible experiments, leakage-free evaluation, and clear model comparisons**.

- **Academic record:** CGPA **3.77 / 4.00** · Dean’s List · XMUM Merit Scholarship for the four-year undergraduate programme (**2023–2027**).
- **Internship availability:** **29 March 2027**, for **3–5 months**.
- **Open to:** AI/ML and Computer Vision internships, plus part-time and project-based collaboration, subject to availability and work authorisation.

## Featured projects

### PaddyLiteX · Paddy disease detection · Final-year thesis

Built a YOLOv8n baseline with a DenseNet-121 backbone, then developed a lighter DenseLiteX backbone with SPPF and C2PSA for nine-class paddy disease detection. The proposed model achieved **81.67% mAP@0.5**, compared with 80.69% for the DenseNet-121-based baseline, using 68.01% fewer parameters and 72.59% lower GFLOPs.

Compared with original YOLOv8n, it achieved 0.88 percentage points higher mAP@0.5 with 4.24% fewer parameters. I prepared annotations, conducted baseline and ablation experiments, and built an interactive demo comparing all three models under consistent dataset splits.

Python · PyTorch · Ultralytics YOLO · OpenCV  
[Repository](https://github.com/WAYTECHG/PaddyLiteX) · [Live demo](https://paddylitex.onrender.com/)

### MarineLite · Marine organism detection

Adapted DU-MobileYOLO with GhostConv and SimSPPF on URPC2020, increasing mAP@0.5 from 74.23% to **75.36%** while reducing parameters from 4.70M to 4.37M, a 7.02% reduction.

I evaluated accuracy–complexity trade-offs through baseline and ablation experiments and deployed an interactive demo with bounding-box visualisation and model comparisons. The repository credits the original DU-MobileYOLO work.

Python · PyTorch · YOLO · OpenCV  
[Repository](https://github.com/WAYTECHG/GhostConv-and-SimSPPF-Integration-for-Marine-Organism-Detection) · [Live demo](https://marine-object-detection.onrender.com/)

### dPickleball · Autonomous reinforcement learning agent

Trained a PPO agent in Unity ML-Agents using a two-stage pipeline combining a six-level wall-training curriculum with league self-play. I experimented with reward and penalty configurations to develop movement, paddle rotation and ball-return behaviour.

I contributed candidate policies and participated in collaborative tournament evaluation and final agent selection, helping the team achieve **2nd place in the competition**. The project builds on the [original dPickleBall environment](https://github.com/dPickleball/dPickleBallEnv).

Python · PyTorch · Unity ML-Agents · PPO  
[Repository](https://github.com/WAYTECHG/dpickleball-reinforcement-learning-agent) · [Watch the competition on YouTube](https://www.youtube.com/live/CitFn9FK12s)

### FER2013 · Facial expression recognition

Trained and compared a custom CNN with VGG16, MobileNetV2 and ResNet50 for classification across seven facial expression categories. The custom CNN achieved **66.00% reported test accuracy**, outperforming the three transfer learning models in the project evaluation.

Built a browser demo for image uploads and webcam inference with face detection, confidence scores and model switching. Evaluation includes confusion matrices, class-wise metrics, ROC curves and saved Grad-CAM visualisations.

Python · TensorFlow/Keras · OpenCV · scikit-learn · ONNX Runtime Web  
[Repository](https://github.com/WAYTECHG/FER2013-Project) · [Live demo](https://fer2013-project.onrender.com/)

## Tech stack

**Programming & tooling**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

**Machine learning & computer vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-042AFF?style=flat)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Reinforcement learning**

![Unity ML-Agents](https://img.shields.io/badge/Unity_ML--Agents-222222?style=flat&logo=unity&logoColor=white)
![PPO](https://img.shields.io/badge/PPO-2563EB?style=flat)

Curriculum learning · Reward shaping · League self-play · Policy evaluation

**Data & deployment**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Applied skills:** CNNs · DenseNet · ResNet · Image classification · Object detection · Reinforcement learning · RAG · Embeddings · Reference retrieval

**Evaluation:** Dataset preparation · Leakage prevention · Baseline comparisons · Ablation studies

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

## Leadership & collaboration

- **Head of General Affairs, XMUM AI Club** — project coordination, logistics, and team communication.
- **Head of Photography and Videography, Community Service** — production planning, directing, editing, and asset management.
- **AIESEC involvement** — committee collaboration and fundraising-event support.

## Let’s connect

Looking for someone to contribute to **computer vision, efficient deep learning, or reinforcement learning**? Explore my [portfolio](https://wilbert-andrew-yonathan.vercel.app/), connect on [LinkedIn](https://www.linkedin.com/in/wilbert-andrew-yonathan-85562326a/), or [email me](mailto:30587wilbertandrewyonathan@gmail.com).
