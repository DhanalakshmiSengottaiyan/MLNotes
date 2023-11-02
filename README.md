**Logistic regression:**
Logistic Regression is a supervised ML algorithm to solve a classification problem based on a linear-regression output as their input. Hence, regression is named in the algorithm for a classification problem. The outcome of the logistic regression is determined by the Confusion matrix data which is further detailed into accuracy, recall, specificity,precision and ROC-AUC(Region of convergence and Area under curve)

**Problem Statement:**
Based on the HR-dataset, we need to determine if an employee will be promoted or not.

**Algorithm:**
1. Load the dataset.
2. Import the necessary library for the Logistic Regression model such as numpy,pandas,matplotlib.pyplot,linear model and its associated metrics.
3. Observe the dataset for data-cleaning and data-preprocessing such as drop null values, imputing null values if neccessary, checking for outliers, dropping duplicates, dummy creations(one- hot encoding) for categorical variables,normalize(to make an equal representation among the input variables),correlation between the variables involved.
4. Split the dataset into train-test,fit the model and predict the output and monitor the confusion matrix and Accuracy, recall, specificity and F1-score.
5. If there is an imbalanced data among the inputs, add weights and re-fit the model again.
