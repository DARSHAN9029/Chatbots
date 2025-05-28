# 🧠 AI Chatbots with LangChain, Groq, and Vector Databases

This repository showcases **three intelligent chatbots** developed using the **LangChain framework**, **Groq LLMs**, **Ollama**, and **Hugging Face** embeddings. Each chatbot demonstrates different core functionalities in the conversational AI space.

---

## 🛠️ Technologies Used

- **[LangChain](https://www.langchain.com/)** – for building modular LLM applications
- **[Groq](https://groq.com/)** – as the Large Language Model (LLM) backend
- **[Ollama](https://ollama.com/)** – for local LLM support
- **[Hugging Face](https://huggingface.co/)** – for generating text embeddings
- **Vector Database** – for storing and retrieving context (e.g., ChromaDB or FAISS)
- **Python** – core language for development

---

## 🤖 Chatbots Included

### 1. 📚 Chatbot with Chat History

A memory-based chatbot that remembers previous conversations. Ideal for applications where session continuity is important.

**Features:**
- Stores and retrieves conversation history
- Personalizes responses based on past interactions

📂 File: `chatbot.ipynb`

---

### 2. 💬 Conversational Chatbot

A general-purpose chatbot with real-time conversational abilities, leveraging the LLM's understanding without external context.

**Features:**
- Contextual natural language conversation
- Stateless (each message is processed independently)

📂 File: `conversationalqna.ipynb`

---

### 3. 📖 Vector DB Chatbot with Retrievers

An advanced chatbot that uses a vector database to retrieve relevant documents or facts to augment the LLM's answers.

**Features:**
- Embeds documents using Hugging Face models
- Stores embeddings in a vector database
- Uses retrievers to provide contextually accurate responses

📂 File: `vs&r.ipynb`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone 
```
---

2. Install Requirements

```bash
pip install -r requirements.txt
```
