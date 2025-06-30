# 📄 AI Document Reader & Q&A Agent

An AI-powered PDF reader that **automatically summarizes documents** and answers questions based on their content. Built using **Langchain**, **Ollama**, **FAISS**, **HuggingFace Embeddings**, and **Streamlit**.

## 🚀 Features

- 📂 Upload PDF documents for analysis
- 🧠 AI-generated **summary** of the uploaded content
- 💬 Ask **natural language questions** about the document
- 🧾 Content stored in-memory using **FAISS** for fast retrieval
- 🎯 Embeddings powered by HuggingFace’s `all-MiniLM-L6-v2`
- 🔄 Downloadable summary via Streamlit's download button

## 🧠 How It Works

1. Upload a `.pdf` file via the Streamlit UI.
2. Text is extracted using `PyPDF2`.
3. Text is split, embedded, and indexed with **FAISS**.
4. A summary is generated using the **Mistral model** (or other Ollama LLMs).
5. Ask any question about the document and get contextual AI answers.

## 🧰 Tech Stack

- [Langchain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Hugging Face Sentence Transformers](https://huggingface.co/sentence-transformers)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [Streamlit](https://streamlit.io/)

### Install dependencies

```bash
pip install streamlit langchain langchain-community langchain-ollama langchain-huggingface faiss-cpu numpy PyPDF2
