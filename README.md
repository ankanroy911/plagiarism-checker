# plagiarism-checker
# 🧠 AI-Based Plagiarism Checker (Flask Web App)

This is a Flask-based web application for detecting plagiarism in student assignments across subjects like **DBMS** and **COA**. It compares student submissions against multiple teacher-uploaded reference files and returns a plagiarism percentage. The app supports both direct text input and PDF file uploads.

---

## 🚀 Features

- 📁 **Multiple Reference File Uploads** for DBMS & COA
- 📝 **Student Assignment Input** via Text Box or PDF Upload
- 🧠 **AI-Powered Sentence Embedding** using Sentence Transformers
- 🔍 **Smart Filtering** of common/short words and special characters
- ✅ **Plagiarism Threshold Evaluation**
- 🌐 **Simple, Responsive Web UI** with Flask & HTML

---

## 🛠️ Tech Stack

- Python 3
- Flask
- [Sentence Transformers](https://www.sbert.net/)
- PyMuPDF (fitz)
- HTML/CSS (Jinja2 templates)

---

## 📦 Installation

```bash
git clone https://github.com/YOUR-USERNAME/plagiarism-checker-flask.git
cd plagiarism-checker-flask
pip install -r requirements.txt
