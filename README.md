# ML-Assignment
Assignment 1
Classification Techniques

Part One: 
In this Assignment you will explore and experiment with several classification and predictive modeling (KNN, SVM, Decision tree and Naïve Bayesian). Use 5-fold cross-validation for training and evaluations
For decision tree you should tune it for the best hyperparameters 
For KNN you should tune it for best K
For the best tuned classifier, you should determine the
•	The confusion matrix
•	Precision
•	Recall
•	F1-Score
•	Draw the ROC curves for all classifier on one graph
•	Draw the training error and validation error curves for all classifier on one graph
Interpret and explain your observations on results

Part Two:
Inject label noise systematically to data set as follow:
•	Split data set into two groups (grup1 whose class label Yes, group2 whose class label No)
•	Randomly select 5% records of the group1 and change their class labels for Yes to No
•	Randomly select 10% records of the group2 and change their class labels for No to Yes
•	The merge the two groups after flips to be one data set
Apply the classification and predictive modeling (KNN, SVM, Decision tree and Naïve Bayesian) to the noisy data set and compare their robustness by inspecting their:
•	confusion matrix
•	Precision
•	Recall
•	F1-Score
•	ROC curves
•	Training error and validation error curves
Provide theoretical justification for observed behavior

Note 1. You can find the data file on Moodle course page as “liver_cancer_prediction.csv”
Note 2. The target column is the Prediction
Note 3. You need to pre-process the data such as filling missing, cleaning, scaling etc., you should do that before you start applying the algorithms
