# Supervised Regression California Housing Prediction
Created a supervised regression model to predict housing prices of cities/groups in California
- Extracted data from census.gov containing features for 2017 such as
    - Median House Value, Household Income Value, Various Race Populations, Various Age Group Populations, geolocation, etc
- Used RMSE as performance measure
- Visualized Data to gain Insights and to look for correlations
- Experimented with Attribute Combinations
- Prepared Data for Machine Learning Algorithms
- Cleaned the data
  - NAN values
  - Duplicates
- Transformation Pipelines
  - Created Custom Transformers
  - Feature Scaling
  - Separate Number Attributes
- Selected and Trained Model
  - Tested Linear Regression, Decision Tree, and Random Forest models
    - Evaluated with CrossValidation
  - Tuned Hyperparamters for optimal paramters
    - Stochastic Gradient Descent for Linear Regression
    - GridSearchCV and RandomizedSearchCV for Random Forest
   - Feature Engineering
  - Predicted CA housing prices on Test Set with a Random Forest Model with optimized hyperparamters via GridSearchCV
  
  
  Results:
    - Final RMSE: 173621.92240298502
    - Compared to test RMSE: 0.33797187945329926
    - Accuracy: 78.20%
    - Overfitted, will need to use more data to mitigate overgeneralization of data
    
    
    # Please Note
I used plotly but github performs a static render of the notebooks and it doesn't include the embedded HTML/JavaScript that makes up a plotly graph. If you'd like to see the dynamic graphs paste the link of any GitHub notebooks into http://nbviewer.jupyter.org/, which will present a rich view of the notebook.

Notebook Links:
https://github.com/M-Krilano/Supervised_Regression_Housing_Prediction/blob/master/CA_Median_Housing_Prediction.ipynb

    
