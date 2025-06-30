# 🧠 Conversational RAG with PDF Uploads and Chat History

This is a Streamlit application that allows users to upload PDF files, ask questions about their content, and receive concise answers using **Conversational Retrieval-Augmented Generation (RAG)**. It supports chat history for contextual understanding and uses a combination of HuggingFace embeddings and Groq's Gemma-2 9B language model.

---
## Demo
[▶️ Watch demo video](./assets/demo1.mp4)
---
## 🚀 Features

- 📄 Upload and process multiple PDF files
- 💬 Chat with the PDF content using a conversational interface
- 📚 Maintains chat history for context-aware answers
- 🔎 Uses HuggingFace sentence embeddings and Chroma vector store for retrieval
- 🧠 RAG pipeline using LangChain and Groq LLM
- 🔐 API key entry for secure Groq usage

---

## 🛠️ Setup Instructions

### 1. Clone the repository

<pre><code>git clone https://github.com/Areen-09/pdf_Q-A_chatbot.git
cd pdf_Q-A_chatbot
</code></pre>

### 2. Install dependencies

Create a virtual environment (optional but recommended), then run:

<pre><code>pip install -r requirements.txt
</code></pre>

### 3. Set environment variables

Create a `.env` file in the root directory and add your HuggingFace API token:

<pre><code>HF_TOKEN=your_huggingface_api_token
</code></pre>

> ⚠️ **Never share your `.env` file. It's automatically excluded via `.gitignore`.**

---

## 💡 How to Use

### Run the app

<pre><code>streamlit run app.py
</code></pre>

### In the browser interface:

- Enter your **Groq API key**
- Upload one or more PDF files
- Provide a **Session ID** (to manage chat history)
- Ask questions related to the PDF content
- View answers and the evolving chat history

---

## 🧩 Tech Stack

- **Streamlit** – frontend UI
- **LangChain** – chaining and retrieval logic
- **Groq (Gemma-2 9B)** – LLM for answering
- **HuggingFace Transformers** – sentence embeddings
- **Chroma** – vector storage and retrieval
- **PyPDFLoader** – PDF document loader

---

## 📄 License

MIT License. Feel free to use and modify this project for personal or commercial use. Just don't forget to give credit! 🙌

---
