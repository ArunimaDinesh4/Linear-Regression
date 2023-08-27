# Linear-Regression
Salary Prediction using linear regression

Predicting Salaries using Linear Regression
In this project, I aimed to predict salaries based on the years of experience of individuals. The dataset consists of two columns: 'YearsExperience' representing the years of experience and 'Salary' representing the corresponding salary values. 
To prepare the data for modeling, I employed the Min-Max Scaling technique using the MinMaxScaler from Scikit-Learn. This scaling transformed the 'YearsExperience' and 'Salary' values to a common scale within the range of 0 to 1. This step ensures that the features do not dominate the outcome due to differences in magnitude.

After splitting the data into training and testing sets, I utilized the Linear Regression algorithm to build a predictive model. The linear regression model establishes a linear relationship between the independent variable ('YearsExperience') and the dependent variable ('Salary').

Once the model was trained, I used it to make predictions on the test data. Subsequently, I employed several evaluation metrics to assess the performance of the model:

Mean Absolute Error (MAE): The MAE measures the average absolute difference between the predicted and actual salary values. A lower MAE indicates better performance.
Root Mean Squared Error (RMSE): The RMSE calculates the square root of the average squared differences between predictions and actual values. It provides an idea of the model's accuracy.
R-squared (R2) Score: The R2 score quantifies the proportion of the variance in salary that is explained by the 'YearsExperience' variable. A higher R2 score indicates a better fit of the model to the data.
My model achieved an R2 score of approximately 0.984, suggesting that around 98.4% of the variability in salary can be attributed to the variation in years of experience. This indicates a strong linear relationship between these variables.

In conclusion, this project demonstrates the application of linear regression for predicting salaries based on years of experience. The high R2 score underscores the model's effectiveness in capturing the relationship between the variables.
