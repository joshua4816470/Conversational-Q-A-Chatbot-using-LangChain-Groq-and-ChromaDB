# Conversational Q&A Chatbot with LangChain, Groq, and ChromaDB 

A **conversational question-answering chatbot** built using **LangChain**, **Groq LLaMA 3.1**, **ChromaDB**, and **Hugging Face embeddings**.  
This project demonstrates how to implement **Retrieval-Augmented Generation (RAG)** to answer questions based on custom data rather than only relying on a language model’s internal knowledge.

---

##  Project Overview

This chatbot retrieves relevant information from a dataset and generates context-aware, accurate answers.  
It showcases how modern AI tools can be combined to build real-world, domain-specific AI assistants.

### Key Features
- **Web Scraping** – Load data from web pages using `WebBaseLoader` and `BeautifulSoup`.
- **Chunking** – Split large documents into smaller, meaningful pieces for efficient search.
- **Vector Embeddings** – Generate embeddings using **Hugging Face Transformers**.
- **Semantic Search** – Store and query embeddings using **ChromaDB**.
- **LLM Integration** – Use **Groq LLaMA 3.1 (8B Instant)** for fast and context-aware responses.
- **Retrieval-Augmented Generation** – Build a pipeline that fetches context and generates answers dynamically.

---

## 🛠 Tech Stack

| Component        | Technology Used            |
|------------------|----------------------------|
| **Language**     | Python 3.10+               |
| **Framework**    | LangChain                  |
| **LLM Provider** | Groq LLaMA 3.1 (8B Instant)|
| **Vector DB**    | ChromaDB                    |
| **Embeddings**   | Hugging Face Transformers  |
| **Data Loader**  | WebBaseLoader, BeautifulSoup|
| **Environment**  | Python `venv`, `.env` file |
| **Notebook**     | Jupyter Notebook           |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/conversationalqa.git
cd conversationalqa

