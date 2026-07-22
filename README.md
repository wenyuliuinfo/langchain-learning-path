# LangChain & LangGraph Learning Path

This repository is a comprehensive, code-first learning path designed to master **LangChain** and **LangGraph**, the leading frameworks for building stateful, multi-actor applications with Large Language Models (LLMs). It is built upon the official LangChain documentation.

## 🎯 About This Repository

LangChain and LangGraph are powerful but complex ecosystems. This learning path is designed to take you from the core fundamentals to advanced concepts like graph-based agents and stateful workflows, providing a structured, hands-on experience.

**The goal is to move beyond theory** and equip you with the practical skills needed to build robust, production-ready LLM applications. You'll learn by doing, with a focus on clear, well-commented Jupyter Notebooks and Python code.

## 📂 Repository Structure

The content is organized into progressive modules, each building on the last. This structure mirrors the official LangChain documentation but provides a more guided, practical learning flow.

```
langchain-learning-path/
├── 00-module/          # Core concepts and setting up LangChain
├── 01-module/          # Working with chat models and messages
├── 02-module/          # Prompt templates, message history, and basic chains
├── 03-module/          # Retrieval-Augmented Generation (RAG) fundamentals
├── 04-module/          # Function/tool calling and building agents
├── 05-module/          # Introduction to LangGraph for stateful, multi-agent workflows
├── .env.example        # Example environment variables file
├── .gitignore
├── README.md
└── requirements.txt    # All required Python dependencies
```
Each module folder typically contains:
- **`.ipynb` Jupyter Notebooks**: Interactive, step-by-step code examples.


## 🚀 Getting Started

### Prerequisites

To effectively use this repository, you should have:
- Solid knowledge of Python programming.
- A basic understanding of LLMs and API interactions.
- An API key for an LLM provider (e.g., OpenAI, Azure OpenAI, Anthropic, or a local model via Ollama).

### Installation & Running the Code

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/wenyuliuinfo/langchain-learning-path.git
    cd langchain-learning-path
    ```

2. **Set up a Python environment:**
It's highly recommended to use a virtual environment.
    ```bash
    # Using venv (Python 3.9+)
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate
    ```

3. **Install dependencies:**
All necessary packages are listed in `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your API Keys:**
Most modules will require an API key. Copy the `.env.example` file to `.env` in the root directory and add your keys:
    ```bash
    cp .env.example .env
    # Edit .env with your credentials (e.g., OPENAI_API_KEY="your-key-here")
    ```

5. **Run a Module:**
Navigate into a module folder and launch Jupyter Notebook or run the Python script.
    ```bash
    cd 00-module
    jupyter notebook
    ```


## 🧠 Key Topics & Learning Path
This repository is structured to guide you through the entire LangChain and LangGraph ecosystem.

#### Module 00: Core Concepts
- **Introduction**: Understand what LangChain and LangGraph are, their architecture, and the problems they solve.
- **Setup**: Configure your environment and get started with your first LLM call.

#### Module 01: Chat Models
- **Chat Interfaces**: Learn how to work with `ChatOpenAI`, and other chat models.
- **Message Types**: Master the use of `SystemMessage`, `HumanMessage`, and `AIMessage` for structured conversations.

#### Module 02: Prompts & Chains
- **Prompt Templates**: Create dynamic and reusable prompts.
- **Message History**: Implement conversational memory.
- **Chains**: Build simple processing pipelines (LLMChain, SimpleSequentialChain).

#### Module 03: Retrieval-Augmented Generation (RAG)
- **Document Loading**: Load data from various sources.
- **Text Splitting & Embeddings**: Prepare documents for vector search.
- **Vector Stores & Retrieval**: Use Chroma, FAISS, and other vector databases.
- **RAG Chains**: Build a system that answers questions based on your documents.

#### Module 04: Tools & Agents
- **Function Calling**: Enable LLMs to call external functions (APIs, web search, etc.).
- **Agent Types**: Explore different agent architectures (e.g., ReAct, OpenAI Tools).
- **Custom Tools**: Build your own tools for agents to use.

#### Module 05: LangGraph (Stateful Multi-Agent Systems)
- **Graph-Based Workflows**: Understand the core concepts of LangGraph (Nodes, Edges, State).
- **State Management**: Build applications with persistent, shared state.
- **Complex Agents**: Create agents that can loop, branch, and perform complex, multi-step reasoning.
- **Multi-Agent Systems**: Design and implement systems where multiple agents collaborate.

