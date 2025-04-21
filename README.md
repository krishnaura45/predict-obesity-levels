<h1 align="left">predict-obesity-levels</h1>
Predicting obesity risk levels to support early intervention and cardiovascular disease prevention using machine learning<br>

### **Project Duration**: Feb 1, 2024 - Mar 1, 2024

## 🧠 Problem Statement
The aim is to classify individuals into different obesity risk categories based on multiple input features such as physical activity, eating habits, age, gender, and other health indicators. This challenge was hosted on Kaggle as part of **Playground Series - Season 4, Episode 2**. Submissions were evaluated based on the **accuracy score** .

---

## 🧩 Approach

You can explore the complete methodology in this notebook:
🔗 [PS4E2 - EDA LGBM XGB CAT Blend](https://github.com/krishnaura45/predict-obesity-levels/blob/main/ps4e2-eda-lgbm-xgb-cat-blend.ipynb)

Key steps followed:

- 📊 **Exploratory Data Analysis (EDA)**:
  - Assessed feature distributions and relationships.
  - Checked for outliers, imbalance, and preprocessing needs.

- 🧠 **Model Training**:
  - Trained three models independently: **LightGBM**, **XGBoost**, and **CatBoost**.
  - Tuned hyperparameters for optimized performance.

- 🔀 **Model Blending**:
  - Combined predictions using a **weighted average** strategy to boost performance.
  - Aimed to reduce individual model bias and variance.

---

## 🏆 Results / Outcomes

- ✅ **Public Leaderboard**:
  - Achieved **91.40%** and **91.54%** accuracy scores.

- 🏁 **Private Leaderboard**:
  - Best score of **90.89%** on final submission.

- 🥇 **Rank Achieved**:
  - Ranked **364 / 3746 participants** and **3587 teams**, as a **solo participant**.

---

## 🔗 References

- 📂 Kaggle Competition: [Multi-Class Prediction of Obesity Risk](https://www.kaggle.com/competitions/playground-series-s4e2)
- 📁 Dataset: [Data Info](https://www.kaggle.com/competitions/playground-series-s4e2/data)
- 📊 Data Source: [Obesity or CVD risk](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster)

---

## 🛠️ Tech Stack

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for visualization
  - `lightgbm`, `xgboost`, `catboost` for modeling
- **Tools**:
  - Jupyter Notebook 📓 for development and analysis
  - Colab/kaggle kernels

---

📌 *This project demonstrates the impact of ensemble modeling and feature understanding in achieving high performance on multi-class classification tasks in the health domain.*
