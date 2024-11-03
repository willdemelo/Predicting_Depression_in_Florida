# Predicting_Depression_in_Florida
Using SimplyAnalytics' data by US county, I use a variety of machine learning methods to estimate rates of depression of counties in Florida, where they have not been recorded. To my knowledge, this data has not been recorded by anyone else. I draw from statistics on crime rates, health conditions, basic demographics, and more in my analysis.

## Project Overview
I divide rates of depression in my testing data into quartiles and use multiple classification methods to predict depresion in Florida. I use the following tests in my analysis:
  - Logistic Regresssion
  - Linear Discriminant Analysis
  - Gaussian Naive Bayes
  - K-Nearest Neighbors Classification
  - Support Vector Classification
  - Random Forest Classification

At the end, I use a function to tally each of the usable models' predictions, from which I can determine an estimate of each county's rates of depression. Relative to other counties, my models predict that the majority of Floridian counties would be in the third quartile of country-wide depressive rates, meaning that depression is more common than average in Florida. Although there is no data for me to use to compare my imputation to, my findings could perhaps function as a starting point for research on mental health in Florida.

To reproduce my code, please use my Jupyter notebook. Data for all of my variables can be found on SimplyAnalytics, utilizing the variables outlined in the codebook I've included in this repository.

## Resources
- **Editor Used:**  Jupyter Notebook
- **Python Version:** Python 3.11.5
### Sci-Kit Learn
  Sci-Kit Learn provides all of the necessary models I need to implement my analysis.
### Plotly
  Plotly helps with all of my visualizations, including the confusion matrices, line plots, and feature importance graphs I need.
### Numpy/Pandas
  Numpy and Pandas are needed for my data organization, and for sci-kit learn to function.
