# Simple Linear Regression  
This project focuses on predicting salaries based on years of experience using Python. The dataset contains two columns: YearsExperience and Salary. The project demonstrates data analysis, visualization, and regression modeling. Using Pandas, the dataset is loaded, explored, and prepared. Seaborn and Matplotlib are used to create scatter plots and regression plots to visualize the relationship between experience and salary.

Two regression models are applied:

Linear Regression (degree 1):
Using np.polyfit(X, y, 1), a straight line is fitted to the data to model a linear relationship between experience and salary. The slope and intercept are calculated, and the model is used to predict salaries for new experience values.

Polynomial Regression (degree 3):
Using np.polyfit(X, y, 3), a cubic polynomial model is fitted to capture non-linear trends in the data. This helps compare linear and polynomial fits, showing how higher-degree models can better capture complex patterns in salary growth.

The project highlights:

Data visualization techniques

Regression modeling with NumPy

Prediction and comparison of different models

Understanding the impact of linear vs polynomial regression

It’s a hands-on example of using Python for data analysis, regression, and predictive modeling in a real-world scenario.
