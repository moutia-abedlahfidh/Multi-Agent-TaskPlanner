# 🧠 Multi-Agent Task Planner

A simple yet powerful **multi-agent system** built in Python that simulates collaboration between intelligent agents to plan, estimate, and describe tasks.

## 🚀 Overview

This project demonstrates how multiple AI agents can work together in a coordinated pipeline to solve user requests. Instead of acting independently, each agent contributes a specific role:

* **TaskAgent** → Breaks down a task into structured steps
* **EstimationAgent** → Estimates the time required for each step
* **DescriptiveAgent** → Explains how to execute the steps clearly
* **CoordinatorAgent** → Orchestrates communication between agents

The system transforms a simple user query into a complete workflow:
**Plan → Estimate → Explain**

---

## 🏗️ Architecture

User input is processed through a central coordinator that routes and chains agents:

User → Coordinator → TaskAgent → EstimationAgent → DescriptiveAgent

Each agent builds on the output of the previous one, enabling real collaboration instead of isolated responses.

---

## ⚙️ Features

* ✅ Multi-agent collaboration (pipeline-based)
* ✅ Task decomposition into actionable steps
* ✅ Time estimation for planning
* ✅ Clear execution guidance
* ✅ Modular and extensible architecture
* ✅ Easy to integrate with LLMs (e.g., LLaMA3)

---

## 📌 Example

**Input:**

> "Full build a web platform for students"

**Output:**

* 📋 Task plan (step-by-step)
* ⏱️ Time estimation
* 🧾 Detailed explanation

---

## 🧩 Technologies

* Python 🐍
* LLM integration (e.g., LLaMA 3)
* Prompt engineering

---

## 📈 Future Improvements

* 🔹 Structured JSON outputs for better agent communication
* 🔹 Memory integration for context-aware reasoning
* 🔹 Additional agents (DeveloperAgent, UIAgent, etc.)
* 🔹 API integration (FastAPI / frontend UI)
* 🔹 Autonomous agent loops (AutoGPT-style)

---

## 💡 Purpose

This project is designed as a **learning and experimentation framework** for:

* Multi-agent systems
* AI orchestration
* Prompt engineering
* Task automation

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Developed as part of a learning journey into AI systems and software engineering.
