# 🧠 Deep Research — Agentic Multi-Agent Research System

- An AI-powered multi-agent research assistant that performs deep research on any topic through collaboration between specialized agents.

- This project demonstrates an Agentic workflow — where agents like Planner, Searcher, Email, and Writer cooperate to gather, analyze, and summarize information automatically.
<img width="1034" height="607" alt="deep research" src="https://github.com/user-attachments/assets/36ddbeac-446c-417c-90c1-5c399d199ca2" />

<img width="759" height="940" alt="deep research2" src="https://github.com/user-attachments/assets/fd4bf835-18e7-43e7-9be1-69486fc07da7" />

## 🚀 Features

- 🤖 Multi-agent coordination (Planner, Searcher, Writer, Email, Manager)

- 🔍 Automated web research with AI search agents

- 🧩 Structured planning for subtopic exploration

- 📝 Summarized report generation by the Writer Agent

- 📧 Optional email sharing of results

- 💬 Interactive Gradio interface for local exploration

## ⚙️ Setup
1. Clone the repository
```bash
git clone https://github.com/melisamehe/deep-research-agents.git
cd deep-research
```
2. Create a .env file

Inside the project folder, create a file named .env and add your OpenAI API key:
```bash
OPENAI_API_KEY=your_openai_api_key_here

```
3. Install dependencies

If you're using uv, run:
```bash
uv sync
```
## ▶️ Run Locally

Launch the interactive Gradio interface:
```bash
uv run deep_research.py
```
Then open the link shown in the terminal (usually http://127.0.0.1:7860/) to start researching any topic you want.
.

## 🧩 Example Workflow

1. Enter a topic (e.g., “The future of autonomous robotics”)

2. The Planner Agent creates subtopics

3. The Search Agent gathers real-world data

4. The Writer Agent composes a clear, concise research summary

5. (Optional) The Email Agent can send you the final report

## 🧑‍💻 Technologies Used

- Python
- Gradio (for the UI)
- OpenAI API
- Multi-Agent Orchestration Logic

## 🏗️ Project Idea

This project is inspired by the Agentic AI paradigm, showcasing how independent AI agents can collaborate to perform complex, multi-step research autonomously.

