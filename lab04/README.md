# 🚢 Titanic Fare Prediction – Regression Modeling

**Author:** Prince  
**Date:** 2025-04-01  
**Course:** Applied Machine Learning  
**Lab:** Lab 4 – Predicting a Continuous Target with Regression  

---

## 📘 Overview

This lab focuses on predicting **Titanic passenger fares** using regression techniques. The goal is to explore how different models perform when predicting a continuous variable, and how feature choices, regularization, and model complexity affect results.

The Titanic dataset is loaded from Seaborn and includes features like passenger age, gender, class, and fare. We apply multiple regression techniques to understand which combinations and approaches work best.

---

## 🎯 Objectives

- Use regression to predict a continuous target (`fare`)
- Compare different models (Linear, Ridge, Elastic Net, Polynomial)
- Evaluate models using RMSE, MAE, and R² metrics
- Visualize results and reflect on model behavior

---

## 📁 Project Structure

applied-ml-prince/
└── lab04/
    ├── ml04_prince.ipynb
    └── README.md  👈 This file


---

## ⚙️ Requirements

This project requires the following Python libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- markdown (optional for rendering)

### To install all at once:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn markdown

## 🧪 How to Run

- Open `ml04_prince.ipynb` in Jupyter Notebook or VS Code  
- Run each code cell in order  
- All outputs, plots, and reflections are included inline


## 📊 Feature Sets Used

- `age` – Passenger's age  
- `family_size` – Calculated as `sibsp + parch + 1`  
- `pclass` – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `sex_encoded` – Gender encoded as 0 (male) or 1 (female)

## 🧠 Models Compared

- **Linear Regression**  
- **Ridge Regression** (L2 regularization)  
- **Elastic Net** (L1 + L2 combination)  
- **Polynomial Regression** (Degrees 3 and 6)

## 📊 Performance Summary (Test Set Results)

| Model                          | R² Score | RMSE  | MAE   |
|-------------------------------|----------|--------|--------|
| Linear Regression             | 0.399    | 29.49  | 20.08  |
| Ridge Regression              | 0.400    | 29.47  | 20.05  |
| Elastic Net                   | 0.429    | 28.75  | 17.39  |
| Polynomial Regression (deg 3) | 0.506    | 26.72  | 15.05  |

✅ **Best Performance:** Polynomial Regression (Degree 3)  
🧠 **Best Regularized Fit:** Elastic Net

## 📈 Visualization – Polynomial Regression

### Degree 3  
Captured general trends in age vs fare

### Degree 6  
More flexible fit, captured subtle curves

## 🔗 GitHub Repository

[Click here to view the project on GitHub](https://github.com/don4ye/applied-ml-prince)


