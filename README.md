# Codebase-Rag

## About this Project
This project leverages RAG to create an AI expert that 
provides users with the ability to chat with a codebase 
and learn how certain parts work and how it can be improved. 

## Features
- Codebase Embedding: Automatically processes and embeds the contents of a codebase into a vector database
- Response Generation: Applies RAG and llama-3.1 to generate accurate and expert-level responses
- Interactive Chat: User-friendly web-app built in Streamlit enables efficient interaction

## Tech Stack
- Streamlit: For building the interactive web app
- Pinecone: Vector database for storing and querying embedded code snippets
- SentenceTransformers: For embedding code and text data
- OpenAI: API for generating responses using Large Language Models (LLMs)
- HuggingFace Embeddings: To compute vector representations of text and code snippets

