# Vanilla RAG with Gemini (No LangChain)

A fully custom Retrieval-Augmented Generation (RAG) pipeline built **without** LangChain.  
This project uses Gemini Pro for generation, ChromaDB for local vector storage, and SentenceTransformers for semantic search — all wired together manually for full transparency and control.

---

## 📚 Related Blog Post  
[Read the full blog here](https://genai-rag.hashnode.dev/vanilla-rag) 

---

## 🧩 Tech Stack

- **LLM**: Google Gemini Flash (`google.generativeai`)
- **Vector DB**: Local ChromaDB 
- **Document Parsing**: `PyPDF2` (for PDFs), basic `.txt` loaders
- **Chat Session Management**: In-memory with UUIDs

---

## 🛠️ Features

- Custom PDF/text document ingestion
- Sentence-based chunking with overlap
- Local vector store with ChromaDB
- Semantic search + Gemini-powered generation
- Chat session history handling
- RAG pipeline that combines history and context
