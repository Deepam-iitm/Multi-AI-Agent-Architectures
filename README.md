# 🤖 Multi-AI-Agent Architectures

This repository explores **Multi-AI-Agent systems**, focusing on how multiple intelligent agents can collaborate, reason, and solve tasks together using modern LLM-based frameworks.

The project demonstrates concepts such as agent coordination, tool usage, planning, and message passing in a modular and extensible way.

---

## 🚀 Project Overview

Multi-agent AI systems go beyond single-model intelligence by enabling:
- Task decomposition
- Agent-to-agent communication
- Role-based reasoning
- Tool-augmented decision making

This repository serves as an **experimental and educational playground** to understand and build such systems.
It consists of three types of architecture:
1. Simple Multi AI Agent architechure.
2. Supervised Multi AI Agent architechure.
3. Hierarchical  Multi AI Agent architechure.

---

## 📂 Repository Structure
* multiaiagent.ipynb # Core notebook demonstrating multi-agent architecture
* requirements.txt # Python dependencies
* README.md # Project documentation

## 🔧 Libraries & Tools Used

This project leverages several modern AI and orchestration libraries to build and manage multi-agent systems:

- **LangGraph** – For defining and orchestrating agent workflows using graph-based execution.
- **LangChain** – Provides abstractions for LLMs, tools, prompts, and agent logic.
- **Tavily** – Used as a web search and retrieval tool for agents to access up-to-date external information.
- **Groq** – Provides high-performance LLM inference to power agent reasoning and decision-making.
- **Python** – Core programming language for implementation.
- **Jupyter Notebook** – Interactive environment for experimentation and visualization.

These libraries together enable scalable, modular, and tool-augmented multi-agent architectures.


## ⚙️ Installation

1. Clone the repository
   * `git clone https://github.com/Deepam-iitm/Multi-AI-Agent-Architectures.git`

2. Create a virtual environment
   * `python -m venv venv`
   * `source venv/bin/activate `       # Linux / Mac
   * `venv\Scripts\activate `          # Windows

3. Install dependencies
   * `pip install -r requirements.txt`

4. Create a .env file in the root directory:
   * `GROQ_API_KEY=your_groq_api_key_here `
     
5. Open the notebook `multiaiagent.ipynb` and run step-by-step.



