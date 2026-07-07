AI Resume Analyzer

An intelligent web application that analyzes a candidate's resume against a job description to estimate an ATS (Applicant Tracking System) match score. The application extracts text from PDF resumes, compares it with the job requirements, identifies matched and missing skills, and provides suggestions to improve the resume.

Features

📂 Upload resumes in PDF format
📝 Enter a job description
📊 Generate an ATS-style match score
✅ Identify matched skills
❌ Highlight missing skills
💡 Provide resume improvement suggestions
🔄 Analyze multiple resumes without restarting the application
🌐 Simple and responsive web interface
Tech Stack

Backend: Python, Flask
Frontend: HTML5, CSS3, Bootstrap 5
Resume Parsing: PyMuPDF (or pypdf, depending on your setup)
Text Similarity: RapidFuzz
Version Control: Git & GitHub
Project Structure

Resume-Analyzer/ │ ├── app.py ├── analyzer.py ├── parser.py ├── requirements.txt ├── README.md │ ├── templates/ │ ├── index.html │ └── result.html │ ├── static/ │ └── style.css │ └── uploads/

How It Works

Upload a PDF resume.

Paste the job description.

The application extracts text from the resume.

RapidFuzz compares the resume with the job description.

The application:

Calculates a similarity score
Detects matched skills
Identifies missing skills
Generates improvement suggestions
Future Enhancements

User authentication
Resume ranking for multiple applicants
AI-powered resume recommendations
Resume keyword optimization
Downloadable PDF analysis report
Interactive dashboard and charts
Support for DOCX resumes Author
Maham Faiz Malik

GitHub: https://github.com/mahamfaizmalik1023
