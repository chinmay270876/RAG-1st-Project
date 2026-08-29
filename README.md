# RAG Data Ingestion Pipeline

A lightweight document loader project built with **LangChain** and managed via **`uv`**. This pipeline ingests text and PDF files from local directories and parses them into structured `Document` objects ready for text splitting, embedding, and vector storage.

---

## 🛠️ Setup & Environment

This project uses [`uv`](https://github.com/astral-sh/uv) for fast, reliable package management.

### 1. Prerequisites
Ensure you have `uv` installed. If not, install it via PowerShell:
```powershell
powershell -ExecutionPolicy ByPass -c "irm [https://astral.sh/uv/install.ps1](https://astral.sh/uv/install.ps1) | iex"
