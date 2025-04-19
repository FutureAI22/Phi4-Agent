# 📊 Phi4-Agent: AI-Powered Data Analysis Learning Assistant

Welcome to the **Phi4-Agent** — an AI-powered, Retrieval-Augmented Generation (RAG) agent designed to support **data analysis learners** by combining the reasoning ability of large language models with trusted educational resources like YouTube.

![Banner](https://img.shields.io/badge/AI-Phi4-blue.svg) ![License](https://img.shields.io/github/license/FutureAI22/Phi4-Agent)

---

## 🎯 Project Purpose
This agent helps students and aspiring data analysts:

- Ask natural language questions about topics in **data analysis**
- Retrieve trusted video tutorials from **curated YouTube channels**
- Reference relevant context from a **MongoDB Atlas vector store**
- Generate helpful answers powered by **Microsoft Phi-4** on Hugging Face

The project is part of a real-world educational AI application designed and maintained by Dr. Alaaeldin Mostafa.

---

## 🧠 Key Technologies
| Component        | Tool/Service             |
|------------------|--------------------------|
| LLM              | `microsoft/phi-4` via Hugging Face 🤖 |
| Embeddings       | `sentence-transformers`  |
| Vector Store     | MongoDB Atlas with `$vectorSearch` |
| Tool Framework   | Google ADK-style with `agentkit` |
| Frontend         | Gradio                   |
| Deployment       | Hugging Face Spaces      |
| Package Manager  | Poetry                   |

---

## 🧰 Features
- 🔍 **Natural language interface** for data analysis queries
- 🎥 **YouTube search tool** that recommends educational videos
- 🧾 **Vector retrieval tool** that finds context from embedded documents
- 📦 **Poetry-based environment** for clean dependency management

---

## 🚀 How to Run Locally

### 📦 Step 1: Clone the Repository
```bash
git clone https://github.com/FutureAI22/Phi4-Agent.git
cd Phi4-Agent
```

### 📜 Step 2: Install Poetry (if not installed)
```bash
curl -sSL https://install.python-poetry.org | python3 -
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc
```

### 📚 Step 3: Install Dependencies
```bash
poetry install
```

### 🔑 Step 4: Add Your Environment Variables
Create a `.env` file:
```env
MONGO_URI=your_mongodb_connection_string
YOUTUBE_API_KEY=your_youtube_data_api_key
```

### ▶️ Step 5: Run the App
```bash
poetry run python app.py
```
A Gradio interface will appear where you can ask questions!

---

## 🌐 Live Demo
Check out the deployed version on **Hugging Face Spaces**:
👉 https://huggingface.co/spaces/FutureAI22/Phi4-Agent

---

## 📖 Documentation
Detailed multi-page documentation is available on the project Wiki:
👉 https://github.com/FutureAI22/Phi4-Agent/wiki

---

## 📌 Sample Prompts
Try these in the app:
- "Show me a video tutorial on SQL joins"
- "How to build dashboards in Power BI?"
- "What is correlation in statistics?"

---

## 🙌 Credits
Created by [Dr. Alaaeldin Mostafa](https://www.linkedin.com/in/alaaeldin-mostafa/)  
Inspired by the mission to make AI a force for personalised learning.

---

## 📜 License
This project is open source and available under the [MIT License](LICENSE).

