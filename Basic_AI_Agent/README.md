# 🧠 Basic AI Agent with Memory and Web UI

A minimal yet powerful AI chatbot built using **Langchain**, **Ollama**, and **Streamlit**. This agent supports persistent memory across conversations and a clean web interface for interaction.

## 🚀 Features

- 🤖 **AI-powered Conversations** with [Ollama](https://ollama.com/)
- 🧠 **Contextual Memory**: Maintains chat history using Langchain's `ChatMessageHistory`
- 🖥️ **Interactive Web UI** powered by Streamlit
- 🔄 **Dynamic Prompting**: Uses chat history to enhance AI responses
- 🛠️ Easily extensible for other agentic capabilities

## 📦 Tech Stack

- [Streamlit](https://streamlit.io/) – Frontend UI for interaction
- [Langchain](https://www.langchain.com/) – Memory management and prompt chaining
- [Ollama](https://ollama.com/) – Lightweight local LLMs like `mistral`, `llama3`, etc.

## 📋 How It Works

1. User types a question in the Streamlit web UI.
2. Chat history is retrieved and fed into a prompt template.
3. The model (via Ollama) generates a context-aware response.
4. Both the question and the answer are added to memory.
5. Chat history is displayed in a readable format.

## 💡 Example Use Case

Use this as a starter for:
- Smart personal assistants
- Customer support bots
- Teaching or tutoring agents
- Internal productivity tools

## 📷 UI Snapshot
![image](https://github.com/user-attachments/assets/41676941-cb9e-49c7-8dc1-9398e9e10360)

With Memory Releated Query : 
![image](https://github.com/user-attachments/assets/5502bcfd-bb19-490e-ac90-1a7bb4a229a0)


## 🛠️ Run the Agent

```bash
# Install dependencies
pip install streamlit langchain langchain-community langchain-core langchain-ollama

# Make sure Ollama is installed and running:
# https://ollama.com/download

# Run the Streamlit app
streamlit run app.py
