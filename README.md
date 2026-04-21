Marketing Intelligence RAG System

An AI-powered system that analyzes marketing case studies and provides context-aware insights using Retrieval-Augmented Generation (RAG).

🚀 Project Overview

This project is a Marketing Intelligence Assistant that allows users to ask marketing-related questions and receive accurate answers based on real-world case studies.

It combines:

📚 Document Retrieval (ChromaDB)
🧠 Language Model (Mistral via Ollama)
💬 Chat Interface (Streamlit)
⚙️ Features
✅ Chat-based AI interface
✅ Retrieval-Augmented Generation (RAG)
✅ Hybrid search (semantic + keyword)
✅ Real-time streaming responses
✅ Persistent vector database
✅ Upload PDF/TXT documents
✅ Context-based answers (no hallucination)



System Architecture
User Query
   ↓
Retrieval (ChromaDB)
   ↓
Relevant Context
   ↓
Prompt Builder
   ↓
LLM (Mistral via Ollama)
   ↓
Final Answer


Technologies Used
Python
Streamlit
ChromaDB
Sentence Transformers
Ollama (Mistral LLM)
Scikit-learn (TF-IDF)
PDFPlumber


Project Structure
marketing rag system
│
├── streamlit_app.py
│
├── data
│   ├── hubspot_marketing_cases.json
│   └── db
│
├── src
│   ├── load_docs.py
│   ├── chunk_docs.py
│   ├── embeddings.py
│   ├── vector_store.py
│   ├── retrieval.py
│   ├── prompt_builder.py
│   └── answer_generator.py
│
├── requirements.txt
└── README.md


🛠️ Installation
git clone <https://github.com/radhe2321/Marketing-Intelligence-rag-report>
cd marketing-rag-system

👨‍💻 Author

Radhe Suthar
Marketing Intelligence RAG Project
