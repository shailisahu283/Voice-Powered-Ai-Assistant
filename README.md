# Voice-Powered-Ai-Assistant

> **"Ask anything, get answers instantly – through voice!"**  
> This project is a voice-interactive AI assistant that listens to your question 🎤, fetches accurate facts from **Wikipedia 📚**, and if not found, falls back to a **Generative AI model** (Google FLAN-T5) for an answer.  
> Completed in just **2 weeks 🚀**.

---

## 📋 Table of Contents
1. [✨ Features](#-features)
2. [📅 Project Timeline](#-project-timeline)
3. [⚙️ How It Works](#%EF%B8%8F-how-it-works)
4. [📂 Code & Resources](#-code--resources)
5. [📹 Demo Video](#-demo-video)
6. [☁️ Colab Link](#%EF%B8%8F-colab-link)
7. [🙏 Acknowledgment](#-acknowledgment)

---

## ✨ Features
- 🗣 **Voice input** – Speak your question naturally.
- 📚 **Wikipedia fact retrieval** – Accurate answers for known facts.
- 🤖 **AI fallback** – If facts aren't available, the AI generates a short answer.
- 🔊 **Speech output** – Hear the answer instantly.
- 🌐 **Hybrid knowledge system** – Combines real facts + generative responses.

---

## 📅 Project Timeline
**Week 1**  
- Set up speech recognition & text-to-speech 🎤🔊  
- Integrated Hugging Face `transformers` for FLAN-T5 model 🤖  
- Basic question-answer pipeline  

**Week 2**  
- Added **Wikipedia API integration** 📚  
- Built hybrid "Fact First → AI Fallback" answering module  
- Cleaned responses & improved accuracy ✨  
- Recorded working demo 🎥  

---

## ⚙️ How It Works
1. **Listen** – The assistant records audio using SpeechRecognition 🎙️  
2. **Understand** – Converts speech to text 📝  
3. **Search** – Checks Wikipedia for a direct fact 📚  
4. **Fallback** – If no Wikipedia result, uses FLAN-T5 AI 🤖  
5. **Speak** – Outputs the answer using text-to-speech 🔊

---

## 📂 Code & Resources
- **Full Code:** In the file section
- **Google Colab Notebook:** [☁️ Open in Colab](https://colab.research.google.com/drive/1LHHU5D0biivll88OsB6qMR8kqEELObbU?usp=sharing)  
  *(If link doesn’t work, download `.ipynb` file and open in Colab)*  

---

## 📹 Demo Video
🎥 [Watch the Demo](#) *(Add your video link here)*

---

## ☁️ Colab Link
👉 [Open Project in Colab](https://colab.research.google.com/drive/1LHHU5D0biivll88OsB6qMR8kqEELObbU?usp=sharing) 
💡 If not working, download the `.ipynb` file from this repo and open it in Google Colab manually.

---

## 🙏 Acknowledgment
Special thanks to:  
- **Hugging Face 🤗** for providing the FLAN-T5 model  
- **Wikipedia API 📚** for factual knowledge retrieval  
- **Python SpeechRecognition & pyttsx3** for making voice interaction possible  
- My **mentors & peers** who guided me during these 2 weeks 💙  

---

💬 *If you like this project, don’t forget to ⭐ star the repo!*  
