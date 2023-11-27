
# Salary Prediction Using Support Vector Regression (SVR)

## Overview
This project demonstrates the application of Support Vector Regression (SVR) to predict salaries based on job levels. It uses the `Position_Salaries.csv` dataset, containing job positions, their respective levels, and salaries. The primary goal is to train an SVR model to understand and predict salary structures based on the given data.

## Installation
To run this project, you need to have Python installed on your machine along with the following libraries:
- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries using pip:
```
pip install pandas numpy matplotlib scikit-learn
```

## Dataset
The `Position_Salaries.csv` file includes three columns:
- `Position`: The job title.
- `Level`: The numerical level or rank of the job.
- `Salary`: The salary for each job level.

## Usage
To run the project, follow these steps:
1. Clone the repository to your local machine.
2. Open `main.ipynb` in a Jupyter Notebook environment.
3. Run the cells in the notebook to see the process of data loading, preprocessing, model training, and salary prediction.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## Machine Learning Model
The project uses the Support Vector Regression (SVR) model from the `sklearn.svm` library. The SVR model is trained with a radial basis function (RBF) kernel to fit the salary data based on job levels.

---

For more information or queries, please open an issue in this repository.
