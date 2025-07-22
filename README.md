# 📄 ChatWithPDF

ChatWithPDF is a simple Retrieval-Augmented Generation (RAG)-based chatbot that allows users to upload PDF documents and ask questions based on their content. It uses Hugging Face embeddings and a conversational interface powered by Streamlit.

---

## 🚀 Features

- 📄 Upload multiple PDF files
- 🔍 Extract and chunk text from PDFs
- 🧠 Generate embeddings using Hugging Face models
- 🤖 Ask questions and receive context-aware answers

---

## 🧾 How it Works

1. **User uploads PDF(s)**
2. **Text is extracted** 
3. **Text is split** into chunks (e.g., 500–1000 characters with overlap)
4. **Embeddings are generated** using a Hugging Face sentence transformer
5. **User asks a question**
6. **Relevant chunks are retrieved** based on cosine similarity
7. **Prompt is built** using retrieved chunks + user query
8. **LLM generates response**
9. **Answer is shown** in chat format



