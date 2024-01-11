# MultiPDF Answer Bot

## Overview
MultiPDF Answer Bot is an advanced tool designed for interactive information extraction from multiple PDF documents. Utilizing cutting-edge natural language processing and AI techniques, it provides a unique conversational interface for users to query and receive specific answers from a collection of PDFs.

## Key Technologies
- **Streamlit**: For creating a user-friendly web interface.
- **PyPDF2**: To extract text from PDF files.
- **LangChain**: Leveraging its capabilities for natural language processing and conversational AI.
- **Google Generative AI Embeddings**: Used for generating text embeddings that capture the semantic meaning of the text.
- **FAISS (Facebook AI Similarity Search)**: Employed for efficient indexing and similarity searches within large datasets.

## How It Works
1. **Upload and Process PDFs**: Users upload PDF files, from which text is extracted and processed.
2. **Text Chunking**: Extracted text is split into manageable chunks for better processing.
3. **Vector Embedding**: Chunks are converted into vector embeddings using Google Generative AI Embeddings.
4. **Building FAISS Index**: These embeddings are indexed using FAISS for fast retrieval.
5. **Handling User Queries**: The application takes user queries, finds the most relevant text chunks using FAISS, and then generates appropriate responses.


