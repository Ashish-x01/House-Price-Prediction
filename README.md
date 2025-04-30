House Value Estimation Using Regularized Linear Models

This project focuses on predicting house prices using "Regularized Linear Regression". Regularization helps 
to reduce overfitting by penalizing large coefficient values, thus making the model more robust and generalizable
to unseen data.

Dataset Overview

The dataset contains information on various features affecting house prices. Key columns include:

- `area`: Area of the house in square feet
- `bedrooms`, `bathrooms`: Number of rooms
- `stories`: Number of floors
- `parking`: Availability of parking
- `price`: Target variable (house price in INR)

Technologies Used:

- Python 3
- NumPy, Pandas, Matplotlib
- Custom implementation of Linear Regression with  Regularization ( gradient descent and normal equation)
- Google Colab for execution

Project Workflow

1. Data Preprocessing:

   - Encoded categorical features 
   - Normalized input features to bring all values to a comparable scale

2. Model Training:

   - Implemented "Regularized Linear Regression" using:
     - "Gradient Descent"
     - "Normal Equation"

3. Model Evaluation:

   - Trained the model for multiple values of λ (regularization parameter)
   - Calculated error for each λ to find the one with minimum prediction error

Visualizations:

- Error vs Lambda (Gradient Descent)
  Used to analyze how regularization strength impacts error

- Error vs Lambda (Normal Equation)
  Analytical comparison of error trend using a closed-form solution

Conclusion:
After applying regularized linear regression, we observed a clear reduction in prediction error. 
Tuning the lambda parameter helped in minimizing overfitting and improving accuracy.  It demonstrates
how regularization strengthens linear models.


