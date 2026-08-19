# ML Specialization Notes

Notebooks from working through Andrew Ng's Machine Learning Specialization. Every function here is implemented and debugged by hand with NumPy/TensorFlow.

## Why this repo exists

Most people run the Coursera notebooks once and move on. I wanted to actually understand what every line does, so each notebook here is rebuilt from scratch, line by line, with my own bugs found and fixed along the way. If you look through the commit history, you'll see the debugging process too , that's intentional.

## Course 1: Supervised Machine Learning — Regression and Classification

| # | Notebook | What it covers |
|---|---|---|
| 1 | [Cost Function](course1-supervised-ml/week_1/cost_function_lab.ipynb) | Implementing the cost function for single-variable linear regression |
| 2 | [Gradient Descent](course1-supervised-ml/week_1/C1_W1_Lab04_Gradient_Descent.ipynb) | Automating parameter optimization instead of guessing w and b manually |
| 3 | [NumPy & Vectorization](course1-supervised-ml/week_2/C1_W2_Lab01_Python_Numpy_Vectorization.ipynb) | Vectors, matrices, indexing, slicing, and the dot product |
| 4 | [Multiple Variable Regression](course1-supervised-ml/week_2/C1_W2_Lab02_Multiple_Variable.ipynb) | Extending regression to multiple features using np.dot |
| 5 | [Feature Scaling & Learning Rate](course1-supervised-ml/week_2/C1_W2_Lab03_Feature_Scaling_and_Learning_Rate.ipynb) | Why mismatched feature scales break gradient descent, and how z-score normalization fixes it |
| 6 | [Feature Engineering & Polynomial Regression](course1-supervised-ml/week_2/C1_W2_Lab04_FeatEng_PolyReg.ipynb) | Fitting curves (even a cosine wave) with plain linear regression by engineering polynomial features |
| 7 | [Scikit-Learn Gradient Descent](course1-supervised-ml/week_2/C1_W2_Lab05_Sklearn_GD.ipynb) | Reproducing the hand-built regression pipeline using scikit-learn's SGDRegressor and StandardScaler |
| 8 | [Classification Intro](course1-supervised-ml/week_3/C1_W3_Lab01_Classification.ipynb) | Contrasting regression vs classification, and why linear regression fails on categorical data |
| 9 | [Sigmoid Function](course1-supervised-ml/week_3/C1_W3_Lab02_Sigmoid_Function.ipynb) | Implementing the sigmoid function and combining it with linear regression to build logistic regression |
| 10 | [Decision Boundary](course1-supervised-ml/week_3/C1_W3_Lab03_Decision_Boundary.ipynb) | Deriving and plotting the line where a logistic regression model switches its prediction |
| 11 | [Logistic Loss](course1-supervised-ml/week_3/C1_W3_Lab04_LogisticLoss.ipynb) | Why squared error breaks with sigmoid, and building the logistic loss function that fixes it |
| 12 | [Logistic Cost Function](course1-supervised-ml/week_3/C1_W3_Lab05_Cost_Function.ipynb) | Full multi-feature logistic regression cost function, comparing two candidate decision boundaries |
| 13 | [Gradient Descent for Logistic Regression](course1-supervised-ml/week_3/C1_W3_Lab06_Gradient_Descent.ipynb) | Gradient descent for logistic regression, decision boundary visualization, cost function surface |
| 14 | [Logistic Regression with Scikit-Learn](course1-supervised-ml/week_3/C1_W3_Lab07_Scikit_Learn_logistic_regression.ipynb) | Logistic regression using scikit-learn — fit, predict, score |
| 15 | — | Overfitting (interactive Coursera widget lab, no code to rebuild — skipped) |
| 16 | [Regularization](course1-supervised-ml/week_3/C1_W3_Lab09_Regularization.ipynb) | Regularized cost and gradient for both linear and logistic regression |

Course 1 is complete.

## Course 2: Advanced Learning Algorithms

| # | Notebook | What it covers |
|---|---|---|
| 1 | [Neurons and Layers](course2-advanced-learning-algorithms/week_1/C2_W1_Lab01_Neurons_and_Layers.ipynb) | Building TensorFlow/Keras neurons that mirror Course 1's linear and logistic regression models |

Currently in progress: Course 2, Week 1.

## Stack

Python · NumPy · Matplotlib · Jupyter Notebook · scikit-learn · TensorFlow · Keras

## Running locally

```bash
git clone https://github.com/Abdullahjaved-82/ml-specialization-notes.git
cd ml-specialization-notes
jupyter notebook
```

These are my own implementations of concepts taught in the course, not copies of the official solutions.
