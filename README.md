# Predict Students' Dropout and Academic Success: Project Overview 
* Created a tool to estimate the risk of dropout and failure based on academic path, demographics, and social-economic factors, helping to provide more accurate help to students by deploying multiple machine learning classification methods and deep learning
* Increased the accuracy from 0.78 (Random Forest Algorithm) to 0.92 by implementing efficient feature engineer (eliminating outliers and deleting repeating features) and deploying Deep Learning with the support of Dropout and EarlyStopping
* Generated a Tensorboard visualization tool for evaluating purposes

## Code and Resources Used 
**Python Version:** 3.10  

**Packages:** pandas, numpy, matplotlib, seaborn, sklearn

**Dataset:** https://archive-beta.ics.uci.edu/api/static/ml/datasets/697/ 

**Citation:** M.V.Martins, D. Tolledo, J. Machado, L. M.T. Baptista, V.Realinho. (2021) "Early prediction of student’s performance in higher education: a case study" Trends and Applications in Information Systems and Technologies, vol.1, in Advances in Intelligent Systems and Computing series. Springer. DOI: 10.1007/978-3-030-72657-7_16

## Data Cleaning
The dataset I got was almost ready to use. However, to separate each element in a list, instead of using comma ",", the original dataset uses a semicolon ";", which generated a mistake when I used pandas to read the dataset. Therefore, the only cleaning step I did was to change all ";" to "," by changing extension csv to txt, opening txt file and replacing all ";" to ",".  

## EDA
I looked at the distributions of the data. Below are a few highlights from the pivot tables. 

![alt text](https://github.com/ahnngo/Predict-students-dropout-and-academic-success/blob/master/Charts/Age%20at%20enrollment.png)
![alt text](https://github.com/ahnngo/Predict-students-dropout-and-academic-success/blob/master/Charts/dropout_rate.png)


## Choosing Efficient Machine Learning Model

After building Logistic Regression, KNN, Decision Tree, Random Forest, SVM, and GridSearchCV models and testing accuracy, I was able to see that Random Forest perform the best. While choosing the best algorithm, I graphed a chart about Error Rate vs K value in KNN. 
![alt text](https://github.com/ahnngo/Predict-students-dropout-and-academic-success/blob/master/Charts/Error%20Rate%20vs%20K%20value.png)

## Improve Accuracy by Practicing Feature Engineering and Deploying Deep Learning

After implementing efficient feature engineer (eliminating outliers and deleting repeating features) and deploying Deep Learning with the support of Dropout and EarlyStopping, I was able to increase the accuracy from 0.72 to 0.92. Below is a chart comparing loss and val_loss:
![alt text](https://github.com/ahnngo/Predict-students-dropout-and-academic-success/blob/master/Charts/Correlation_Deep_Learning.png)
