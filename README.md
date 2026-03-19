# 🚀 Hybrid RAG-Based Personal Knowledge Assistant

This project is a **Retrieval-Augmented Generation (RAG) chatbot** that answers questions about a candidate’s profile by combining:

- 📄 Personal documents (CV, project descriptions)
- 🧠 LLM knowledge (Gemini API)

---

## 🔥 Features

- Hybrid RAG (Document + LLM knowledge)
- Semantic search using FAISS
- HuggingFace embeddings (free)
- Gemini-powered intelligent responses
- Context-aware and explainable answers

---

## 🧠 Architecture

User Query → Vector Search (FAISS) → Context Retrieval → Gemini LLM → Answer

---

## ⚙️ Tech Stack

- Python
- LangChain
- FAISS (Vector DB)
- HuggingFace Embeddings
- Google Gemini API

---

## 📂 Project Structure





---

## 🚀 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/jubin5/hybrid-rag-personal-assistant.git
cd hybrid-rag-personal-assistant


pip install -r requirements.txt

genai.configure(api_key="YOUR_GEMINI_API_KEY")

python app.py


---

# 🚀 🔹 6. Upload to GitHub

### Run these commands:

```bash
git init
git add .
git commit -m "Initial commit - Hybrid RAG chatbot"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/hybrid-rag-personal-assistant.git
git push -u origin main
