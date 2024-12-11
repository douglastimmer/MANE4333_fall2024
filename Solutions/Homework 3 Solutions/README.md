# MANE 4333 - Data Science in Manufacturing

## Homework 3 Assignment: Simple Linear Regression

### Assigned: September 26, 2024
### Due: October 7, 2024

Your third homework assignment focuses on Simple Linear Regression. Please download the GitHub repository and work on your local computer. Once completed, please commit the changes and push your local repository back to the master repository.

Your Homework 3 Repository should contain the following files: train.csv, HomeworkThree.ipynb, and README.md (this file).

The first cell of the Jupyter Notebook is a Markdown cell that contains the title information for this assignment. Please edit the third heading and enter your name. 

The second cell is a code cell that contains code to load the data, describe the data and plots the data. This is a dataset that contains information about home saling prices. Note that the response variable (*y*) is SalePrice and the regressor variable (*x*) is GrLivArea.

---

#### Problem 1, Cell 3

Cell 3 is a Markdown cell. Review the scatter plot of GrLivArea versus SalePrice found in cell two. Does there appear to be any outlier(s)? If so, please identify the point or points that you believe to be outliers. Do not remove the outliers from the dataframe.

#### Problem 2, Cell 4

Enter the necessary Python code to fit a simple linear regression model using the Statsmodel library.

#### Problem 3, Cell 5

Cell 5 is a Markdown cell for your interpretation of the results from cell four. Examine the results of the Python output from cell four and comment if the y-intercept and slope terms are statistically significant. You may use the value of alpha = 0.05 to make your decision.

#### Problem 4, Cell 6

Enter the necessary Python to construct and plot standardized residuals in cell 6.

#### Problem 5, Cell 7

Cell 7 is a Markdown cell for you to interpet the results from cell 6. Examine the results of the Python output in cell six and determine if the linear regression assumptions are satisfied.

#### Problem 6, Cell 8

Enter the necessary Python code to construct a normal probability plot of the residuals.

#### Problem 7, Cell 9

Cell 9 is a Markdown cell for you to interpret the normal probability plot created in cell 7. Make sure to state whether you believe that the residuals are normally distributed or not normally distributed and why.

#### Problem 8, Cell 10

Enter the necessary Python code to perform Cook's Distance analysis.

#### Problem 9, Cell 11

Cell 11 is a Markdown cell for your interpretation of Cook's Distance analysis conducted in cell 10. Are there any influential point data points for this regression problem.

#### Problem 10, Cell 12

Enter the Python code to perform an analysis of DFFITS.

#### Problem 11, Cell 13

Cell 13 is a Markdown cell for your interpretation of the DFFITS analysis performed in cell 12. Examine the results of the Python output from cell twelve to determine if there are any influential data points in the data set. What value(s) did you use to determine if points were influential?

#### Problem 12, Cell 14

Enter the Python code to perform an analysis of DFBETA for the y-intercept term (beta-0).

#### Problem 13, Cell 15

Cell 15 is a Markdown cell. Interpret the results of DFBeta for the y-intercept. What value(s) were used as cutoff when determining if a problem existed.

#### Problem 14, Cell 16

Enter the Python code to perform an analysis of DFBETA for the slope term (beta-1).

#### Problem 15, Cell 17

Cell 17 is a Markdown cell. Interpret the results of DFBeta for the slope term. What value(s) were used as cutoff when determining if a problem existed.



