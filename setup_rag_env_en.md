# Creating Python 3.10 virtual environment "rag_env"

---

## Option 1: With Anaconda/Miniconda

**Create the environment:**
```bash
conda create -n rag_env python=3.10
```

**Activate the environment:**
```bash
conda activate rag_env
```

**Install ipykernel and register in Jupyter:**
```bash
conda install ipykernel
python -m ipykernel install --user --name=rag_env --display-name "Python (rag_env)"
```

---

## Option 2: With virtualenv

**Create the environment** (make sure you have Python 3.10 installed):
```bash
python3.10 -m venv rag_env
```

**Activate the environment:**

*Linux/macOS:*
```bash
source rag_env/bin/activate
```

*Windows:*
```bash
rag_env\Scripts\activate
```

**Install ipykernel and register in Jupyter:**
```bash
pip install ipykernel
python -m ipykernel install --user --name=rag_env --display-name "Python (rag_env)"
```

---

## Verification

To verify that the kernel was installed correctly:
```bash
jupyter kernelspec list
```

Now when you open Jupyter Notebook, you will find "Python (rag_env)" among the available kernels.
