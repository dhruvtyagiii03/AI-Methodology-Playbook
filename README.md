# 🧠 AI Methodology Playbook

A fully functional, real-time AI-powered conversational assistant engineered using modern full-stack technologies including Python, Flask, FastAPI, PostgreSQL, Next.js, and Docker — deployed on **Google Cloud Platform (GCP)**.

---

## 🚀 Overview

The **AI Methodology Playbook** is a context-aware, multi-turn Large Language Model (LLM) based conversational bot designed to streamline internal workflows and deliver adaptive, real-time assistance. It dynamically adjusts model responses using user feedback, ensures multi-model flexibility, and features a responsive interface with live admin monitoring.

---

## 🧩 Key Features

- 🤖 **Multi-turn LLM Bot**: Retains user context for smarter, natural conversations.
- 🔄 **Model Adaptivity**: Automatically switches models based on user-rated response quality.
- 🧠 **Prompt Template System**: Flexible prompt design tailored to query types.
- 📊 **Live Monitoring**: Admin dashboard with WebSocket integration for real-time session tracking.
- 🌐 **Frontend**: Built using **Next.js** and **Tailwind CSS** for a clean and responsive UX.
- 🛠️ **Backend**: FastAPI & Flask-based logic handling with REST APIs and async capabilities.
- 🗃️ **Database**: PostgreSQL for managing user sessions, feedback, and logs.
- 🐳 **Deployment**: Dockerized and deployed on **Google Cloud Platform (GCP)** for scalable infrastructure.

---

## 🖼️ Demo

> 🎥 A complete demo video has been prepared to showcase the app in action.  
> *(Add your video link here)*

---

## ⚙️ Tech Stack

| Layer        | Technology                       |
|--------------|----------------------------------|
| Frontend     | Next.js, Tailwind CSS            |
| Backend      | Python, FastAPI, Flask           |
| Database     | PostgreSQL                       |
| Live Updates | WebSocket                        |
| Deployment   | Docker, GCP (Google Cloud Platform) |

---

## 🧪 Setup Instructions

> To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/ai-methodology-playbook.git
cd ai-methodology-playbook

# Set up backend (Flask + FastAPI)
cd backend
pip install -r requirements.txt

# Set up frontend (Next.js)
cd ../frontend
npm install
npm run dev

# PostgreSQL setup (ensure you have a DB running or use Docker Compose)

# (Optional) Run with Docker
docker-compose up --build
