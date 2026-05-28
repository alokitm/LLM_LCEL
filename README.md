# 🔗 LLM Application using LCEL, LangServe & Groq

A simple educational project demonstrating how to build an LLM-powered application using:

* LangChain LCEL
* Groq API
* FastAPI
* LangServe
* Streamlit

This repository focuses on understanding:

* LCEL chaining
* API serving using LangServe
* Client-server architecture for LLM apps
* Prompt templates and output parsing
* Language translation workflow using LLMs

---

# 🚀 Features

* LCEL-based LangChain pipeline
* FastAPI backend using LangServe
* Streamlit frontend client
* Translation workflow using Groq LLM
* API endpoint integration
* Educational project structure

---

# 🛠️ Tech Stack

* Python
* LangChain
* LangServe
* FastAPI
* Streamlit
* Groq API

---

# 📚 Concepts Covered

* LCEL (LangChain Expression Language)
* Prompt Templates
* Output Parsers
* LangServe API routes
* FastAPI integration
* Streamlit frontend
* Client-server communication
* LLM API workflow

---

# 📁 Project Structure

```text id="x5q9wc"
LLM_LCEL/
│
├── client.py          # Streamlit frontend
├── serve.py           # FastAPI + LangServe backend
├── LLM_LCEL.ipynb     # Learning & experimentation notebook
├── requirements.txt
├── .env
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash id="u1p4tx"
git clone https://github.com/alokitm/LLM_LCEL.git
```

Move into project directory:

```bash id="r7m8qp"
cd LLM_LCEL
```

Install dependencies:

```bash id="f2m5vk"
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file:

```env id="k9q2wc"
GROQ_API_KEY=your_groq_api_key
```

---

# ▶️ Run FastAPI Server

```bash id="v4m8tx"
python serve.py
```

Backend runs on:

```text id="p6q1vk"
http://127.0.0.1:8000
```

---

# ▶️ Run Streamlit Client

Open another terminal and run:

```bash id="x3m7wc"
streamlit run client.py
```

Frontend runs on:

```text id="m1v4tx"
http://localhost:8501
```

---

# 🔄 Workflow

1. User enters text in Streamlit UI
2. Streamlit client sends request to FastAPI server
3. LangServe executes LCEL chain
4. Groq LLM processes translation request
5. Response is returned to frontend

---

# 📦 Requirements

```text id="u5k2qp"
langchain
langchain-core
langchain-groq
langserve
fastapi
uvicorn
streamlit
python-dotenv
requests
ipykernel
```

---

# 📌 Note

This repository was created mainly for educational and learning purposes to understand:

* LCEL workflows
* LangServe architecture
* LLM application structure
* API integration with LangChain

The project is intended for experimentation and hands-on practice with modern LLM frameworks.

---

# 👨‍💻 Author

**Alokit Mishra**
