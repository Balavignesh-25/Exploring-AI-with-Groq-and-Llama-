# Groq + LLaMA 3.1 Demo (Secure API Usage)

This repository demonstrates how to use the **Groq API with LLaMA 3.1** in a **secure and production-ready way**, following best practices for API key management.

The project is compatible with:
- ✅ Google Colab (using Colab Secrets)
- ✅ Local development (using environment variables)
- ✅ GitHub (no secrets committed)

---

## 🚀 Features

- Secure API key handling (no hardcoding)
- Works seamlessly in Google Colab and local environments
- Clean, modular Python code
- Uses `llama-3.1-8b-instant` via Groq API
- GitHub-safe and recruiter-friendly

---

## 🔐 API Key Setup (IMPORTANT)

### Google Colab (Recommended)

1. Open the notebook in Google Colab
2. Click **🔑 Secrets** (left sidebar)
3. Add a new secret:
   - **Name**: `GROQ_API_KEY`
   - **Value**: your Groq API key
4. Enable **Notebook access**
5. Restart the runtime
6. Run all cells

> ⚠️ The API key is never stored in the notebook or committed to GitHub.

---

### Local Development (Optional)

Set the API key as an environment variable.

**Linux / macOS**
```bash
export GROQ_API_KEY=your_api_key_here
```

Windows (PowerShell)
```
setx GROQ_API_KEY "your_api_key_here"
```
---

📝 Notes

This project can be extended to:

- Streamlit applications
- FastAPI backends
- RAG pipelines
- Multi-model comparisons

---
