# 🧠 Agent Exercise: Multi-Agent Content Creation Pipeline

This repository contains a hands-on exercise designed to help you build and run a multi-agent system using [CrewAI](https://github.com/joaomdmoura/crewai) inside a Jupyter Notebook. You’ll define agents, assign tasks, and execute an end-to-end content pipeline for marketing or communication strategy.

---

## 🧩 Problem Statement

You are building a **multi-agent content creation system** that will:

- Research a domain or topic
- Formulate a marketing or communication strategy
- Generate creative campaign ideas
- Write content or copy
- Review and approve outputs

---

## 📁 Repo Structure

```bash
.
├── agents.yaml               # Agent definitions (for reference)
├── tasks.yaml                # Task definitions (for reference)
├── exercise_marketing.ipynb  # Main notebook for the hands-on exercise
├── requirements.txt          # Python dependencies
├── .env_example              # Template for environment variables
├── Assets/                   # Supporting images and branding
└── README.md

```
⸻

## ⚙️ Setup Instructions

### ✅ Prerequisites
	•	Python 3.11 (recommended)
	•	pip or pipenv
	•	OpenAI, Serper, and Astra DB accounts

### 🏗️ Create Virtual Environment

#### Create and activate virtual environment
```
python3.11 -m venv .exenv
source .exenv/bin/activate  # For Unix/macOS
.exenv\Scripts\activate   # For Windows
```

#### 📦 Install Requirements

```
pip install -r requirements.txt
```

---

#### 🔐 Environment Variables

Create a .env file in the root of your project using .env_example as a template:

```
OPENAI_API_KEY=your-openai-key
SERPER_API_KEY=your-serper-api-key
```

Make sure the .env file is NOT checked into version control. The .gitignore already excludes it.

To automatically load environment variables, add this to your notebook or script:

```
from dotenv import load_dotenv
load_dotenv()
```

---

### 🚀 Running the Exercise

Launch the notebook:

```
jupyter notebook
```

Open exercise_marketing.ipynb and follow the instructions:

#### 🧪 Step-by-Step

1.	Define Agents - Add unique roles, goals, and backstories.

2.	Define Tasks - Use the Task class to describe the action and link it to the right agent.

3.	Run Your Crew - Use the Crew class to execute your agents.

---

### 💡 Tips for Success
	•	Set verbose=True to trace agent thinking
	•	Ensure agents and tasks are properly linked
	•	Use markdown in the notebook to annotate your decisions and learning
	•	Make each agent’s goal and task very clear and unique

--- 

### 🔗 References
	•	CrewAI GitHub
	•	Serper.dev

--- 
### 🙋‍♂️ Questions?

Feel free to raise issues or ping abhinav.kimothi.ds@gmail.com if you’re stuck during setup or want to extend the framework!

---



