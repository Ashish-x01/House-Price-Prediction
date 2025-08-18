# House Value Estimation Using Ridge and Lasso Regression

This project focuses on predicting house prices using **Regularized Linear Regression models** — specifically **Ridge (L2)** and **Lasso (L1)** regression.  
Regularization helps to reduce overfitting by penalizing large coefficient values, making the model more robust and generalizable to unseen data.

---

##  Dataset Overview
The dataset contains information on various features affecting house prices. Key columns include:

- **lotsize**: Area of the plot in square feet  
- **bedrooms**: Number of bedrooms  
- **bathrms**: Number of bathrooms  
- **stories**: Number of floors  
- **garagepl**: Number of garages/parking spaces  
- **price**: Target variable (house price in INR)  

---

##  Technologies Used
- Python 3  
- NumPy, Pandas, Matplotlib, Seaborn  
- Scikit-learn (for Linear, Ridge, and Lasso Regression)  
- Jupyter Notebook 

---

##  Project Workflow

### 1. Data Preprocessing
- Dropped unnecessary index column  
- Standardized numerical features to bring all values to a comparable scale  

### 2. Model Training
- Implemented **Linear Regression (baseline)**  
- Applied **Ridge Regression (L2)**  
- Applied **Lasso Regression (L1)**  

### 3. Model Evaluation
- Used **MAE, MSE, and RMSE** to evaluate performance  
- Compared Ridge and Lasso with baseline Linear Regression  

### 4. Visualizations
- Distribution plots of features and target  
- Correlation heatmap to analyze feature relationships  

---

##  Conclusion
- Ridge and Lasso regression improved generalization compared to plain Linear Regression.  
- Ridge performed better in handling multicollinearity, while Lasso helped in feature selection by shrinking less important coefficients to zero.  
- Regularization proved effective in **reducing overfitting** and improving model reliability.  
