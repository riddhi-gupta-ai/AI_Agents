# 🌐 AI Web Scraper Agent with FAISS and Ollama

An **AI-powered web scraper agent** that extracts content from websites, stores it using vector embeddings in a **FAISS** index, and allows users to **ask questions** based on the scraped content. Built using **Langchain**, **Ollama**, **HuggingFace Embeddings**, **FAISS**, and **Streamlit**.

---
## 🚀 Features

- 🌍 **Scrape any public website** and extract meaningful text
- 🧠 **Semantic search** powered by HuggingFace embeddings and FAISS
- 💬 **Ask context-aware questions** about the scraped content
- ⚡ **Real-time Q&A interface** with Mistral via Ollama
- 🖥️ Web interface built with Streamlit

---
## 🧠 How It Works

1. User enters a URL — the app scrapes and extracts content using `BeautifulSoup`.
2. Text is split into chunks and converted into embeddings using `sentence-transformers/all-MiniLM-L6-v2`.
3. Embeddings are stored in a **FAISS** vector database.
4. User asks a question — the app retrieves similar chunks using vector search.
5. Contextual chunks are passed to the **LLM via Ollama** to generate an intelligent answer.

---
## 🧰 Tech Stack

- [Langchain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Hugging Face Sentence Transformers](https://huggingface.co/sentence-transformers)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Streamlit](https://streamlit.io/)

---

## 📷 UI Snapshot

<img width="1227" alt="Screenshot 2025-07-01 at 2 18 41 AM" src="https://github.com/user-attachments/assets/d9d0bb78-724f-4546-acc9-cf2e1c2ac5ac" />

---
### Install dependencies

```bash
pip install streamlit langchain langchain-community langchain-ollama langchain-huggingface beautifulsoup4 faiss-cpu numpy requests


