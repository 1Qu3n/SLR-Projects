## Simple Linear Regression Analysis of TV Marketing Data

**Overview**

This project investigates the relationship between TV advertising spending and product sales using a simple linear regression model. The analysis aims to understand and potentially predict the impact of TV advertising expenditure on sales outcomes.

**Kaggle Notebook**

* My analysis on Kaggle: https://www.kaggle.com/code/jaidasondi/tvmarketingprediction


**Data Dictionary**

* **TV:** TV advertising spend (in thousands of dollars)
* **Sales:** Number of units sold

**Methodology**

1. **Data Loading and Preparation:** The TV marketing dataset was loaded, and relevant columns were extracted.
2. **Exploratory Data Analysis (EDA):**  Visualizations (e.g., scatter plot) were used to examine the relationship between TV advertising and sales.
3. **Model Development:** A simple linear regression model was trained using Scikit-learn.
4. **Evaluation:** Performance metrics – including R-squared, RMSE, and MAE – were calculated to assess the model's fit.

**Results**

* **R-squared:** 0.7
* **RMSE:** 3.194
* **MAE:** 2.494

**Interpretation**

The model achieved a good fit, with 70% of the variance in sales explained by TV advertising spending. The RMSE and MAE indicate that, on average, the model's predictions deviate from actual sales by about $3.19 and $2.49, respectively.  These error levels should be evaluated within the specific business domain to determine acceptability.

**Future Plans**

* **Feature Engineering:** Incorporate additional factors (e.g.,  radio advertising, newspapers, promotions) to potentially improve the model's accuracy.
* **Model Exploration:**  Experiment with different regression models or ensemble techniques to see if performance can be further enhanced.
* **Advanced Visualization:**  Create more visualizations to analyze error patterns and identify areas for improvement.

