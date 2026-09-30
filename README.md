# 🎓 AI SCHOLARSHIP FINDER AGENT

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nandhinii02/AI_SCHOLARSHIP_FINDER_AGENT/blob/main/AI_SCHOLARSHIP_FINDER_AGENT%20(2).ipynb)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![LangChain](https://img.shields.io/badge/LangChain-0.3-emerald)
![Groq](https://img.shields.io/badge/Groq-LLaMA--3.3--70B-orange)
![Gradio](https://img.shields.io/badge/Gradio-Live_UI-red)

> **Autonomous AI Agent for Scholarship Discovery, GPA Eligibility Verification, and Financial Aid Budget Planning.**

---

## 🚀 Quick Run in Google Colab (1-Click Direct Launch)

Click the badge below to open and run this notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nandhinii02/AI_SCHOLARSHIP_FINDER_AGENT/blob/main/AI_SCHOLARSHIP_FINDER_AGENT%20(2).ipynb)

**Direct URL:**  
https://colab.research.google.com/github/Nandhinii02/AI_SCHOLARSHIP_FINDER_AGENT/blob/main/AI_SCHOLARSHIP_FINDER_AGENT%20(2).ipynb

### How to Run Once Opened in Colab:
1. Open the link above.
2. Run **`⚡ OPTION 1: ALL-IN-ONE MASTER CELL (Run Directly)`** (or select **Runtime → Run all**).
3. Wait ~45 seconds for packages, vector store indexing, and Groq initialization.
4. Click the generated **`https://xxxxxxxx.gradio.live`** public link to interact with the full web app!

---

## 🌟 Key Architecture & Capabilities

1. **PDF Knowledge Base (RAG):**
   - Ingests `scholarships_database.pdf` with verified criteria ($5,000–$50,000 grants, STEM, Women in Tech, Need-based).
   - Text split using `RecursiveCharacterTextSplitter` (700 chars, 120 overlap).

2. **Semantic Vector Store (FAISS):**
   - High-speed semantic search using HuggingFace embeddings (`all-MiniLM-L6-v2`) and **FAISS** in-memory vector store (100% stable in Google Colab with zero SQLite errors).

3. **High-Speed Inference (Groq Cloud):**
   - Powered by **LLaMA-3.3-70B-Versatile** running at 500+ tokens/second.
   - Built-in automatic model fallback handling.

4. **Specialized Agent Tools:**
   - 🔍 **RAG Knowledgebase Tool:** Queries the PDF for verified criteria and requirements.
   - 💰 **Student Budget Calculator Tool:** Calculates annual out-of-pocket costs, monthly student burden, and financial aid coverage percentage.
   - 🌐 **Live Web Search Tool (Tavily):** Searches the live web for the latest 2026/2027 grants and deadlines.

5. **Gradio Web Interface:**
   - 💬 **Scholarship Chat:** Ask questions in plain English.
   - ⚡ **Fast Profile Matcher:** Filter by major, GPA, and degree level.
   - 📊 **Budget Estimator:** Calculate net tuition, living costs, and out-of-pocket expenses.
   - 🔗 Public URL sharing enabled (`share=True`).

---

## 👤 Author & Repository
- **Author:** Nandhinii02
- **Repository:** [https://github.com/Nandhinii02/AI_SCHOLARSHIP_FINDER_AGENT](https://github.com/Nandhinii02/AI_SCHOLARSHIP_FINDER_AGENT)
- **Agent Name:** AI SCHOLARSHIP FINDER AGENT
