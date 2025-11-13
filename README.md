✉️ AI-Powered Email Assistant
Chrome Extension + React (Vite) Frontend + Spring Boot Backend | Full Stack AI Project










📌 Overview

AI-Powered Email Assistant is a full-stack productivity tool built using Spring Boot, React, Vite, and a Chrome Extension (Manifest V3).
It uses AI/LLM-based text processing to generate, rewrite, improve, and summarize emails directly inside Gmail or any email editor.

This project demonstrates expertise in:

Full-stack web development

Chrome Extension engineering

Spring Boot REST API development

AI/LLM integration

Frontend development with React & Vite

Content scripts and browser automation

Cloud-ready & production-grade architecture

🧠 Key Features
🔹 Chrome Extension (Manifest V3)

Injects AI features directly inside Gmail

Captures email text and user prompts

Inserts generated replies automatically

Lightweight and secure MV3 architecture

🔹 React + Vite Frontend

Modern UI for interacting with the AI model

Fast HMR and optimized build via Vite

Component-based architecture

Environment variable support for API URLs

🔹 Spring Boot Backend

REST API for AI-powered email generation

Controller–Service–DTO layered architecture

WebClient-based API integration

Scalable and production-ready backend

Simple to deploy (Docker, Render, Railway, etc.)

🏗️ Full Project Architecture
┌──────────────────────────┐
│      Chrome Extension     │
│ (content.js, manifest V3) │
└─────────────┬────────────┘
              │
              ▼
┌──────────────────────────┐
│     React + Vite UI       │
│ (email-writer-frontend)   │
└─────────────┬────────────┘
              │ HTTP (JSON)
              ▼
┌──────────────────────────┐
│     Spring Boot API       │
│ (email generation logic)  │
└─────────────┬────────────┘
              │ AI Call
              ▼
       ┌───────────────┐
       │   LLM Model    │
       │ (Gemini / GPT) │
       └───────────────┘

📂 Project Structure
Email-Assistant/
│
├── email-writer-ext/               # Chrome Extension (Manifest V3)
│   ├── manifest.json
│   ├── content.js
│   ├── content.css
│
├── email-writer-frontend/          # React + Vite Frontend
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
└── backend/                        # Spring Boot Backend
    ├── src/main/java/
    ├── src/main/resources/
    ├── pom.xml

🛠️ Tech Stack (ATS Optimized)
🔸 Frontend

React.js

Vite

JavaScript (ES6+)

HTML5 / CSS3

Component-based architecture

🔸 Chrome Extension

Manifest V3

Content Scripts

DOM Injection

Event Listeners

Secure background messaging

🔸 Backend

Spring Boot

REST Controller

WebClient / RestTemplate

Java 17+

Layered Architecture (Controller → Service → DTO)

JSON-based API communication

CORS support

🔸 AI / NLP

LLM-based Text Generation

Prompt Engineering

Summarization / Rewriting

AI API Integration (Gemini/OpenAI/etc.)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone <your-repo-url>
cd Email-Assistant

Frontend Setup (React + Vite)
cd email-writer-frontend
npm install
npm run dev


Runs at:
👉 http://localhost:5173

Chrome Extension Setup

Open Chrome → Extensions

Enable Developer Mode

Click Load Unpacked

Select:

email-writer-ext/

Backend Setup (Spring Boot)
Run backend:
cd backend
mvn spring-boot:run


Backend runs at:
👉 http://localhost:8080

Example API Endpoint
POST /api/generate-email

🔑 Environment Variables
Frontend (email-writer-frontend/.env)
VITE_API_URL=http://localhost:8080/api/generate-email

Backend (application.properties)
ai.api.key=YOUR_API_KEY
ai.api.url=YOUR_MODEL_ENDPOINT

📸 Demo (replace later)
Gmail Integration	AI Popup UI

	
📈 Future Enhancements (ATS Keywords)

Tone analysis (NLP, sentiment analysis)

Multi-language support (i18n)

Email classification using ML models

Cloud deployment (AWS, GCP, Render, Railway)

User authentication (JWT, OAuth2)

Template storage with databases (MySQL, PostgreSQL, MongoDB)

👨‍💻 Author

Kuldeep Chaudhary
Full Stack Developer | Java | Spring Boot | React
📧 dc629753@gmail.com

🔗 GitHub: https://github.com/Kuldeepch13

🔗 LinkedIn: https://www.linkedin.com/in/kuldeepchuadhary1311/

📜 License

This project is licensed under the MIT License.