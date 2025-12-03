

---

#  Chat with PDF — RAG-Based Document QA System

##  Project Overview

This project provides an intelligent **Chat with PDF** system built using a Retrieval-Augmented Generation (RAG) pipeline.
Users can upload documents (PDF, TXT, DOCX, CSV), and the system automatically preprocesses the text, splits it into semantic chunks, generates embeddings, builds a vector index, and then answers user queries with high accuracy using an LLM.

The goal is to enable fast, reliable, and context-aware question answering directly from user-provided documents.

---

## 🔧 Key Features

* **Multi-format document ingestion** (PDF, TXT, DOCX, CSV).
* **Text preprocessing**: cleaning, normalization, deduplication.
* **Chunking** with configurable size and overlap.
* **Deep-learning embeddings** (Sentence Transformers / BGE / E5).
* **FAISS vector index** for fast semantic search.
* **Semantic retrieval + re-ranking** for high-quality answers.
* **LLM response generation** using a custom RAG prompt.
* **Gradio interface** for uploading files and chatting.
* **Source citation** for transparency and traceability.

---

##  System Architecture

1. **Upload Files**
2. **Load & Parse Documents**
3. **Text Preprocessing**
4. **Chunk Generation**
5. **Embedding Creation**
6. **FAISS Vector Index Building**
7. **User Query Input**
8. **Semantic Retrieval (Top-k)**
9. **Context Construction**
10. **LLM Answer Generation**
11. **Display Answer + Sources**

---
---

## 🛠️ Technologies Used

* **Python 3.10+**
* **FAISS** for vector indexing
* **HuggingFace Transformers** for embeddings
* **LangChain** for orchestration
* **Gradio** for UI
* **PyPDF / Unstructured** for document parsing

---

## 📌 Future Improvements

* Add hybrid search (sparse + dense).
* Add conversation memory.
* Add multi-user session support.
* Optional cloud vector DB (Pinecone / Weaviate).

---
