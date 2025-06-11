⚖️ ElSadok – Votre Assistant Légal Tunisien 🇹🇳
ElSadok is a conversational legal assistant tailored for Tunisian law. It leverages LLM (Large Language Models) and semantic search to provide accurate, context-aware answers based on official legal documents.

![RAGarchitectureFINAL drawio](https://github.com/user-attachments/assets/d6162ed8-7af2-44ef-849c-92dc7078289a)


🧠 Core Features
💬 Chat Interface – Powered by Streamlit for an intuitive, real-time Q&A experience.

📚 Custom Legal Corpus – Embeds and indexes Tunisian legal documents for accurate retrieval.

🔎 Semantic Search with FAISS – Retrieves relevant chunks from your custom document set.

🔁 FastAPI Backend – Handles the prompt-routing logic between the frontend and the LLM.

🔐 Environment Secured – API keys and configurations managed through .env.

🏗️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	FastAPI
Vector DB	FAISS
LLM	OpenAI / HuggingFace Models
Embeddings	Sentence Transformers / OpenAI
DevOps	Python, uvicorn, gunicorn

🚀 Getting Started
1. Clone the repo
bash
Copy
Edit
git clone https://github.com/your-username/elsadok-assistant.git
cd elsadok-assistant
2. Set up the environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
3. Add your .env file
bash
Copy
Edit
OPENAI_API_KEY=your_key_here
✅ Make sure .env is listed in .gitignore.

4. Start the backend
bash
Copy
Edit
uvicorn main:app --reload
5. Run the Streamlit UI
bash
Copy
Edit
streamlit run app.py
🧪 How it Works
User asks a legal question via Streamlit.

Prompt is sent to the FastAPI backend.

The question is embedded and matched against a FAISS index built from legal documents.

Relevant chunks are retrieved and injected into a prompt.

An LLM generates a response based on that context.

📌 TODO
 Add authentication

 Improve prompt templates

 Add feedback system for incorrect answers

 Deploy on HuggingFace/Render/Heroku

