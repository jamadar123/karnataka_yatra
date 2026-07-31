# 🏞️ Karnataka Yatri — AI Tourism Assistant

**Karnataka Yatri** is a lightweight, local, RAG-inspired (Retrieval-Augmented Generation) Flask web application that serves as an interactive travel chatbot for Karnataka state, India. It leverages **Ollama** running **Llama 3.2** locally to provide fast, reliable, and context-aware responses regarding regions, local cuisine, transportation, stay options, network coverage, and payment modes.

---

## ✨ Features

* **Local AI Processing:** Runs completely offline/locally via Ollama with `llama3.2:latest`.
* **Structured Knowledge Base:** Embedded dictionary containing rich metadata for major regions like Bengaluru, Mysuru, Hampi, Coorg, Gokarna, Badami, and more.
* **Smart Context Filtering:** Dynamically selects only relevant regional and categorical data based on the user's prompt to keep responses accurate and concise.
* **Interactive UI:** Clean, modern, responsive frontend built with Bootstrap 5, FontAwesome, and dynamic region pills.
* **Conversation History:** Maintains recent chat context for seamless multi-turn conversations.

---

## 🏗️ Project Structure

```text
karnataka-yatri/
│
├── app.py              # Main Flask application logic & embedded Knowledge Base
├── templates/
│   └── index.html      # Modern chat interface (HTML/CSS/JS)
└── README.md           # Project documentation
