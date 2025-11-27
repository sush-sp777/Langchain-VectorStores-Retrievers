# Langchain-Message-History

This repository contains practice code while learning LangChain VectorStores, Embeddings, and Retrievers.  
It contains how to store documents, embed them, and query them using a RAG-style pipeline.

## Contents
- Creating `Document` objects
- Using `HuggingFaceEmbeddings`
- Building a Chroma VectorStore
- Converting VectorStore into a Retriever
- RunnableLambda for splitting inputs (question/context)
- RunnableParallel for building the RAG input
- End-to-end RAG chain using prompt + retriever + LLM

## Purpose
This repository is only for practicing and understanding:
- How vector embeddings work  
- How to store and retrieve documents  
- How LangChain creates RAG pipelines with runnables  

It is purely for learning and experimentation.

## How to Run
1. Create a virtual environment  
2. Install dependencies from `requirements.txt`  
3. Open the notebook and run cells step-by-step  

You will need:
- `GROQ_API_KEY`
- `HUGGINGFACE_TOKEN`

Add these to your `.env` file before running.
