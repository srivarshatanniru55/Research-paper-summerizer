# 📚 Research Paper Summarizer using AI

## 🚀 Overview

Research Paper Summarizer is an AI-powered web application that helps users quickly understand research papers by generating concise summaries and key insights from PDF documents.

The application extracts text from uploaded research papers, analyzes the content, calculates NLP metrics, and generates intelligent summaries using Google's Gemini AI model.

---

## ✨ Features

* 📄 Upload and analyze PDF research papers
* 🤖 AI-generated summaries using Gemini API
* 🔍 Automatic text extraction from PDFs
* 📊 NLP-based document statistics

  * Word Count
  * Estimated Reading Time
  * Complexity Level
  * Keyword Extraction
* 💬 Chat with your research paper
* 🌐 Modern React-based user interface
* ⚡ FastAPI backend for efficient processing

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript
* CSS

### Backend

* Python
* FastAPI
* Uvicorn

### AI & NLP

* Google Gemini API
* PDF Text Extraction
* Custom NLP Analysis

---

## 📂 Project Structure

```text
Research-Paper-Summarizer/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── main.py
│   ├── services/
│   │   ├── parser.py
│   │   ├── summarizer.py
│   │   └── chat.py
│   └── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/research-paper-summarizer.git
cd research-paper-summarizer
```

### 2. Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

### 3. Configure Gemini API Key

Create a `.env` file inside the backend folder:

```env
GEMINI_API_KEY=your_api_key_here
```

### 4. Start Backend

```bash
uvicorn main:app --reload
```

Backend runs on:

```text
http://localhost:8000
```

### 5. Start Frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## 📖 How It Works

1. User uploads a research paper PDF.
2. Backend extracts text from the document.
3. NLP metrics are calculated.
4. Gemini AI generates a summary.
5. Results are displayed on the frontend.
6. Users can ask questions about the paper using the chat feature.

---

## 📊 Output Includes

* Research Paper Summary
* Key Insights
* Keywords
* Word Count
* Reading Time
* Complexity Analysis
* Interactive Paper Chat

---

## 🔮 Future Improvements

* Multi-paper comparison
* Citation extraction
* Research trend analysis
* Export summaries to PDF
* Support for DOCX and TXT files
* Advanced semantic search

---

## 👨‍💻 Author

Developed as an AI-powered academic assistance project for simplifying research paper understanding and analysis.

---

## 📜 License

This project is intended for educational and learning purposes.
