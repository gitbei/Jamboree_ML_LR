# Jamboree Admission Chance Prediction - Linear Regression Model

## Overview
This project involves building a linear regression model to predict the probability of admission to Ivy League colleges for Indian applicants. The project includes applying multiple linear regression techniques, validating assumptions of linear regression, and using regularization to optimize the model performance. This case study aims to provide actionable insights to Jamboree, an educational institution that helps students get admitted to top global colleges, by predicting admission chances based on features such as GRE scores, TOEFL scores, CGPA, and more.

## Project Structure
**Data Understanding:**- The dataset includes various features such as GRE Score, TOEFL Score, University Rating, SOP (Statement of Purpose), LOR (Letter of Recommendation), CGPA, and Research Experience.
The target variable is Chance of Admission (on a scale of 0-1), which is our continuous dependent variable for the regression model.

**Problem Statement:** - Predict the Chance of Admission for each applicant based on their academic and extra-curricular credentials.

## Model Development

1. Linear Regression Model - Built a standard multiple linear regression model using the features provided in the dataset. Formulated the regression equation using the OLS method.
2. Regularization- Applied Ridge (L2) regularization and Lasso (L1) regularization to avoid overfitting and improve model generalization. Compared performance with Ordinary Least Squares (OLS) regression, observing the impact of regularization on the model.
3. Error Metrics - Calculated common error metrics to evaluate model performance:
 - Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
 - R-Square and Adjusted R-Square
4. Validation of Linear Regression Assumptions:
- Multicollinearity Check: Used Variance Inflation Factor (VIF) to check for multicollinearity, ensuring that the independent variables are not too highly correlated.
- Residual Analysis: The mean of residuals is approximately zero, ensuring that the errors have zero mean.
- Homoscedasticity was checked to verify that residuals have constant variance.
- Normality of Residuals: Plotted a QQ plot and used KDE plots to check that residuals follow a normal distribution, ensuring model validity.
5. Model Comparison and Insights
Compared the performance of OLS regression and the regularized models (Lasso and Ridge). Noted that regularization helps in reducing the complexity of the model by penalizing larger coefficients, thus avoiding overfitting.

## Key Findings
Significance of Predictor Variables:
- GRE Score and CGPA were the most significant predictors of admission chances.
- Research experience and LOR also contributed positively but to a lesser extent.
- The university rating had a moderate impact.
- Model accuracy was 83% for training and 82% for testing data.
- Further Recommendations and Insights have provided as well. 
