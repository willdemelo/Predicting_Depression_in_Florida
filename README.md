# Predicting_Depression_in_Florida
Using SimplyAnalytics' data by US county, I use a variety of machine learning methods to estimate rates of depression of counties in Florida, where they have not been recorded. To my knowledge, this data has not been recorded by anyone else. I draw from statistics on crime rates, health conditions, basic demographics, and more in my analysis.

I divide rates of depression in my testing data into quartiles and use multiple classification methods such as logistic regression, linear discriminant analysis, and random forest classifying. At the end, I use a function to tally each of the usable models' predictions, from which I can determine a rough estimate of each county's rates of depression. Relative to other counties, my models predict that the majority of Floridian counties would be in the third quartile of country-wide depressive rates, meaning that depression is more common than average in Florida.

To reproduce my code, please use my Jupyter notebook. Data for all of my variables can be found on SimplyAnalytics, utilizing the variables outlined in the codebook I've included in this repository.
