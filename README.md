# Gen-AI-Chat-bot
AI document assistant built with Python, FastAPI, Redis, Jina Embeddings, and Mistral-7B for semantic search and contextual Q&amp;A.
# 🤖 Gen-AI Chatbot for Enterprise Document Analysis

An AI-powered document assistant that enables semantic search and contextual question answering over enterprise documentation using Retrieval-Augmented Generation (RAG).

The application combines modern embedding models, vector search, reranking, and Large Language Models (LLMs) to provide accurate and context-aware responses from technical documents.

---

## 📌 Overview

Traditional keyword-based search often fails to retrieve relevant information from large technical documentation.

This project addresses that challenge by implementing a Retrieval-Augmented Generation (RAG) pipeline that understands semantic meaning and generates accurate responses grounded in enterprise documents.

---

## ✨ Features

- 📄 Upload and process PDF documents
- 🔍 Semantic document search
- 🧠 Context-aware question answering
- ⚡ Fast vector similarity search
- 🤖 Mistral-7B powered responses
- 📚 Redis Vector Database
- 🎯 TinyBERT reranking
- 🌐 REST API using FastAPI
- 💻 Interactive React user interface

---

## 🏗️ System Architecture

```
User Query
      │
      ▼
 React Frontend
      │
      ▼
 FastAPI Backend
      │
      ▼
Jina Embeddings
      │
      ▼
Redis Vector Database
      │
      ▼
TinyBERT Re-ranker
      │
      ▼
Mistral-7B LLM
      │
      ▼
Generated Response
```

---

## 🛠️ Technology Stack

| Category | Technologies |
|-----------|--------------|
| Programming | Python |
| Backend | FastAPI |
| Frontend | React |
| Vector Database | Redis + RediSearch |
| Embeddings | Jina Embeddings |
| Reranking | TinyBERT |
| LLM | Mistral-7B |
| Containerization | Docker |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```
Gen-AI-Chatbot/
│
├── backend/
├── frontend/
├── documents/
├── embeddings/
├── api/
├── utils/
├── README.md
├── LICENSE
└── requirements.txt
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/vismaya0813/Gen-AI-Chat-bot.git
```

### Navigate to the project

```bash
cd Gen-AI-Chat-bot
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Start Redis

```bash
docker compose up
```

### Run the backend

```bash
uvicorn main:app --reload
```

### Start the frontend

```bash
npm install
npm start
```

---

## 📊 Key Capabilities

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- PDF Document Processing
- Vector Similarity Search
- Enterprise Knowledge Base
- AI-powered Question Answering

---

## 🎯 Applications

- Enterprise Documentation
- Technical Knowledge Base
- Internal AI Assistant
- Customer Support
- Network Documentation
- Research Assistance

---

## 📈 Future Enhancements

- Multi-document collections
- OCR support
- Role-based authentication
- Multi-language support
- Voice interaction
- Cloud deployment

---

## 👨‍💻 Author

**Vismaya C**

M.Tech Computer Engineering

Python • AI • Network Automation • Enterprise Networking

---

## 📄 License

This project is licensed under the MIT License.
