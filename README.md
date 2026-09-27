# House Price Prediction

This is my first hands-on Machine Learning project. I build all by myself.

I used the **Ames Housing dataset** to build a model that predicts house prices based on different features of a house.

## What I did

* Loaded and explored the dataset
* Handled missing values
* Converted categorical data into numerical data
* Split the data into training and testing sets
* Standardized the features
* Trained a Linear Regression model
* Evaluated the model using MSE, RMSE and R²
* Used 6-Fold Cross-Validation

## Model

For this project, I used **Linear Regression** from Scikit-learn.

The model uses the available house features to learn the relationship between them and the final sale price.

## Results

My current results on the test set:

| Metric         |      Result |
| -------------- | ----------: |
| R²             |       0.816 |
| RMSE           |      30,617 |
| MSE            | 937,429,612 |
| Test Samples   |         586 |
| 6-Fold CV RMSE |      28,871 |

The R² score means the model explains around **81.6% of the variation in house prices** on my test data.

## Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Why I Made This

I made this project while learning Machine Learning and wanted to move beyond small practice datasets.

This project helped me understand the actual workflow of a regression problem, especially data cleaning, preprocessing, training, and evaluating a model.

## What's Next

I plan to improve this project as I learn more Machine Learning, including trying different regression algorithms and improving the preprocessing.

---

**This is a learning project and one of my first steps into Machine Learning.**
