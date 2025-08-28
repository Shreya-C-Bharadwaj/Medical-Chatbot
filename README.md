# 🩺 Medical-Chatbot
**Medical Chatbot** is an intelligent AI-powered assistant designed to answer medical queries with accurate responses. The chatbot can understand natural language questions, retrieve relevant medical information from a knowledge base, and provide detailed answers in real-time.

---

## 🚀 Project Highlights

-  **LangChain** – Manages conversation flow and context  
-  **Pinecone** – Performs semantic search over your medical documents  
-  **Sentence Transformers (`all-MiniLM-L6-v2`)** – Generates embeddings for semantic similarity  
-  **LLaMA-3.1-8b Instant** – Produces fast and coherent AI responses  

---

## ⚡ Features

-  Natural conversational AI for medical topics  
-  Context-aware and relevant responses  
-  Simple Flask-based web interface  
-  Scalable vector-based knowledge retrieval  

---

## 🛠️ Tech Stack

- Python 3.10+  
- LangChain  
- Pinecone  
- Sentence Transformers (`all-MiniLM-L6-v2`)  
- LLaMA-3.1-8b Instant  
- Flask


---

## ⚡ How to Run

1. **Install dependencies**

```bash
pip install -r requirements.txt
```
2. **Store documents in Pinecone index**
 ```bash
 python store_index.py
```
3.**Run the Flask App**
```bash
python app.py
```
