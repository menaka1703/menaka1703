# 👋 Hi, I’m Menaka K! 🚀

**Data Science Enthusiast | AI & ML Innovator | Real-Time Tech Builder**

>🎓 Currently pursuing **M.Sc in Data Science** @ *SASTRA Deemed to be University*  
>🔍I specialize in **AI-driven applications**, **predictive modeling**, and **real-time systems** using cutting-edge technology. I’m passionate about building innovative solutions that impact healthcare and business optimization.

---

## 🌟 About Me

Welcome to my data-driven world! I’m **Menaka K**, a dedicated and curious **Data Science professional** with a solid foundation in **mathematics** and hands-on expertise in **Machine Learning**, **Deep Learning**, **Computer Vision**,**NLP** and **Generative AI**.

- **What Drives Me:** A passion for tech, an obsession with impact, and a love for experimentation. I enjoy blending innovation with utility to create solutions that truly make a difference.

- **Career Goal:** To become a leading **AI architect and problem-solver**, designing intelligent systems that empower industries and people—especially in critical areas like healthcare, transport, and automation.

- **My Vibe:** Think of me as a hybrid of a data scientist and AI engineer—someone who codes smart, builds sharp, and thinks ahead.

---

## 🛠️ Technical Skill Set

Here’s a snapshot of my core technical skills—well-rounded, battle-tested, and ready to tackle real-world data and AI challenges.

## 🚀 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

## 🛠️ Tools
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 💻 Operating Systems
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

## 📚 Frameworks
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

---
## 🚀 Projects

### 🤖 Smart AI Interview System for Recruitment & Skill Assessment

I created the **Smart Interview System**, a web platform that uses AI to make hiring **faster**, **fairer**, and **more efficient**. It automates three major interview types:

1. Aptitude Tests  
2. Q&A Interviews  
3. HR Interviews (automated or live)
- 🧠 **Aptitude Test:** Scored spoken answers with TF-IDF.
- 💬 **Q&A Interviews:** Sentence Transformers select job-relevant questions, LLaMA 2 generates QA pairs, and TF-IDF scores responses.
- 👤 **HR Interview:** LLaMA 3.2 evaluates open-ended answers on clarity and relevance.
- 🎯 **Monitoring:** YOLOv5 ensures one person; Faster R-CNN detects mobile phones. 3 violations auto-end the interview.
- 🗣️ **Speech Recognition:** Google Web Speech API converts voice to text.
- 📊 **Admin Dashboard:** Displays scores, trends, and reports.

**Tech Used:** FastAPI, Bootstrap, YOLOv5, Faster R-CNN, TF-IDF, LLaMA 2/3.2, Sentence Transformers, Google Web Speech API  

### 📄 Multimodal PDF Q&A Chatbot using OCR and Local LLM

Built an interactive PDF QA system that understands both text and images from uploaded documents.

- 🖼️ **Image-to-Text:** Used Tesseract OCR + PyMuPDF to extract text from images.
- 🧠 **Semantic Retrieval:** LangChain + HuggingFace embeddings (MiniLM-L6-v2), stored in FAISS.
- 🔍 **Smart Answering:** Enhanced relevance using Maximal Marginal Relevance (MMR).
- 🤖 **LLM Response Generation:** Queried local LLaMA2 model (via Ollama) with custom prompts.
- 💻 **User Interface:** Deployed using Streamlit for real-time uploads and chat-style querying.

**Tech Used:** Tesseract OCR, PyMuPDF, LangChain, FAISS, HuggingFace, LLaMA2 (Ollama), Streamlit

### 🧬 Disease Prediction System

A Streamlit web app that predicts diseases based on selected symptoms using AI.

- 🩺 **Model:** XGBoost trained on a symptom–disease dataset.
- 🧹 **Preprocessing:** One-hot encoding, SMOTE for class balance.
- 🎯 **Feature Selection:** Top 50 symptoms via SelectKBest.
- 🔧 **Tuning:** RandomizedSearchCV to optimize performance.
- 📊 **Output:** Predicts diseases with probabilities (e.g., “Flu: 85%”).
- 💻 **UI:** Simple, user-friendly interface built with Streamlit.

**Tech Used:** XGBoost, SMOTE, SelectKBest, RandomizedSearchCV, Streamlit

### 🛡️ Seatbelt Detection System with Vision Transformer

AI-powered system to detect seatbelt usage from roadside camera images for improved traffic safety.

- 🧠 **Model:** Fine-tuned Vision Transformer (ViT) with custom fully connected layers.
- 🖼️ **Preprocessing:** Image resizing, augmentation, normalization, and dropout.
- 🛠️ **Training:** Trained with AdamW optimizer, early stopping over 50 epochs.
- 📉 **Challenge Solved:** Reduced overfitting while achieving high accuracy.
- 🚗 **Impact:** Helps enforce seatbelt use via automated camera analysis.

**Tech Used:** Vision Transformer (ViT), PyTorch, AdamW, Data Augmentation, Early Stopping

### 🚗 AI-Powered Road Safety Analysis System

A multi-modal AI system to predict road accidents and detect risks like potholes from images and voice input.

- 📊 **Forecasting:** Cleaned a 2020 traffic accident dataset and used a Deep Learning Model Like **Transformer**, **ARIMA**, **LSTM**, **TCN**, **Prophet**  to predict daily accident trends.
- 🖼️ **Image Risk Detection:** Used **LLaVA** to analyze uploaded road images for dangers (e.g., potholes).
- 🎙️ **Voice Input:** Used **Whisper** to convert questions (English/Tamil) into text; **LLaVA** answers and **gTTS** speaks it back.
- 🌐 **User Interface:** Built using **Gradio** for interactive, multilingual access.
- ⚙️ **Optimization:** Removed noisy data and deployed a lightweight LLaVA model for faster response.

**Tech Used:** Transformer, ARIMA, LSTM, Prophet, TCN, TensorFlow, LLaVA, Whisper, gTTS, Gradio

---

## 💼 Real-World Experience

### AI & ML Intern @ VDart  
*Jan 2025 – May 2025*

- **Mentor:** Mr. Derrick Alex — a visionary in AI who helped me navigate advanced real-world projects.
- **What I Did:** Built and deployed AI-powered applications with real-time capabilities using tools like FastAPI.
- **Big Wins:**
  - Engineered a **Smart AI Interview System** with automated evaluation, face/mobile detection, and real-time scoring.
- **Why It Rocked:** This internship pushed me to apply theory in production-like environments and build systems that are scalable, smart, and impactful.

---
# 📊 GitHub Stats and Activity:

<table>
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=Sundar-Data-Scientist&theme=shades-of-purple&hide_border=false&include_all_commits=false&count_private=false" alt="Sundar's GitHub Stats" /></td>
    <td><img src="https://nirzak-streak-stats.vercel.app/?user=Sundar-Data-Scientist&theme=shades-of-purple&hide_border=false" alt="GitHub Streak" /></td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sundar-Data-Scientist&theme=shades-of-purple&hide_border=false&layout=compact" alt="Most Used Languages" />
</p>

## 📬 Contact Me

- 📧 **Email**: [velsundar490@gmail.com](mailto:velsundar490@gmail.com)  
- 🔗 [LinkedIn](http://www.linkedin.com/in/sundar-v-389bb4310)  
- 📍 **Location**: Virudhachalam, Tamil Nadu
