# 🧠💬 Mental Health Companion – Emotional Support Chatbot

An **AI-powered Mental Health Companion** that provides **emotional support, mood detection, emergency handling**, and **empathetic conversations**.
The system consists of a **Flask-based backend chatbot** and an **Android mobile application frontend**.

---

## 🌟 Features

✅ Emotion detection from user messages
✅ Empathetic AI responses using **Groq LLM**
✅ Emergency & crisis message detection 🚨
✅ Offline response handling
✅ Memory-based conversation context 🧠
✅ Android mobile app interface 📱
✅ Dockerized backend for easy deployment 🐳

---

## 🏗️ Project Structure

```
Hassan Project/
├── emotional_support_chatbot/   # Flask Backend
│   ├── app.py
│   ├── chatbot_groq.py
│   ├── emotion_detector.py
│   ├── emergency_detector.py
│   ├── offline_responder.py
│   ├── memory_store.py
│   ├── config.py
│   ├── requirements.txt
│   ├── Dockerfile
│   ├── .dockerignore
│   └── .env
│
├── MentalHealthCompanion/        # Android App (Frontend)
│   ├── app/
│   ├── gradle/
│   └── build.gradle
│
└── docker-compose.yml
```

---

## ⚙️ Technologies Used

### 🔹 Backend

* 🐍 Python 3.10
* 🌐 Flask
* 🤖 Groq LLM API
* 🧠 NLP & Emotion Detection
* 🐳 Docker & Docker Compose

### 🔹 Frontend

* 📱 Android (Java)
* 🎨 XML UI
* 🌍 REST API Integration

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure you have installed:

* Docker 🐳
* Docker Compose
* Git

---

## 🐳 Run Backend Using Docker (Recommended)

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd "Hassan Project"
```

---

### 2️⃣ Add Environment Variables

Create `.env` inside `emotional_support_chatbot/`

```env
GROQ_API_KEY=your_api_key_here
FLASK_ENV=production
```

---

### 3️⃣ Build & Run

```bash
docker-compose build
docker-compose up
```

📍 Backend will be available at:

```
http://localhost:5000
```

---

## 🧪 Test API

Use **Postman / Curl**:

```http
POST /chat
Content-Type: application/json

{
  "message": "I feel very anxious today"
}
```

---

## 📱 Android App Setup

1. Open **MentalHealthCompanion** in **Android Studio**
2. Sync Gradle
3. Update API URL:

   ```
   http://10.0.2.2:5000
   ```
4. Run on Emulator or Physical Device 📲

---

## 🚨 Emergency Detection

If a user message contains:

* suicidal thoughts
* self-harm indicators
* extreme distress

🚑 The chatbot automatically switches to **emergency response mode** and suggests **professional help resources**.

---

## 🔐 Security Notes

* ❌ Do NOT commit `.env` files
* 🔑 API keys are securely injected via environment variables
* 🐳 Containers isolate dependencies safely

---

## 📦 Future Improvements

✨ Add user authentication
✨ Store chat history in database
✨ Deploy on AWS / Railway / Render
✨ Add push notifications
✨ Improve emotion classification accuracy

---

## 👨‍💻 Author

**Adeel Tahir**
🎓 AI & Software Engineering Student
💡 Passionate about Mental Health Tech & AI

---

## 📜 License

This project is licensed for **educational and research purposes** 📚
Commercial use requires permission.

---

## ❤️ Acknowledgements

* Groq AI 🤖
* Flask Community 🌐
* Mental Health Open Resources 💚


