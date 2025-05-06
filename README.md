# Resume-Scanner
  A beginner-friendly, menu-driven Resume Scanner using Python and NLP that extracts text from resumes (PDF/DOCX), matches skills with job descriptions, and exports results to Excel – fully compatible with Google Colab.
  # Resume Scanner 
      A beginner-friendly, menu-driven Resume Scanner built with Python, NLP (spaCy), and Pandas. This project extracts text from resumes (PDF/DOCX), matches them against a given job description, and displays/extracts the match results as an Excel report – all within Google Colab.

Features

 Upload and parse multiple PDF/DOCX resumes
   Extract text using PyMuPDF and python-docx
   Match extracted content with user-defined job skills
   Show matching percentage and matched keywords
   Export results to Excel and download them directly from Colab
Setup Instructions (Google Colab)

1. Clone or open this project in Google Colab.
2. Install dependencies:

python
!pip install python-docx PyMuPDF openpyxl spacy
!python -m spacy download en_core_web_sm
