# GenAI Engineering Playlist

A hands-on **Generative AI Engineering** playlist focused on building, integrating, evaluating, and deploying real-world AI applications.

The playlist emphasizes **practical engineering skills over theory**, with a focus on working with existing codebases, RAG systems, AI agents, tool calling, MCP, deployment, evaluation, and observability.

---

## Modules

### Module 7 — Codebase Fluency & AI-Assisted Development

Learn how to enter an unfamiliar codebase, understand it, modify it, and ship changes using modern AI-assisted development tools.

* Repository structure
* README and dependency analysis
* Configuration and environment variables
* Application entry points
* API routes
* Database connections
* Business logic
* Logs and debugging
* Request → Service → Database → Response flow
* Git branching and history
* Focused commits
* Pull requests and code review
* Merge conflicts
* Claude Code / Cursor / GitHub Copilot
* AI-assisted codebase exploration
* Bug investigation
* Feature implementation
* Refactoring
* Test generation
* Reviewing AI-generated code
* Cold repository challenge

---

### Module 8 — AI Agents & Tool Integration

Build practical AI agents that can reason, select tools, execute actions, and work with external systems.

* LLM vs Workflow vs Agent
* Agent architecture
* Agent loop
* State and memory
* Planning
* Tool selection
* Agent limitations
* Function calling
* Tool schemas
* API tools
* Python tools
* SQL tools
* File and document tools
* Tool validation
* Error handling
* Retry and fallback strategies
* SQL Agent
* Data Analysis Agent
* Data Pipeline Assistant
* MCP fundamentals
* MCP client/server architecture
* Connecting external tools
* MCP vs traditional APIs/functions

---

### Module 9 — RAG + AI-Powered Data Applications

**Current Module**

Build production-oriented Retrieval-Augmented Generation applications and understand how retrieval quality affects AI application performance.

#### 9.1 RAG Fundamentals

* What is RAG?
* RAG vs Prompting
* RAG vs Fine-tuning
* Embeddings
* Chunking
* Vector databases
* Retrieval

#### 9.2 Build a RAG Application

End-to-end pipeline:

```text
Documents
    ↓
Chunking
    ↓
Embeddings
    ↓
Vector Store
    ↓
Retrieval
    ↓
LLM
    ↓
Response
```

Topics include:

* PDF/document ingestion
* Document processing
* Text chunking
* Embedding generation
* Vector databases
* Similarity search
* Metadata filtering
* Context construction
* LLM integration
* Source citations
* Document Q&A

#### 9.3 Retrieval Quality

* Retrieval relevance
* Context quality
* Precision and recall
* Retrieval failures
* Chunking strategies
* Improving retrieval
* Retrieval evaluation
* Answer evaluation

---

### Module 10 — Deploy, Evaluate & Observe

Take AI applications from development to an engineering workflow:

```text
Build → Deploy → Evaluate → Observe → Improve
```

#### 10.1 Deployment

* FastAPI
* REST APIs
* Docker fundamentals
* Environment variables
* Secrets management
* Cloud deployment concepts

#### 10.2 AI Evaluation

* Golden datasets
* Test cases
* Expected outputs
* LLM-as-a-Judge
* Accuracy
* Relevance
* Faithfulness
* Agent task completion
* Regression testing

#### 10.3 Observability

* Logs
* Traces
* Latency
* Token usage
* Cost tracking
* Failure analysis
* LangSmith concepts
* Langfuse concepts

---

## Repository Structure

```text
genai-engineering-playlist/
│
├── module-07-codebase-fluency/
│
├── module-08-ai-agents/
│
├── module-09-rag/
│   ├── 01-rag-fundamentals/
│   ├── 02-rag-application/
│   └── 03-retrieval-quality/
│
├── module-10-deploy-evaluate-observe/
│
├── README.md
└── .gitignore
```

---

## Tech Stack

The playlist will use tools and frameworks commonly used for modern GenAI application development, including:

* Python
* FastAPI
* LangChain
* LangGraph
* Vector Databases
* FAISS
* Chroma
* BM25
* Embedding Models
* LLM APIs / Local LLMs
* Docker
* Git & GitHub
* MCP
* LangSmith
* Langfuse

---

## Learning Approach

The focus is on **building rather than just studying concepts**.

Each module aims to follow:

```text
Understand
   ↓
Implement
   ↓
Debug
   ↓
Evaluate
   ↓
Deploy
   ↓
Improve
```

Projects and exercises are designed to simulate real-world GenAI engineering workflows.

---

## Status

| Module                                        | Status      |
| --------------------------------------------- | ----------- |
| Module 7 — Codebase Fluency                   | Planned     |
| Module 8 — AI Agents & Tool Integration       | Planned     |
| Module 9 — RAG + AI-Powered Data Applications | In Progress |
| Module 10 — Deploy, Evaluate & Observe        | Planned     |

---

## Goal

The goal of this repository is to build practical skills required to develop and ship **real-world Generative AI applications**, rather than focusing only on LLM concepts and demos.

---

## Author

**Gagan Rajput**

GitHub: [Gagan47raj](https://github.com/Gagan47raj)
