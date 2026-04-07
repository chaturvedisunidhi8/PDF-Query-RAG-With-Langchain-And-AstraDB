 PDF-Query-RAG-With-LangChain-And-AstraDB

 Project Overview
This project builds a Retrieval-Augmented Generation (RAG) system that allows users to query and chat with PDF documents intelligently. It combines the power of LangChain, AstraDB, and LLMs (like Groq or OpenAI) to deliver accurate, context-aware answers from PDF data.

 Key Features

🔹 PDF Upload & Parsing – Effortlessly upload PDF files for automated text extraction and chunking. <br>
🔹 Vector Store Integration – Uses AstraDB (powered by Cassandra) as a vector database to store embeddings for efficient document     retrieval.<br>
🔹 LangChain RAG Pipeline – Integrates Retrieval-Augmented Generation for factual and context-based responses. <br>
🔹 Semantic Search – Retrieve the most relevant document chunks before generating responses. <br>
🔹 Chat Interface – User-friendly interface to ask questions and get concise, context-aware answers. <br>
🔹 Memory Integration – Keeps conversation history to maintain context over multiple queries.<br>
 
 Tech Stack

 LangChain – For RAG pipeline and orchestration. 
 AstraDB – As a vector store for document embeddings.
 LLMs (Groq / OpenAI / Llama3) – For generating responses.
 PyPDF / Unstructured Loader – For PDF text extraction.
 Streamlit / Gradio – For building an interactive front-end.

 How It Works

1️ Upload a PDF
2️ The system extracts and embeds text chunks 
3️ AstraDB stores these embeddings for fast retrieval 
4️ User asks a question 
5️ Relevant chunks are retrieved and passed to the LLM 
6️ A detailed, contextually accurate response is generated 

 Use Cases

 Academic Research Summaries
 Book or Report Query Systems
 Business Document Analysis
 Legal / Policy Document Q&A
 Financial or Technical Report Assistants
