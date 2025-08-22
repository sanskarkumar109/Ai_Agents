# 🤖 AI Agents Hub

Welcome to **AI Agents Hub** – a collection of intelligent agents built with modern AI frameworks, designed for practical tasks like document understanding, search, and automation.  

This repository is a **work-in-progress**, where new agents will be added regularly as experiments and projects evolve.  

---

## 📌 Current Agents

### 1. 🔍 Web Search Agent  
- Uses free search APIs to fetch relevant information from the web.  
- Integrates with **LangChain** and **LLMs** to process, summarize, and answer queries.  
- Example use case: "Find me the latest AI research papers on multimodal models."

### 2. 📄 PDF Query Agent  
- Upload a PDF and query it with natural language.  
- Uses **FAISS Vectorstore** + **LLM** for semantic search.  
- Example use case: "Summarize Chapter 3 of this research paper" or "What are the key findings?"

---

## 🛠️ Tech Stack
- [Python 3.10+](https://www.python.org/)  
- [LangChain](https://www.langchain.com/)  
- [FAISS](https://github.com/facebookresearch/faiss)  
- [Google Generative AI](https://ai.google/) (Gemini)  
- Free APIs for search and embeddings 

## 🚀 Getting Started

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-agents-hub.git
cd ai-agents-hub
2️⃣ Create a Virtual Environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run an Agent
Example: Running the PDF Query Agent
python pdf_agent.py
📂 Repository Structure
ai-agents
│── agents/
│   ├── web_search_agent.py
│   ├── pdf_query_agent.py
│── requirements.txt
│── README.md

🌟 Roadmap
 Add YouTube Transcript Agent 🎥

 Add Email Summarizer Agent 📧

 Add Knowledge Graph Agent 🌐

 Web UI for all agents

🤝 Contributing
Contributions are welcome!
If you have ideas for new agents, open an issue or submit a PR.

⭐ If you like this project, give it a star on GitHub!
