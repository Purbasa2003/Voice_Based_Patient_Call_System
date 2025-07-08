Voice-Based Patient Call System

The project aims to develop a voice-based patient call system that allows patients to
communicate their needs to nurses in a natural and convenient manner. Through the use of
a friendly voice assistant powered by Azure OpenAI, the system will engage in interactive
dialogues with patients to understand and analyse their requests. The system will make use
of Autonomous AI Agents, which will take patient concerns and autonomously act upon
them based on predefined rules and priorities. These agents will work with Speech Services
(both Speech to Text and Text to Speech), combined with Natural Language Processing
(NLP), to improve the overall user experience.

The AI will then assign a priority level to each request and send it to nurses via a
smartphone app, providing a clear overview of requests with the room number and content.
This system improves patient care by facilitating seamless communication between patients
and nurses, allowing quicker responses to critical requests.

Here’s a **clean, professional, and GitHub-ready README** for your **CARE-CONNECT: Voice-Based Patient Call System** project. It's been fully structured with:

* 🔥 A **project title & tagline**
* 📂 Clear **sections** with styled headings
* ✅ Proper **code blocks** for commands
* ⚙️ Setup instructions for **Admin App**, **Frontend**, and **AI backend**
* 🛠 **Docker** & **Virtual environment** alternatives
* 💡 A neat **Troubleshooting + Notes** section

---


# 🗣️ CARE-CONNECT — Voice-Based Patient Call System  
> Bridging accessibility gaps in hospitals through real-time, AI-powered voice interfaces

---

## 📌 Overview

**CARE-CONNECT** is a voice-activated system designed to assist patients in clinics and hospitals. It translates patient speech into real-time commands and notifications for healthcare staff — improving responsiveness and accessibility, especially for patients with mobility challenges.

---

## 🧭 Quick Navigation

- [Frontend Setup](#frontend-setup)
- [Admin App Setup](#admin-app-setup)
- [AI-Part](#ai-part)
- [Docker Setup](#docker-setup)
- [Python Virtual Environment Setup](#python-virtual-environment-setup)
- [Troubleshooting & Notes](#troubleshooting--notes)

---

## 🎨 Frontend Setup

### 🔧 Prerequisites
- Node.js (v14 or higher)
- npm (Node Package Manager)

### 🚀 Steps to Run Frontend Main App

```bash
cd SpringBoardApp_Frontend
cd CareConnect
npm install
npx expo start
````

App will open in your browser at: [http://localhost:8081](http://localhost:8081)

---

## 🧩 Admin App Setup

### 🔧 Prerequisites

* Node.js
* npm

### 🚀 Steps to Run Admin App

```bash
cd SpringBoardApp_AdminApp
npm install
npm start
```

Admin dashboard will run at: [http://localhost:8081](http://localhost:8081)

---

## 🤖 AI-Part

### 🔽 Model Download

Download the AI model and place it inside the `model/` directory.
**[Model Download Link](#)** *(Insert actual link here)*

---

## 🐳 Docker Setup

### 🔨 Build the Docker Container

```bash
# With sudo
sudo docker-compose build --no-cache

# Or without sudo
docker-compose build --no-cache
```

### 🚀 Run the Container

```bash
# With sudo
sudo docker-compose up -d

# Or without sudo
docker-compose up -d
```

### 📜 View Logs

```bash
sudo docker-compose logs -f
# Or
docker-compose logs -f
```

### 🌐 Access the API

* Endpoint: [http://0.0.0.0:8000](http://0.0.0.0:8000)
* Docs: [http://0.0.0.0:8000/docs](http://0.0.0.0:8000/docs)

---

## 🐍 Python Virtual Environment Setup

### 🔧 Create and Activate Virtual Environment

```bash
python3 -m venv env

# Linux / MacOS
source env/bin/activate

# Windows (CMD)
env\Scripts\activate

# Windows (PowerShell)
.\env\Scripts\Activate.ps1
```

### 📦 Install Requirements

```bash
pip install -r requirements.txt
```

### 🚀 Run the Application

```bash
uvicorn app:app --reload
```

API is available at:

* [http://0.0.0.0:8000](http://0.0.0.0:8000)
* [http://0.0.0.0:8000/docs](http://0.0.0.0:8000/docs)

---

## 🛠 Troubleshooting & Notes

* Delete `node_modules` and `package-lock.json` if facing dependency issues, then run:

```bash
npm install
```

* Ensure **Python 3.7+** is installed
* Check that all required **environment variables** are set if the backend/API fails

---

## 🙌 Contributors

> Built as part of the Infosys Springboard Internship
> Designed and developed by a team of 20 under guided mentorship

---

