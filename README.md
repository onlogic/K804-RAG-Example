# K804 RAG Example

This repository contains the code for a minimal example running a local LLM with RAG. RAG is a concept that allows LLMs to access relavent context to support question answering tasks. The `k800_local_rag.ipynb` file creates a simple RAG pipeline using LangChain, which uses Ollama to execute a Llama 3.1 model locally. More information on downloading the required packages is included in the notebook file. 

The AI chatbot uses context data from the `product_manuals` folder, which contain OnLogic product manual pdfs. The notebook shows the process for loading and splitting these pdfs, and then creating a simple chroma vector database to store embeddings for the model to access. 