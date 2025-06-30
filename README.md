# 🤖 AI Agents: A Modular Collection of Intelligent Agents with Langchain + Ollama

Welcome to the **AI Agents** repo — a collection of modular, production-ready AI-powered agents built with **Langchain**, **Ollama**, and **Streamlit**. Each agent serves a unique use case, from voice-controlled assistants to document readers, enabling you to build end-to-end intelligent applications.

---

## 🧠 What's Inside?

| Agent | Description | Problem Solved |
|-------|-------------|----------------|
| 🔹 [Basic AI Agent with Memory](./basic-agent-memory-ui) | A simple chatbot with memory and Web UI | Maintains conversation context for smarter interactions |
| 🔹 [AI Voice Assistant Agent](./voice-assistant-agent) | Talk to your AI — supports voice input/output | Hands-free AI conversations with persistent memory |
| 🔹 [AI Web Scraper Agent](./web-scraper-agent) | Scrape any website and ask questions on its content | Automates knowledge extraction and contextual Q&A |
| 🔹 [AI Document Reader Agent](./document-reader-agent) | Upload PDFs, get summaries and ask questions | Extracts value from unstructured documents instantly |

---

## 💡 Use Cases

- ✅ AI customer service or virtual assistant
- ✅ Internal productivity tools (knowledge assistants)
- ✅ Research Q&A bots (web/doc)

---

## 🧰 Tech Stack (Shared)

- **Langchain** – Memory, prompts, chaining
- **Ollama** – Lightweight local LLMs (`mistral`, `llama3`, etc.)
- **Streamlit** – Easy-to-build web interface
- **FAISS** – Semantic vector search for documents and web content
- **HuggingFace Transformers** – Embedding generation for similarity search
- **PyPDF2** – PDF parsing for document analysis
- **SpeechRecognition & pyttsx3** – Voice input and output (voice agent)

---

