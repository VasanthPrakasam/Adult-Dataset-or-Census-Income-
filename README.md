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

| Column Name       | Example Value   | Description                                                                             |
| ----------------- | --------------- | --------------------------------------------------------------------------------------- |
| `age`             | `39`            | Age of the individual                                                                   |
| `workclass`       | `State-gov`     | Type of employer (e.g., Private, Self-employed, Government)                             |
| `fnlwgt`          | `77516`         | Final weight – represents the number of people the census believes the entry represents |
| `education`       | `Bachelors`     | Highest level of education attained                                                     |
| `education-num`   | `13`            | Numerical representation of education level                                             |
| `marital-status`  | `Never-married` | Marital status                                                                          |
| `occupation`      | `Adm-clerical`  | Type of occupation/job                                                                  |
| `relationship`    | `Not-in-family` | Relationship to the head of the household                                               |
| `race`            | `White`         | Race of the individual                                                                  |
| `sex`             | `Male`          | Gender of the individual                                                                |
| `capital-gain`    | `2174`          | Capital gain from investment sources                                                    |
| `capital-loss`    | `0`             | Capital loss, if any                                                                    |
| `hours-per-week`  | `40`            | Average working hours per week                                                          |
| `native-country`  | `United-States` | Country of origin or citizenship                                                        |
| `income` (target) | `<=50K`         | **Target variable** – Does the person make more than \$50K per year?                    |


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
