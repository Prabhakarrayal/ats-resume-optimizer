# 📝 ATS Resume Optimizer using Google Gemini AI

This project is an AI-powered resume optimization tool that analyzes your resume against a target job description and rewrites it to maximize ATS (Applicant Tracking System) compatibility. It intelligently detects missing skills, improves bullet points, and produces polished resume files in DOCX and PDF formats.

---

## 🔧 Technologies Used

- Python  
- Google Gemini API (`google-generativeai` SDK)  
- NLTK (text processing)  
- python-docx (DOCX generation)  
- FPDF (PDF export)  
- Jupyter Notebook / VS Code (development environment)

---

## 📌 Features

- Extracts missing hard and soft skills from the job description  
- Classifies resumes as technical or non-technical for tailored optimization  
- Estimates ATS keyword match score before and after rewriting  
- Rewrites resume content to add relevant skills and improve clarity  
- Generates clean, formatted DOCX and PDF resume files  
- Produces a detailed change report summarizing added skills and suggestions

---

## 📁 What You Need to Run

- Python 3.8 or higher  
- Google Gemini API key with access enabled  
- Sample resume file (DOCX or plain text)  
- Target job description text  

---

## 🚀 How to Run

1. Clone the repository:  
   
   #git clone ["https://github.com/yourusername/ats-resume-optimizer.git"]
   #colab 
       cd ats-resume-optimizer
   
3. Install dependencies:

       pip install -r requirements.txt

4. Set your Google Gemini API key in environment variables or in the code

5. Open and run the Jupyter notebook (Resume_Optimizer.ipynb) in Google Colab or VS Code

6. Upload your resume and paste the job description when prompted

7. Run all notebook cells to generate optimized resume and reports

8. Download the output DOCX, PDF, and change summary files

## 🚀 Future Improvements
Add fuzzy matching to better handle varied resume formats

Build a web app interface using Flask or Streamlit

Integrate more advanced ATS keyword scoring algorithms

Support multiple resume file formats (PDF parsing, etc.)

Add tone and confidence analysis for interview preparation
## ✍️ Author
Prabhakar Rayal
B.Tech CSE | Graphic Era Hill University
📍 Rishikesh, Uttarakhand, India

GitHub Profile | LinkedIn Profile
