# 🧠 AI Agents from Scratch

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Build 5 kinds of AI agents in Python, from a one-shot Q&A bot up to a multi-agent team.**  
> — *Repository for the "AI Agents from Scratch" course by qurioskill*

This repository is your hands-on guide to understanding and implementing AI agents from the ground up. Instead of relying on high‑level frameworks, we build every component ourselves — giving you deep insight into how agents reason, use tools, retrieve knowledge, and collaborate.

---

## 📚 Table of Contents
- [Overview](#overview)
- [The 5 Agents You'll Build](#the-5-agents-youll-build)
- [Prerequisites](#prerequisites)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How to Study This Repo](#how-to-study-this-repo)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Overview

AI agents are programs that perceive their environment, reason about it, and take actions to achieve a goal. In this repo, we progressively build five agents, each introducing new concepts:

1. **One‑Shot Q&A Bot** – the simplest form, answering questions with a single LLM call.
2. **ReAct Agent** – combines reasoning and acting in a loop, using tools when needed.
3. **Tool‑Calling Agent** – explicitly invokes external functions (APIs, calculators, etc.).
4. **Retrieval‑Augmented (RAG) Agent** – grounds answers in your own documents via vector search.
5. **Multi‑Agent Team** – a group of specialised agents that collaborate to solve complex tasks.

Each agent is implemented in pure Python with minimal dependencies, so you can see exactly how the magic happens.

---

## 🤖 The 5 Agents You'll Build

| # | Agent | Description | Key Concepts |
|---|-------|-------------|--------------|
| 1 | **One‑Shot Q&A** | Answers user queries with a single prompt to an LLM. | Prompt engineering, parsing |
| 2 | **ReAct** | Iteratively "Reason" and "Act" – thinks, takes actions, observes, and repeats. | Thought‑Action‑Observation loop, tool integration |
| 3 | **Tool‑Calling** | Calls external functions (e.g., weather API, calculator) based on user intent. | Function calling, JSON schema |
| 4 | **RAG (Retrieval‑Augmented)** | Retrieves relevant documents from a vector database and uses them in the prompt. | Embeddings, chunking, similarity search |
| 5 | **Multi‑Agent Team** | Multiple agents (e.g., Researcher, Writer, Validator) cooperate to produce a final answer. | Handoffs, message passing, supervisor pattern |

---

## ✅ Prerequisites

- Python 3.9 or higher
- An API key for an LLM provider (e.g., OpenAI, Anthropic, or local model)
- (Optional) A vector database like Chroma, FAISS, or Pinecone – we'll use a lightweight in‑memory store for development.
- Basic knowledge of Python and asynchronous programming (helpful but not mandatory).

---

## 🛠 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/qurioskill/AI-Agents-from-Scratch.git
   cd AI-Agents-from-Scratch

the first two agents are in my ai-agents-python 
https://github.com/anexbin/AI-agents-fundamentals
