# rag
PDF Question-Answering with Google Gemini + LangChain

This project is a Retrieval-Augmented Generation (RAG) pipeline that lets you upload a PDF and ask natural language questions about its contents. It uses Google Gemini, LangChain, FAISS, and Gradio to provide an interactive Q&A interface.

Features

Upload any PDF document and process it automatically.

Split the document into semantic chunks for better retrieval.

Generate embeddings using Google Gemini (models/embedding-001).

Store and search embeddings with FAISS vector database.

Ask questions with Gemini (gemini-1.5-flash) via LangChain’s RetrievalQA.

Interactive web UI powered by Gradio.
