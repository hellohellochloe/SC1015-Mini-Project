# SC1015-Mini-Project
# Contributors to Food Organic Waste Repository

## About
This is a mini project for SC1015. Our dataset is from Kaggle, https://www.kaggle.com/datasets/zvr842/global-pollution-by-counties. We will be going through the following: 
1. Data extraction
2. Data cleaning
3. Tackling imbalanced data (categorical)
4. Data analysis (univariate, bivariate, multivariate)
5. Conclusion

## Contributors 
Chloe Lee: Data extraction, Data analysis (univariate), Conclusion, Slides, Script, Video editing, Video recording, Researching for new analysis and prediction methods
Valen Tang: Data cleaning, Data analysis (bivariate), Conclusion, Slides, Script, Video editing, Video recording, Researching for new analysis and prediction methods
Zann Ang: Tackling imbalanced data, Data analysis (multivariate), Conclusion, Slides, Script, Video editing, Video recording, Researching for new analysis and prediction methods

## Problem Definition   
1. Contributing factors to high food organic waste levels
  - Gdp
  - Recycling percentage
  - Presence of national law
  - Presence of enforcement
2. Significance of identified factors contributing to high food organic waste levels
3. The most significant factor contributing to high food organic waste levels 

## Models 
1. Linear Regression   
2. Binary Classification  
3. Random Forest Regressor 

## Conclusion
1. GDP is the most significant factor contributing to high food organic waste levels. 
2. GDP has an inverse relationship with food organic wastage.

## Lessons learnt
1. Predicting NA values using linear regression and binary classification
2. Using stacked bar charts to check if there is a relationship between food organic waste and the categorical variables
3. Random Forest Regressor to conduct multivariate analysis across multiple variables (both numerical and categorical) simultaneously
4. Using F and probability (p) values to determine the significance of different factors in affecting a certain outcome (food organic waste)
5. Collaboration using GitHub and Jupyter Notebook    

## References
Predicting NA values using linear regression:  
https://plainenglish.io/blog/predict-missing-dataframe-values-with-an-ml-algorithm-717cd872f1a8 
 
Merging tables together: 
https://towardsdatascience.com/python-pandas-tricks-3-best-methods-4a909843f5bc 
 
Converting value of array into 1 and 0: 
https://www.w3schools.com/python/numpy/numpy_array_filter.asp 
 
Splitting the data into different range for stacked bar chart: 
https://stackoverflow.com/questions/45751390/pandas-how-to-use-pd-cut 
 
Plotting stacked bar chart: 
https://www.datasciencelearner.com/stacked-bar-graph-in-python-step/ 
 
Changing the Yes and No value into 1 and 0: 
https://www.geeksforgeeks.org/how-to-replace-values-in-column-based-on-condition-in-pandas/ 
 
Combining data into high and low waste: 
https://matplotlib.org/stable/gallery/lines_bars_and_markers/bar_stacked.html 
 
Comparing the significance of categorical variables against food organic waste: 
https://www.investopedia.com/terms/p/p-value.asp 
https://statisticsbyjim.com/anova/f-tests-anova/ 
https://www.statsmodels.org/stable/examples/notebooks/generated/interactions_anova.html 
 
Comparing the significance of numerical variables against food organic waste: 
https://www.statsmodels.org/dev/generated/statsmodels.regression.linear_model.OLS.html 
 
Randomforest: 
https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html 
 
Tolist function: 
https://www.educative.io/answers/what-is-the-array-tolist-function-in-python
