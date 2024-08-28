# Predicting student's academic performance: A SMOTE and ADASYN approach.

## Objective 
The dataset, sourced from https://archive.ics.uci.edu includes details known at the time of student enrollment and their academic performance by the end of the first and second semesters. This task is designed as a three-class classification problem, with a notable imbalance favoring one of the classes. We aim to develop classification models and examine how imbalanced data affects performance and the impact of balancing techniques like SMOTE and ADASYN.

The completion of this project can help contribute to the identification of students who are at risk of either dropping out or failing in higher education. With this, strategies can be developed to help support those students.

## Data Understanding

The dataset did not contain any missing values, and the outliers were not removed. The extreme values which were classified as outliers were the true value of students' performance. The data contains 36 features and 4424 instances.

## Exploration of the data
I explored the data to gain valuable insight into information such as

•   Age at the time of enrollment and its impact on student's performance.

•   Whether the payment of tuition fees affects students' performance and which gender is affected the most economically.

•   Does the course of study affect the performance of the student?

•   Does the time of the day that a student attends school impact the performance of the student?

•   What is the admission grade and previous first-year grade distribution and what insight can we get concerning the performance of a student? 

## Classification task
Logistic regression and Random Forest were considered for this project and the data was split into 70-30 for training and testing data respectively. The features were scaled for the logistic regression algorithm. The models were evaluated using metrics like accuracy score, f1 score, precision and recall score, and confusion matrix. 
