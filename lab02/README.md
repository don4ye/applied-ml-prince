# Titanic Survival Prediction  

## Project Overview  
This project analyzes the **Titanic dataset** to understand **what factors influenced survival rates**.  
We clean and explore the data, engineer useful features, and train a **Logistic Regression model** to predict survival.  

## Steps in This Project  

### **1️⃣ Data Exploration and Cleaning**  
- Checked for **missing values** and handled them properly.  
- Converted **categorical features to numbers** so the model could understand them.  
- Created **new features like `family_size`** to capture relationships in the data.  

### **2️⃣ Data Visualization**  
- Used **histograms, scatter plots, and count plots** to explore the dataset.  
- Compared survival rates by **passenger class, gender, and fare**.  

### **3️⃣ Feature Selection and Model Training**  
- Chose **age, fare, passenger class, sex, and family size** as input features.  
- Used **train_test_split()** and **StratifiedShuffleSplit()** to split the data properly.  
- Trained a **Logistic Regression model** to predict survival.  

### **4️⃣ Model Evaluation**  
- Measured model **accuracy** and checked its performance with a **confusion matrix**.  
- Analyzed **precision, recall, and F1-score** to see how well it predicted survival.  

## Key Insights  
- **Women and first-class passengers had much higher survival rates.**  
- **People traveling alone were less likely to survive.**  
- **Fare price played a role—higher-paying passengers had better chances.**  

## How to Run This Project  
1. Clone this repository:  
   ```bash
   git clone <https://github.com/don4ye/applied-ml-prince>
   
   
