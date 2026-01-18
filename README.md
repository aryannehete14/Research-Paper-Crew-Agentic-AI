# 📄 Multi-Agent IEEE Research Paper Generator

An **AI-driven multi-agent system** built using **LangChain** and **LangGraph** that automatically generates **IEEE-format research papers** from simple topic prompts.
The system coordinates multiple specialized agents to collaboratively produce structured, technical, and publication-ready academic content with minimal human intervention.

---

## 🚀 Project Overview

Writing research papers is time-consuming and requires strict adherence to formatting, structure, and academic tone. This project addresses that challenge by leveraging **agentic AI workflows** to automate the entire research paper generation pipeline.

Given a topic prompt, the system:

* Plans the paper structure
* Generates IEEE-style sections
* Ensures technical depth and coherence
* Maintains academic tone and formatting consistency

---

## 🧠 System Architecture

The system is built using a **graph-based multi-agent architecture**:

* **LangChain** → For LLM orchestration and tool integration
* **LangGraph** → For agent coordination and execution flow control

### 🔹 Core Agents

* **Planner Agent** – Defines paper outline and section flow
* **Abstract Agent** – Generates concise IEEE-style abstracts
* **Content Agents** – Draft Introduction, Methodology, Results, and Discussion
* **Formatting Agent** – Ensures IEEE structure and section consistency
* **Review Agent** – Improves clarity, coherence, and academic tone

Each agent performs a focused task and communicates via a directed graph, enabling modular and scalable execution.

---

## ✨ Key Features

* 🧩 **Multi-Agent Collaboration** using LangGraph
* 📝 **IEEE-Format Research Paper Generation**
* 🔄 **Graph-Based Execution Flow**
* 📚 **Structured Academic Writing** (Abstract, Introduction, Methodology, etc.)
* ⚙️ **Modular & Extensible Architecture**
* 🚀 **Minimal Prompt → Full Paper Output**

---

## 📂 Project Structure

```
├── Research_Paper_Crew_–_Agentic_AI.ipynb
├── README.md
├── requirements.txt
└── outputs/
    └── generated_papers/
```

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **LangGraph**
* **OpenAI / LLM APIs**
* **Jupyter Notebook**

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set environment variables**

```bash
export OPENAI_API_KEY="your_api_key_here"
```

4. **Run the notebook**

```bash
jupyter notebook
```

Open `Research_Paper_Crew_–_Agentic_AI.ipynb` and follow the cells.

---

## 🧪 Usage

1. Provide a **research topic prompt**
2. Execute the notebook cells
3. The system:

   * Creates a paper outline
   * Generates section-wise content
   * Outputs a structured IEEE-style research paper

---

## 📈 Example Input

```
"Blockchain-enabled AI systems for secure healthcare data management"
```

### Example Output

* Abstract
* Keywords
* Introduction
* Literature Review
* Methodology
* Results & Discussion
* Conclusion
* References (structured)

---

## 🎯 Use Cases

* Academic research assistance
* Research paper drafting
* IEEE conference preparation
* Student research projects
* Exploring agentic AI systems

---

## 🔮 Future Enhancements

* 📑 Automated citation generation (IEEE Xplore / Google Scholar)
* 🧠 Memory-enabled agents for long-term research context
* 🖨️ Direct PDF & LaTeX IEEE template export
* 🤖 Reviewer feedback & revision loop
* 🌐 Web-based UI interface

---

## 👤 Author

**Aryan Nehete**
Second-Year B.Tech Student
MIT Art, Design and Technology University

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute.

---


