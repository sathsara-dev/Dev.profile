---

### 3. 🧠 InsightAI - Intelligent Document Analysis Platform
*(Use for the PDF/CSV Analysis & Chat Project)*

```markdown
# 🧠 InsightAI - RAG-Based Document Intelligence Platform

InsightAI is a powerful AI tool that transforms static documents (PDF, DOCX, CSV) into interactive insights. It utilizes **RAG (Retrieval-Augmented Generation)** with Semantic Search to allow users to "chat" with their documents and generates automated data visualizations.

![InsightAI Screenshot](Add-Your-Screenshot-Here.png)

## 🚀 Master Features
- **AI Chat (RAG):** Ask questions about your PDF/Docs and get context-aware answers using `Sentence-Transformers` & Cosine Similarity.
- **Smart Data Visualization:** Automatically generates Bar Charts and Analytics for uploaded CSV files.
- **Multi-Format Support:** Handles .CSV (Data), .PDF (Text), and .DOCX (Word) seamlessly.
- **Holographic UI:** A futuristic interface with Framer Motion animations.
- **Smart Chunking:** Advanced text processing window logic for better AI accuracy.

## 🛠️ Tech Stack
- **Frontend:** React JS, Recharts, Framer Motion
- **Backend:** Python Flask, Pandas, Scikit-Learn
- **AI Model:** HuggingFace `multi-qa-MiniLM-L6-cos-v1`
- **NLP:** PyPDF2, Python-Docx, Sentence-Transformers

## 📦 Installation & Run

### 1. Setup Backend (AI Engine)
```bash
cd backend
pip install flask flask-cors pandas scikit-learn sentence-transformers torch pypdf2 python-docx
python server.py