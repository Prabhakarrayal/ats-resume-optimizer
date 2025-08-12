##📝 ATS Resume Optimizerusing Google Gemini AI
This project is an AI-powered resume optimization tool that analyzes your resume against a target job description and rewrites it to maximize ATS (Applicant Tracking System) compatibility. It intelligently detects missing skills, improves bullet points, and produces polished resume files in DOCX and PDF formats.

##🔧 Technologies Used
Python

Google Gemini API (google-generativeai SDK)

NLTK (text processing)

python-docx (DOCX generation)

FPDF (PDF export)

Jupyter Notebook / VS Code (development)

📌 Features
Extracts missing hard and soft skills from the job description

Classifies resumes as technical or non-technical for tailored optimization

Estimates ATS keyword match score before and after rewriting

Rewrites resume content to add relevant skills and improve clarity

Generates clean, formatted DOCX and PDF resume files

Produces a detailed change report summarizing added skills and suggestions

📁 What You Need to Run
Python 3.8+ installed

Google Gemini API key with access enabled

Sample resume file (DOCX or text)

Target job description text

🚀 How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/ats-resume-optimizer.git
cd ats-resume-optimizer
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set your Google Gemini API key in environment variables or code

Open and run the Jupyter notebook (Resume_Optimizer.ipynb) in Google Colab or VS Code

Upload your resume and paste the job description when prompted

Run all cells to generate optimized resume and reports

Download the output DOCX, PDF, and change summary files

##🚀 Future Improvements
Add fuzzy matching to better handle varied resume formats

Build a web app interface using Flask or Streamlit

Integrate more advanced ATS keyword scoring

Support multiple resume file formats (PDF parsing, etc.)

Add tone and confidence analysis for interview prep (voice model)

✍️ Author
Prabhakar Rayal
B.Tech CSE | Graphic Era Hill University
📍 Rishikesh, Uttarakhand, India

GitHub Profile | LinkedIn Profile
