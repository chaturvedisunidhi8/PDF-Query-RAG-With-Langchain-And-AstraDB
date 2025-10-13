📘 PDF-Query-RAG-With-LangChain-And-AstraDB

🚀 Project Overview
This project builds a Retrieval-Augmented Generation (RAG) system that allows users to query and chat with PDF documents intelligently. It combines the power of LangChain, AstraDB, and LLMs (like Groq or OpenAI) to deliver accurate, context-aware answers from PDF data.

🧩 Key Features

🔹 PDF Upload & Parsing – Effortlessly upload PDF files for automated text extraction and chunking.
🔹 Vector Store Integration – Uses AstraDB (powered by Cassandra) as a vector database to store embeddings for efficient document retrieval.
🔹 LangChain RAG Pipeline – Integrates Retrieval-Augmented Generation for factual and context-based responses.
🔹 Semantic Search – Retrieve the most relevant document chunks before generating responses.
🔹 Chat Interface – User-friendly interface to ask questions and get concise, context-aware answers.
🔹 Memory Integration – Keeps conversation history to maintain context over multiple queries.

🧠 Tech Stack

🦜 LangChain – For RAG pipeline and orchestration.
🧮 AstraDB – As a vector store for document embeddings.
🤖 LLMs (Groq / OpenAI / Llama3) – For generating responses.
📄 PyPDF / Unstructured Loader – For PDF text extraction.
🧰 Streamlit / Gradio – For building an interactive front-end.

⚙️ How It Works

1️⃣ Upload a PDF 📂
2️⃣ The system extracts and embeds text chunks 🔍
3️⃣ AstraDB stores these embeddings for fast retrieval 💾
4️⃣ User asks a question 💬
5️⃣ Relevant chunks are retrieved and passed to the LLM 🧠
6️⃣ A detailed, contextually accurate response is generated ✨

🌟 Use Cases

📑 Academic Research Summaries
📚 Book or Report Query Systems
💼 Business Document Analysis
⚖️ Legal / Policy Document Q&A
🧾 Financial or Technical Report Assistants
