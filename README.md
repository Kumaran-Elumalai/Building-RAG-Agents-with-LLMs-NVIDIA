# 🚀 Building RAG Agents with LLMs – NVIDIA

This repository showcases my **hands-on implementation of Retrieval-Augmented Generation (RAG) agents** as part of **NVIDIA’s “Building RAG Agents with LLMs” course**.  

It demonstrates my ability to design, implement, debug, and evaluate an **end-to-end RAG pipeline** using state-of-the-art AI tools and frameworks, combining retrieval, generation, and evaluation.

---

## 💡 Project Overview

RAG systems are the backbone of modern AI-powered chatbots and assistants. They combine:

- **Retrieval** – Fetching the most relevant real-world data  
- **Generation** – Producing natural, contextually accurate responses  

Designing a RAG system that balances **retrieval accuracy** and **generation quality** is challenging. This project is a **real-world application of AI engineering principles**, emphasizing **prompt engineering, vector search, and end-to-end pipeline orchestration**.

**Achievement:**  
- Successfully **built and deployed a full RAG system**  
- **Passed the final synthetic QA evaluation successfully ✅**, demonstrating strong semantic alignment and end-to-end pipeline performance  

---

## 🧩 Implementation Details

**Frameworks & APIs:** LangChain + LangServe + FastAPI  
**Vector Store:** FAISS for high-performance similarity search  
**Embeddings:** NVIDIA nv-embed-v1 for high-quality semantic representations  
**LLM:** Meta Llama 3 (via ChatNVIDIA API)  
**Data Source:** ArXiv papers on RAG  
**Deployment:** Custom API endpoints (`/retriever`, `/generator`, `/basic_chat`)  

**Core Components Built:**  
1️⃣ **Retriever Chain** – Fetches top-k relevant documents using FAISS  
2️⃣ **Generator Chain** – Produces factual, concise answers  
3️⃣ **RAG Chain** – Integrates both to ensure contextually accurate and semantically aligned responses  

---
## ⚙️ Evaluation & Debugging Journey

During development, I encountered several challenges:

- **Evaluation Errors:** Gradio stream failures and client errors  
- **Low QA Scores:** Initial outputs lacked semantic accuracy  

Through **iterative debugging, prompt refinement, and chain optimization**, the **final evaluation successfully passed ✅**, highlighting the importance of **retrieval quality, prompt design, and chain orchestration** in RAG systems.

---
