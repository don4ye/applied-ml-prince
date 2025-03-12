# 🏡 Machine Learning Lab 1: Linear Regression  

📌 **GitHub Repo:** [Applied ML Prince](https://github.com/don4ye/applied-ml-prince)  
👤 **Author:** Prince  
📅 **Date:** 03/11/2025  
🎯 **Objective:** Predict California house prices using **Median Income (`MedInc`)** and **Average Rooms (`AveRooms`)**.

---

## 📂 Project Overview  

This project applies **Linear Regression** to predict housing prices based on two key features from the **California Housing Dataset** (provided by Scikit-learn).  
The dataset contains various **housing-related attributes**, including income levels and the number of rooms per household.

---

## 🚀 Steps Followed  

✅ **1. Data Loading & Exploration**  
✅ **2. Data Visualization (Histograms, Boxplots, Scatter Plots)**  
✅ **3. Feature Selection (`MedInc` and `AveRooms`)**  
✅ **4. Train/Test Split (80% Training, 20% Testing)**  
✅ **5. Model Training (Linear Regression)**  
✅ **6. Model Evaluation (R², MAE, RMSE)**  
✅ **7. Model Saving (`linear_regression_model.pkl`)**  

---

## 📊 Results  

📌 **Model Performance Metrics:**  

| Metric  | Value |
|---------|-------|
| **R² Score** | 0.46 |
| **Mean Absolute Error (MAE)** | 0.6247 |
| **Root Mean Squared Error (RMSE)** | 0.8379 |

- **R² = 0.46** → The model explains **46% of the variance** in house prices.  
- **Lower RMSE (0.84) and MAE (0.62)** indicate that predictions are somewhat close but can be improved.

---

## 🔧 How to Run This Project  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/don4ye/applied-ml-prince.git
cd applied-ml-prince

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt

### 3️⃣ Open Jupyter Notebook  
```bash
jupyter notebook

## 📁 Files Included  

| File | Description |
|------|------------|
| **ml01.ipynb** | Jupyter Notebook with all analysis and model training. |
| **linear_regression_model.pkl** | Saved trained model for future use. |
| **README.md** | This project documentation. |
| **requirements.txt** | List of required Python packages. |

## 🔗 GitHub Repository  

📌 **[Applied ML Prince](https://github.com/don4ye/applied-ml-prince)**
