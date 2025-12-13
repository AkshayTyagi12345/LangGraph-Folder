# 🧠 LangGraph Workflows – Sequential & Parallel Implementations

This repository contains hands-on projects using **LangGraph**, demonstrating how to build structured LLM applications with **stateful workflows, branching logic, parallel function execution, memory, and agents**.

It’s designed for developers and enthusiasts to learn LangGraph through practical examples.

**New Additions:** Parallel workflow notebooks include a **cricket batsman statistics workflow** and an **essay analysis workflow**, demonstrating concurrent node execution and partial state updates.

---

## 🚀 Project Files Overview

| File / Folder              | Description                                                                                                                                                                                                                                                   |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `1_sequential_graph.ipynb` | A Jupyter notebook demonstrating a **simple sequential workflow** using LangGraph. It shows how to define a state, create a node function calling an LLM (HuggingFace API), add nodes and edges to a graph, and execute the workflow to get the final result. |
| `parallel_graph/`          | Contains **parallel workflow notebooks**, including a cricket batsman statistics workflow and an essay analysis workflow, demonstrating concurrent node execution and partial state updates.                                                                  |
| `workflow_examples/`       | Placeholder for **real-world workflows** integrating LLM calls, tools, prompts, and memory.                                                                                                                                                                   |
| `state_management/`        | Placeholder for examples of **TypedDict state objects and passing state between nodes**.                                                                                                                                                                      |
| `agents/`                  | Placeholder for **multi-agent collaboration examples**.                                                                                                                                                                                                       |
| `memory/`                  | Placeholder for examples of **persistent memory and conversation history**.                                                                                                                                                                                   |

---

## 📁 Project Structure

```
langgraph-examples/
│── 1_sequential_graph.ipynb
│── parallel_graph/
│     ├── batsman_workflow.ipynb
│     └── essay_analysis_workflow.ipynb
│── workflow_examples/
│── state_management/
│── agents/
│── memory/
│── README.md
```

---

## 🔑 Key Concepts Demonstrated

* Sequential and parallel workflows
* Partial state updates
* Concurrent node execution
* Integration with LLMs (HuggingFace / OpenAI)
* Use of TypedDict for structured state
* Agent collaboration and memory management

---

## 📌 How to Run

1. Clone the repository:

```bash
git clone https://github.com/AkshayTyagi12345/LangGraph-Folder.git
```

2. Open the project in VS Code or Jupyter.

3. Install required packages (example):

```bash
pip install -r requirements.txt
```

4. Open any notebook (`.ipynb`) and execute cells sequentially.

   * Sequential workflow: `1_sequential_graph.ipynb`
   * Parallel workflows: `parallel_graph/batsman_workflow.ipynb` and `parallel_graph/essay_analysis_workflow.ipynb`

---

## 📖 Notes

* Parallel workflows demonstrate **state isolation**, meaning only modified attributes are sent as input to avoid unintended full-state updates.
* Jupyter notebooks are used for hands-on learning and experimentation.
