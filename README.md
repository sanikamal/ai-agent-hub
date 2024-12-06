# AI-Agent-Hub 🤖

Welcome to **AI-Agent-Hub**! This repository is a collection of AI agent projects and notebooks, showcasing the use of various powerful libraries such as **LangGraph**, **AutoGen**, **CrewAI**, and more. Each project demonstrates different approaches to creating intelligent, autonomous agents capable of tackling complex tasks and workflows.

## Contents📂

|          **Title**           |                      **Description**                    |     **Technology/Tools**      |      **Link**         |
|------------------------------|---------------------------------------------------------|-------------------------------|-----------------------|
| **Simple ReAct Agent from Scratch** | Build a ReAct (Reasoning + Acting) agent from scratch, combining reasoning capabilities with action-oriented execution to solve tasks efficiently. | `ReAct`, `AI Agents`, `Python`,`OpenAI` | [Notebook](notebook/simple_react_agent_from_scratch.ipynb) |
| **LangGraph Components** | Explore the components of LangGraph and combine them to build flow-based applications for seamless execution and management of tasks. | `LangGraph`, `AI Agents`, `OpenAI` | [Notebook](notebook/langgraph_components.ipynb) |
| **Agentic Search** | Explore how agentic search retrieves multiple answers in a structured and predictable format, offering a streamlined alternative to traditional search engines that provide links. | `Agentic Search`, `AI Agents`, `LangGraph`, `Tavily` | [Notebook](notebook/agentic_search.ipynb) |
| **Persistence and Streaming** | Implementing persistence in agents to manage state across multiple threads, enable conversation switching, and reload previous states for continuity. | `State Management`, `Streaming`, `AI Agents`,`LangGraph` | [Notebook](notebook/persistence_and_streaming.ipynb) |
| **Human in the Loop** | Integrating human-in-the-loop mechanisms into agent systems to enhance decision-making, validate outputs, and ensure higher accuracy. | `Human-in-the-Loop`, `AI Agents`, `Decision Making`, `LangGraph` | [Notebook](notebook/human_in_the_loop.ipynb) |
| **LlamaIndex Router Query Engine** | Build a basic agentic RAG system by implementing a router that selects between query engines, such as Q&A or summarization, to execute queries over a single document. | `LlamaIndex`, `RAG`, `Query Engine` | [Notebook](notebook/llamaindex_router_query_engine.ipynb) |
| **Llamaindex Tool Calling** | Enhancing the router agent by enabling tool calling, allowing an LLM to determine the appropriate function to execute and infer the required arguments. | `Llamaindex`, `LLM`, `Tool Calling`, `Function Execution` | [Notebook](notebook/llamaindex_tool_calling.ipynb) |
| **Building an Agent Reasoning Loop with Llamaindex** | Developing a research assistant agent capable of reasoning over tools in a multi-step process, moving beyond single-shot tool calling. | `LLM`, `Llamaindex`, `Multi-step Reasoning`, `OpenAI` | [Notebook Link](notebook/llamaindex_agent_reasoning_loop.ipynb) |
| **Building a Multi-Document Agent with Llamaindex** | Develop a multi-document agent using Llamaindex to intelligently navigate, summarize, and compare information across multiple research papers from arXiv. | `Llamaindex`, `Multi-Document Navigation`, `Summarization`, `Research Paper Comparison` | [Notebook Link](notebook/llamaindex_multi_document_agent.ipynb) |


## How to Use 🚀

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sanikamal/ai-agent-hub.git
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run notebooks**:
   Open the notebooks with Jupyter Notebook or JupyterLab to explore each agent's implementation.

## Contributing 🌟

Contributions are welcome! If you have suggestions or want to add your own AI agent projects, feel free to open an issue or submit a pull request.

## License 📢

This project is licensed under the [MIT License](LICENSE).
