# Hi, I'm Agastya 👋

I build LLM-powered applications, with a focus on agent design patterns — multi-agent orchestration, retrieval pipelines, self-correction loops, and iterative reasoning. The projects here are built with LangChain, LangGraph, and OpenAI, and range from full-stack web apps to deeper explorations of how agentic systems work under the hood. They're all informal projects I decided to build with the purpose of learning new tech concepts by implementation rather than strictly theory.

---

### 🖥️ Projects with Web Interface

| Project | What it does |
|---|---|
| [ice_breaker2](https://github.com/gstsen75-ctrl/ice_breaker2) | Enter a name — two ReAct agents find their LinkedIn and Twitter, scrape the data, and an LLM generates a profile summary |
| [agentic-rag](https://github.com/gstsen75-ctrl/agentic-rag) | Self-RAG pipeline that grades its own retrieved documents, detects hallucinations, and falls back to web search when needed |
| [code-interpreter](https://github.com/gstsen75-ctrl/code-interpreter) | Ask questions in plain English — a grand agent routes to either a Python REPL or a CSV analyst automatically |
| [reflection-agent](https://github.com/gstsen75-ctrl/reflection-agent) | Paste a rough tweet — a generator and critic alternate in a loop, each round making it sharper |
| [reflexion-agent](https://github.com/gstsen75-ctrl/reflexion-agent) | Research assistant that drafts an answer, searches the web to fill gaps, then revises with citations |

### ⚙️ Systems / Backend Projects

| Project | What it demonstrates |
|---|---|
| [in-memory-db](https://github.com/gstsen75-ctrl/In_Memory_DB) | From-scratch database engine in Python — implements schema validation, indexing, LRU buffer pool, write-ahead logging (WAL), and crash recovery |


### 📚 Educational / Terminal

| Project | What it demonstrates |
|---|---|
| [react-langchain](https://github.com/gstsen75-ctrl/react-langchain) | ReAct agent built from scratch — the raw Thought → Action → Observation loop with no high-level abstractions |
| [langgraph_project](https://github.com/gstsen75-ctrl/langgraph_project) | Minimal ReAct agent using LangGraph's native `MessagesState` and `ToolNode` |
| [vectorstore-in-memory](https://github.com/gstsen75-ctrl/vectorstore-in-memory) | Basic PDF RAG pipeline — load, chunk, embed into FAISS, retrieve and answer |
