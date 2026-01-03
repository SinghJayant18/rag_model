# RAG Model with LangChain & ChromaDB

##  Introduction
This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using **LangChain**, **ChromaDB**, and **LLMs**.  
It demonstrates how to load external data, clean and chunk it, generate embeddings, store them in a vector database, and retrieve relevant context for question answering.

The notebook is designed to run in **Google Colab** and focuses on practical RAG implementation.

---





##  Features
- Web-based document loading
- Text cleaning and recursive chunking
- Embedding generation using HuggingFace models
- Vector storage with ChromaDB
- Retrieval-based question answering
- Compatible with OpenAI and open-source embeddings

---

##  Tech Stack & Dependencies
- Python 3.8+
- LangChain
- LangChain Community
- LangChain Hub
- ChromaDB
- HuggingFace Sentence Transformers
- OpenAI (optional)
- Google Colab

---

##  Installation
Run the following commands inside your environment or Colab notebook:

```bash
pip install langchain langchain_community langchainhub chromadb
pip install sentence-transformers
pip install langchain-openai


