**Logistic regression:**
Logistic regression is a supervised machine learning algorithm mainly used for classification tasks where the goal is to predict the probability that an instance of belonging to a given class.It’s referred to as regression because it takes the output of the linear regression function as input and uses a sigmoid function to estimate the probability for the given class.The outcome of the logistic regression is determined by the Confusion matrix data which is further detailed into accuracy, recall, specificity, precision and ROC-AUC(Reciever Operating Characteristics - Area under curve)

**Problem Statement:**
Based on the HR-dataset, we need to determine if an employee will be promoted or not.

**Algorithm:**
1. Load the dataset.
2. Import the necessary library for the Logistic Regression model such as numpy,pandas,matplotlib.pyplot,linear model and its associated metrics.
3. Observe the dataset for data-cleaning and data-preprocessing such as drop null values, imputing null values if neccessary, checking for outliers, dropping duplicates, dummy creations(one- hot encoding) for categorical variables,normalize(to make an equal representation among the input variables),correlation between the variables involved.
4. Split the dataset into train-test,fit the model and predict the output and monitor the confusion matrix and Accuracy, recall, specificity and F1-score.
5. If there is an imbalanced data among the inputs, add weights and re-fit the model again.

**Inference**
1. The acuuracy of predicting the employee of getting promotion is 92% on an imbalanced data class where as the accuracy where the dataset has a balanced class is at 74%.
2. Precision and recall parameters have taken a hit between imbalanced and balanced dataset classes.
