# Micro Knowledgebase RAG Bot

A lightweight Retrieval-Augmented Generation (RAG) bot that answers questions based on a curated collection of documents. Built using [LangChain](https://github.com/hwchase17/langchain), [Pinecone](https://www.pinecone.io/), and OpenAI's GPT models.

## Overview

This project demonstrates how to:
- **Scrape and embed documents**: Process a set of articles (e.g., on UX + AI) into vector embeddings.
- **Store embeddings in Pinecone**: Index and search document vectors efficiently.
- **Query the knowledge base**: Use LangChain to retrieve contextually relevant documents based on user questions.
- **Generate responses**: Leverage GPT-4 to produce human-like answers informed by retrieved context.

The goal is to showcase a minimal yet fully functional RAG system that can be expanded for various applications.

## Features

- **Document Scraping & Processing**: Ingests text data from pre-defined sources.
- **Vector Embeddings**: Utilizes OpenAI embeddings for high-quality semantic search.
- **Pinecone Integration**: Stores and queries vectors for rapid retrieval.
- **LangChain Orchestration**: Manages document retrieval and answer generation.
- **Simple CLI/Streamlit Interface**: Interact with the bot using a terminal-based or web-based interface.

## Setup & Installation

### Prerequisites

- Python 3.8+
- An OpenAI API key
- Pinecone API key and environment

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/micro-knowledgebase-rag-bot.git
   cd micro-knowledgebase-rag-bot
