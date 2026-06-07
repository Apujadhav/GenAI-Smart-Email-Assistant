# 📩 GenAI Smart Email Assistant – AI-Powered Email Management

**An AI-powered email assistant built using Java, Spring Boot, Spring AI, Gemini AI, React, and Chrome Extension integration for intelligent email automation and smart response generation.**

---

## 🔥 Key Features

✅ **AI-Powered Email Suggestions** – Generates intelligent email replies using Gemini AI.

✅ **Context-Aware Responses** – Understands email content and generates relevant responses.

✅ **Seamless Chrome Extension Integration** – Provides AI-powered suggestions directly inside Gmail.

✅ **Email Tone Customization** – Generate responses in Professional, Casual, Formal, and Friendly tones.

✅ **Real-Time Response Generation** – Helps users draft emails quickly and efficiently.

✅ **Secure & Scalable Backend** – Built using Spring Boot, Spring AI, and REST APIs.

---

## 🛠️ Tech Stack

### Backend (Spring Boot + AI)

* Java 17
* Spring Boot 3
* Spring AI
* Gemini AI API
* REST APIs
* Maven

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Chrome Extension

* Manifest V3
* Content Scripts
* Background Scripts

---

## 🎯 How It Works

1️⃣ The Chrome Extension injects an AI-powered assistant inside Gmail.

2️⃣ When composing an email, the assistant generates smart responses based on email context.

3️⃣ The extension sends the email content to the Spring Boot backend.

4️⃣ The backend communicates with Gemini AI using REST APIs.

5️⃣ The AI-generated response is returned and displayed directly inside Gmail.

---

## 🚀 Installation & Setup

### Backend – Spring Boot AI Server

#### Clone the Repository

```bash
git clone https://github.com/Apujadhav/GenAI-Smart-Email-Assistant.git
cd GenAI-Smart-Email-Assistant
```

#### Configure Gemini API Key

Update `application.properties`:

```properties
gemini.api.url=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=
gemini.api.key=YOUR_GEMINI_API_KEY
```

#### Run the Application

```bash
./mvnw spring-boot:run
```

Backend runs on:

```text
http://localhost:8080
```

---

### Chrome Extension – Setup

1. Open Chrome.
2. Navigate to `chrome://extensions/`
3. Enable Developer Mode.
4. Click **Load Unpacked**.
5. Select the extension folder.

---

## 📝 API Endpoints

| Method | Endpoint              | Description                       |
| ------ | --------------------- | --------------------------------- |
| POST   | `/api/email/generate` | Generate AI-powered email replies |

---

## 🚀 Future Enhancements

* Voice-to-Text Email Drafting 🎙️
* Multi-Language Support 🌍
* Smart Email Categorization 📂
* Response History Tracking 📜
* Calendar Integration 📅
* Personalized Writing Styles ✨

---

## 👨‍💻 Author

**Apurva Jadhav**

GitHub: https://github.com/Apujadhav
