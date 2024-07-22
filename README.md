Medico Chatbot

Medico Chatbot is an AI-powered conversational agent designed for detailed and well-explained responses to medical and scientific inquiries. It leverages LlamaCpp, SentenceTransformer embeddings, and Qdrant for efficient and accurate answers.

Features
oAdvanced language model processing with LlamaCpp
oSemantic search using SentenceTransformer embeddings
oHigh-performance vector storage and retrieval with Qdrant
oUser-friendly interaction via Gradio interface

Usage
1.  Run the Chatbot:
Start the application using your preferred method (e.g., `python app.py`).

2. Interact via Gradio Interfac:
Open the Gradio interface in your browser for real-time interactions.

Qdrant Setup

1. Ensure Qdrant is Running:
For local setup, you can use Docker:
  docker run -d --name qdrant -p 6333:6333 qdrant/qdrant
Confirm Qdrant is running and accessible at `http://localhost:6333`.

2. Database Integration:
The chatbot connects to Qdrant for storing and retrieving vector embeddings efficiently. Ensure that the Qdrant server is configured and the collection is named appropriately (e.g., `vector_db`).

Overview
Model Initialization: Loads LlamaCpp with optimal parameters.
Embeddings Setup: Uses SentenceTransformer for semantic embeddings.
Database Setup: Connects to Qdrant for efficient vector storage and retrieval.
Conversational Chain: Integrates LLM and retriever for context-aware responses.
Gradio Interface: Provides a seamless user interaction platform
