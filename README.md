# 🚀 Resume Matcher System

AI-powered Resume Matcher built with **FastAPI** (backend) + **Streamlit** (frontend).  
This project allows applicants to upload resumes and recruiters to match them against job descriptions with ATS-style keyword scoring.

---

## 📌 Features

✅ User authentication (Applicant & Recruiter roles)  
✅ Resume parsing (PDF, DOCX, Excel, Code files)  
✅ Keyword-based ATS scoring & feedback  
✅ Recruiter dashboard with KPIs, charts, and ranking  
✅ SQLite database storage  
✅ CSV download for results  

---

## 🛠️ Tech Stack

- **Backend:** FastAPI + SQLite
- **Frontend:** Streamlit
- **Auth:** JWT tokens
- **Libraries:** PyMuPDF, docx2txt, pandas, matplotlib

---

## 📂 Project Structure



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/resume-matcher.git
cd resume-matcher


Create a virtual environment & install dependencies
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

Run the Backend (FastAPI)
uvicorn backend:app --reload

Run the Frontend (Streamlit)
streamlit run frontend.py
Frontend will run on: http://localhost:8501

You can change the secret key in backend.py:

SECRET_KEY = "your_secret_key_here"

Future Enhancements

Resume parsing with NLP (spaCy/transformers)
Auto-shortlisting based on configurable thresholds
Recruiter notes & feedback storage
Candidate profile vie

Contributing

Pull requests are welcome!
Please open an issue first to discuss changes.

