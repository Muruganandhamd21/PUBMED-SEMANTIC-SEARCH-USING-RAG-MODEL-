# PubMed Semantic Search using RAG

## 📌 Project Overview
This project implements an **end-to-end Retrieval-Augmented Generation (RAG)** system for
semantic search over **PubMed biomedical research articles**.  
It allows users to ask natural language questions and retrieves relevant articles using
vector similarity search, then generates accurate answers using a language model.

---

## 🧠 Key Features
- Automated fetching of PubMed research articles
- Text preprocessing and chunking
- Semantic embedding generation
- FAISS-based vector database
- Retrieval-Augmented Generation (RAG) pipeline
- LLM-powered question answering

---

## 🛠️ Tech Stack
- Python
- Sentence Transformers
- FAISS
- PubMed API
- Ollama / LLM integration

---

## 📂 Project Structure
RAG_PUBMED/
├── backend/ # Core RAG pipeline
├── data/ # Data files (ignored in GitHub)
├── db/ # Vector database (ignored in GitHub)
├── app.py # Main application
├── chatbot_ollama.py # LLM chatbot interface
├── fetch_pubmed_articles_batch.py
├── index_articles.py
├── index_from_json.py
├── END_TO_END_FLOW.txt # End-to-end pipeline explanation
├── requirements.txt
├── .gitignore


