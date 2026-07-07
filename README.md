# Machine Learning Specialization — Coursework

Personal repository collecting my work, labs, and assignments for the
**[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)**
by **DeepLearning.AI & Stanford Online**, taught by **Andrew Ng** on Coursera.

This is a hands-on, beginner-to-intermediate program covering the core ideas of modern
machine learning: supervised learning (regression and classification), neural networks,
and best practices for building models that generalize. All code is in Python using
NumPy, scikit-learn, TensorFlow/Keras, and Matplotlib, mostly inside Jupyter notebooks.

> **Work in progress.** Course 3 has not been completed yet and will be added later.
> The repository is updated as I progress through the specialization.

---

## Repository structure

```
Machine Learning Specialization Coursera/
├── Course 1 - Supervised Machine Learning/
│   ├── Week 1 - Introduction to Machine Learning/
│   ├── Week 2 - Regression with multiple input variables/
│   └── Week 3 - Classification/
├── Course 2 - Advanced Learning Algorithms/
│   ├── Week 1 - Neural Networks/
│   ├── Week 2 - Neural Network Training/
│   └── Week 3 - Advice for applying machine learning/
└── Course 3 - Unsupervised Learning, Recommenders, Reinforcement Learning/   (coming soon)
```

Each week folder contains the optional practice labs (`*_Lab*` notebooks), the graded
programming assignment, the helper modules provided by the course (`lab_utils_*.py`,
`utils.py`, `public_tests.py`, etc.), the shared Matplotlib style (`deeplearning.mplstyle`)
and any datasets under a `data/` subfolder.

---

## Course 1 — Supervised Machine Learning: Regression and Classification

Foundations of supervised learning: how to fit a model to data, measure its error, and
optimize it with gradient descent, for both continuous (regression) and categorical
(classification) targets.

**Week 1 — Introduction to Machine Learning**
Model representation, the cost function, and gradient descent for univariate linear
regression. Labs cover the Python/Jupyter environment, model representation, the cost
function, and running gradient descent.

**Week 2 — Regression with multiple input variables**
Multiple linear regression with NumPy vectorization, feature scaling and learning-rate
tuning, feature engineering and polynomial regression, and linear regression with
scikit-learn. Includes the graded **Linear Regression** assignment.

**Week 3 — Classification**
Logistic regression: the sigmoid function, decision boundaries, logistic loss, the cost
function and its gradient, classification with scikit-learn, and the problem of
overfitting together with regularization. Includes the graded **Logistic Regression**
assignment.

---

## Course 2 — Advanced Learning Algorithms

Neural networks and the practical judgement needed to make learning algorithms work well.

**Week 1 — Neural Networks**
Neurons and layers, forward propagation, and building a small network both in TensorFlow
and from scratch in NumPy (the "coffee roasting" example). Includes the assignment on a
neural network for handwritten-digit (binary) recognition.

**Week 2 — Neural Network Training**
Training neural networks in TensorFlow: activation functions (ReLU), Softmax and
multiclass classification, plus notebooks on derivatives and backpropagation. Includes the
multiclass digit-recognition assignment.

**Week 3 — Advice for applying machine learning**
Model evaluation and selection with train/validation/test splits, and diagnosing bias vs.
variance to decide what to improve next. Includes the corresponding graded assignment.

---

## Course 3 — Unsupervised Learning, Recommenders, Reinforcement Learning

*Not completed yet — this section and its folder will be added once I finish the course.*
Expected topics: clustering and anomaly detection, recommender systems (collaborative
filtering and content-based), and an introduction to reinforcement learning.

---

## Tech stack

Python · Jupyter Notebook · NumPy · pandas · Matplotlib · scikit-learn · TensorFlow / Keras

## Notes & credits

All course materials, datasets, and starter code belong to **DeepLearning.AI** and
**Stanford Online**. This repository stores my own solutions and lab work for learning and
reference purposes only.
