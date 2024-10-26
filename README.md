# End-to-End Document Q&A Chatbot Using Llama3, LangChain, and Groq

## Overview
This project demonstrates an end-to-end, high-performance document Q&A chatbot using **Llama3**, **LangChain**, and **Groq**. Designed to handle extensive and complex documents, this system allows users to query PDFs effectively, leveraging a powerful pipeline for natural language processing and inferencing.

## Key Features
- **Document Ingestion**: Reads and parses PDF files directly using **PyPDFLoader**, allowing seamless document handling for QA purposes.
- **Embeddings**: Uses **Ollama embeddings** to enhance context awareness, ensuring more accurate answers for user queries.
- **Frontend Interface**: A user-friendly interface built with **Streamlit** enables easy interaction, displaying questions, and real-time responses.
- **Inferencing with Groq**: The Groq inferencing engine boosts model performance, reducing latency for a smooth, responsive user experience.

## Tech Stack
- **Llama3**: Core language model powering the Q&A system.
- **LangChain**: Framework for managing prompt creation, memory, and response generation.
- **Groq**: High-performance inferencing engine enhancing processing efficiency.
- **Ollama Embeddings**: Generates embeddings to capture document context for improved answer relevance.
- **PyPDFLoader**: Facilitates PDF file loading, parsing, and text extraction.
- **Streamlit**: Provides an intuitive web interface for user interaction.

## Project Components
1. **Data Loader**: `PyPDFLoader` imports and processes PDFs, making the content accessible for Q&A.
2. **Embedding Creation**: Ollama embeddings are generated to index and capture context across documents.
3. **QA Pipeline**: LangChain manages the Q&A flow, from prompt construction to response generation.
4. **Inferencing with Groq**: Groq’s inferencing engine provides efficient model inferencing for low-latency responses.
5. **Frontend Application**: A Streamlit-powered web app allows users to ask questions and receive accurate answers instantly.

## Contributing
Contributions are welcome! Please create an issue or a pull request for proposed changes.

## Screenshot
![Screenshot (65)](https://github.com/user-attachments/assets/654945a5-f033-4816-97d5-4799dc96b7cf)
