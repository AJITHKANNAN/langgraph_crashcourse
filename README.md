
🧠 LangGraph Crash Course

Welcome to the **LangGraph Crash Course**!
This repository walks you through hands-on examples of building modular and intelligent AI systems using **LangGraph** — a framework for building **stateful, reactive, and composable workflows** around LLMs.

Each notebook introduces a new concept, starting from simple graphs to advanced agent systems with memory, tools, and LangSmith integration.

---

📚 Course Outline

**SimpleGraph**
* Learn the fundamentals of **LangGraph**.
* Build your first minimal graph with input → node → output.
* Understand graph.add_node(), graph.set_entry_point(), and graph.invoke().

🧩 **Concepts Covered**
* Basic node creation
* Graph execution flow
* Passing data between nodes

---

**ConditionalGraph**
* Add **logic branching** to your graph.
* Use conditions to control flow dynamically (like an if/else inside the graph).

🧩 **Concepts Covered**
* Conditional edges (graph.add_conditional_edges)
* Decision nodes
* Dynamic routing

---

**Chatbot**
* Build an interactive **multi-turn chatbot** using LangGraph.
* Integrate memory and message history for context retention.

🧩 **Concepts Covered**
* Stateful graph design
* Role-based messages (user, assistant)
* Streaming and response handling

---

**ToolsInChat**
* Enable your chatbot to **use external tools** (like calculators, APIs, or knowledge fetchers).
* Teach LLMs to reason when to call a tool.

🧩 **Concepts Covered**
* Tool definitions and invocation
* Function-calling workflow
* Integrating LLM + Python logic

---

**AgentWithTools**
* Combine LangGraph with **LangChain Agents**.
* Create an agent capable of planning, acting, and reasoning using multiple tools.

🧩 **Concepts Covered**
* Agent node design
* Multi-tool orchestration
* Observing reasoning chains

---

**Memory**
* Persist and reuse context across multiple interactions.
* Use memory to build session-aware systems.

🧩 **Concepts Covered**
* In-memory checkpointing
* Stateful workflows
* Thread and checkpoint configuration

---

**BasicLangSmith**
* Introduce **LangSmith** for tracing, debugging, and evaluating your LangGraph runs.

🧩 **Concepts Covered**
* @traceable decorator
* Tracing execution and nodes
* Viewing runs on LangSmith dashboard

---

**HumanInTheLoop**
* Integrate human review or feedback into your LangGraph pipeline.
* Pause execution, wait for manual approval, then continue.

🧩 **Concepts Covered**
* Human checkpoints
* Controlled workflow resumption
* Hybrid AI-human decision flow

---

🚀 Getting Started


Clone the repo
git clone https://github.com/AJITHKANNAN/langgraph_crashcourse.git
cd langgraph_crashcourse

(Optional) Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate     or .venv\Scripts\activate on Windows

Install dependencies
pip install -r requirements.txt


---

🧩 Requirements

* Python 3.10+
* langgraph
* langchain
* langsmith
* openai or google-generativeai
* ipython / jupyter

---

🧭 Recommended Execution Order
01_simplegraph.ipynb
02_conditionalgraph.ipynb
03_chatbot.ipynb
04_toolsinchat.ipynb
05_agentwithtools.ipynb
06_memory.ipynb
07_basiclangsmith.ipynb
08_humanintheloop.py
