# ML Specialization Notes

Personal notebooks, notes, and implementations built while working through the **Machine Learning Specialization** (Supervised Machine Learning: Regression and Classification). Every notebook here is written and understood line-by-line — no black-box copy-pasting.

## About

This repo tracks my hands-on practice with core machine learning fundamentals — implementing algorithms like cost functions and gradient descent from scratch using NumPy and Matplotlib, rather than relying solely on high-level libraries. The goal is to build genuine intuition for how these models work under the hood before moving on to frameworks like scikit-learn and TensorFlow.

## Tech Stack

- **Python 3**
- **NumPy** — numerical computing and array operations
- **Matplotlib** — data visualization
- **Jupyter Notebook** — interactive development

## Progress

### Week 1 — Linear Regression Fundamentals

| Notebook | Topic | Status |
|---|---|---|
| [`C1_W1_Lab03_Cost_Function`](./week1/cost_function_lab.ipynb) | Implementing the cost function for linear regression | ✅ Complete |
| [`C1_W1_Lab04_Gradient_Descent`](./week1/C1_W1_Lab04_Gradient_Descent.ipynb) | Implementing gradient descent to automatically optimize model parameters | ✅ Complete |

More labs added as the course progresses.

## What I'm Learning

- How to translate mathematical notation (cost functions, partial derivatives) directly into working code
- Building intuition for how `w` (weight) and `b` (bias) parameters affect a linear model
- Implementing gradient descent manually — the update rule, learning rate, and convergence behavior
- Visualizing cost surfaces to understand *why* gradient descent works (convexity, the "bowl shape")
- Debugging real code — every bug in this repo was found and fixed by hand, not copy-pasted from a solution key

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

Requires Python 3, NumPy, and Matplotlib (all included with [Anaconda](https://www.anaconda.com/)).

## Note

These notebooks are my own independent implementations built while studying the concepts taught in Andrew Ng's Machine Learning Specialization on Coursera. They are not copies of the official course solutions.

---

*Currently working through: Course 1 — Supervised Machine Learning: Regression and Classification*
