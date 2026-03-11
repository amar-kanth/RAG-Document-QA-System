# RAG Document Question Answering System

This project demonstrates a Retrieval-Augmented Generation (RAG) system that allows users to interact with document content using natural language questions.

The application processes uploaded documents, converts them into embeddings, stores them in a vector database, and retrieves relevant information to generate contextual answers using a Large Language Model (LLM).

---

## Technologies Used

Python  
LangChain  
FAISS Vector Database  
Google Gemini LLM  
Streamlit  

---

## Project Pipeline

Document Upload  
↓  
Text Chunking  
↓  
Embedding Generation  
↓  
Vector Storage (FAISS)  
↓  
Similarity Retrieval  
↓  
LLM Response Generation  

---

## How the System Works

1. A user uploads a document (PDF or TXT).
2. The document is split into smaller text chunks.
3. Each chunk is converted into embeddings using an embedding model.
4. The embeddings are stored in a FAISS vector database.
5. When a user asks a question, the system retrieves the most relevant chunks.
6. The retrieved content is passed to the LLM to generate a contextual response.

---

## Running the Project

Install dependencies


pip install -r requirements.txt


Run the application


streamlit run app.py


Then open your browser:


http://localhost:8501


---

## Learning Objective

This project was explored to understand how Retrieval-Augmented Generation (RAG) systems work using LangChain, vector databases, and large language models.

---

## Key Concepts Demonstrated

Retrieval-Augmented Generation (RAG)  
Document Embeddings  
Vector Similarity Search  
Large Language Models  
Document Question Answering  

---

## Folder Structure


project/
│
├── app.py
├── requirements.txt
├── data/
├── notebooks/
└── README.md


---

## Future Improvements

Add support for more document formats  
Enable multi-document querying  
Add document summarization features  
Improve UI for better user interaction