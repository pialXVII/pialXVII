<div align="center">

# A. K. M Foyshal Sarkar

**Full-Stack Development · Applied Machine Learning & NLP**

Computer Science undergraduate at BRAC University, working across ML research and production web systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-foyshal--sarkar-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/foyshal-sarkar)
[![Email](https://img.shields.io/badge/Email-akmfoyshalsarkar@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:akmfoyshalsarkar@gmail.com)
[![Location](https://img.shields.io/badge/Dhaka-Bangladesh-2F855A?style=flat&logo=googlemaps&logoColor=white)](#)
## 🌐 Live Portfolio

[**View My Portfolio →**](https://portfolio-foyshal-sarkar.vercel.app/)

</div>

---

## About

I work at the intersection of machine learning research and full-stack engineering.

My undergraduate thesis extends **JEPA** (Joint-Embedding Predictive Architecture) with graph-conditioned attention for task-fMRI classification — injecting structural brain connectivity directly into the attention mechanism as an explicit graph bias.

On the engineering side I build multi-role web platforms in **TypeScript/Next.js** and **PHP/Laravel**, applied ML pipelines in **PyTorch** and **TensorFlow**, and embedded IoT systems on **ESP32/Arduino**.

- 🎓 B.Sc. Computer Science & Engineering, **BRAC University** — CGPA **3.71 / 4.00**, University Merit List Scholarship
- 🔬 Research focus: self-supervised learning, graph neural networks, medical image analysis
- 🌏 Bengali (native) · English (professional working proficiency) · Mandarin Chinese (currently learning)

---

## Research

### Graph-Conditioned Attention for Task-fMRI Classification (GC-JEPA)

`Self-Supervised Learning` · `Graph Neural Networks` · `Brain Connectivity Modeling` · `PyTorch`

Extended the Joint-Embedding Predictive Architecture with graph-conditioned attention, injecting structural brain connectivity into the attention mechanism as an explicit graph bias.

- Designed and implemented the full experimental pipeline: self-supervised pretraining followed by supervised fine-tuning for downstream classification
- Evaluated on the **Human Connectome Project (HCP)** Task-fMRI dataset across a 7-class task-state classification problem
- Ablation studies isolating each architectural component, with multi-seed evaluation to establish stability of reported results

---

## Featured Projects

### 🏗️ Buildora — Construction Lifecycle Platform

`Next.js 16` `React 19` `TypeScript` `Express 5` `MongoDB` `Socket.IO` `Zustand` `Tailwind CSS`

A multi-role platform serving **six actor types** — land owner, architect, structural engineer, contractor, material supplier and administrator — across the full building lifecycle.

- **Escrow-backed contracts** covering proposal submission, milestone claims, inspection sign-off and staged fund release
- **Real-time layer** over Socket.IO for messaging and notifications, extended with Web Push (VAPID) and transactional email
- **Security**: JWT authentication, bcrypt hashing, zod validation and helmet enforcing role-based access control, plus single-use hashed password-reset tokens with full session revocation
- **Cost estimator**: rate-table engine that recalculates as a project moves from brief to floor plans to BOQ to live bids, snapshotting every revision for variance tracking
- **Site reporting**: daily logs of per-trade labour counts, materials, equipment and issues aggregated into progress summaries and a rain-day tally used to justify schedule delays
- **LLM assistants** with tool calling over live database queries, automatic failover between Groq (Llama 3.3 70B) and Google Gemini, and vision-based National ID OCR verification
- **Integrations**: SSLCommerz payments (bKash, Nagad, Rocket, cards), Open-Meteo, OpenRouteService, Nominatim, Cloudinary
- Structured as a **pnpm + Turborepo monorepo** with shared TypeScript packages across web and API applications

### 🤖 [Samsung AI Phone Advisor](https://github.com/pialXVII/SamsungAI-PhoneAdvisor)

`Python` `FastAPI` `MySQL` `RAG` `FAISS` `CrewAI` `Transformers`

End-to-end system for querying Samsung smartphone data, running entirely locally on open-source models.

- **Scraper**: BeautifulSoup crawler over GSMArena, parsing free-text specifications into typed columns across a normalised MySQL schema (phones · specifications · prices)
- **RAG chatbot**: MiniLM embeddings in a FAISS index with intent routing — superlative questions become SQL rankings and comparisons fetch both spec sheets, so retrieval never has to infer ordering from embeddings
- **Multi-agent system**: CrewAI agents driven by a local Qwen2.5 model, where one agent retrieves specifications from the database and another writes the review from those facts
- **API**: FastAPI with 11 endpoints, Swagger documentation and a browser UI, covered by 37 automated tests

### 🧠 [Brain Tumor Detection via Multimodal Machine Learning](https://github.com/pialXVII/Brain-Tumor-Prediction)

`Python` `Vision Transformers` `Clinical Metadata` `Segmentation Features` `Random Forest`

Multimodal MRI classification pipeline fusing ViT embeddings, clinical metadata and segmentation-derived features.

- Built feature extraction and fusion components handling image, tabular and mask-based inputs within a single model
- Performed feature importance analysis and a critical review of data-alignment issues affecting multimodal fusion

### 💬 Question Topic Classification using NLP and Deep Learning

`Python` `PyTorch` `Scikit-learn` `TF-IDF` `Word2Vec (Skip-gram)`

Multi-class text classifier predicting topics across 10 categories with a full preprocessing and vectorisation pipeline.

- Implemented and compared **six architectures**: Logistic Regression, DNN, RNN, GRU, LSTM and bidirectional variants
- Tuned hyperparameters and evaluated on accuracy and **macro F1** to account for class imbalance

<details>
<summary><b>More projects</b></summary>

<br>

**🧪 [Mice Protein Expression Classification](https://github.com/pialXVII/Mice_protein_expression_ML_Project-CSE422-)** — `Python` `Scikit-learn` `TensorFlow/Keras`

End-to-end ML pipeline for multi-class classification with preprocessing, feature selection and scaling. Compared KNN, Logistic Regression, Decision Tree, Naive Bayes, Neural Network and K-Means under a shared evaluation protocol.

**📅 Smart Appointment Booking System** — `PHP` `Laravel` `MySQL`

Multi-role scheduling system supporting user, provider and administrator accounts. Booking, cancellation, automated reminders and post-appointment feedback, over a relational schema with a role-based access control layer governing each account type.

**🏠 [Home Security & Automation System](https://github.com/pialXVII/Robotics-Project)** — `Arduino` `ESP32` `C++` `IoT Sensors`

Sensor-based IoT system (RFID, PIR, flame, raindrop, temperature) providing automatic fan control, fire alerts, rain-triggered clothes protection and remote notifications, using servo motors and microcontroller-based automation to keep the build low-cost and self-contained.

**🎮 [Mood Bullet Arena — 3D Survival Game](https://github.com/pialXVII/Emotional_damage-)** — `Python` `OpenGL`

3D survival arena game with dynamic enemy behaviour and mood-based bullet mechanics, including player movement, camera control, enemy AI, bullet inventory, cheat mode and difficulty scaling.

</details>

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Machine Learning & NLP**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Zustand](https://img.shields.io/badge/Zustand-2D3748?style=flat&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socketdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Tools & Hardware**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat&logo=pnpm&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat&logo=turborepo&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat&logo=opengl&logoColor=white)

**Methods** — Self-supervised pretraining · Attention mechanisms · Graph neural networks · Multimodal fusion · Ablation study design · Multi-seed evaluation

---

## Education & Achievements

| Qualification | Details |
|---|---|
| **B.Sc. Computer Science & Engineering** — BRAC University | Sept 2022 – Present · CGPA **3.71 / 4.00** |
| **Higher Secondary Certificate (Science)** — Birshreshtha Munshi Abdur Rouf Public College | 2019 – 2021 · GPA **5.00 / 5.00** |
| **Secondary School Certificate (Science)** — Momtaz Mostofa Ideal School | 2017 – 2019 · GPA **5.00 / 5.00** |

🏅 **Duke of Edinburgh's International Award** — Bronze Standard
🎓 **University Merit List Scholarship**, BRAC University

---

<div align="center">

### GitHub Activity

![Stats](https://github-readme-stats.vercel.app/api?username=pialXVII&show_icons=true&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pialXVII&layout=compact&hide_border=true)

<br>

**Open to research collaborations and software engineering opportunities.**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/foyshal-sarkar)
[![Email](https://img.shields.io/badge/Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akmfoyshalsarkar@gmail.com)

</div>
