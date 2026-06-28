# 📄 Company Document RAG Chatbot

## Overview

The Company Document RAG Chatbot is an AI-powered Retrieval-Augmented Generation (RAG) application that enables users to ask questions about company documents and receive accurate, context-aware answers.

The chatbot processes multiple document formats, generates vector embeddings, stores them in a ChromaDB vector database, retrieves the most relevant information, and uses an OpenAI Large Language Model (LLM) to generate responses based only on the uploaded documents.

---

## Features

- 📄 Upload PDF documents
- 📧 Upload Email (.eml) files
- 📜 Upload Log (.txt) files
- ✂️ Automatic document chunking
- 🔍 Semantic search using vector embeddings
- 🗂️ ChromaDB vector database
- 🤖 AI-powered question answering
- 💬 Context-aware responses based on uploaded company documents

---

## Technologies Used

- Python
- Google Colab
- LangChain
- OpenAI GPT
- ChromaDB
- PyPDF
- Unstructured
- Text Splitters
- Vector Embeddings

---

## Project Workflow

1. Upload company documents (PDFs, emails, and log files).
2. Extract text from each document.
3. Split documents into smaller chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in ChromaDB.
6. Retrieve the most relevant chunks based on the user's query.
7. Generate an accurate response using the OpenAI LLM.

---

## Project Structure

```
Company-Document-RAG-Chatbot/
│
├── Company_Document_RAG.ipynb
├── requirements.txt
├── README.md
├── .gitignore
│
└── documents/
    ├── sample.pdf
    ├── sample_email.eml
    ├── sample_log.txt
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Company-Document-RAG-Chatbot.git
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Add your OpenAI API Key and run the notebook in Google Colab.

---

## Sample Documents

The repository includes sample company documents for testing purposes.

Supported formats include:

- PDF (.pdf)
- Email (.eml)
- Log files (.txt)

---

## Future Improvements

- Support DOCX and Excel files
- Web interface using Streamlit or Gradio
- Multi-user authentication
- Conversation memory
- OCR support for scanned PDFs
- Source citations in responses

---

## Author

**Ume  e Hani**

BS Data Science

---

## License

This project is created for educational and learning purposes.
