# hdb-resale-flat
This is a mini project for SC1015 where our group decided to analyse and predict HDB Resale Flat Prices.
The following python project consists of:
1. Exploratory Data Analysis
2. Data Cleaning
3. 3 Machine Learning Models
4. Conclusion

# Contributors:
  - @shamz-10: EDA, Data Cleaning, Linear Regression
  - @Maaxxx002: Decision Tree Regressor
  - @meoweyy: Random Tree Regressor

# Problem Definition:
How can we predict the prices of resale flat to help people decide if they want buy a resale flat? 

# Variables used to analyse:
- Location (North, South, East, West, Central)
- Storey range (Upper/Lower)
- Flat Type (1 Room...5 Room, Exec. Apt)
- Floor Area
- Remaining Lease

   

# Models used:
- Linear Regression
- Decision Tree Regressor
- Random Tree Regressor

# Conclusion
After analysing all 3 models, it was evident that the Random Forrest Regressor is the best model in predicting Resale Flat Prices. This is because it has the highest mean squared error amongst the 3 models. 

# Learning Points
1. Regression models to solve regression problem with supervised data
2. Tuning hyperparameters using Gridsearch and its nuances
3. Using new APIs for model display
4. Using appropriate measures for accuracy in Gridsearch
5. 

# References:
- Generic references to code parameters, plotting and EDA:
  - https://scikit-learn.org/stable/
- Linear regression:
  - https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
- Tuning hyperparameters:
  - https://towardsdatascience.com/how-to-tune-a-decision-tree-f03721801680#:~:text=The%20theoretical%20maximum%20depth%20a,one%20big%20reason%20being%20overfitting.
- Gridsearch:
  - https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
- Decision Tree Regressor:
  - https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html
- Dtreeviz:
  - https://github.com/parrt/dtreeviz/blob/master/README.md
- Installing python packages temporarily in Jupyter:
  - https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/

- Random Forest Regressor:
  - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
  - https://towardsdatascience.com/improving-random-forest-in-python-part-1-893916666cd
  - https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74

- Random Forest Improvements:
  - https://neptune.ai/blog/random-forest-regression-when-does-it-fail-and-why
- The Elements of Statistical learning: 
  - https://hastie.su.domains/Papers/ESLII.pd

