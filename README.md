# Recipe RAG System

This project implements a Retrieval-Augmented Generation (RAG) system to answer questions about cooking recipes.

## Features
- Recipe dataset
- Embeddings with Hugging Face
- Vector database with ChromaDB
- Answer generation using a language model
- Simple interface with Gradio

## How it works
1. Load the dataset
2. Generate embeddings
3. Store them in ChromaDB
4. Retrieve relevant recipes
5. Generate structured answers

## How to run

Install dependencies:
!pip install transformers chromadb gradio pandas

## Example output

The system returns structured recipes including:
- Recipe name
- Ingredients
- Step-by-step instructions
