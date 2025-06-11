# ⚖️ ElSadok – Votre Assistant Légal Tunisien 🇹🇳

ElSadok is a conversational legal assistant tailored for Tunisian law. It leverages LLMs and semantic search to provide accurate, context-aware answers based on official legal documents.

![Architecture Diagram](./architecture.png)  
*📌 Replace this with your actual architecture image file.*

---

## 🧠 Features

- 💬 **Interactive Chat Interface** – Built with Streamlit for smooth, real-time Q&A.
- 📚 **Custom Legal Corpus** – Uses Tunisian legal documents for context.
- 🔎 **Semantic Search (FAISS)** – Finds relevant document chunks using embeddings.
- ⚙️ **FastAPI Backend** – Handles queries, search, and communication with the LLM.
- 🔐 **Secure Environment** – `.env` used to manage sensitive keys.

---

## 🛠️ Tech Stack

| Layer       | Technology                     |
|-------------|--------------------------------|
| Frontend    | Streamlit                      |
| Backend     | FastAPI                        |
| Vector Store| FAISS                          |
| Embeddings  | Sentence Transformers / OpenAI |
| LLM         | OpenAI / HuggingFace           |
| DevOps      | Python, Uvicorn                |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/elsadok-assistant.git
cd elsadok-assistant


