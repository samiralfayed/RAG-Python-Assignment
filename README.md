# RAG-Python-Assignment

A simple Retrieval-Augmented Generation (RAG) system that answers English and Bangla questions using uploaded documents.

 Features
Upload PDF, DOCX, TXT, or images

Ask questions in English or Bangla

Uses FAISS for retrieval & FLAN-T5 for generation

FastAPI backend + HTML frontend (ngrok for public access)

 Usage
Run rag.py in Colab or locally

Update ngrokUrl in index.html

Open index.html in browser to start chatting

 API
POST /upload: Upload file

POST /query: Ask question and get answer

