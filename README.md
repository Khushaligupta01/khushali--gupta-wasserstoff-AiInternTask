

# 🚀 AI Intern Task — Wasserstoff Innovation & Learning Labs

This is my submission for the AI Internship Task assigned by Wasserstoff Innovation and Learning Labs. The project is a minimal, cleanly structured Gen-AI powered chatbot that allows uploading documents and extracts key themes and insights using NLP.

## 📁 Project Structure

```bash
samarth--thakur-wasserstoff-AiInternTask/
├── backend/          # FastAPI server with upload & processing logic
│   └── app/
│       ├── api/      # Upload endpoint (file receiver)
│       ├── core/     # Configuration settings
│       ├── services/ # (To be used for theme extraction logic)
│       └── main.py   # Entry point for FastAPI
│
├── frontend/         # Streamlit-based user interface
│   └── app.py        # Clean UI for uploading documents
│
├── requirements.txt  # Python package dependencies
└── README.md         # This file
```

---

## 🧠 Features

✅ Upload document (.pdf, .txt, .docx)
✅ User-friendly Streamlit UI
✅ Backend built with FastAPI
✅ Ready for semantic search, theme detection, and embeddings
✅ Minimalistic & well-commented structure

---

## 🛠️ Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/samarththakurr/samarth--thakur-wasserstoff-AiInternTask.git
cd samarth--thakur-wasserstoff-AiInternTask
```

2. Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the backend:

```bash
cd backend
uvicorn app.main:app --reload
```

4. Run the frontend:

```bash
cd ../frontend
streamlit run app.py
```

---

## 📹 Demo Video

A short video walkthrough is included with my submission explaining:

* My thought process
* Project structure
* How it works
* Scope for further enhancements (like theme extraction & embeddings)

---

## ✨ Future Work

* Implementing vector database for semantic search
* Using OpenAI/LLM APIs for document theme summarization
* Enhanced frontend (drag-and-drop, preview)
* Secure file upload & user sessions

---

## 🙏 Acknowledgment

Thanks to the Wasserstoff team for this opportunity. I’ve built this from scratch with care, a focus on clean design, and a passion for learning AI.



Secure file upload & user sessions

🙏 Acknowledgment
Thanks to the Wasserstoff team for this opportunity. I’ve built this from scratch with care, a focus on clean design, and a passion for learning AI.

