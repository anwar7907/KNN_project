# K Nearest Neighbors project

# Problem:  
Which borrower have high probability of paying back the loan in full?

# Goal:
Create a deascion tree model that will help predict wether or not the borrower will pay back the loan in full.

# Summary of the solution:
## 1. Data overview:
   1. Data type
   2. Number of columns
   3. Numbers of rows
   4. Data description and statistical summary
## 2. Data Analysis Exploration (EDA)
   1. Pairplot to take overview of the data for the target class
## 3. Setting up the data for machine learning
   1. Standarize the variables
       * StandardScalar
   2. Data train test split
       * Sklearn.cross_validation
   3. Model train
       * K Nearest Neighbors model
         * KNeighorsClassifier
## 4. Model predection
## 5. Model evaluations
   * Classification_report
   * Confusion_matrix
