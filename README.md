# Mini RAG Chatbot

## Open in Google Colab

[Open Notebook in Colab](https://colab.research.google.com/github/Prabhavathi-k/Mini_Rag_Chatbot/blob/main/Mini_Rag_Chatbot.ipynb)

## Project Overview

This project implements a simple Retrieval-Augmented Generation (RAG) chatbot capable of answering questions from a PDF document.

The chatbot reads a PDF, extracts text, splits it into chunks, generates embeddings using Sentence Transformers, stores them in a FAISS vector database, retrieves relevant chunks based on user questions, and generates answers using Google's Gemini LLM.

---

## Architecture

PDF Document
->
Text Extraction (PyPDF)
->
Text Chunking
->
Embeddings Generation
->
FAISS Vector Database
->
Semantic Search
->
Context Retrieval
->
Gemini LLM
->
Answer Generation

---

## Technologies Used

* Python
* Google Colab
* PyPDF
* Sentence Transformers
* FAISS
* Google Gemini API
* NumPy

---

## Features

* PDF Text Extraction
* Text Chunking
* Embeddings Generation
* Vector Database Storage
* Semantic Search
* Context Retrieval
* LLM-based Question Answering

---

## Installation

```bash
pip install pypdf
pip install sentence-transformers
pip install faiss-cpu
pip install google-generativeai
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Install dependencies.
3. Upload a PDF file.
4. Run all notebook cells.
5. Ask questions related to the uploaded PDF.

---

## Sample Questions

* What is feedback hell?
* What are the key findings?
* Summarize the document.
* What recommendations are mentioned?

---

## Future Improvements

* Use ChromaDB instead of FAISS
* Add conversational memory
* Support multiple PDFs
* Build a Streamlit UI

---

## Screenshots

Screenshots are available in the screenshots folder.
