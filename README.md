# RAG Implementation

This notebook demonstrates how to build a Retrieval-Augmented Generation (RAG) system using OpenAI APIs.

## What It Does

RAG combines large language models with information retrieval to answer questions using external knowledge. This implementation:

1. Loads text data from an essay
2. Splits the text into manageable chunks
3. Creates embeddings for each chunk using OpenAI's embedding model
4. Stores these embeddings in a vector database (FAISS)
5. Retrieves relevant chunks when a question is asked
6. Generates accurate answers based on the retrieved information

## Requirements

- OpenAI API key
- Python packages: openai, faiss-cpu, numpy, requests, dotenv

## Two Implementations

1. **RAG from scratch**: A basic implementation using only essential dependencies
2. **RAG with LangChain**: The same functionality using the LangChain framework

This notebook is perfect for understanding the fundamentals of RAG systems before exploring more complex implementations.
