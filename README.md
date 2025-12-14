# 🌍 Smart Tourism

### Emotion & Trust Driven Travel Planning Platform

Smart Tourism is an emotion-first, trust-aware travel planning platform that helps users plan trips based on **how they feel**, not just where everyone else is going.

Unlike traditional travel apps that prioritize popularity and discounts, Smart Tourism focuses on **emotional comfort, safety, and trust**, ensuring travelers return refreshed, not exhausted.

---

## ✨ What Makes Smart Tourism Different

Most travel platforms ask:
*Where do you want to go?*

Smart Tourism asks first:
**How do you feel right now?**

Trips are planned by combining **emotions + trust + safety signals**, then adjusted for budget, duration, and companions.

---

## 🧠 Core Concept

### Emotion-First Planning

User emotions such as:

* Romantic
* Healing
* Fun
* Solo / Peaceful

are mapped to:

* Destination type
* Travel pace
* Activity intensity
* Accommodation style

### Trust-Aware Recommendations

Each recommendation considers:

* Verified places
* Trust score signals
* Scam and fair pricing alerts

---

## 🚀 Key Features

* ❤️ Emotion-based trip planning
* 🛡️ Verified places with Trust Score
* ⚠️ Scam protection and fair pricing alerts
* 🎨 Modern dark UI with glassmorphism
* 🧭 Familiar travel inputs with emotion-first logic
* 🔐 Guest mode and login support

---

## 🏗️ Project Architecture

```text
Smart-Tourism/
│
├── frontend/        # React + Vite frontend
│
├── backend/         # Node.js + Express backend
│
└── README.md
```

---

## 🖥️ Tech Stack

### Frontend

* React
* Vite
* JavaScript (ES6+)
* CSS3 (Glassmorphism, dark UI)
* Mobile-first design

### Backend

* Node.js
* Express.js
* Rule-Based Emotion Engine
* Google Gemini API (AI reasoning support)

---

## ⚙️ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:
👉 `http://localhost:5173`

### Frontend Deployment (Vercel / Netlify)

1. Push code to GitHub
2. Connect repo to Vercel or Netlify
3. Root directory: `frontend`
4. Framework preset: **Vite**
5. Build command: `npm run build`
6. Output directory: `dist`

---

## ⚙️ Backend Setup

```bash
cd backend
npm install
```

### Environment Variables

Create a `.env` file inside `backend`:

```env
PORT=5000
GEMINI_API_KEY=your_google_gemini_api_key
```

### Run Backend

```bash
npm run dev
```

Backend runs at:
👉 `http://localhost:5000`

### Backend Deployment (Render / Railway)

1. Push backend code to GitHub
2. Connect repo to Render or Railway
3. Root directory: `backend`
4. Build command: `npm install`
5. Start command: `npm start`
6. Add `GEMINI_API_KEY` in environment variables

---

## 🌐 Live Preview

👉 **Deployed App:**
`https://trusted-trip-planner.lovable.app`

---

## 📌 Current Status

* ✅ Frontend MVP completed
* ✅ Emotion-based logic implemented
* ✅ Trust-centric experience designed

This repository represents a **startup-grade MVP**, built to scale without changing the core philosophy.

---

## 🔮 Future Roadmap

* Emotion detection from text or voice
* Personalized recommendations using history
* Real booking integrations
* Advanced trust scoring models
* Android and iOS apps

---

## 📄 License

Currently intended for educational, MVP, and prototype purposes.
License will be added based on future commercialization plans.

---

### Smart Tourism

**Plan trips based on trust and emotions, not just popularity.**
