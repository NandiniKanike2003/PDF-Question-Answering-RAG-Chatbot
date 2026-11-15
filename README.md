# PDF Question-Answering AI System (RAG Chatbot)

## About the Project
This project is a PDF-based question-answering chatbot that uses Retrieval-Augmented Generation (RAG) to answer questions using information from a PDF document.

Users can ask questions about the uploaded document and receive answers based on the relevant content retrieved from it.

## How It Works
1. Extracts text from PDF documents using PyMuPDF.
2. Splits the extracted text into smaller chunks.
3. Converts text chunks into embeddings using Sentence Transformers.
4. Retrieves relevant chunks using cosine similarity.
5. Uses Qwen 2.5 to generate answers from the retrieved context.
6. Displays answers through an interactive chatbot interface.

## Technologies Used
- Python
- Google Colab
- PyMuPDF
- Sentence Transformers
- Hugging Face Transformers
- Qwen 2.5
- ipywidgets

## Key Features
- PDF text extraction
- Semantic search and information retrieval
- Context-based question answering
- Interactive chatbot interface

## Project Workflow
PDF Document → Text Extraction → Text Chunking → Embeddings → Similarity Search → Qwen LLM → Answer

## How to Run
1. Open the project notebook in Google Colab.
2. Install the required libraries if they are not already available.
3. Upload a PDF document.
4. Run the notebook cells in order.
5. Ask questions about the document using the chatbot.

## Note
The chatbot generates answers based on the retrieved PDF content. Its responses may need verification, especially when information is missing or unclear.
