# 🚀 Study Mate – AI-Powered Smart Learning Platform

**Study Mate** is an intelligent learning assistant that transforms raw study material into structured, interactive, and personalized learning experiences.

Upload your notes, PDFs, or even YouTube transcripts — and Study Mate will automatically generate summaries, flashcards, quizzes, and contextual Q&A to help you learn faster and retain more.

---

## ✨ Why Study Mate?

Traditional studying is passive and inefficient.
**Study Mate turns it into an active learning system** using AI + spaced repetition.

---

## 🔥 Core Features

* 🧠 **AI Content Engine**
  Convert documents (PDF, DOCX, TXT) and YouTube transcripts into:

  * Smart summaries
  * Flashcards
  * Auto-generated quizzes

* ❓ **Contextual Q&A System**
  Ask anything about your study material and get instant AI-powered answers.

* 🔁 **Spaced Repetition (SM2 Algorithm)**
  Optimize long-term memory with scientifically proven revision techniques.

* ⚡ **Real-Time Processing Updates**
  Track document processing with live status updates.

* 📊 **Learning Dashboard**
  Monitor your progress, revision history, and performance.

* 🔐 **Secure Authentication**
  JWT-based authentication with Google & GitHub login support.

---

## 🛠️ Tech Stack

### Backend

* **Runtime & Framework**: Node.js, Express, TypeScript
* **Database**: MongoDB (Mongoose)
* **AI Stack**:

  * LLM: Google Gemini
  * Framework: LangChain.js
  * Vector DB: Pinecone / ChromaDB
* **Real-Time**: Socket.IO
* **Storage**: Cloudinary
* **Auth**: Passport.js (JWT, OAuth)
* **Background Jobs**: Redis
* **Scheduling**: node-cron
* **Validation & Logging**: Zod, Winston

### Frontend

* **Framework**: React + Vite + TypeScript
* **Styling**: Tailwind CSS
* **State Management**: Zustand
* **Data Fetching**: React Query + Axios
* **Routing**: React Router
* **Realtime**: Socket.IO Client

---

## ⚙️ Getting Started

### Prerequisites

* Node.js (v18+)
* npm (v9+)
* Docker & Docker Compose
* API keys: Google Gemini, Pinecone/ChromaDB, Cloudinary

---

### Installation

```bash
git clone https://github.com/your-username/study-mate.git
cd study-mate
```

```bash
npm run install:all
```

```bash
cp backend/.env.example backend/.env
```

Update `.env` with your credentials.

```bash
npm run dev
```

* Backend → http://localhost:3001
* Frontend → http://localhost:3000

---

## 📁 Project Structure

```
study-mate/
├── backend/         # Express + AI processing
├── frontend/        # React UI
├── package.json
└── README.md
```

---

## 🔌 API Overview

Main endpoints:

* `POST /api/auth/register`
* `POST /api/auth/login`
* `POST /api/contents/upload-document`
* `GET /api/contents`
* `GET /api/flashcards/:contentId`
* `GET /api/quizzes/:contentId`
* `POST /api/qa/ask`

---

## 🚀 Future Improvements

* 🎯 Personalized learning paths
* 🧩 Gamification (XP, streaks, leaderboards)
* 📱 Mobile app version
* 🗣️ Voice-based learning assistant

---

## 🤝 Contribution

Open to improvements, feature ideas, and collaborations.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Shivansh Singh**
Building AI-powered tools + visual storytelling 🚀
