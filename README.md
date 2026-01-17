AI Resume Analyzer

Project Overview:
AI Resume Analyzer is a web-based application that allows students, fresh graduates, and job seekers to upload their PDF resumes and get instant, AI-powered feedback. The system checks whether the uploaded document is a resume, analyzes it based on a selected job role, and provides insights such as strengths, areas for improvement, ATS score, and actionable tips.

Features

Upload PDF resumes through a simple web interface

Automatic resume classification (Resume / Not a Resume)

Job-specific analysis and recommendations

ATS (Applicant Tracking System) scoring

Downloadable feedback report

Built using Python, Streamlit, and Groq AI

Technologies Used

Python – Core programming language

Streamlit – Web application UI

PyPDF2 – PDF text extraction

Groq API – Access AI language model

LLaMA 3.1 (LLM) – Resume classification and analysis

dotenv – Secure API key management

Installation & Setup

Clone the repository:

git clone <your-repo-link>


Navigate to the project directory:

cd ai-resume-analyzer


Install required libraries:

pip install streamlit PyPDF2 python-dotenv groq


Create a .env file and add your Groq API key:

GROQ_API_KEY=your_api_key_here


Run the application:

streamlit run app.py

Usage

Open the web app in your browser (Streamlit provides a local URL).

Upload your PDF resume using the file uploader.

Enter the target job role in the sidebar.

Click Analyze Resume to get AI feedback.

View strengths, weaknesses, ATS score, and actionable tips.

Download the feedback report for later use.

Deployment

The application can be deployed on:

Streamlit Community Cloud: https://streamlit.io/cloud

Render: https://render.com

AWS EC2 / Cloud: https://aws.amazon.com/ec2/

Source code hosted on GitHub: https://github.com/

Future Scope

Support for DOCX and TXT file formats

Resume vs job description matching

Interview preparation and skill-gap analysis

Multi-language resume analysis

User login and resume history tracking

References

Streamlit Documentation – https://docs.streamlit.io/

PyPDF2 Documentation – https://pypdf2.readthedocs.io/

Groq API Documentation – https://console.groq.com/docs

LLaMA Model (Meta AI) – https://ai.meta.com/llama/
