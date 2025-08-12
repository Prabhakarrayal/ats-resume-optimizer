📄 ATS Resume Optimizer
An AI-powered tool that rewrites resumes to maximize Applicant Tracking System (ATS) match scores by aligning them with a given job description. This project uses Google Gemini API for text analysis and rewriting, extracting missing skills, and producing an optimized, ATS-friendly version of the resume.

🚀 Features
Automatic Skill Extraction
Detects missing keywords, skills, and phrases from the job description.

Technical & Non-Technical Resume Handling
Classifies resumes as technical or non-technical and optimizes accordingly.

ATS Match Estimation
Provides an estimated ATS keyword match score before and after optimization.

Professional Rewriting
Improves grammar, tone, and structure while keeping facts intact.

DOCX & PDF Export
Outputs clean, recruiter-ready resumes in both .docx and .pdf formats.

Change Report
Generates a JSON report summarizing modifications for transparency.

🛠️ Tech Stack
Language: Python 3.

AI API: Google Gemini API. (THE API KEY I USED IN THIS PROJECT WILL BE AVAILABLE FOR 7 DAYS AFTER SUBMISSION)

Libraries: google-generativeai (Gemini API client),

nltk (skill extraction), python-docx (DOCX creation),

fpdf (PDF generation), re (text cleaning).
📂 Project Structure
resume-optimizer/

├── Resume_Optimizer.ipynb # Main notebook

├── requirements.txt # Dependencies

├── sample_resume.docx # Example resume

├── job_description.txt # Example job description

├── optimized_resume.docx # Output DOCX

├── optimized_resume.pdf # Output PDF

├── resume_change_report.json # Summary of changes

└── README.md # Project documentation

⚙️ Setup Instructions
1️⃣ Clone the Repository
from colab
git clone https://github.com/Prabhakarrayal

cd resume-optimizer
2️⃣ Install Dependencies

pip install -r requirements.txt
3️⃣ Set up Google Gemini API Key

Go to Google AI Studio

Generate an API key Save it in a .env file:

GEMINI_API_KEY=your_api_key_here
4️⃣ Run the Notebook In Google Colab or VS Code Jupyter Extension:

jupyter notebook Resume_Optimizer.ipynb
🖥️ Usage
Upload Resume (DOCX or TXT format)

Paste Job Description in the input cell

Run All Cells

Download Optimized Resume & Report

📊 Example Output
ATS Match Before: 62%

ATS Match After: 88%

Added Skills: ["Agile Methodology", "SQL", "Stakeholder Management"]

📎 Resources
Google Gemini API Docs

Python-docx Documentation

FPDF Documentation

NLTK Documentation
