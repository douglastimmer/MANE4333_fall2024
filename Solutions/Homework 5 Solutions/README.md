# MANE 4333 - Data Science in Manufacturing

## Homework 5 Assignment: Neural Network Regression

### Assigned: October 10, 2024
### Due: October 21, 2024

Your fifth homework assignment focuses on Neural Network Modeling. Please download the the GitHub repository and work on your local computer. Once completed, please commit the changes and push your local repository back to the master repository.

Your Homework 5 Repository should contain the following files: nutrition.dat, Homework5.ipynb, Folds5x2_pp.xlsx (Excel spreadsheet), powerPlantPaper.pdf, and README.md (this file). This data set was found at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant). The data file contains five columns and the response variable is PE. A description of the variables is found on page 127 of the [Power Plant Paper](images/powerPlantPaper.pdf).

The first cell of the Jupyter Notebook is a Markdown cell that contains the title information for this assignment.

---

#### Problem 1, Cell 2

Enter the necessary Python code to load the data found in Folds5x2_pp.xlss into a dataframe and prepare a scatter matrix of all variables.

#### Problem 2, Cell 3

In cell 3 (Markdown), interpret the scatter matrix produced for problem 1. Do there appear to be any outliers? Do any variables appear to be associated with PE? If there is an association, is it positive or negative and is it linear or non-linear.

#### Problem 3, Cell 4

Enter the Python code to scale the data. Assign 70% of the data to training and 30% to testing. Create data frames for the training and testing sets to be used to train a neural network.

#### Problem 4, Cell 5

Enter the necessary Python code to specify a neural network model that is appropriate for the data and fit the model.

#### Problem 5, Cell 6

In cell 6, enter the necessary Python code to evaluate the fitted neural network model on both the training and testing datasets.

#### Problem 6, Cell 7

In cell 7 (Markdown), comment on the results of fitting the neural network model. Does the fitted model work well for both the training and testing sets? Are there signs of overfitting?
