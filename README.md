# 🧠 NeuroNarrative-AI

<div align="center">

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic_AI-purple?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-Framework-success?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-LLM-orange?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_DB-red?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker)

### 🚀 AI-Powered Ephemeral Storytelling Platform built with Agentic AI, LangGraph, RAG, and Large Language Models.

*The next generation of social storytelling powered by intelligent AI agents.*

</div>

---

# 📖 Overview

NeuroNarrative is an enterprise-grade AI-powered storytelling platform inspired by Instagram Stories, but redesigned with Generative AI at its core.

Instead of simply uploading images, users can create intelligent, searchable, multilingual, AI-enhanced stories that automatically disappear after 24 hours.

The platform leverages **Agentic AI**, **LangGraph**, **Retrieval-Augmented Generation (RAG)**, and **Vector Search** to transform traditional social media into an intelligent storytelling ecosystem.

---

# ✨ Features

## 📱 Smart Story Upload

- Upload Images
- Upload Voice Stories
- Story Preview
- Auto Image Compression
- Client-side Storage
- 24 Hour Expiry

---

## 🤖 AI Story Enhancement

- AI Caption Generator
- AI Hashtag Generator
- AI Emoji Suggestions
- AI Mood Detection
- AI Story Summary
- AI Title Generator

---

## 🌍 Multilingual AI

- Translate Stories
- Auto Language Detection
- Multilingual Captions

---

## 🧠 Agentic AI System

Powered by LangGraph.

Multiple AI agents collaborate together to process every uploaded story.

Agents include

- Caption Agent
- Emotion Agent
- Translation Agent
- Search Agent
- OCR Agent
- Recommendation Agent

---

## 🔍 Semantic Search

Instead of searching by keywords,

Users can search naturally

Example

> Show me stories about beaches.

> Find stories with dogs.

> Show happy birthday stories.

Powered by

- ChromaDB
- Embeddings
- Semantic Search

---

## 📄 OCR

Extract text from images automatically.

Stories become searchable.

---

## 🎙 Voice Stories

Upload audio.

AI automatically

- Transcribes
- Summarizes
- Creates captions

---

## 🎨 AI Image Intelligence

Automatically detects

- Objects
- Scene
- Mood
- Colors

---

## 📊 Story Analytics

Every story includes

- AI Engagement Score
- Sentiment Analysis
- Readability
- Popularity Prediction

---

## 🌙 Beautiful UI

- Responsive
- Mobile First
- Glassmorphism
- Dark Mode
- Framer Motion Animations

---

# 🏗 Architecture

```
                  User
                    │
                    ▼
          React + TypeScript Frontend
                    │
                    ▼
               FastAPI Backend
                    │
                    ▼
          LangGraph Supervisor Agent
                    │
      ┌─────────────┼─────────────┐
      ▼             ▼             ▼
 Caption Agent  OCR Agent   Emotion Agent
      │             │             │
      ▼             ▼             ▼
 Translation   Recommendation  Search Agent
      │
      ▼
 ChromaDB + Groq LLM
      │
      ▼
 Intelligent Story Response
```

---

# 🛠 Tech Stack

| Layer | Technology |
|--------|------------|
| Frontend | React 19 |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Animations | Framer Motion |
| Backend | FastAPI |
| AI Framework | LangChain |
| Agent Framework | LangGraph |
| LLM | Groq |
| Vector Database | ChromaDB |
| Embeddings | HuggingFace |
| Database | SQLite |
| Authentication | JWT |
| DevOps | Docker |

---

# 🤖 AI Pipeline

```
Upload Story
      │
      ▼
Image Processing
      │
      ▼
LangGraph Supervisor
      │
      ├── Caption Agent
      ├── Emotion Agent
      ├── OCR Agent
      ├── Translation Agent
      ├── Search Agent
      └── Recommendation Agent
      │
      ▼
Groq LLM
      │
      ▼
Vector Embeddings
      │
      ▼
ChromaDB
      │
      ▼
Story Published
```

---

# 📂 Project Structure

```
NeuroNarrative/

├── backend/
│
│   ├── agents/
│   ├── api/
│   ├── database/
│   ├── models/
│   ├── routers/
│   ├── services/
│   ├── tools/
│   ├── utils/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│
│   ├── src/
│   │
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── store/
│   ├── utils/
│   ├── App.tsx
│   └── main.tsx
│
├── screenshots/
├── docs/
├── docker-compose.yml
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Key AI Features

✅ Agentic AI

✅ Multi-Agent Workflows

✅ LangGraph

✅ LangChain

✅ RAG

✅ ChromaDB

✅ Semantic Search

✅ OCR

✅ Story Translation

✅ AI Caption Generation

✅ Emotion Detection

✅ Voice Story

✅ AI Recommendation System

---

# 📷 Screenshots

Coming Soon

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/NeuroNarrative.git

cd NeuroNarrative
```

Backend

```bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload
```

Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 🎯 Roadmap

- Story Upload
- Story Viewer
- Swipe Navigation
- AI Caption Generator
- AI Translation
- OCR
- Semantic Search
- Voice Stories
- Story Analytics
- Multi-Agent AI
- Docker Deployment
- CI/CD

---

# 🌟 Future Scope

- AI Video Stories
- Face Recognition
- Story Collaboration
- AI Story Generator
- Story Scheduling
- AI Moderation
- Social Feed
- Push Notifications
- Mobile App

---

# 🤝 Contributing

Contributions are welcome!

Feel free to open an issue or submit a pull request.

---

# 📜 License

Distributed under the MIT License.

---

# 👨‍💻 Author

**Rose Sharma**

AI/ML Engineer | Generative AI Developer | Full Stack AI Developer

- 💼 LinkedIn: https://linkedin.com/in/rose-sharma13
- 💻 GitHub: https://github.com/Rosesharma13
- 🌐 Portfolio: https://rosesharma13.github.io

---

<div align="center">

### ⭐ If you like this project, don't forget to star the repository!

**Building the future of AI-powered storytelling with Agentic Intelligence.**

</div>
