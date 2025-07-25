# 🏏 CricketMind - Strategy Maker App

CricketMind is a web-based app that helps cricket coaches and players plan and visualize strategies by selecting ball types, pitch lengths, field setups, and more.

---

## 🌐 Tech Stack

- **Frontend**: React + Vite + TailwindCSS + Lottie
- **Backend**: Python + FastAPI
- **Database**: SQLite (via SQLAlchemy)
- **Auth**: JWT-based authentication with OTP flow for mobile
- **Deployment**: GitHub + Vercel (Frontend), PythonAnywhere (Backend)
- **Mobile**: Responsive Layout (PWA-ready)

---

## 🚀 Local Setup Instructions

### 🔧 Backend Setup (Python + FastAPI)

```bash
cd backend

# Create a virtual environment
python -m venv venv

# Activate virtual environment
# On Unix/macOS:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run FastAPI server
uvicorn main:app --reload
```

Once running, the backend will be available at: `http://localhost:8000`

---

### 💻 Frontend Setup (React + Vite)

```bash
cd frontend

# Install dependencies
npm install

# Check scripts in package.json
# Ensure it has:
# "scripts": {
#   "dev": "vite",
#   "build": "vite build",
#   "preview": "vite preview"
# }

# Run development server
npm run dev
```

Frontend will be available at: `http://localhost:5173`

---

## ✅ Features

- Choose ball type: Red, White, Tape, Tennis, etc.
- Select pitch map length (full, good, short)
- Animated Lottie previews for each delivery
- Fielding strategies with visual overlays
- Role-based access for Admin/Users
- Strategy knowledge base and filters
- JWT-based login flow with OTP support

---

## 📁 Folder Structure

```
CricketMind/
├── backend/
│   ├── main.py
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── requirements.txt
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
└── README.md
```

---

## 🧪 Testing

We’ve included end-to-end and edge-case tests using Pytest and React Testing Library.

```bash
# Backend
cd backend
pytest

# Frontend (if test config added)
npm test
```

---

## 📲 Mobile Support

- Fully responsive layout
- Optimized for Android/iOS via PWA standards
- Mobile login via OTP

---

## 📬 Contact & Contribution

Feel free to fork, contribute, or raise issues. For feature requests, open an issue on GitHub.

---