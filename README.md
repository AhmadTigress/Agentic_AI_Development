# Agentic AI Development

This repository contains experimental and functional code to build agent-based AI systems using Google Colab as the development environment. It leverages tools like LangChain, Hugging Face, and Google Drive integration for collaborative and scalable AI workflow design.

---

## 🚀 Overview

Agentic AI systems are modular and context-aware, capable of reasoning and taking actions based on internal and external feedback loops. This project aims to demonstrate:

- Agent-based state graphs and task flow
- Use of LLMs for decision-making
- Colab integration with file system and model checkpoints
- Prompt engineering and feedback loops

---

##  Structure








---

## ⚠️ **Important Warning**

> **This Python code is only applicable to the Google Colab environment.**  
> ⚠️ **Caution:** Avoid using `!pip install ...` or file paths like `/content/drive/...` outside of Colab.  
> These commands and paths are tightly coupled with the Colab system and will not work in standard Python editors or local environments.

---

##  Dependencies

The main packages required include:

```txt
langchain==0.1.0
chromadb==0.4.24
transformers==4.39.3
sentence-transformers==2.2.2
google-colab
```

Install them (inside Colab only):
```python
!pip install -q -r requirements.txt
```

## Usage
- Open the notebook in Google Colab.

- Mount your Google Drive

```python
from google.colab import drive
drive.mount('/content/drive')
```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.
