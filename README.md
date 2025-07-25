
# 🏏 CricketMind - Smart Cricket Strategy App

CricketMind is a cross-platform web app designed to create, visualize, and manage cricket bowling strategies intelligently using pitch maps, field setup, ball types, and animations.

## 🚀 Features

### 🧠 Strategy Engine
- Dynamic delivery type detection (spin, swing, pace, etc.)
- Shot recommendation based on delivery
- Fielding suggestions for each delivery
- Ball types: Red/White leather, Tennis, Tape, etc.

### 🎨 Frontend (React + Tailwind)
- Mobile-first layout
- Interactive pitch & field maps
- Animation previews using Lottie
- Role-based access (Admin/User)
- Fully responsive

### ⚙️ Backend (FastAPI + PostgreSQL)
- Strategy API
- Authentication (JWT + OTP)
- Admin panel setup
- REST endpoints for strategy input/output

### 📱 Mobile Optimization
- Designed to work across devices
- Optional PWA / Native app wrapper using Capacitor

## 🧪 Testing
- Unit & E2E tests with edge validations
- Strategy rendering test cases
- Field/batting logic checks

## 📦 Stack

| Layer      | Tech                         |
|------------|------------------------------|
| Frontend   | React, TailwindCSS, Lottie   |
| Backend    | Python, FastAPI, PostgreSQL  |
| Auth       | JWT, OTP                     |
| Hosting    | Vercel (Frontend), TBD (Backend) |

## 🛠️ Run Locally

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

## 📤 Deployment

- Web hosted on [Vercel](https://vercel.com/)
- Backend will be deployed on Render / Railway

## 🙌 Contributing

PRs welcome! Please fork the repo, create a branch, and submit pull requests.

---

© 2025 CricketMind Team | MIT License
