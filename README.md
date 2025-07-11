# 🧾 Adult Census Income Dataset – Predicting Annual Income (>50K)

This project uses the **UCI Adult Census Income dataset** to predict whether an individual earns **more than $50,000 per year** based on various demographic and employment-related features.

---

## 📌 Dataset Overview

This dataset contains information collected from the U.S. Census, including personal, professional, and socio-economic attributes.

### ✅ Use Case
To build a **binary classification model** that predicts:
> Whether an individual earns `>50K` or `<=50K` annually.

---

## 🧩 Columns Description

| Column Name       | Description                                      |
|-------------------|--------------------------------------------------|
| `age`             | Age of the individual                           |
| `workclass`       | Employment category (e.g., Private, Self-emp)    |
| `fnlwgt`          | Census-assigned weight                          |
| `education`       | Educational level (e.g., Bachelors, Masters)     |
| `education-num`   | Numerical form of education level                |
| `marital-status`  | Marital status (e.g., Married, Never-married)    |
| `occupation`      | Job category (e.g., Tech-support, Sales)         |
| `relationship`    | Role in family (e.g., Husband, Own-child)        |
| `race`            | Race category                                    |
| `sex`             | Gender                                           |
| `capital-gain`    | Investment profits                               |
| `capital-loss`    | Investment losses                                |
| `hours-per-week`  | Weekly work hours                                |
| `native-country`  | Country of origin                                |
| `income`          | **Target variable** (`<=50K` or `>50K`)          |

---

## 🎯 Objective

To develop a supervised classification model to **predict an individual's income level**, enabling applications in:
- Workforce analytics
- Socio-economic research
- Bias/fairness testing in ML models

---

## 🤖 Machine Learning Approach

- **Target variable:** `income` (`>50K`, `<=50K`)
- **Model type:** Supervised Classification
- **Encoding:** Label and One-Hot Encoding for categorical variables

---

## 📁 Files Included

- `adult.data` – Training dataset
- `adult.test` – Testing dataset
- `adult.names` – Column documentation
- `preprocessing.ipynb` – Data cleaning & encoding
- `modeling.ipynb` – Model training and evaluation

---

## 📊 Outcome

This dataset provides a strong foundation for exploring:
- Income prediction
- Feature importance
- Bias detection and fairness in machine learning
- End-to-end ML pipeline design

---
## 📚 Conclusion:
- This dataset is widely used for classification problems in supervised learning. 
- It is a great resource for building models that predict income levels based on education, occupation, and personal background. 
- It also serves as a benchmark dataset for bias detection, feature importance analysis, and fair AI modeling in real-world socio-economic contexts.
---

## 📚 Source

- UCI Machine Learning Repository:  
  [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult)

---
