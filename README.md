

A collection of beginner-friendly LangChain projects demonstrating different chain architectures using the LangChain Expression Language (LCEL)

📌 Overview.

This repository contains practical implementations of common LangChain chain patterns:

- Simple Chain
- Sequential Chain
- Parallel Chain
- Conditional Chain

These examples showcase how to build AI workflows using prompts, language models, output parsers, branching logic, and parallel execution.

---

🚀 Technologies Used

- Python
- LangChain
- OpenAI GPT Models
- Anthropic Claude Models
- LCEL (LangChain Expression Language)
- Pydantic
- dotenv

---

📂 Project Structure

├── simple_chain.py
├── sequential_chain.py
├── parallel_chain.py
├── conditional_chain.py
└── README.md

---

1️⃣ Simple Chain

A basic LangChain pipeline that:

1. Accepts a topic as input
2. Sends it to an LLM
3. Generates 5 interesting facts
4. Parses and displays the output

Concepts Covered

- PromptTemplate
- ChatOpenAI
- StrOutputParser
- LCEL Pipe Operator ("|")

---

2️⃣ Sequential Chain

Demonstrates chaining multiple LLM calls together.

Workflow

1. Generate a detailed report on a topic
2. Pass the generated report to another prompt
3. Create a concise 5-point summary

Concepts Covered

- Sequential Processing
- Output Chaining
- Multi-Step AI Workflows

---

3️⃣ Parallel Chain

Demonstrates running multiple tasks simultaneously.

Workflow

- Generate notes from a given text
- Generate quiz questions from the same text
- Merge both outputs into a final document

Concepts Covered

- RunnableParallel
- Multi-Model Execution
- OpenAI + Claude Integration
- Parallel Processing

---

4️⃣ Conditional Chain

Demonstrates dynamic branching based on model output.

Workflow

1. Classify user feedback as Positive or Negative
2. Route execution to the appropriate response generator
3. Produce a context-aware reply

Concepts Covered

- RunnableBranch
- Sentiment Classification
- PydanticOutputParser
- Conditional Logic in LangChain

---

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/langchain-chains.git
cd langchain-chains

Install dependencies:

pip install -r requirements.txt

Create a ".env" file:

OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key

---

▶️ Running Examples

Simple Chain:

python simple_chain.py

Sequential Chain:

python sequential_chain.py

Parallel Chain:

python parallel_chain.py

Conditional Chain:

python conditional_chain.py

---

🎯 Learning Outcomes

Through these projects, I learned:

- LangChain fundamentals
- LCEL syntax and pipelines
- Prompt engineering
- Output parsing
- Sequential workflows
- Parallel execution
- Conditional routing
- Multi-model orchestration

---

📚 References

- LangChain Documentation
- OpenAI API
- Anthropic API

---

👨‍💻 Author

Muhammad Saad Bin Zubair

Final Year Artificial Intelligence Student

Passionate about:

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- NLP
- AI Agents
- Generative AI

If you found this repository useful, feel free to star ⭐ the project.
