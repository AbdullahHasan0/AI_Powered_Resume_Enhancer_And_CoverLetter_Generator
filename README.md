# AI-Powered Resume Maker

An AI-powered workflow that updates your resume and generates a personalized cover letter based on any job description.

# Built with:
- OpenAI GPT models (resume analysis & generation)
- PyPDF2 / python-docx (resume text extraction)
- Gradio (interactive UI)
- Pydantic for LLM Output Validation
- Designed to run seamlessly on Google Colab 🚀

# ⚠️ Disclaimer
Add your OpenAI API key first in Colab Secrets or via environment variable (OPENAI_API_KEY).
This notebook is for educational/demo purposes only.
Do not upload confidential or sensitive resumes.

# ✨ Features
📂 Upload your resume in .pdf, .docx, or .txt format
📝 Paste any job description
🔍 AI-powered gap analysis between your resume and job description
📄 Generate an Updated Resume tailored to the role
✉️ Create a Personalized Cover Letter instantly
🖥️ Interactive Gradio web app with a clean Ocean theme

# 🚀 How to Use (Google Colab)
- Open the notebook in Google Colab.
- Add your OpenAI API key securely:

    - import os
    - from getpass import getpass
    - os.environ["OPENAI_API_KEY"] = getpass("🔑 Enter your OpenAI API key: ")

- Run cells step by step:
    - ✅ Load resume + job description
    - 🤖 Perform AI-powered analysis & updates
    - 📄 Generate updated resume + cover letter
    - 🎛️ Launch the Gradio interface

# 💡 Example Prompts
"Optimize my resume for a Data Scientist role at Google."
"Generate a cover letter highlighting teamwork and leadership skills."
"Update my resume for a Senior Software Engineer position in FinTech."

# 📝 Notes
- Works Only for text-based resumes for now(PDF).
- For scanned image-only PDFs, OCR (e.g., Tesseract) is needed.
