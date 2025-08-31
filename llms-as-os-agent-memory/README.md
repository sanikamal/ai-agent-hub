# LLMs as Operating Systems: Agent Memory

This repo demonstrates how Large Language Models (LLMs) can function as operating systems by managing and persisting memory efficiently. Inspired by the *MemGPT* research paper, the course demonstrates how to build agentic memory into applications using the **Letta** framework.

LLMs have finite input context windows, making memory management crucial for scalability. By leveraging persistent storage, summarization, and retrieval, agents can optimize context use and achieve adaptive, collaborative behavior for real-world applications.

---

## Key Features

* **Persistent Agent Memory**
  Build agents with long-term, self-editing memory that persists across sessions.

* **Memory-Aware Context Management**
  Summarize, swap, and restore information between context memory and searchable storage.

* **Fact & Task Persistence**
  Track names, preferences, and domain-specific data (e.g., research findings, HR info).

* **Letta Framework Integration**
  Add advanced reasoning and transparent long-term memory to LLM agents.

* **Multi-Agent Collaboration**
  Share memory blocks, send messages, and orchestrate teams of agents.

* **Streaming Agent Reasoning**
  Retrieve step-by-step reasoning in real time instead of waiting for full outputs.

* **Real-World Deployment**
  Run pre-deployed cloud-based agents via Letta services.

---

## Notebooks

1. **Editable Memory** — [Build and update memory in real time.](editable_memory.ipynb)
2. **Building Agents with Memory** — [Combine reasoning, tools, and memory into prompts.](building_agents_with_letta.ipynb)
3. **Programming Agent Memory** — [Customize core memory with blocks and memory tools.](customizing_memory_management_in_MemGPT.ipynb)
4. **Agentic RAG & External Memory** — [Connect external databases for retrieval-augmented workflows.](agentic_RAG_with_external_memory.ipynb)
5. **Multi-Agent Orchestration** — [Share knowledge and collaborate via memory blocks.](multi_agent_orchestration_with_MemGPT.ipynb)

---

## References

* **MemGPT Paper:** *Towards LLMs as Operating Systems*
* **Letta Framework:** [https://www.letta.com/](https://www.letta.com/)
* **course:** [LLMs as Operating Systems: Agent Memory](https://www.deeplearning.ai/short-courses/llms-as-operating-systems-agent-memory/)

