# 💡 Bayes to the Future: Predicting Heart Disease with Data!

Welcome to **MediMystery Labs**! In this project, we build a Bayesian Network to predict heart disease risk using a dataset of simulated patient records.

---

## 🧪 Project Overview

As a Data Detective, your mission is to:
- Clean and preprocess patient data (`heart_disease.csv`)
- Normalize key features using Min-Max scaling
- Build a **Bayesian Network** using the `pgmpy` library
- Train the model with **Maximum Likelihood Estimation**
- Use probabilistic inference to answer diagnostic queries

---

## 🧰 Tech Stack

- Python 🐍
- Pandas, NumPy, scikit-learn
- `pgmpy` for Bayesian Networks
- Matplotlib & NetworkX (for visualization)

---

## ▶️ How to Run

1. **Download** the following files from this repo:
   - `bayes_heart_predictor.ipynb`
   - `heart_disease.csv`

2. **Open the notebook** in Jupyter or VS Code

3. **Run each cell sequentially** to:
   - Clean the data
   - Build and train the Bayesian Network
   - Perform inference and display results

> ✅ No command-line setup needed!

---
## Bayesian Network
![image](https://github.com/user-attachments/assets/28195467-3e65-44c8-bfb4-225246165313)

## 🧠 Inference Results

### 1. P(target | age = 0.6)

| Target | Probability |
|--------|-------------|
| 0 (No disease) | 45.93% |
| 1 (Has disease) | **54.07%** |

---

### 2. P(chol | target = 1)

Top normalized cholesterol levels (given heart disease):

| Cholesterol (normalized) | Probability |
|--------------------------|-------------|
| 0.1621                   | 2.44%       |
| 0.1780                   | 2.44%       |
| 0.1941                   | 2.44%       |
| 0.2466                   | 2.44%       |

---

### 3. P(target | fbs = 1)

| Target | Probability |
|--------|-------------|
| 0 (No disease) | 48.89% |
| 1 (Has disease) | **51.11%** |

