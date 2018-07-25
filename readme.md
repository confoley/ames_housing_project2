# Ames: Using Housing Data to Predict Price

This was the second project for the Data Science Immersive course at General Assembly in NYC. I completed this in week 3 of the course, and it was generally an exercise in using regression models with special attention to cross validation,  train-test split, and cleaning data.  

 I created a model to predict price based on a dataset on the housing stock of Ames, Iowa, a small midwestern town north of Des Moines that is home to Iowa State University. There were 81 columns with about an even split between categorical data and numerical data. Some of the columns, such as "Overall Quality," could be initially assumed to have a strong correlation with price, while other more obscure qualities such as "Garage Type" and "Masonry Veneer Type" occupied most of the columns. I only had a limited amount of time to complete this project, so efficiency was critical. My goal was to create a model that accurately predicted price without combing over every minute detail. Using Lasso Cross Validation, I selected the most important features and then transformed them with Polynomial Features. Much of the time spent on this project was handling missing data and using mapping or dummy variables to turn categorical data with string datatypes into numerical data. This project was a very important learning process, as much of what I did seems like second nature after completing the course. 

 This repository include:
 - The main jupyter notebook for the project
 - A folder with the data used

 Imports Used:
 - NumPy
 - Pandas
 - Patsy
 - Scikit-Learn
 - Matplotlib
 - Seaborn