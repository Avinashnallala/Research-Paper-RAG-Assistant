# 📚 Research Paper RAG Assistant

An AI-powered Research Paper Assistant built using LangChain, FAISS, Ollama, and Hugging Face Embeddings.

The application enables users to upload research papers and ask natural language questions. Using Retrieval-Augmented Generation (RAG), the system retrieves the most relevant document chunks and generates context-aware answers with a local LLM.

---

## Features

- PDF document ingestion
- Intelligent text chunking
- Hugging Face embeddings (all-MiniLM-L6-v2)
- FAISS vector database
- Semantic similarity search
- LangChain Retrieval Pipeline
- Ollama local LLM (Qwen3:8b)
- Context-aware question answering
- Local inference (no cloud required)

---

## Technology Stack

- Python
- LangChain
- FAISS
- Ollama
- Hugging Face
- Sentence Transformers
- PyPDF
- Streamlit (optional UI)

---

## Architecture

```
PDF
   │
PyPDFLoader
   │
Chunking
   │
Embeddings
   │
FAISS
   │
Retriever
   │
Prompt
   │
Qwen3 (Ollama)
   │
Answer
```

---

## Installation

```bash
git clone https://github.com/yourusername/Research-Paper-RAG-Assistant.git

cd Research-Paper-RAG-Assistant

pip install -r requirements.txt
```

Install Ollama model

```bash
ollama pull qwen3:8b
```

Run

```bash
python app.py
```

---

## Future Improvements

- Multi-PDF Support
- Research Paper Comparison
- Citation Generation
- Hybrid Search
- Streamlit Dashboard
- LangGraph Agents
- Conversation Memory
- Source Highlighting

---

## Author

Avinash Nallala
