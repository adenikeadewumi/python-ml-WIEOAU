# 🐍 Python for Machine Learning & Data Science
### A Complete, Interactive Learning Path for Beginners to Practitioners

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 🎯 Who Is This For?

This course is designed for:
- **Complete beginners** who have never written a line of Python
- **Self-taught developers** who want to fill gaps in their Python knowledge
- **Students** aiming to break into Data Science or Machine Learning
- **Analysts** who want to automate their work and build models

No prior programming experience required — just curiosity and persistence.

---

## 🗺️ Learning Path

```
PART 1 — PYTHON FOUNDATIONS
├── 00. Setup & Environment
├── 01. Python Basics (variables, types, operators)
├── 02. Data Structures (lists, dicts, sets, tuples)
├── 03. Control Flow (if/else, loops)
├── 04. Functions (def, args, lambdas, decorators)
├── 05. Object-Oriented Programming
├── 06. Modules & Packages
├── 07. File I/O & Working with Data Files
├── 08. Error Handling & Debugging
└── 09. Advanced Python (comprehensions, generators, context managers)

PART 2 — DATA SCIENCE STACK
├── 10. NumPy — Numerical Computing
├── 11. Pandas — Data Manipulation
├── 12. Matplotlib & Seaborn — Visualization
└── 13. Scikit-learn Intro — The ML Workflow

PART 3 — MACHINE LEARNING
├── 14. Core ML Algorithms
└── 15. Deep Learning (intro with Keras/TensorFlow)
```

---

## 📁 Repository Structure

```
python-ml-course/
│
├── README.md                    ← You are here
├── SETUP.md                     ← Installation guide
├── CONTRIBUTING.md              ← How to contribute
│
├── 00_setup/
│   └── 00_environment_check.ipynb
│
├── 01_python_basics/
│   ├── 01_variables_and_types.ipynb
│   └── exercises/
│       └── 01_exercises.ipynb
│
├── 02_data_structures/
│   ├── 02_data_structures.ipynb
│   └── exercises/
│       └── 02_exercises.ipynb
│
├── 03_control_flow/
│   ├── 03_control_flow.ipynb
│   └── exercises/
│       └── 03_exercises.ipynb
│
├── 04_functions/
│   ├── 04_functions.ipynb
│   └── exercises/
│       └── 04_exercises.ipynb
│
├── 05_oop/
│   ├── 05_oop.ipynb
│   └── exercises/
│       └── 05_exercises.ipynb
│
├── 06_modules_packages/
│   └── 06_modules_and_packages.ipynb
│
├── 07_file_io/
│   ├── 07_file_io.ipynb
│   ├── data/
│   │   └── sample.csv
│   └── exercises/
│       └── 07_exercises.ipynb
│
├── 08_error_handling/
│   └── 08_error_handling.ipynb
│
├── 09_advanced_python/
│   └── 09_advanced_python.ipynb
│
├── 10_numpy/
│   ├── 10_numpy.ipynb
│   └── exercises/
│       └── 10_exercises.ipynb
│
├── 11_pandas/
│   ├── 11_pandas.ipynb
│   └── exercises/
│       └── 11_exercises.ipynb
│
├── 12_visualization/
│   └── 12_visualization.ipynb
│
├── 13_ml_intro/
│   └── 13_ml_intro.ipynb
│
├── 14_ml_algorithms/
│   └── 14_ml_algorithms.ipynb
│
├── 15_deep_learning_intro/
│   └── 15_deep_learning_intro.ipynb
│
└── resources/
    └── RESOURCES.md             ← Curated further learning
```

---

## 🚀 Quick Start

### Option 1: Run Locally (Recommended)

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/python-ml-course.git
cd python-ml-course

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

### Option 2: Run in the Cloud (Zero Setup)

| Platform | Link | Notes |
|----------|------|-------|
| Google Colab | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/) | Free GPU access |
| Binder | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/) | No account needed |
| Kaggle Kernels | [kaggle.com](https://www.kaggle.com/) | Free GPU + datasets |

---

## 📚 Module Overview

| # | Module | Key Concepts | Exercises |
|---|--------|-------------|-----------|
| 00 | Setup | Installation, Jupyter, first cell | — |
| 01 | Python Basics | Variables, data types, operators, input/output | ✅ 10 exercises |
| 02 | Data Structures | Lists, tuples, dicts, sets | ✅ 12 exercises |
| 03 | Control Flow | if/elif/else, for/while, break/continue | ✅ 10 exercises |
| 04 | Functions | def, *args/**kwargs, lambdas, decorators | ✅ 12 exercises |
| 05 | OOP | Classes, inheritance, magic methods | ✅ 8 exercises |
| 06 | Modules | import, pip, virtual envs | — |
| 07 | File I/O | open(), csv, json, pathlib | ✅ 6 exercises |
| 08 | Error Handling | try/except, custom exceptions, logging | — |
| 09 | Advanced Python | Comprehensions, generators, context managers | ✅ 8 exercises |
| 10 | NumPy | Arrays, broadcasting, linear algebra | ✅ 10 exercises |
| 11 | Pandas | DataFrames, groupby, merging, cleaning | ✅ 12 exercises |
| 12 | Visualization | Matplotlib, Seaborn, Plotly basics | — |
| 13 | ML Intro | Train/test split, cross-validation, metrics | — |
| 14 | ML Algorithms | Linear/Logistic Regression, Trees, SVM, KNN | — |
| 15 | Deep Learning | Neural networks, Keras, CNNs intro | — |

---

## ⚠️ Topics Not Covered (With Resources)

These are important Python topics we don't cover deeply in this course. We've linked the best resources for each:

| Topic | Why It Matters | Resource |
|-------|---------------|----------|
| **Async / Await** | Concurrent I/O, web scraping at scale | [Real Python — Async IO](https://realpython.com/async-io-python/) |
| **Multithreading & Multiprocessing** | Parallel computing | [Python Docs — concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) |
| **Regular Expressions** | Text parsing and cleaning | [Regex101 + Python re docs](https://regex101.com/) |
| **Web Scraping** | Data collection | [BeautifulSoup Tutorial](https://realpython.com/beautiful-soup-web-scraper-python/) |
| **REST APIs** | Data ingestion | [requests library docs](https://requests.readthedocs.io/) |
| **SQL & Databases** | Structured data | [SQLite3 Tutorial](https://docs.python.org/3/library/sqlite3.html) |
| **Testing (pytest)** | Code reliability | [pytest docs](https://docs.pytest.org/en/stable/) |
| **Docker / Deployment** | Shipping ML models | [FastAPI + Docker tutorial](https://fastapi.tiangolo.com/deployment/docker/) |
| **MLOps & Experiment Tracking** | Production ML | [MLflow docs](https://mlflow.org/docs/latest/index.html) |
| **Natural Language Processing** | Text ML | [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1) |
| **Computer Vision** | Image ML | [PyTorch Vision Tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html) |
| **Time Series Analysis** | Forecasting | [Statsmodels docs](https://www.statsmodels.org/stable/tsa.html) |
| **Reinforcement Learning** | Advanced ML | [Spinning Up in RL](https://spinningup.openai.com/en/latest/) |

---

## 🤝 Contributing

Found a bug, typo, or want to add an exercise? See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

MIT License — free to use, share, and modify with attribution.

---

*Built with ❤️ for learners everywhere. Star ⭐ the repo if it helps you!*
