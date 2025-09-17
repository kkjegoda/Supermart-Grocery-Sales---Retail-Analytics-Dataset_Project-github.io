# Supermart-Grocery-Sales---Retail-Analytics-Dataset_Project-github.io


✅ Project Summary

This project is designed to help beginners and intermediate learners practice data analysis and machine learning using a grocery store dataset. 
It shows how you can explore sales data, clean it, and build a model to predict sales.


✅ What You’ll Learn

How to work with datasets using Python.

How to clean data and handle missing or duplicate values.

How to analyze data using graphs and charts.

How to build a simple machine learning model to predict sales.

How to interpret the results using metrics like Mean Squared Error (MSE) and R-squared (R²).


✅ Tools Used

Python for coding.

Libraries like pandas, numpy, matplotlib, seaborn, and sklearn.

You can also use Excel or SQL to explore the data.

✅ Dataset Description

It contains data about orders placed in a grocery delivery app.

The data includes:

Order ID

Customer name

Product category and sub-category

City and region

Order date

Sales, discount, and profit amounts

The dataset is fictional but reflects realistic scenarios from Tamil Nadu, India.

✅ Step-by-Step Process Explained

1️⃣ Import Libraries You first load libraries like pandas for data manipulation, matplotlib for plotting graphs, and sklearn for building models.

2️⃣ Load Data You load the dataset into a Python environment using pd.read_csv().

3️⃣ Data Preprocessing

Check for missing values and remove them.

Check for duplicates and remove them.

Convert order dates into proper date format and extract useful information like month, year.

Convert categories like “City” and “State” into numbers using label encoding so they can be used in models.

4️⃣ Exploratory Data Analysis (EDA)

You create charts to understand trends:

Boxplot of sales by category – which products sell more?

Line chart of sales over time – when do sales increase or decrease?

Heatmap of correlations – how features like discount and profit relate to sales.

5️⃣ Feature Selection

You choose important columns like Category, City, Discount, etc., as input for the model and Sales as the output you want to predict.

6️⃣ Split the Data

The data is divided into a training set (to teach the model) and a testing set (to check if it works).

7️⃣ Build and Train Model

You use Linear Regression to build a model that tries to predict future sales based on past data.

8️⃣ Evaluate Model

You calculate:

Mean Squared Error (MSE) – how much your predictions deviate from actual sales.

R² Score – how well the model explains the variations in sales (closer to 1 means better).

9️⃣ Visualize Results

You compare actual and predicted sales using scatter plots to see how accurate your model is.

🔟 Conclusion

The model works well but can be improved.

You can try advanced models like Random Forest or XGBoost.

The final goal is to use the model for real-time sales predictions.

✅ Takeaways

This is a beginner-friendly project with real-life applications.

It teaches you how to clean, analyze, and predict using data.

It’s a great way to build your data analytics skills and start working with machine learning models.


If you want, I can also:

✔ Summarize the steps with example code

✔ Help you set up the environment and run the project

✔ Create quizzes or exercises based on this dataset
