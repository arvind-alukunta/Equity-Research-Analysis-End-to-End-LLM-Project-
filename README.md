# Equity Research Analysis using LLMs
A Retrieval-Augmented Generation (RAG) based news intelligence system for equity research.

# Overview
This project implements an end-to-end Generative AI solution that allows users to input multiple financial news article URLs and ask analytical questions. 
The system uses Retrieval-Augmented Generation (RAG) to generate accurate, context-aware answers grounded in the provided sources.

# Problem Statement
Equity research analysts spend significant time manually reviewing multiple news articles to extract insights for investment decisions. 
This process is time-consuming and difficult to scale.

# Solution Approach
The system ingests news articles, converts them into semantic embeddings, stores them in a vector database, and retrieves the most relevant content at query time. 
An LLM then generates precise answers based on the retrieved context.

# Technical Architecture
News URLs → Document Loader → Text Chunking → OpenAI Embeddings → Vector Database (FAISS) → Retriever → LLM → Answer with Sources

# Tech Stack
- Python
- LangChain
- OpenAI (LLM & Embeddings)
- FAISS (Vector Database)
- Streamlit

# Key Features
- URL-based document ingestion
- Semantic search using vector embeddings
- Retrieval-Augmented Generation (RAG)
- Source-aware answers
- Interactive Streamlit UI
