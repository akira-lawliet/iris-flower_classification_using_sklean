# Iris Flower Classification Using Scikit-Learn

This project aims to build a simple machine learning model using the scikit-learn library to classify different species of iris flowers based on their features. The iris dataset is a well-known and widely used dataset in the field of machine learning, making it an excellent choice for beginners to get familiar with the concept of prediction models in Python.

## Libraries Used

1. **scikit-learn**: A powerful machine learning library for Python, used for data preprocessing, model training, and evaluation. In this project, we use the following modules from scikit-learn:
  - `datasets`: For loading the iris dataset.
  - `linear_model`: For importing the Linear Regression model.
  - `model_selection`: For splitting the dataset into training and testing sets.
  - `metrics`: For evaluating the performance of the model.

2. **pandas**: A library for data manipulation and analysis, providing data structures and data analysis tools. In this project, we use pandas for exploring and preprocessing the dataset.

3. **numpy**: A library for working with large multi-dimensional arrays and matrices, enabling efficient numerical operations. Numpy is used for converting the data into a suitable format for the machine learning model.

4. **seaborn** and **matplotlib**: Data visualization libraries used for creating informative and visually appealing plots and graphs. In this project, we use these libraries to visualize the dataset and the model's performance.

## Dataset

The iris dataset consists of 150 instances of iris flowers, with each instance described by four features:

1. Sepal Length (in cm)
2. Sepal Width (in cm)
3. Petal Length (in cm)
4. Petal Width (in cm)

The target variable is the species of iris flower, which can be one of the following:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The dataset is included in the scikit-learn library and can be loaded using the `datasets` module.

## Model

The iris flower classification problem is approached using a Linear Regression model from scikit-learn. Linear Regression is a supervised learning algorithm that models the relationship between a dependent variable (target) and one or more independent variables (features).

The linear regression equation is expressed as:

$$y = \beta_0 + \beta_1x_1 + \beta_2x_2 + \ldots + \beta_nx_n$$

Where:

- $y$ is the dependent variable (target)
- $x_1, x_2, \ldots, x_n$ are the independent variables (features)
- $\beta_0$ is the intercept (the value of $y$ when all $x$ values are zero)
- $\beta_1, \beta_2, \ldots, \beta_n$ are the coefficients (the effect of each independent variable on the dependent variable)

The model is trained on a subset of the dataset, and its performance is evaluated on the remaining data. The trained model can then be used to predict the species of a new iris flower based on its feature values.

## Getting Started

To run the project, you need to have Python and the required libraries installed. You can install the dependencies by running:
