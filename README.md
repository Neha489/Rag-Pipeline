# RAG Pipeline

Retrieval-Augmented Generation (RAG) pipeline that scrapes articles from news channels, embeds them using nomic-embed-text, stores them in a vector database, and answers user queries using Ollama's LLaMA 3 8B model.

## Features

- Scrape articles from TOI using provided URLs
- Generate text embeddings using nomic-embed-text via Ollama
- Store embeddings in a local macro vector database
- Query articles and get context-aware responses with llama3:8b
- Fully local, lightweight, and customizable

