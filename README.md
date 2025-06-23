
---

## 📦 2. `wellsrag-advisor`  
**Name:** `wellsrag-advisor`  
**Purpose:** Retrieval-augmented GenAI that answers regulatory/TCOO questions.

```markdown
# WellsRAG-Advisor 📑💡

> A RAG-powered QA microservice over regulatory & process documentation.

## 🚀 Features
- **Embeddings store:** FAISS-backed vector search of PDF/docs.  
- **LLM in-context QA:** Llama-3 or OpenAI LLM via LangChain.  
- **Web UI:** React frontend (or Streamlit) for interactive queries.  
- **Auth layer:** Simple API key guard for corporate usage.

## 🛠️ Tech Stack
- **Backend:** Python 3.11 + FastAPI  
- **Embeddings:** Sentence-Transformers + FAISS  
- **LLM:** Hugging Face Llama-3 local (or Azure OpenAI)  
- **Frontend:** React with MUI (or Streamlit)  
- **CI/CD:** GitHub Actions + Codecov badge

## 🚀 Quick Start

```bash
# 1. Clone & install
git clone https://github.com/Br111t/wellsrag-advisor.git && cd wellsrag-advisor
pip install -r requirements.txt

# 2. Start service
uvicorn app.main:app --reload

# 3. Open UI
open http://localhost:3000      # React dev server
