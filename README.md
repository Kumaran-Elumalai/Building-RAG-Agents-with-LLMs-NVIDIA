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

## 🏁 Key Skills & Takeaways

This project strengthened my expertise in:  

- Designing **retriever–generator pipelines** using LangChain runnables  
- **Prompt engineering** for factuality, conciseness, and semantic alignment  
- Working with **FAISS vector stores** and **NVIDIA embeddings**  
- Integrating **LLMs** (Meta Llama 3) into a robust RAG pipeline  
- Debugging **evaluation metrics** and API routing issues  
- Understanding **synthetic QA evaluation** and system performance metrics  

---
## ✨ Next Steps

I plan to extend this project into a **RAG Agent with memory**, **advanced evaluation dashboards**, and **dynamic prompt adaptation**, aiming for even more robust, enterprise-ready AI applications.

---
```
/Building-RAG-Agents-with-LLMs-NVIDIA
│
├─ 00_JupyterLab/
├─ 01_Microservices/
├─ 02_ILMs/
├─ 03_LangChain_Intro/
├─ 04_Running_State/
├─ 05_Documents/
├─ 06_Embeddings/
├─ 07_VectorStores/
├─ 08_Evaluation/
├─ 09_LangServe_Assessment/
├─ 64_Guardrails/
├─ 99_Table_of_Contents.md
├─ Chatbot/
├─ Composer/
├─ Frontend/
├─ ILM_Client/
├─ Docker_Router/
├─ Slides/
├─ Solutions/
├─ Imgs/
└─ README.md
```
---

## 🛠 Technologies Used

- **LangChain, LangServe, FastAPI**  
- **FAISS** for vector similarity search  
- **NVIDIA nv-embed-v1 embeddings**  
- **Meta Llama 3 (ChatNVIDIA API)**  
- **Python 3.11**

---

## 🔖 References

- NVIDIA “Building RAG Agents with LLMs” course  
- ArXiv papers used as retrieval data  

---

## 🔖 Keywords / Hashtags

#RetrievalAugmentedGeneration #LangChain #FAISS #NVIDIAAI #LLM #GenerativeAI #PromptEngineering #AIProjects #MachineLearning #AIEngineering
