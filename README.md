🤖 AI Interview System

An AI-powered mock interview platform that uses Google Gemini AI to generate personalized interview questions, evaluate answers, and provide a detailed performance report.

🚀 Live Demo

👉 https://ai-interview1-0wg4.onrender.com/index.html


 💻 GitHub Repository

👉 **[View Source Code on GitHub](https://github.com/ashish752code/Ai_interview)**

---

 📌 About The Project

The AI Interview System is a web-based application designed to simulate a real interview experience.

The application analyzes a candidate's resume and uses **Google Gemini AI** to generate personalized interview questions.

During the interview, the system:

- Generates AI-powered interview questions
- Evaluates candidate answers
- Provides scores and feedback
- Supports voice-based answers
- Uses camera-based face detection
- Detects interview violations
- Generates a final interview performance report

---

 ✨ Features

🧠 AI-Powered Interview

Uses Google Gemini AI to generate personalized interview questions based on the candidate's resume.

 📄 Resume Analysis

Upload your resume and allow the system to generate questions based on your:

- Skills
- Education
- Projects
- Experience
- Technical knowledge

📊 AI Answer Evaluation

Each answer is evaluated by AI and receives:

- Score from 0–10
- Feedback
- Strengths
- Areas for improvement

 🎙️ Voice Interview

Candidates can answer interview questions using their microphone.

 📷 Face Detection

The system monitors the camera during the interview.

It can detect:

- No face detected
- Multiple faces detected
- Interview violations

🖥️ Fullscreen Interview

The interview runs in fullscreen mode to simulate a real online assessment environment.

📈 Final Report

After completing the interview, the application generates a detailed report containing the candidate's performance and hiring recommendation.

---

 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend server |
| HTML | Frontend structure |
| CSS | User interface |
| JavaScript | Frontend functionality |
| Google Gemini AI | AI interview & evaluation |
| PyPDF2 | PDF resume processing |
| python-docx | DOCX resume processing |
| Python HTTP Server | Backend server |

---

📂 Project Structure

```text
AI-Interview/
│
├── server.py
├── index.html
├── interview.html
├── report.html
├── README.md
└── requirements.txt

**Resume upload fails** → Make sure the file is PDF, DOCX, or TXT and under 10MB
