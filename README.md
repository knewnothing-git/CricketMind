# 🏏 CricketMind: AI-powered Cricket Strategy Maker

CricketMind is a web and mobile-friendly application designed to help players, coaches, and enthusiasts create, simulate, and understand cricket strategies for different ball types, match situations, and field placements.

---

## 🔥 Features

### 🧠 Strategy Generator
- Ball type input: Spin, Fast, Medium, Tape, Tennis, Leather (Red/White)
- Pitch location input: Full length, Good length, Short, Yorker, Overpitched, etc.
- Dynamic suggestions:
  - For bowlers: Ideal pitch zones, expected result
  - For batters: Shot type, ideal hitting area

### 🗺️ Pitch Map & Zone Graphics
- Interactive pitch with visual markers
- Area-based insights (Overpitched, Bouncer, Wide Yorkers, etc.)

### 🧤 Field Setup Suggestions
- Adaptive field setup by delivery type & match phase (Powerplay, Middle Overs, Death Overs)
- Dynamic zone mapping: slips, covers, fine leg, etc.

### 🎬 Strategy Animation
- Lottie-powered animations
- Explanation of delivery-to-shot conversion

### 🔐 Role-Based Access
- Admin panel for managing strategies
- JWT-authenticated users
- Mobile OTP login system

---

## ⚙️ Tech Stack

### Frontend
- React + Tailwind CSS
- Vite
- Lottie for animations

### Backend
- Python + FastAPI
- SQLite/PostgreSQL (selectable)
- JWT-based authentication

### DevOps
- GitHub Actions (CI-ready)
- Fully containerizable (Docker-ready optional)

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/knewnothing-git/CricketMind.git
cd CricketMind
```

### 2. Start Backend
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3. Start Frontend
```bash
cd frontend
npm install
npm run dev
```

---

## ✅ Project Progress Checklist

- [x] UI Wireframe (Mobile-first)
- [x] React Frontend
- [x] Backend with FastAPI
- [x] Auth (JWT, OTP)
- [x] Strategy Generator
- [x] Pitch Map Zones
- [x] Field Placement Logic
- [x] Lottie Animation Integration
- [x] Admin Dashboard
- [x] Mobile Optimization
- [x] Strategy Submission Form
- [ ] Cloud Deployment

---

## 🧪 Coming Soon
- AI-enhanced delivery prediction engine
- Upload ball videos for strategy suggestions
- Player-level data insights (pro vs amateur)

---

## 📄 License
MIT License

---

## 🙌 Contribute
Open to contributions, suggestions, and collaborations. Just raise an issue or submit a PR!

