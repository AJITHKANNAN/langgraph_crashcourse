🧠 LangGraph Crash Course

Welcome to the LangGraph Crash Course!
This repository walks you through hands-on examples of building modular and intelligent AI systems using LangGraph — a framework for building stateful, reactive, and composable workflows around LLMs.

Each notebook introduces a new concept, starting from simple graphs to advanced agent systems with memory, tools, and LangSmith integration.

📚 Course Outline
1️⃣ SimpleGraph

Learn the fundamentals of LangGraph.

Build your first minimal graph with input → node → output.

Understand graph.add_node(), graph.set_entry_point(), and graph.invoke().

🧩 Concepts Covered

Basic node creation

Graph execution flow

Passing data between nodes

2️⃣ ConditionalGraph

Add logic branching to your graph.

Use conditions to control flow dynamically (like an if/else inside the graph).

🧩 Concepts Covered

Conditional edges (graph.add_conditional_edges)

Decision nodes

Dynamic routing

3️⃣ Chatbot

Build an interactive multi-turn chatbot using LangGraph.

Integrate memory and message history for context retention.

🧩 Concepts Covered

Stateful graph design

Role-based messages (user, assistant)

Streaming and response handling

4️⃣ ToolsInChat

Enable your chatbot to use external tools (like calculators, APIs, or knowledge fetchers).

Teach LLMs to reason when to call a tool.

🧩 Concepts Covered

Tool definitions and invocation

Function-calling workflow

Integrating LLM + Python logic

5️⃣ AgentWithTools

Combine LangGraph with LangChain Agents.

Create an agent capable of planning, acting, and reasoning using multiple tools.

🧩 Concepts Covered

Agent node design

Multi-tool orchestration

Observing reasoning chains

6️⃣ Memory

Persist and reuse context across multiple interactions.

Use memory to build session-aware systems.

🧩 Concepts Covered

In-memory checkpointing

Stateful workflows

Thread and checkpoint configuration

7️⃣ BasicLangSmith

Introduce LangSmith for tracing, debugging, and evaluating your LangGraph runs.

🧩 Concepts Covered

@traceable decorator

Tracing execution and nodes

Viewing runs on LangSmith dashboard

8️⃣ HumanInTheLoop

Integrate human review or feedback into your LangGraph pipeline.

Pause execution, wait for manual approval, then continue.

🧩 Concepts Covered

Human checkpoints

Controlled workflow resumption

Hybrid AI-human decision flow
