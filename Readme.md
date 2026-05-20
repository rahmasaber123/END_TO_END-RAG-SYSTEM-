# End to End Rag project 


An end-to-end Retrieval-Augmented Generation (RAG) system built using FastAPI, LangChain, MongoDB, and Python 3.10.

The system processes documents, generates embeddings, stores vector data, and retrieves relevant context for LLM-based responses.

---

## Tech Stack

- Python 3.10
- FastAPI
- LangChain
- MongoDB
- Vector Database
- LLM Integration

---

## Setup

### 1. Install Miniconda

Download Miniconda:

https://www.anaconda.com/docs/getting-started/miniconda/install

---

### 2. Create Conda Environment

```bash
conda create -n env python=3.10
```

---

### 3. Activate Environment

```bash
conda activate env
```

---

### 4. Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
uvicorn app:app --reload
```

API URL:

```text
http://127.0.0.1:8000
```

Swagger Docs:

```text
http://127.0.0.1:8000/docs
```

---

## Git Workflow

Create a new branch:

```bash
git checkout -b feature-name
```

Push branch:

```bash
git push -u origin feature-name
```

---

## Future Improvements

- Streaming responses
- Multi-agent workflows
- Hybrid search
- Docker deployment
- Authentication system