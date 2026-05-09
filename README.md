# 🤖 Robotics & Deep Learning Tutorials

A collection of hands-on deep learning tutorials implemented from scratch in Python and Jupyter Notebook, covering foundational concepts in neural networks and machine learning.

---

## 📚 Tutorials

| # | Topic | Notebook | Concepts Covered |
|---|-------|----------|-----------------|
| 01 | Building a Perceptron | [`Tutorial_01.ipynb`](./Tutorial_01.ipynb) | Perceptron, Weighted Sum, Step Function, Weight Update Rule, Iris Classification |

> More tutorials coming soon!

---

## 🧠 Tutorial 01 — Building a Perceptron

A complete walkthrough of building a **Perceptron classifier from scratch** using NumPy, trained on the classic Iris dataset.

### What you'll learn
- How a Perceptron works (inputs → weighted sum → activation → output)
- How weights and bias are initialized and updated during training
- The **Step Function** as an activation function
- Loading and preprocessing the **Iris dataset**
- Splitting data into train/test sets
- Training and evaluating the model

### Key Formula — Weight Update Rule

```
Wi = Wi + ΔWi
ΔWi = η * (y − ŷ) * Xi
```

Where `η` is the learning rate, `y` is the actual label, `ŷ` is the predicted label, and `Xi` is the input feature.

### Tasks Completed
- ✅ **Task 1** — Manual input prediction (enter flower measurements, get a prediction)
- ✅ **Task 2** — Replaced Step Function with **Sigmoid** activation
- ✅ **Task 3** — Replaced labels `1 / -1` with `1 / 0`

---

## 🗂️ Repository Structure

```
Robotics_DL/
│
├── Tutorial_01.ipynb       # Perceptron from scratch
└── README.md
```

---

## ⚙️ Setup & Requirements

**Python 3.8+** is recommended.

Install dependencies:

```bash
pip install numpy pandas scikit-learn jupyter
```

Launch Jupyter:

```bash
jupyter notebook
```

---

## 📊 Dataset

The tutorials use the [Iris Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data) — 150 samples of iris flowers described by 4 features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The perceptron performs **binary classification**: *Iris-setosa* vs. everything else.

---

## 👩‍💻 Author

**Tasbiha Mirza**
[GitHub Profile](https://github.com/Tasbiha-mirza)
