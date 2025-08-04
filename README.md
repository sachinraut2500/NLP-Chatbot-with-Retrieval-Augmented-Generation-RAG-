# 🤖 Retrieval-Augmented Generation (RAG) Chatbot

This chatbot combines semantic search (retrieval) with language generation to answer user queries based on a small knowledge base.

---

## 💡 What is RAG?

RAG = Retrieval-Augmented Generation  
It retrieves relevant context using dense vector search and feeds it to a language model for generating answers.

---

## Model Stack

- SentenceTransformer (`all-MiniLM-L6-v2`) for context retrieval
- GPT-2 (transformers) for generation
- Top-1 relevant document retrieved and used as prompt context

---

## ⚙️ Requirements

```bash
pip install sentence-transformers transformers torch
