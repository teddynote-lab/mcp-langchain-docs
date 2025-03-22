# LangGraph

This guide brings together the key content from two major LangGraph resource sets. It is organized into several parts, covering everything from a quickstart overview to core components, advanced features, and practical use cases.

---

## Part 1: Getting Started and Overview

### 1.1 Quickstart Guides (GitBook)
- **LangGraph Quickstart:**  
  [Build a chatbot with tools, human‑in‑the‑loop, and time-travel](https://langchain-ai.github.io/langgraph/tutorials/introduction/)
- **Common Workflows:**  
  [Overview of typical LangGraph workflows](https://langchain-ai.github.io/langgraph/tutorials/workflows/)
- **Server and Deployment:**  
  - [Local LangGraph Server Quickstart](https://langchain-ai.github.io/langgraph/tutorials/langgraph-platform/local-server/)  
  - [Deploy with LangGraph Cloud Quickstart](https://langchain-ai.github.io/langgraph/cloud/quick_start/)

### 1.2 Overview & Concepts (GitBook)
- **Why LangGraph?**  
  [Motivation and high‑level overview](https://langchain-ai.github.io/langgraph/concepts/high_level/)
- **LangGraph Glossary:**  
  [Key terms and primitives in LangGraph](https://langchain-ai.github.io/langgraph/concepts/low_level/)
- **FAQ:**  
  [Frequently Asked Questions](https://langchain-ai.github.io/langgraph/concepts/faq/)

---

## Part 2: Core Components

### 2.1 Core Features & Basic Functionality

#### Wikidocs (CH17 – 핵심 기능)
- **핵심 기능 Overview:**  
  [Core Functionality](https://wikidocs.net/265670)  
  *Includes:*  
  - Python syntax common in LangGraph  
  - Building chatbots and agents  
  - Adding memory, streaming outputs, human‑in‑the‑loop, state modifications, tool calling, parallel execution, subgraph usage, etc.

#### GitBook (Core Features)
- **Introduction to LangGraph:**  
  [01. Introduction to LangGraph](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/01-langgraph-introduction)
- **LangGraph Chatbot & Agent:**  
  [02. LangGraph Chatbot](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/02-langgraph-chatbot)  
  [03. LangGraph Agent](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/03-langgraph-agent)
- **Agent with Memory & Human in the Loop:**  
  [04. LangGraph Agent with Memory](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/04-langgraph-agent-with-memory)  
  [05. Human in the Loop](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/06-langgraph-human-in-the-loop)
- **State Customization & Conversation Summaries:**  
  [06. State Customization](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/08-langgraph-state-customization)  
  [07. Managing Conversation Summaries](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/01-core-features/12-conversation-summaries-with-langgraph)

### 2.2 Structural Design & Advanced Graph Construction

#### Wikidocs (구조 설계)
- **Structure Design:**  
  [01. 기본 그래프 생성](https://wikidocs.net/267808)  
  [02. Naive RAG](https://wikidocs.net/267809)  
  [03. 관련성 체커 모듈 추가](https://wikidocs.net/267810)  
  [04. 웹 검색 모듈 추가](https://wikidocs.net/267811)  
  [05. 쿼리 재작성 모듈 추가](https://wikidocs.net/267812)  
  [06. Agentic RAG](https://wikidocs.net/267813)  
  [07. Adaptive RAG](https://wikidocs.net/267814)

#### GitBook (Structures)
- **Building LangGraph Structures:**  
  [01. Building LangGraph Structures](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/02-structures/01-langgraph-building-graphs)
- **Advanced Integrations:**  
  [02. Naive RAG Integration](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/02-structures/02-langgraph-naive-rag)  
  [03. Adding Groundedness Check](https://langchain-opentutorial.gitbook.io/langchain-opentutorial/17-langgraph/02-structures/03-langgraph-add-groundedness-check)

---

## Part 3: Advanced How‑Tos and Functional Guides

*(The GitBook “How-tos” section covers these topics in depth.)*

### Graph API & Fine‑grained Control
- [Update Graph State from Nodes](https://langchain-ai.github.io/langgraph/how-tos/state-reducers/)
- [Creating a Sequence of Steps](https://langchain-ai.github.io/langgraph/how-tos/sequence/)
- [Creating Branches for Parallel Execution](https://langchain-ai.github.io/langgraph/how-tos/branching/)
- [Loop Control with Recursion Limits](https://langchain-ai.github.io/langgraph/how-tos/recursion-limit/)
- [Graph Visualization](https://langchain-ai.github.io/langgraph/how-tos/visualization/)

### Persistence & Memory
- **Persistence Guides:**  
  [Thread-level Persistence](https://langchain-ai.github.io/langgraph/how-tos/persistence/)  
  [Cross-thread Persistence](https://langchain-ai.github.io/langgraph/how-tos/cross-thread-persistence/)  
  [Subgraph Persistence](https://langchain-ai.github.io/langgraph/how-tos/subgraph-persistence/)  
  [Postgres Checkpointer](https://langchain-ai.github.io/langgraph/how-tos/persistence_postgres/)  
  [MongoDB Checkpointer](https://langchain-ai.github.io/langgraph/how-tos/persistence_mongodb/)  
  [Custom Checkpointer using Redis](https://langchain-ai.github.io/langgraph/how-tos/persistence_redis/)
- **Memory Management:**  
  [Managing Conversation History](https://langchain-ai.github.io/langgraph/how-tos/memory/manage-conversation-history/)  
  [Deleting Messages](https://langchain-ai.github.io/langgraph/how-tos/memory/delete-messages/)  
  [Adding Summary Memory](https://langchain-ai.github.io/langgraph/how-tos/memory/add-summary-conversation-history/)  
  [Long-term Memory (Cross-thread)](https://langchain-ai.github.io/langgraph/how-tos/memory/cross-thread-persistence/)  
  [Semantic Search for Memory](https://langchain-ai.github.io/langgraph/how-tos/memory/semantic-search/)

### Human-in-the-Loop & Interactive Workflows
- [Waiting for User Input](https://langchain-ai.github.io/langgraph/how-tos/human_in_the_loop/wait-user-input/)
- [Reviewing Tool Calls](https://langchain-ai.github.io/langgraph/how-tos/human_in_the_loop/review-tool-calls/)
- [Adding Static Breakpoints](https://langchain-ai.github.io/langgraph/how-tos/human_in_the_loop/breakpoints/)
- [Editing Graph State](https://langchain-ai.github.io/langgraph/how-tos/human_in_the_loop/edit-graph-state/)
- *(Functional API versions available)*

### Time Travel & Streaming
- [Time Travel: Viewing/Updating Past Graph State](https://langchain-ai.github.io/langgraph/how-tos/time-travel/)
- [Streaming Guides (General, Tokens, Specific Nodes, Tools, Subgraphs)](https://langchain-ai.github.io/langgraph/how-tos/streaming/)

### Tool Calling & Subgraphs
- [Tool Calling using ToolNode](https://langchain-ai.github.io/langgraph/how-tos/tool-calling/)
- [Handling Tool Calling Errors](https://langchain-ai.github.io/langgraph/how-tos/tool-calling-errors/)
- [Passing Runtime Values and Config to Tools](https://langchain-ai.github.io/langgraph/how-tos/pass-run-time-values-to-tools/)
- [Updating Graph State from Tools](https://langchain-ai.github.io/langgraph/how-tos/update-state-from-tools/)
- [Handling Many Tools](https://langchain-ai.github.io/langgraph/how-tos/many-tools/)
- **Subgraphs:**  
  [Using Subgraphs](https://langchain-ai.github.io/langgraph/how-tos/subgraph/)  
  [Subgraph State Management](https://langchain-ai.github.io/langgraph/how-tos/subgraphs-manage-state/)  
  [Transforming Subgraph Inputs/Outputs](https://langchain-ai.github.io/langgraph/how-tos/subgraph-transform-state/)

### Multi-agent and State Management
- **Multi-agent Systems:**  
  [Implementing Agent Handoffs](https://langchain-ai.github.io/langgraph/how-tos/agent-handoffs/)  
  [Building a Multi-agent Network](https://langchain-ai.github.io/langgraph/how-tos/multi-agent-network/)  
  [Multi-turn Conversation in Multi-agent Applications](https://langchain-ai.github.io/langgraph/how-tos/multi-agent-multi-turn-convo/)
- **State Management:**  
  [Using Pydantic Models as Graph State](https://langchain-ai.github.io/langgraph/how-tos/state-model/)  
  [Defining Input/Output Schemas](https://langchain-ai.github.io/langgraph/how-tos/input_output_schema/)  
  [Passing Private State Between Nodes](https://langchain-ai.github.io/langgraph/how-tos/pass_private_state/)

### Additional How-tos
- [Asynchronous Graph Execution](https://langchain-ai.github.io/langgraph/how-tos/async/)
- [Forcing Tool-calling Agents to Structure Output](https://langchain-ai.github.io/langgraph/how-tos/react-agent-structured-output/)
- [Passing Custom LangSmith Run ID](https://langchain-ai.github.io/langgraph/how-tos/run-id-langsmith/)
- [Integrating with Other Frameworks (AutoGen, CrewAI, etc.)](https://langchain-ai.github.io/langgraph/how-tos/autogen-integration/)

---

## Part 4: Use Cases & Applications

### Chatbots & Conversational Agents
- **Customer Support Bot:**  
  [Build a multi-functional support bot](https://langchain-ai.github.io/langgraph/tutorials/customer-support/customer-support/)
- **Prompt Generation:**  
  [Generate prompts from user requirements](https://langchain-ai.github.io/langgraph/tutorials/chatbots/information-gather-prompting/)
- **Code Assistant:**  
  [Build a code analysis and generation assistant](https://langchain-ai.github.io/langgraph/tutorials/code_assistant/langgraph_code_assistant/)

### Retrieval-Augmented Generation (RAG)
- **Agentic RAG:**  
  [Use an agent to retrieve and answer questions](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_agentic_rag/)
- **Adaptive RAG:**  
  [Adaptive RAG with query analysis and self-correction](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_adaptive_rag/)  
  *(Local LLM version available)*
- **Corrective RAG:**  
  [Use LLM to assess retrieval quality and re-fetch information](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_crag/)  
  *(Local LLM version available)*
- **Self-RAG:**  
  [Incorporate self-reflection and self-grading](https://langchain-ai.github.io/langgraph/tutorials/rag/langgraph_self_rag/)  
  *(Local LLM version available)*
- **SQL Agent:**  
  [Build an agent to interact with SQL databases](https://langchain-ai.github.io/langgraph/tutorials/sql-agent/)

### Multi-Agent Systems
- **Collaboration Network:**  
  [Enable agents to collaborate on tasks](https://langchain-ai.github.io/langgraph/tutorials/multi_agent/multi-agent-collaboration/)
- **Supervisor Agent:**  
  [Orchestrate and delegate tasks among agents](https://langchain-ai.github.io/langgraph/tutorials/multi_agent/agent_supervisor/)
- **Hierarchical Teams:**  
  [Build nested teams of agents for complex problem solving](https://langchain-ai.github.io/langgraph/tutorials/multi_agent/hierarchical_agent_teams/)

---

## Part 5: Additional Resources

### Miscellaneous (from Wikidocs)
- **Other Information:**  
  [StreamEvent 타입별 정리](https://wikidocs.net/265576)

---

## Other Resources

- [테디노트의 랭체인LangChain 노트](https://wikidocs.net/book/14314)
- [랭체인 한국어 튜토리얼 코드저장소(GitHub)](https://github.com/teddylee777/langchain-kr)
- [패스트캠퍼스 - RAG 비법노트](https://fastcampus.co.kr/data_online_teddy?utm_source=wikidocs&utm_medium=viral&utm_campaign=prd%5E250318%5E239355&utm_content=teacher%5E239355)