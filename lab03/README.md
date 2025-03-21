# 🚢 Lab 3: Predicting Titanic Survival with Machine Learning  
**Author:** Prince  
**Course:** Applied Machine Learning  
**Date:** March 2025  

## 📌 Overview  
In this lab, I explored different machine learning classification models to predict survival on the Titanic. The dataset includes various features about the passengers, such as age, fare, family size, and whether they were traveling alone.

Three models were trained and evaluated:  
- **Decision Tree**
- **Support Vector Machine (SVM)**
- **Neural Network (MLPClassifier)**  

Each model was tested using different feature combinations to assess performance, accuracy, and generalizability.

---

## 📂 Dataset  
The Titanic dataset was loaded directly from the `seaborn` library. Missing values were handled, categorical variables were encoded, and feature engineering was applied to create meaningful new features such as `family_size`.

---

## 📌 Model Performance Summary
This project evaluates multiple classification models to predict Titanic survival using different feature sets. The models compared include Decision Trees, SVM (with different kernels), and a Neural Network (MLP). Below is a summary of their performance:

| Model Type                 | Accuracy | Precision | Recall  | F1-Score |
|----------------------------|----------|-----------|---------|----------|
| **Decision Tree**          | 71.51%   | 62.64%    | 77.03%  | 69.09%   |
| **SVM (RBF Kernel)**       | 65.92%   | 76.00%    | 25.67%  | 38.38%   |
| **SVM (Linear Kernel)**    | 78.21%   | 75.36%    | 70.27%  | 72.73%   |
| **SVM (Poly Kernel)**      | 62.01%   | 75.00%    | 12.16%  | 20.93%   |
| **SVM (Sigmoid Kernel)**   | 60.89%   | 52.94%    | 48.65%  | 50.70%   |
| **Neural Network (MLP)**   | 79.33%   | 77.61%    | 70.27%  | 73.76%   |


## ⚙️ Models & Evaluation  
The dataset was split using `StratifiedShuffleSplit` to maintain class balance. For each model, I used the following cases:

- **Case 1**: Single feature – `age`  
- **Case 2**: Single feature – `fare`  
- **Case 3**: Combined features – `age` and `fare`  

Performance was evaluated using **accuracy**, **precision**, **recall**, and **f1-score**.

---

## 📊 Results Summary

| Model Type           | Case   | Features Used     | Accuracy | Precision | Recall | F1-Score | Notes |
|----------------------|--------|-------------------|----------|-----------|--------|----------|-------|
| SVM (RBF Kernel)     | Case 1 | age               | 61.00%   | 83.00%    | 07.00% | 12.00%   | -     |
| SVM (RBF Kernel)     | Case 2 | fare              | 65.00%   | 75.00%    | 24.00% | 37.00%   | -     |
| SVM (RBF Kernel)     | Case 3 | age + fare        | 65.00%   | 74.00%    | 23.00% | 35.00%   | -     |

> 💡 Additional models like Decision Tree and MLPClassifier were also implemented and compared during the notebook stages.

---

## 🧠 Reflections

- **Best Performing Features**: Fare combined with age performed slightly better.
- **Surprising Insight**: The model performed well in predicting who did *not* survive, but struggled with survivors.
- **Model Comparison**: SVM was better at handling non-linear data compared to the decision tree, which tended to overfit.

---

## 🔍 Final Thoughts

- Missing values, especially in age and embarkation features, needed proper handling.
- SVM showed better margin classification, but required careful tuning.
- Neural Network added complexity without a major boost in accuracy.
- Future improvements could involve adding more features or tuning hyperparameters.

---

## 📁 Files in `lab03/`

- `ml03_prince.ipynb` – Main notebook with model development and evaluation  
- `README.md` – This documentation  
- `decision_tree_titanic.png` – Saved decision tree visualization  

## 🔗 How to Use this Project
1. **Clone this repository**
git clone <https://github.com/don4ye/applied-ml-prince/tree/main>

2. **Install dependencies**
pip install -r requirements.txt

3. **Run the Jupyter Notebook to explore results.**