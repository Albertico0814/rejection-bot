# Rejection Bot

AI-powered rejection email assistant. This app auto-generates polite rejection responses based on incoming messages or user prompts.

## Features

* GPT-powered rejection message generation
* Supabase client for user data and storage
* FastAPI backend
* React + Tailwind frontend
* Persistent chat history (optional)

---

## 🛠️ Tech Stack

* **Frontend**: React (Vite), Tailwind CSS
* **Backend**: FastAPI, Uvicorn
* **Auth/DB**: Supabase
* **AI**: OpenAI GPT-4 API

---

## 🚀 Getting Started

### Backend Setup

```bash
# 1. Create & activate venv
python3 -m venv venv
source venv/bin/activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set environment variables (edit .env)
OPENAI_API_KEY=your-key-here
SUPABASE_URL=your-url
SUPABASE_KEY=your-key

# 4. Run API
uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend/rejection-bot-ui
npm install
npm run dev
```

---

## 📁 Project Structure

```
rejection-bot/
├── main.py                # FastAPI app
├── .env                  # Environment config
├── requirements.txt      # Python deps
├── frontend/
│   └── rejection-bot-ui/ # React app
│       ├── index.html
│       ├── vite.config.ts
│       └── src/
└── README.md
```

---

## ✅ To Do

* [ ] Supabase auth integration
* [ ] Message templates UI
* [ ] Export to PDF/email

---

## 📄 License

MIT
