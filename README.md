# Retrieval-Augmented-Generation-RAG---Project
Retriever And Chain With Langchain--->

# 📚 Retrieval-Augmented Generation (RAG) using LangChain + Ollama + FAISS  
This project implements a **fully local RAG pipeline** using:

- 🧠 **Ollama LLaMA2** as the LLM  
- 📄 **PDF Loader** for document ingestion  
- ✂️ **Recursive Text Splitter** for chunking  
- 🔍 **FAISS Vector Database** for semantic search  
- 🔗 **LangChain Retrieval Chain** for contextual Q&A  

This RAG chatbot answers user questions **using only the given PDF** and provides accurate, context-aware responses.

---

## 🚀 Features
- Load any **PDF document**
- Split document into optimized **text chunks**
- Generate **embeddings locally** using Ollama
- Store embeddings into **FAISS vector database**
- Build a **retrieval pipeline**
- Query using natural language
- Get **context-driven answers** from LLaMA2 (Ollama)

---
## 🛠️ Tech Stack
| Component | Library / Model |
|----------|------------------|
| LLM | Ollama (LLaMA2) |
| Embeddings | OllamaEmbeddings |
| Vector DB | FAISS |
| Framework | LangChain |
| Document Loader | PyPDFLoader |
| Text Splitter | RecursiveCharacterTextSplitter |

---

## 📂 Project Structure
RAG-Project/
│── Data/
│ └── Data Science Interview Preparation(#DAY 04).pdf
│── rag_app.py
│── README.md

## 📂 Project Structure

