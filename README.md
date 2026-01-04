# 📈 Simple Linear Regression – Salary Prediction

This project demonstrates the implementation of **Simple Linear Regression** using Python to predict an employee’s salary based on their years of experience. It serves as a beginner-friendly introduction to regression analysis, model training, visualization, and evaluation.

---

## 🎯 Objective
- Load and explore the dataset  
- Split the data into training and testing sets  
- Train a Simple Linear Regression model  
- Visualize the regression line  
- Evaluate the model using R² score  

---

## 📂 Dataset
**File:** `Salary_Data.csv`  

| Column          | Description                  |
|-----------------|------------------------------|
| YearsExperience | Years of work experience     |
| Salary          | Annual salary (in USD)       |

- Total records: **30**  
- No missing values  
- Numerical continuous data  

---

## 🛠️ Tools & Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🔎 Methodology
1. Import required libraries  
2. Load and analyze the dataset  
3. Separate independent (YearsExperience) and dependent (Salary) variables  
4. Split data into training (80%) and testing (20%) sets  
5. Train the Simple Linear Regression model  
6. Predict salary values  
7. Visualize training and testing results  
8. Evaluate model performance using R² score  

---

## 📊 Model Equation
𝑆𝑎𝑙𝑎𝑟𝑦 = 26780.10 + 9312.58 × 𝑌𝑒𝑎𝑟𝑠 𝐸𝑥𝑝𝑒𝑟𝑖𝑒𝑛𝑐𝑒

---

## 📈 Model Performance
R² Score: 0.988

---

## 📁 Project Structure
Salary_Prediction/
├── Salary_Data.csv
├── simple_linear_regression.py
└── README.md

---

## ✅ Conclusion
The Simple Linear Regression model effectively predicts salary based on years of experience with high accuracy. This project highlights the fundamentals of regression analysis, model training, visualization, and evaluation.

Explains 98.8% of the variation in salary

Indicates a very strong linear relationship between experience and salary
