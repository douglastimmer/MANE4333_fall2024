# MANE 4333 - Data Science in Manufacturing

## Homework 2 Assignment: Principal Components Analysis (PCA)

### Assigned: September 19, 2024
### Due: September 30, 2024

Your second homework assignment focuses on Principal Components Analysis. Please download the the GitHub repository and work on your local computer. Once completed, please commit the changes and push your local repository back to the master repository.

Your Homework 2 Repository should contain the following files: wdbc_data.xslx, homework2.ipynb, and README.md (this file).

---

#### Problem 1

Consider the data found in wbcd_data.xlsx spreadsheet in the Week 4 Learning Materials. WBCD stands for the Wisconsin Breast Cancer Data set. This data set was taken from the UCI Machine Learning site. It is a data set for classification of tumors based upon radiological measurements. The classification variable was removed for this analysis.

##### Part A
In cell 2, load the data into a Pandas data frame and then analyze the data. Your analysis should include a scatter matrix, descriptive statistics and correlation matrix. The analysis for
part a should be performed in one (code) cell.

##### Part B
In cell 3, state if you believe that multicollinearity is a problem with this dataset. Support your answer using results found in Part A.

##### Part C
In cell 4, perform the standardization of the wbcd data and whatever analyses are needed to demonstrate that the data was properly transformed.

##### Part D
In cell 5, explain why you know that the data was properly standardized in Part C. Provide as much evidence as possible.

##### Part E
In cell 6, perform a PCA on all components in the data set. Display the eigen values, eigen vectors, percent variability explained by the PCA and a Scree plot.

##### Part F
In cell 7, use Markdown to suggest how many components should be used in the PCA. Use the Eigen values criteria, percent variability explained and Scree plot to support your decision.

##### Part G
In cell 8, conduct a second PCA on the full, standardized data set using the number of components you found in Part F. Display the eigen values and eigen vectors in this cell.

##### Part H
In cell 9, use Markdown to attempt to profile the reduced set of principle components found in Part G.
