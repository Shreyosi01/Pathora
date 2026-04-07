# Pathora 🚀

Pathora is an AI-powered learning platform that helps users generate personalized learning paths, access structured lessons, and track their progress through a modern and intuitive dashboard.

---

## 🌐 Deployed Website

👉 Live Demo:  
https://approach-methods-avon-beatles.trycloudflare.com/?view=learning-path

---

## ✨ What Pathora Does

- User authentication (login & register)
- Guided onboarding based on learning goals
- AI-generated learning paths and lessons
- Dashboard to view lessons and progress
- Clean, responsive, and fast user interface

---

## 🛠 Tech Stack

### Frontend
- React
- Vite
- JavaScript / TypeScript
- Tailwind CSS
- shadcn/ui

### Backend
- FastAPI
- Python
- Uvicorn

---

## 📂 Project Structure

```bash
Pathora/
├── backend/
│   ├── app/
│   ├── requirements.txt
│   └── main.py
├── frontend/
│   ├── src/
│   ├── package.json
│   └── vite.config.ts
└── README.md
```

---

## 🚀 How to Run Pathora Locally
#🔹 Backend Setup
1. Navigate to the backend folder:
cd backend

2. Install dependencies:
pip install -r requirements.txt

3. Run the FastAPI server:
uvicorn app.main:app --reload


Backend will start at:
http://localhost:8000

#🔹 Frontend Setup
1. Navigate to the frontend folder:
cd frontend

2. Install dependencies:
npm install

3. Start the development server:
npm run dev


Frontend will start at:
http://localhost:5173

# 🔗 Environment Variables (Optional)
Create a .env file in the frontend directory if required:
VITE_API_BASE_URL=http://localhost:8000
