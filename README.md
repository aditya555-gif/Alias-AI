# <p align="center">Alias AI</p>

<p align="center">
Uncensored offline desktop AI assistant built with Python, Flet and Ollama.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flet](https://img.shields.io/badge/Flet-Desktop_App-0099FF?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-black?style=for-the-badge)
![Offline](https://img.shields.io/badge/Works-Offline-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</p>

---

## About

Alias AI is an offline desktop AI assistant built using **Python**, **Flet**, and **Ollama**.

The application runs a locally hosted **Dolphin Phi 2.7B** language model, allowing conversations to stay on the user's machine without relying on cloud AI services.

The primary goal of this project was to learn how desktop applications can integrate local Large Language Models while maintaining complete user privacy.

---

## Features

- 🖥️ Desktop application built with Flet
- 🧠 Powered by Dolphin Phi 2.7B through Ollama
- 🔌 Completely offline after model installation
- 🔒 Conversations stay on your local machine
- 💬 Highly unrestricted responses (behavior depends on the selected local model)
- 🗑️ No chat history is stored
- 🖱️ Clicking the **Alias logo** in the top-left corner immediately clears the current conversation from the interface
- ⚡ Lightweight and simple interface

---

## Tech Stack

- Python
- Flet
- Ollama
- Dolphin Phi 2.7B

---

## Installation

### Clone the repository

```bash
git clone https://github.com/aditya555-gif/Alias-AI.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Install Ollama

Download and install Ollama.

### Pull the model

```bash
ollama pull dolphin-phi:2.7b
```

### Run

```bash
python main.py
```

---

## 📷 Screenshots

![Model Response](images/Model_Response.png)
---

## Current Limitations

- No response streaming
- RAG was planned but never implemented
- Supports one local model at a time

---

## Notes

- Chat history is intentionally **not saved**.
- Clearing the chat removes the conversation from the application interface.
- Model responses are generated entirely by the locally running LLM.

---

## Future Improvements

- PDF RAG
- Response streaming
- Multiple model support
- Better chat management
- Standalone executable

---

## 📄 License

This project is shared for educational and portfolio purposes.
feel free to use, modify, and distribute.
