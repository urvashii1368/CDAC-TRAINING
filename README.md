# 🩺 AI Medico Bot

An AI-powered Medical Document Question Answering system built using **Retrieval-Augmented Generation (RAG)**. The application allows users to upload medical PDF reports and ask questions about their contents using Large Language Models (LLMs).

## 🚀 Features

- 📄 Upload medical PDF documents
- 🔍 Extract and split PDF text into chunks
- 🧠 Generate embeddings for semantic search
- 📚 Store embeddings in a vector database (FAISS/Chroma)
- 🤖 Answer user queries using Gemini or Ollama LLMs
- 💻 Interactive Streamlit web interface

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini API
- Ollama
- FAISS
- ChromaDB
- Sentence Transformers

## 📂 Project Structure

```
AI_Medico_Bot/
│
├── app.py
├── requirements.txt
├── .gitignore
├── data/
├── utils/
│   ├── loader.py
│   ├── splitter.py
│   ├── embeddings.py
│   ├── vectorstore.py
│   ├── rag_chain.py
│   ├── llm.py
│   └── prompts.py
│
├── test_loader.py
├── test_splitter.py
├── test_embedding.py
├── test_faiss.py
├── test_chroma.py
├── test_gemini.py
├── test_ollama.py
└── test_rag.py
```

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/urvashii1368/CDAC-TRAINING.git
```

Move into the project

```bash
cd AI_Medico_Bot
```

Create a virtual environment

```bash
python -m venv medico_env
```

Activate the environment

Windows

```bash
medico_env\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root.

Example:

```env
GOOGLE_API_KEY=your_google_api_key
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

## 📌 Future Enhancements

- Chat history
- Multi-document support
- Medical report summarization
- Authentication
- Cloud deployment

## 👩‍💻 Author

**Urvashi**

CDAC Training Project
