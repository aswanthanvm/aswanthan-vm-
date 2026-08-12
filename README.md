AI Resume Screening System

A simple web application that checks how well a resume matches a job description.

 Features

- Upload PDF, DOCX, or TXT resumes
- Enter a job description
- Compare resumes with the job description
- Show a match score (0–100)
- Display matching skills
- Rank candidates based on score



 Project Structure


resume-screening-app/
│
├── backend/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   └── index.html
│
└── README.md


Requirements

- Python 3.10 or above
- Internet connection (only for the first run)



 Run the Backend

 bash
cd backend

python -m venv venv

Windows
venv\Scripts\activate

Install packages
pip install -r requirements.txt

Start server
uvicorn main:app 


Open in browser:


http://localhost:8000




 Run the Frontend

Open the `frontend/index.html` file

or

 bash
cd frontend
python -m http.server 5500


Then open:

http://localhost:5500




 How to Use

1. Enter a job description.
2. Upload one or more resumes.
3. Click  Run Screening.
4. View:
   - Resume Score
   - Matching Skills
   - Candidate Ranking



Technologies Used

- Python
- FastAPI
- HTML
- CSS
- JavaScript
- Sentence-BERT


Scoring

The system compares:

- Resume content
- Job description
- Matching technical skills

Then it gives a score from 0–100.



 Future Improvements

- Login System
- Resume History
- Database Support
- AI Suggestions
- Better Skill Detection

  
  Author
  Aswanthan V M
Computer Science & Engineering
