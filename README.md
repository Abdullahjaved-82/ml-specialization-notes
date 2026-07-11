# ML Specialization Notes

Notebooks and notes from working through the Machine Learning Specialization (Supervised Machine Learning: Regression and Classification). Everything here is implemented and understood line by line — no copy-pasted solutions.

## About

This repo tracks my practice building core ML algorithms from scratch using NumPy and Matplotlib, before moving on to higher-level libraries like scikit-learn. The focus is on actually understanding how cost functions and gradient descent work under the hood, not just running someone else's code.

## Tech Stack

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

## Progress

### Week 1 — Linear Regression Fundamentals

| Notebook | Topic | Status |
|---|---|---|
| [`cost_function_lab`](./week1/cost_function_lab.ipynb) | Implementing the cost function for linear regression | Complete |
| [`C1_W1_Lab04_Gradient_Descent`](./week1/C1_W1_Lab04_Gradient_Descent.ipynb) | Implementing gradient descent to optimize model parameters | Complete |

More labs get added here as I finish them.

## What I'm Learning

- Translating math notation (cost functions, partial derivatives) directly into working code
- How `w` and `b` affect a linear model's predictions
- Implementing gradient descent manually — update rule, learning rate, convergence
- Visualizing cost surfaces to understand why gradient descent actually works
- Debugging real code, including my own mistakes along the way

## Repository Structure

```
ml-specialization-notes/
├── README.md
├── .gitignore
└── week1/
    ├── cost_function_lab.ipynb
    └── C1_W1_Lab04_Gradient_Descent.ipynb
```

## Running These Notebooks

```bash
git clone https://github.com/Abdullahjaved-82/ml-specialization-notes.git
cd ml-specialization-notes
jupyter notebook
```

Needs Python 3, NumPy, and Matplotlib (all come with Anaconda).

These notebooks are my own implementations of the concepts taught in Andrew Ng's Machine Learning Specialization on Coursera, not copies of the official solutions.
