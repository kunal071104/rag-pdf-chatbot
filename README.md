# 🤖 Offline AI PDF Chatbot

This is a fully offline AI chatbot that allows users to interact with PDF documents using natural language.

## 🔥 Features
- Works completely offline
- Uses Mistral 7B via Ollama
- PDF Question Answering
- Semantic Search using FAISS

## 🛠️ Tech Stack
- Python
- Streamlit
- LangChain
- FAISS
- Ollama (Local LLM)

## ⚙️ Run Locally

```bash
pip install -r requirements.txt
ollama serve
ollama run mistral
streamlit run app.py
