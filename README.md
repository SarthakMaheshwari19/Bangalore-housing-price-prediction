# Bangalore-housing-price-prediction

Problem Statement: 
Make a machine learning model for House Price prediction

Description: 
This Python code is a comprehensive machine learning project focused on predicting house prices in Bangalore using linear regression. It begins with data loading from a dataset containing various features of houses in Bangalore. The data cleaning process includes handling missing values, encoding categorical variables, and scaling numerical features. The EDA phase involves statistical analysis and data visualizations using libraries like Matplotlib and Seaborn to explore relationships between variables and identify important factors affecting house prices.
Instead of splitting the data into training and testing sets, this code utilizes k-fold cross-validation for model evaluation. The k-fold cross-validation technique partitions the data into k subsets, trains the model on k-1 subsets, and evaluates its performance on the remaining subset. This process is repeated k times, with each subset serving as the validation set once. The code includes steps for fitting a linear regression model, performing k-fold cross-validation to assess its predictive performance, and calculating evaluation metrics such as mean squared error.
By incorporating k-fold cross-validation, this code provides a robust approach to developing and evaluating a machine learning model for predicting house prices, enhancing its reliability and generalization capability for real-world applications in real estate analysis and investment decision-making.
