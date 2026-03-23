# Digital Memory Twin

A full-stack RAG-based system for intelligent document understanding, semantic retrieval, and automated flashcard generation.

## 🚀 Features

* Multi-agent RAG pipeline for context-aware question answering
* Semantic chunking and FAISS-based document retrieval
* Context filtering to improve answer relevance
* Keyword-based flashcard generation for faster revision
* Interactive React frontend for real-time user queries

## 🛠️ Tech Stack

* **Backend:** FastAPI, Python
* **Frontend:** React, TypeScript, Vite
* **Vector Search:** FAISS
* **AI/NLP:** Sentence Transformers / RAG pipeline

## 🧠 System Architecture

The system follows a modular RAG pipeline:

1. **Question Understanding** – Processes and refines user queries
2. **Context Retrieval** – Fetches relevant document chunks using FAISS
3. **Answer Generation** – Produces accurate responses using retrieved context
4. **Flashcard Generation** – Extracts key concepts for revision

## 📂 Project Structure

```id="a1"
backend/
  ├── rag_engine/
  ├── simple_engine/
  ├── gateway.py

frontend/
  ├── src/
  ├── public/
```

## ⚙️ Setup Instructions

### 1. Clone repository

```id="a2"
git clone https://github.com/your-username/digital-memory-twin.git
cd digital-memory-twin
```

### 2. Backend setup

```id="a3"
cd backend
pip install -r requirements.txt
python gateway.py
```

### 3. Frontend setup

```id="a4"
cd frontend
npm install
npm run dev
```

## 🔒 Environment Variables

Create a `.env` file in backend:

```id="a5"
API_KEY=your_key_here
```

## 📊 Highlights

* Improved retrieval relevance by reducing irrelevant context
* Designed modular RAG pipeline for scalability
* Built end-to-end system from document ingestion to response generation

## 🚀 Future Improvements

* Add authentication system
* Improve UI/UX
* Deploy using Docker / cloud

---

