# COMPAS Recidivism Analysis

## Purpose of the Analysis
The purpose of this analysis is to examine the COMPAS recidivism dataset and understand how risk scores are assigned. The project investigates whether there are differences in risk predictions across demographic groups, particularly race, and evaluates the fairness of the model. A logistic regression model is used to analyze the relationship between risk scores and factors such as age, gender, prior offenses, and recidivism.

##️ Python Libraries Used
- pandas – for data manipulation and cleaning  
- numpy – for numerical computations  
- matplotlib – for data visualization  
- seaborn – for statistical visualizations  
- statsmodels – for logistic regression modeling  
- scikit-learn – for evaluation metrics such as confusion matrix  

## Instructions to Reproduce the Results

1. Clone the repository
git clone https://github.com/EasierJohn/Responsible-Machine-Learning-/upload/main

2. Install required libraries
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
4. Run the Python code in Jupyter Notebook

jupyter notebook Lecture_01_alignment.ipynb

Run all cells in the notebook to reproduce the results including:
- Data cleaning
- Logistic regression model
- Confusion matrix
- Fairness analysis by race

## Repository Contents

Lecture_01_alignment.ipynb – Python implementation of the analysis  
README.md – Project documentation

## Author
Prepared for a Responsible Machine Learning assignment analyzing fairness in recidivism prediction models.

