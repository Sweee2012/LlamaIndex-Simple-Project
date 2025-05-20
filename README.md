# 💡 LlamaIndex-Simple-Project

A hands-on project built by following the official **LlamaIndex Starter Tutorial**, demonstrating how to create an AI agent that can both solve math problems and answer natural language questions from documents using **RAG (Retrieval-Augmented Generation)**. This project uses the **Gemini API** as the LLM backend. 🤖✨

---

## 🚀 Project 1: Basic Function-Agent (Using Gemini API)

This module is based on the Basic Agent Example from the LlamaIndex documentation. The goal was to build a simple AI assistant that calls a Python function to perform calculations. 🧮

### 🔧 What the Agent Can Do:
- Accepts natural language prompts like:  
  ➤ _"What is 1234 * 4567?"_  
- Internally maps the query to a `multiply(a, b)` Python function.  
- Returns the accurate result:  
  ➤ _"The answer to 1234 * 4567 is: 5,618,916."_ ✅

### 🛠️ Tech Stack:
- 📚 LlamaIndex – For agent and workflow setup  
- 🌌 Gemini API – As the LLM backend  
- 🐍 Python (asyncio) – For asynchronous execution  
- 🛠️ FunctionAgent – To route tool-based queries

---

## 📚 Project 2: AI Agent with RAG Capabilities

Building on top of the function-agent setup, I extended the assistant to handle document-based queries using **RAG (Retrieval-Augmented Generation)**. 📄🔍

### 🔧 What the Agent Can Do:
- Handles combined questions like:  
  ➤ _"What did the author do in college? Also, what's 7 * 8?"_  
- Dynamically routes queries to the appropriate tool:  
  - 🧠 **RAG Tool** – Searches and summarizes content from a local document  
  - ➗ **Math Tool** – Performs calculations  
- Delivers combined, accurate, and context-aware responses. 💡

### 🧠 Tech Additions:
- 📂 SimpleDirectoryReader – To load documents  
- 🗃️ VectorStoreIndex – For document embedding and retrieval  
- 🤗 Hugging Face Embeddings (BAAI/bge-base-en-v1.5) – Used for RAG indexing

---

## ✅ Key Learnings:
- 🧩 How to build agents using **LlamaIndex** and **Gemini API**  
- 🔧 How to integrate custom tools and route function calls  
- 📚 Implementing RAG workflows for document search and Q&A  
- 🚀 Running a complete local or cloud-assisted AI assistant

---

