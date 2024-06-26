# PDF-Chat-Gemini
# PDF Chatbot with Google Generative AI

This project is a Streamlit-based application that allows users to interact with PDF documents by asking questions. The application uses Google Generative AI for embedding and answering questions, and FAISS for vector storage.

## Features

- Upload multiple PDF files
- Extract and process text from PDF files
- Split text into manageable chunks for efficient processing
- Generate and save FAISS vector store from text chunks
- Use Google Generative AI to answer questions based on the PDF content
- Simple and intuitive Streamlit interface

## Requirements

- Python 3.7+
- Streamlit
- PyPDF2
- langchain
- langchain-google-genai
- langchain-community
- google-generativeai
- python-dotenv
