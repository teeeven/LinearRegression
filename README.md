# LinearRegression

The follwoing notebook is a workflow through building, testing, and using a Linear Regression model on MLB data to predict MLB's Runs Created as a target. 

  Runs Created estimates a player's offensive contribution in terms of total runs. 
  It combines a player's ability to get on base with his ability to hit for extra bases and therefore is a good measure of effectiveness in evaluating players output.

This notebook performs a brief exploratory analysis of data, notes, engineering of both numerical and categorical variables. 

The Linear Regression model built incorporates Ridge regularization:
  Ridge regularization, adds a penalty term equal to the square of the coefficients. 
  This technique tends to produce models with small but non-zero coefficients, which can be useful for reducing the impact of noisy or correlated features.
