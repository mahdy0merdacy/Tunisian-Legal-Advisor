# ⚖️ ElSadok – Votre Assistant Légal Tunisien 🇹🇳

ElSadok is a conversational legal assistant tailored for Tunisian law. It leverages LLMs and semantic search to provide accurate, context-aware answers based on official legal documents.

![RAGarchitectureFINAL drawio](https://github.com/user-attachments/assets/a1c13448-5a1b-4f81-a11d-6914fd7bda6a)


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

```bash
python -m venv venv
source venv/bin/activate 

```bash
pip install -r requirements.txt

```bash
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxx

```bash
uvicorn main:app --reload

```bash
streamlit run app.py


