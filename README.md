# Graduate Prediction Model using Random Forest Classifier
This project focuses on predicting whether a student will graduate or drop out based on their performance in the 2nd semester. The Random Forest Classifier is used to model and predict the likelihood of graduation, given two key features: 2nd-semester approval and 2nd-semester grade.
The primary objective is to identify factors that influence a student's chance of graduation and to predict outcomes with high accuracy, helping educational institutions provide timely interventions for students at risk of dropping out.

# Problem Statement
Understanding which students are at risk of dropping out is essential for educational institutions to implement proactive measures that can help retain students. This project aims to predict whether a student is likely to graduate or drop out based on two important features related to their academic performance in the 2nd semester.

# Dataset & Features
The dataset used for this model includes historical data of student performance. The target variable is whether the student graduates or drops out, and the features are as follows:

Curricular units 2nd sem (approved): Whether the student passed their courses in the 2nd semester.
Curricular units 2nd sem (grade): The grade obtained in the 2nd semester courses.
The target variable Target represents:

1: Graduate
0: Dropout

# Approach
Data Preprocessing: Selecting relevant features from the dataset and preparing the data for training.
Modeling: Using the Random Forest Classifier to train the model based on the selected features.
Evaluation: Evaluating the model's performance with accuracy, precision, recall, F1-score, and confusion matrix to understand its predictive power.
Prediction: Using the trained model to predict student outcomes based on their 2nd-semester performance.

# Model Results
The accuracy of the model is 84.7%

# Confusion matrix results 
True Negatives (208): Correctly predicted as dropouts.
False Positives (69): Incorrectly predicted as graduates.
False Negatives (42): Incorrectly predicted as dropouts.
True Positives (407): Correctly predicted as graduates.

# Evaluation
The model achieves 84.7% accuracy, with strong precision and recall values for both graduation and dropout predictions. The model is more reliable in predicting graduation (class 1) than dropout (class 0), showing a slightly higher recall for graduates.

# Future Improvements
Incorporating additional features such as student demographics, attendance, or extracurricular activities to improve prediction accuracy.
Trying other machine learning models like logistic regression and comparing results.
Implementing a web application or dashboard to make the model accessible for educational institutions to input student data and get predictions in real time.
