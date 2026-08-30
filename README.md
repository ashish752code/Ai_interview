# 🤖 AI Interview System v3.0

## ⚡ Super Simple Setup — 3 Steps Only

### Step 1: Install requirements
```bash
pip install google-generativeai PyPDF2 python-docx
```

### Step 2: Add your Gemini API key
Edit the `.env` file and replace `your_api_key_here` with your key.

Get a FREE key at: https://aistudio.google.com/app/apikey

### Step 3: Run
```bash
python3 server.py
```

Then open your browser at: **http://localhost:8000/index.html**

---

## 📁 Files
```
ai_interview/
├── server.py       ← Run this! (built-in Python http.server, no FastAPI needed)
├── index.html      ← Upload resume page
├── interview.html  ← Live interview
├── report.html     ← Results
└── .env            ← Add your GEMINI_API_KEY here
```

## ✅ Features
- 🧠 Gemini AI analyzes your resume → generates personalized questions
- 📊 AI scores each answer 0-10 with feedback
- 👁️ Camera face detection (0 faces or 2+ faces = violation)
- 🖥️ Auto fullscreen — exiting fullscreen terminates interview
- 🎙️ Voice answers via microphone
- 📈 Full report with hiring recommendation

## ❓ Troubleshooting

**"Cannot reach server"** → Make sure `python3 server.py` is running first, then open http://localhost:8000/index.html

**"Gemini API key not configured"** → Edit `.env` file and set your key, then restart server.py

**Resume upload fails** → Make sure the file is PDF, DOCX, or TXT and under 10MB
