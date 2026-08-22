# 🤖 AI Agents Fundamentals — The Core Foundations

> **What every AI agent has in common, regardless of how you build it.**

This guide explains the universal building blocks of AI agents. Whether you use LangChain, AutoGen, or build from scratch, these concepts are the same.

---

## 🧠 What Is an AI Agent?

**An AI agent is a system that uses a Large Language Model (LLM) to decide what actions to take, and then executes those actions.**

Think of it like this:

| Component | Analogy |
| :--- | :--- |
| **LLM (Brain)** | The CEO who makes decisions. |
| **Tools (Hands)** | The actions the CEO can take (search web, call APIs, calculate). |
| **Memory (Notepad)** | The CEO's notes about what happened earlier. |
| **Loop (Strategy)** | The CEO's process: Think → Act → Observe → Think again. |

---

## 🧩 The 5 Universal Components of Every Agent

### 1. The LLM (Language Model)
- The core decision-maker.
- Takes **prompts** (text) and outputs **responses** (text).
- Examples: GPT-4, Claude, Llama, Gemini.
- **Role:** Understands the user's goal and plans a sequence of actions.

### 2. Tools (Functions/APIs)
- External capabilities the agent can invoke.
- Examples:
  - Web search
  - Database queries
  - Weather API calls
  - Mathematical calculators
  - File system operations
- **Role:** Allow the agent to interact with the real world (not just talk).

### 3. Memory (State)
Agents need to remember things across steps:

| Memory Type | Description | Example |
| :--- | :--- | :--- |
| **Short-term** | Current conversation history. | "Earlier you said you wanted pizza." |
| **Long-term** | Stored knowledge across sessions. | User preferences, saved facts. |
| **Working** | Intermediate thoughts during a single task. | "Step 1: Get lat/long. Step 2: Query weather." |

### 4. Planning & Reasoning
How the agent decides what to do next:

| Strategy | Description |
| :--- | :--- |
| **ReAct** | Reason → Act → Observe → Repeat. |
| **Chain-of-Thought** | Think step-by-step before acting. |
| **Plan-and-Execute** | Create a full plan first, then execute it. |
| **Reflection** | Review your own output and improve it. |

### 5. The Execution Loop
The infinite cycle that powers all agents:
