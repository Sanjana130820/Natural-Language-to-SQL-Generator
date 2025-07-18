
# 🧠 Natural Language to SQL Generation System

This project is a proof-of-concept implementation of an intelligent system that converts natural language questions into SQL queries using an LLM-powered backend.

## 🔍 Overview

The notebook demonstrates:
- How to use OpenAI's GPT models to interpret complex English questions
- How to generate SQL queries dynamically using prompt engineering and semantic embeddings
- How to use a SQLite database as the backend for executing those queries
- Real-time user query examples in a notebook interface

## 🧰 Tech Stack

- Python
- OpenAI GPT (via API)
- FAISS (vector search)
- SQLite (sample database)
- Streamlit (optional UI)
- Jupyter Notebook

## 🛡️ Security Note

For safety, the notebook uses `os.getenv("OPENAI_API_KEY")` instead of hardcoding any API key.
Make sure to define your key as an environment variable before running.

## 🚀 How to Run

1. Clone the repo
2. Create a virtual environment (optional)
3. Install dependencies
4. Export your API key:

```bash
export OPENAI_API_KEY="your-key-here"  # Linux/Mac
set OPENAI_API_KEY="your-key-here"     # Windows CMD
```

5. Open the notebook:

```bash
jupyter notebook main.ipynb
```

## 📌 License

This project is for educational and research use only.
