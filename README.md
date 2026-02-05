# langchain-ollama-local-llm

Local LLM experimentation with LangChain and Ollama, featuring prompt templates, chains, sequences, and parallel runnables.

This project demonstrates how to use **Ollama** with **LangChain** inside a Jupyter Notebook to build local LLM workflows — ranging from simple prompts to advanced chains, pipelines, and parallel execution.

Everything runs **locally** (no cloud APIs required).

---

## ✨ Features

- Direct Ollama usage (Python SDK)
- LangChain + Ollama integration
- Prompt templates with variables
- Temperature / creativity control
- Output parsing (`StrOutputParser`)
- Prompt → LLM pipelines using pipe (`|`)
- Chain composition (multi-step workflows)
- RunnableSequence (explicit pipelines)
- RunnableParallel (parallel translations)
- Translation examples (English, Hindi, French)
- Movie recommendation + summary generation

---

## 🧱 Requirements + Setup (Single Block)

### System

- Python 3.9+
- Ollama installed locally

Download Ollama:

https://ollama.com

---

### Install Model + Start Ollama

bash:

ollama pull ministral-3
ollama serve

### Python Environment + Dependencies

python -m venv venv

source venv/bin/activate  (macOS/linux)

venv\Scripts\activate (linux)

pip install jupyter langchain langchain-core langchain-ollama ollama

### Run Jupyter Notebook:
jupyter notebook
