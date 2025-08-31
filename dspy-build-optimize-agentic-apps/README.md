# DSPy: Build and Optimize Agentic Apps

This respo demonstrates how to build **modular, traceable, and optimizable GenAI applications** using **DSPy**, a flexible open-source framework for agentic apps.

DSPy introduces a **signature-based programming model** and composable modules (e.g., `Predict`, `ChainOfThought`, `ReAct`) that simplify LLM application development. With built-in **MLflow tracing**, developers can debug and visualize program execution. The **DSPy Optimizer** further automates prompt tuning and few-shot learning, improving accuracy and consistency without manual prompt engineering.

---

## Key Features

* **Signature-Based Programming Model**
  Build modular, model-agnostic GenAI apps that are easier to extend and maintain.

* **Composable Agentic Modules**
  Chain together blocks like `Predict`, `ChainOfThought`, and `ReAct` to create multi-step reasoning systems.

* **Integrated Debugging with MLflow**
  Trace, visualize, and interpret DSPy program execution step-by-step.

* **Automated Optimization**
  Use DSPy Optimizer to improve prompts and few-shot examples, boosting task accuracy.

* **Flexible Model Switching**
  Swap LLM backends without rewriting application logic.

* **Robust Agent Development**
  Handle tasks such as classification, document automation, retrieval-augmented generation (RAG), and multi-step assistants.

---

## Notebooks

1. **DSPy Programming - Signatures and Modules**
2. **Debug Your DSPy Agent with MLflow Tracing**
3. **Optimizing Agents with DSPy Optimizer**
---

## Example Applications

* **Sentiment Classifier**
  Build a classifier in \~30 lines of DSPy code.

* **Name the Celebrity Game**
  Extend DSPy modules into an interactive multi-turn guessing game.

* **Travel Booking Assistant**
  Trace and debug the entire agent flow with MLflow.

* **Wikipedia RAG Agent**
  Use DSPy Optimizer to improve exact-match accuracy (e.g., from 31% → 54%) without hand-tuning.


## References

* **DSPy Framework:** [https://github.com/stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)
* **Databricks:** [https://databricks.com](https://databricks.com)
* **MLflow:** [https://mlflow.org](https://mlflow.org)
* **Course on Building and Optimizing Agentic Apps:** [https://www.deeplearning.ai/short-courses/building-and-optimizing-agentic-apps/](https://www.deeplearning.ai/short-courses/building-and-optimizing-agentic-apps/)