# Tutorial 01 — Building a Perceptron

## 🎯 Objectives

- Build a Perceptron from scratch using NumPy
- Understand how weights and bias are updated
- Implement the Step Function as an activation function
- Load and preprocess the Iris dataset
- Train and evaluate the model

---

## 🧠 Concepts

**Perceptron Architecture**

```
Inputs → Weighted Sum (Σ) → Activation Function → Output
```

**Weight Update Rule**

```
Wi = Wi + ΔWi
ΔWi = η * (y − ŷ) * Xi
```

| Symbol | Meaning |
|--------|---------|
| `η` | Learning rate |
| `y` | Actual label |
| `ŷ` | Predicted label |
| `Xi` | i-th input feature |
| `Wi` | i-th weight |

---

## 📂 Files

| File | Description |
|------|-------------|
| `Tutorial_01.ipynb` | Main notebook — full walkthrough |

---

## ✅ Tasks Completed

- **Task 1** — Take manual input for 4 features and predict if the flower is Iris-setosa
- **Task 2** — Replace the Step Function with **Sigmoid** activation
- **Task 3** — Replace labels `1 / -1` with `1 / 0`

---

## 📊 Dataset

The [Iris Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data) — 150 samples, 4 features, 3 classes.
Binary classification: **Iris-setosa** vs. everything else.

---

## ▶️ How to Run

```bash
jupyter notebook Tutorial_01.ipynb
```

---

[← Back to Main](../README.md)
