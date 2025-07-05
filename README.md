# Chat with doc with groq and gemini with chat history.

This Streamlit application allows you to upload PDF documents and interact with them using a Retrieval-Augmented Generation (RAG) pipeline. It supports chat history so that conversations can reference previous questions and answers. You can choose between two large language model providers: **Groq (Gemma2-9b-it)** and **Google Gemini Pro**.

---

## Features

- Upload and parse one or more PDF files
- Chunk and embed document contents using HuggingFace sentence embeddings
- Store and retrieve document chunks using Chroma vector store
- Ask questions with conversational memory
- Maintain per-session chat history
- Choose between Groq (Gemma2-9b-it) or Google Gemini Pro (e.g., gemini-2.5-flash)

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pdf-chat-rag.git
cd pdf-chat-rag

