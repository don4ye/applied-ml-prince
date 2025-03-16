---

# Breast Cancer Prediction  

## Project Overview  
This project analyzes the **Breast Cancer dataset** to predict whether a tumor is **benign (non-cancerous) or malignant (cancerous)**.  
We clean the data, perform exploratory data analysis (EDA), and train a **Logistic Regression model** for classification.  

## Steps in This Project  

### **1️⃣ Data Exploration and Cleaning**  
- Checked for **missing values** (none found).  
- Selected **key tumor features** for prediction.  

### **2️⃣ Data Visualization**  
- Used **histograms, scatter plots, and box plots** to explore feature distributions.  
- Compared tumor characteristics between **benign and malignant cases**.  

### **3️⃣ Feature Selection and Model Training**  
- Chose **mean radius, mean texture, mean perimeter, mean area, and mean smoothness** as input features.  
- Used **train_test_split()** and **StratifiedShuffleSplit()** to split the data properly.  
- Trained a **Logistic Regression model** to predict tumor type.  

### **4️⃣ Model Evaluation**  
- Achieved **93% accuracy** on test data.  
- Analyzed **precision, recall, and F1-score** for both tumor classes.  
- Used a **confusion matrix** to check misclassifications.  

## Key Insights  
- **Larger tumors** tend to be malignant.  
- **Some features clearly separate benign and malignant cases.**  
- **Precision & recall were both high**, meaning the model is reliable.  

## How to Run This Project  
1. Clone this repository:  
   ```bash
   git clone <https://github.com/don4ye/applied-ml-prince>
   
  
