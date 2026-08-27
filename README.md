# LocalBuka Case Study

This repository contains the solutions for the **LocalBuka Case Study**, featuring a restaurant recommendation system and an AI-powered conversational chatbot interface.

## Project Structure

```text
Local-Buka-Case-Study/
│
├── data/
│   └── restaurants.csv
│
├── task_1/
│   └── Recommender System.ipynb
│
├── task_2/
│   └── Chatbot.ipynb
│
├── requirements.txt
└── README.md
```

### Directory & File Descriptions

* **`data/`** — Contains `restaurants.csv`, the dataset used across the project.
* **`task_1/`** — Contains `Recommender System.ipynb`, which implements the restaurant recommendation system.
* **`task_2/`** — Contains `Chatbot.ipynb`, which implements the interactive AI food assistant.
* **`requirements.txt`** — Contains the Python dependencies required to run the notebooks.
* **`README.md`** — Project documentation and setup instructions.

---

## Prerequisites

Before running the project, ensure you have:

* Python **3.10+**
* Git
* Jupyter Notebook or JupyterLab
* A **Groq API key** for the chatbot in Task 2

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/debbie459/Local-Buka-Case-Study.git
cd Local-Buka-Case-Study
```

### 2. Create a Virtual Environment

Creating a virtual environment is recommended to keep the project's dependencies isolated.

#### Windows

```bash
python -m venv venv
.\venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Setup

The chatbot in **Task 2** requires a Groq API key to communicate with the language model.

### 1. Create `env.py`

Create a file named `env.py` in the project root or inside the `task_2/` directory, depending on the import path used in the notebook.

### 2. Add Your API Key

```python
api_key = "YOUR_GROQ_API_KEY_HERE"
```

> **Important:** Never commit your API key to GitHub. Add `env.py` to your `.gitignore` file.

Example:

```text
env.py
```

---

## How to Run the Project

Start Jupyter Notebook or JupyterLab from the project root:

```bash
jupyter notebook
```

Alternatively:

```bash
jupyter lab
```

---

## Task 1 — Restaurant Recommendation System

The first task implements a restaurant recommendation system using the provided restaurant dataset.

### Steps

1. Navigate to the `task_1/` directory.
2. Open `Recommender System.ipynb`.
3. Run the notebook cells sequentially.
4. Follow the prompts or outputs provided by the notebook to generate restaurant recommendations.

The notebook covers the data processing and recommendation logic used to produce relevant restaurant suggestions.

---

## Task 2 — AI-Powered Food Chatbot

The second task implements an AI-powered conversational food assistant using the Groq API.

### Steps

1. Navigate to the `task_2/` directory.
2. Open `Chatbot.ipynb`.
3. Ensure your Groq API key has been correctly configured in `env.py`.
4. Execute the notebook cells sequentially.
5. Continue running the cells until you reach the interactive chat loop.
6. Enter your food-related queries when prompted.
7. Type `quit` or `exit` to terminate the session.

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Sentence Transformers**
* **Groq API**
* **Natural Language Processing (NLP)**
* **Recommendation Systems**
* **Generative AI**

---

## Project Objectives

The LocalBuka Case Study demonstrates the implementation of two AI-driven solutions:

1. **Restaurant Recommendation System**
   Recommends restaurants based on relevant restaurant and user preference information.

2. **AI Food Assistant**
   Provides a conversational interface through which users can interact with an AI assistant to discover food and restaurant options.

---

## Repository

**GitHub:**
https://github.com/debbie459/Local-Buka-Case-Study.git

## License

This project was developed as part of the **LocalBuka Case Study**.
