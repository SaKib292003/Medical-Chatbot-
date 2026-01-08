# Medical Chatbot using RAG 🏥🤖

## Overview
This project is a Medical Question Answering Chatbot built using the Retrieval-Augmented Generation (RAG) approach.  
The chatbot retrieves relevant medical information from documents and generates accurate, context-aware responses using a Large Language Model (LLM).

The main objective of this project is to reduce hallucinations by grounding responses in retrieved medical data instead of relying only on the LLM.

---

## Tech Stack
- Python  
- LangChain  
- Large Language Model (LLM)  
- Embedding Models  
- Vector Database (Pinecone / Chroma)  
- Flask (API)  
- AWS (deployment-ready structure)

---

## System Architecture
1. Medical documents are collected and cleaned  
2. Text data is converted into embeddings using an embedding model  
3. Embeddings are stored in a vector database  
4. User queries are embedded and matched using semantic search  
5. Relevant context is retrieved from the vector database  
6. Retrieved context is passed to the LLM for answer generation  

This Retrieval-Augmented approach improves factual accuracy and response relevance.

---

## Key Features
- Retrieval-Augmented Generation (RAG)
- Semantic search using vector embeddings
- Reduced hallucinations compared to standalone LLMs
- Scalable and modular design
- REST API using Flask

---

## My Contributions
- Designed the end-to-end RAG architecture
- Implemented document ingestion and preprocessing pipeline
- Integrated embedding models and vector database
- Built retrieval and response generation logic using LangChain
- Developed a Flask API to expose chatbot functionality
- Tested and improved response quality through prompt tuning

---

## Future Enhancements
- Add authentication and user management
- Expand medical document coverage
- Add response evaluation metrics
- Full deployment on AWS with CI/CD

---

## Disclaimer
This project is for educational and experimental purposes only.  
It should not be used as a substitute for professional medical advice.
