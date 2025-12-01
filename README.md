<p align="center">
  <img src="logo orizz.png" alt="AI Wonder Logo" width="420">
</p>

# AI Wonder — CHPC Cape Town 2024  
## Retrieval-Augmented Generation (RAG) Workshop Modules

This repository contains the training material used during the **AI Wonder RAG Workshop** at the **CHPC Conference in Cape Town**.

The course is structured into **three self-contained modules**, each focusing on a different aspect of Retrieval-Augmented Generation.  
All notebooks are written in Python and designed to run locally.

---

## 📘 Course Modules

### **1.0 — RAG with Ollama**
This module introduces the fundamentals of building a *local* Retrieval-Augmented Generation pipeline using:

- **Ollama** for local LLM inference  
- **ChromaDB** for vector storage  
- **LangChain** for orchestration  

You will learn how to load documents, embed them, query them, and build your first local RAG system.

---

### **1.1 — RAG Chunking Strategies**
This module explores how **text chunking** affects:

- the critical role of chunking strategies 
- retrieval quality    

Different chunking methods (fixed-size, recursive, semantic) are compared through interactive experiments.

---

### **1.2 — RAG Word Distance**
This module dives into **word embeddings and vector arithmetic** using fastText.  
You will experiment with:

- cosine similarity  
- analogy solving (e.g., *king – man + woman = queen*)  
- PCA visualizations in 3D  
- the role of embedding geometry in RAG systems  

---

## 🧪 Python Environment Setup

To ensure all notebooks run correctly and use the proper dependencies, please follow the instructions in:

👉 **setup_rag_env_en.md**

---

## 🚀 Getting Started

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. **Create and activate the Python environment**  
   Refer to `setup_rag_env_en.md`.

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Select the kernel:
   ```
   Python (rag_env)
   ```

5. Open any module notebook and start experimenting.

---

## 📎 Requirements

- Python **3.10**
- Jupyter Notebook / JupyterLab
- Internet connection (first-time download of models)
- ~3 GB RAM (for fastText model in module 1.2)

---

## 📄 License

The code is free to use. Please mention AI wonder or link this repo when used.

---

## 🤝 Acknowledgements

This material was developed for the **CHPC National Conference, Cape Town**, as part of the *AI Wonder* educational initiative.

Special thanks to all participants and collaborators.
