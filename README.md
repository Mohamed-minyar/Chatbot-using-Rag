## 📌 Overview
**RAG-Emotion** is a **Retrieval-Augmented Generation (RAG)** pipeline that combines:
- **BERT-based classification** → detects emotions (`anger`, `joy`, `sadness`, `optimism`, etc.).
- **FAISS embeddings** → retrieves the most relevant context from your dataset.
- **GPT-2 generation** → generates natural answers guided by the retrieved docs + detected emotion.  

This makes the system **context-aware + emotion-aware** for more human-like interactions.  

---

## 🚀 Features
- ✅ Emotion classification using **BERT / DistilBERT**  
- ✅ Semantic search with **Sentence Transformers + FAISS**  
- ✅ Answer generation with **GPT-2**  
- ✅ Support for **custom JSON datasets**  
- ✅ Deployable with **Streamlit** (UI) or **FastAPI** (API service)  

# 🎭 RAG-Emotion: Retrieval-Augmented Generation for Emotion-Aware Responses

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![HuggingFace](https://img.shields.io/badge/🤗-Transformers-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![FAISS](https://img.shields.io/badge/FAISS-Similarity_Search-yellow)

---
## 🛠️ Tech Stack
- 🤗 Hugging Face Transformers  
- 🧠 DistilBERT (Classification)  
- ✍️ GPT-2 (Generation)  
- 🔎 FAISS (Efficient similarity search)  
- 🎨 Streamlit / FastAPI (Deployment)  

---

## 📂 Project Structure
