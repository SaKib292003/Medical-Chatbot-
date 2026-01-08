# Medical Chatbot using RAG 🏥🤖

## Overview
This project is a Medical Question Answering Chatbot built using the Retrieval-Augmented Generation (RAG) approach.  
The chatbot retrieves relevant medical information from documents and generates context-aware responses using a Large Language Model (LLM).

The goal of this project is to improve answer accuracy by grounding responses in retrieved medical data rather than relying solely on the LLM.

---

## Tech Stack
- Python  
- LangChain  
- Large Language Model (LLM)  
- Embedding Models  
- Vector Database (Pinecone / Chroma)  
- Flask (API)

---

## System Architecture
1. Medical documents are collected and preprocessed  
2. Text data is converted into embeddings using an embedding model  
3. Embeddings are stored in a vector database  
4. User queries are embedded and matched using semantic search  
5. Relevant context is retrieved from the vector database  
6. Retrieved context is passed to the LLM for answer generation  

This Retrieval-Augmented approach helps reduce hallucinations and improves relevance.

---

## Key Features
- Retrieval-Augmented Generation (RAG)
- Semantic search using vector embeddings
- Context-grounded responses
- Modular and extensible design
- REST API using Flask

---

## My Contributions
- Designed the end-to-end RAG architecture
- Implemented document ingestion and preprocessing pipeline
- Integrated embedding models and vector database
- Built retrieval and response generation logic using LangChain
- Developed a Flask API for chatbot interaction
- Tested and refined responses for better relevance

---

## Future Enhancements
- Improve medical document coverage
- Add response evaluation metrics
- Enhance prompt strategies
- Add user interface

---

## Disclaimer
This project is for educational and experimental purposes only.  
It should not be used as a replacement for professional medical advice.
