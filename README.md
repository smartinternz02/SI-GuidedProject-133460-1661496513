# SI-GuidedProject-133460-1661496513
Hospital Readmission Prediction Using Machine Learning
Drive link: https://drive.google.com/drive/folders/1awLsRU8tqB89pLr9oB87tJhz3lp1DeVI?usp=sharing
Project Description:

To predict whether a person will be readmitted to the hospital within 30 days or not, will be of great help to the hospital in developing an idea of the incoming number of repeated patients which in turn helps to provide better services for patients with increased risk of disease.

This will help the hospital in being ready for any number of patients that could be readmitted in the future.

The problem associated is a binary classifcation. Since the target variable in the dataset is quite imbalanced, SMOTE algorithm was used to oversample the minority class.

A number of models were used such as logistic regression, KNN Classifier, Decision Tree Classifier, Random Tree Classifier, Adaboost Classifier etc.
We will train and test the data with these algorithms.
From this, the best model is selected and saved in pkl format. We will also be deploying our model locally using Flask.
Out of all the models, random forest classifier is found to perform the best.
