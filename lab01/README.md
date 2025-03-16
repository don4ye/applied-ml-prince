# 🏡 Machine Learning Lab 1: Linear Regression  

📌 **GitHub Repo:** [Applied ML Prince](https://github.com/don4ye/applied-ml-prince)  
👤 **Author:** Prince  
📅 **Date:** 03/11/2025  
🎯 **Objective:** Predict California house prices using **Median Income (`MedInc`)** and **Average Rooms (`AveRooms`)**.

---

## 📂 Project Overview  

Businesses and organizations often need to understand relationships between different factors to make better decisions.  
Regression analysis helps identify and quantify these relationships, providing insights for **forecasting and decision-making**.  

This project demonstrates **regression modeling techniques** applied to a real-world dataset:  
✅ **Dataset:** **California Housing Prices** (Scikit-learn's `fetch_california_housing`)  
✅ **Goal:** Predict home values based on features like **income level** and **average rooms per household**.  

---

## 🚀 Steps Followed  

✅ **1. Load & Explore Dataset**  
✅ **2. Data Visualization (Histograms, Boxplots, Scatter Plots)**  
✅ **3. Feature Selection (`MedInc` and `AveRooms`)**  
✅ **4. Train/Test Split (80% Training, 20% Testing)**  
✅ **5. Train a Linear Regression Model**  
✅ **6. Evaluate Performance (R², MAE, RMSE)**  
✅ **7. Save the Trained Model (`linear_regression_model.pkl`)**  

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

## 📌 Dataset  

### **California Housing Dataset**  
We use the built-in **Scikit-learn dataset**:  

```python
from sklearn.datasets import fetch_california_housing

data = fetch_california_housing(as_frame=True)
data_frame = data.frame


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
.
