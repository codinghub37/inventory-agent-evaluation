
# 📦 Inventory AI Agent with LangSmith Evaluation

An AI-powered Inventory Agent that answers inventory-related queries using **LangChain**, **Groq LLM**, and **tool calling**. The project also demonstrates **LangSmith evaluation**, measuring response quality through semantic similarity with Sentence Transformers.

---

## 🚀 Features

- AI-powered inventory assistant
- Tool calling for inventory lookup
- Inventory status retrieval
- Out-of-scope query handling
- LangSmith dataset creation
- Automated agent evaluation
- Semantic similarity scoring
- Response quality assessment

---

## 🛠️ Tech Stack

- Python
- LangChain
- Groq LLM
- LangSmith
- Sentence Transformers
- NumPy
- Python Dotenv

---

## 📁 Project Structure

```text
inventory-agent-evaluation/
│── inventory_agent.py
│── func_eval.py
│── utils.py
│── requirements.txt
│── .env
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/codinghub37/inventory-agent-evaluation.git
```

### Navigate to the Project

```bash
cd inventory-agent-evaluation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file and add your API keys.

```env
GROQ_API_KEY=your_groq_api_key
LANGCHAIN_API_KEY=your_langsmith_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=inventory-agent-evaluation
```

---

## ▶️ Run the Inventory Agent

```bash
python inventory_agent.py
```

---

## ▶️ Run the Evaluation

```bash
python func_eval.py
```

---

## 📚 Workflow

1. User asks an inventory-related question.
2. LangChain Agent invokes the inventory tool.
3. The tool retrieves product stock information.
4. Groq LLM generates a concise response.
5. LangSmith evaluates the agent using predefined examples.
6. Sentence Transformers calculate semantic similarity between expected and generated responses.

---

## 💡 Applications

- AI Inventory Management
- Warehouse Assistants
- Customer Support Automation
- Tool Calling Agents
- Agent Evaluation
- LLM Performance Testing

---

## 📊 Evaluation Metrics

- Semantic Similarity
- Response Accuracy
- Tool Calling Validation
- Automated Benchmarking with LangSmith
