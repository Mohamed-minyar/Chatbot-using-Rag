## 📌 Overview
**RAG-Emotion** is a **Retrieval-Augmented Generation (RAG)** pipeline that combines:
- **BERT-based classification** → detects emotions (`anger`, `joy`, `sadness`, `optimism`, etc.).
- **FAISS embeddings** → retrieves the most relevant context from your dataset.
- **GPT-2 generation** → generates natural answers guided by the retrieved docs + detected emotion.  

This makes the system **context-aware + emotion-aware** for more human-like interactions.  

**A NEW FEATURE
🎙️ RAG + Emotion Chatbot (Text & Voice)

A conversational assistant that combines Retrieval-Augmented Generation (RAG), BERT emotion classification, and GPT-2 generation with speech-to-text (STT) and text-to-speech (TTS).
Speak or type a message → the bot detects your emotion, retrieves context documents, generates an answer, and reads it aloud.

🚀 Features

Emotion Detection – BERT model classifies user sentiment.

Retrieval-Augmented Generation – finds relevant info from your knowledge base using embeddings + FAISS.

Text Generation – GPT-2 crafts responses using retrieved docs & your emotional state.

Speech-to-Text – powered by Wav2Vec2 for voice input.

Text-to-Speech – gTTS speaks answers aloud.

Streamlit UI – switch between typing and talking.

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
