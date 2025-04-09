# 🍷 Ensemble Machine Learning – Wine Quality Classification

**Author:** Prince  
**Date:** 04/09/2025

## 📌 Project Overview

This project explores ensemble machine learning methods to predict the quality of red wine based on 11 chemical features. The goal is to classify wine into **low**, **medium**, or **high** quality categories using models like Random Forest and AdaBoost.

## 🧠 Models Used

- **Random Forest (100 trees)**
- **AdaBoost (100 estimators)**

Each model was evaluated on:
- **Accuracy**
- **F1 Score**
- **Train-Test Performance Gap**
- **Confusion Matrix**

## 📊 Results Summary

| Model               | Test Accuracy | Test F1 | Accuracy Gap | F1 Gap |
|---------------------|---------------|---------|---------------|--------|
| Random Forest (100) | 88.75%        | 0.8661  | 11.25%        | 0.1339 |
| AdaBoost (100)      | 82.50%        | 0.8158  | 0.92%         | 0.0051 |

- Random Forest had the best raw performance but signs of overfitting.
- AdaBoost was more balanced and generalized better.

## 🔍 Key Takeaways

- Overfitting can lead to high scores but poor generalization.
- Smaller train-test gaps often mean a more stable model.
- Ensemble methods like AdaBoost are reliable out-of-the-box.

## 🛠️ Next Steps

If this were a competition, I would:
- Tune Random Forest to reduce overfitting
- Try Gradient Boosting or Voting Classifiers
- Address class imbalance with sampling or class weights
- Use cross-validation for more robust evaluation

## 📁 Files Included

- `ensemble-prince.ipynb` – Complete Jupyter notebook with code and explanations
- `winequality-red.csv` – Dataset from UCI
- (Optional) `README.md` – Project summary

## 📚 Dataset Source

UCI Machine Learning Repository:  
https://archive.ics.uci.edu/ml/datasets/Wine+Quality

---

### 🛠️ Set Up Virtual Environment

To create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate


## 📦 Python Requirements

To run this project, install the following packages:

- pandas 
- numpy== 
- matplotlib 
- scikit-learn

git clone <https://github.com/don4ye/applied-ml-prince>


