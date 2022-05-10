# Capstone Project: Customer Segmentation Report

## Table of Contents

1. [Motivation](#motivation)
2. [File description](#file)
3. [Results](#results)
4. [Instructions](#instructions)
5. [Acknowledgements](#acknowledgements)

## Motivation <a name="motivation"></a>

The aim of this project is to create a model that predicts the probability of a person becoming a customer at a mail 
order company in Germany. The first part of the project was the analysis of the provided data and the visualisation of 
important and relevant information. Then, unsurpervised learning techniques such as Principal Component Analysis (PCA) 
and k Means Clustering were used to compare and cluster the two populations of existing customers and the general 
population of Germany.

The last part of the exercise was to create a suitable model to predict whether a person is likely to become a customer 
or not. In other words, to determine whether it is worthwhile to run a marketing campaign for that particular potential 
customer.

The model was then tested with a test data set and submitted to Kaggle.


## File description <a name="file"></a>

Officially stated in the problem description under [Udacity](https://www.udacity.com/):

*"There are four data files associated with this project:*

*Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).*

*Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).*

*Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).*

*Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns)."*


## Results <a name="results"></a>

The results are a cluster analysis of the customers of the company as well as a supervised learning model to predict 
the response of potentially future customers.



#### Reflection

Although the exercise was very taff (especially at the beginning) it was again a great experience for me and my data 
science journey. I would like to mention a few points:

The data analysis at the beginning was the most difficult part. The cleaning process followed a logical structure, but 
seemed a bit rudimentary. Apart from deleting columns and rows and transforming some other columns, there would be many 
more possibilities. One could ask for covariances between features, skewness or more detailed examinations of the 
deleted columns, just to name a few possibilities.
The PCA and clustering are heavily dependent on the previous data cleaning. I am relatively satisfied with this 
stand-alone part. The elbow plot could have been more powerful, but the clusters generated seem reasonable and a logical 
consequence of the work done before.
The process of choosing the right model could certainly have been more detailed and elaborate. I chose to compare only 
two (but very common) classifiers and compared them head to head. At this point I'm not sure it was the right choice, 
but with hyperparameter tuning I gained some points for the ROC-AUC metric. Uploading the Kaggle submission worked well, 
although there is certainly room for improvement for the scoring here too.
I am happy with the notebook and the big effort I put into this project. Thank you very much at Udacity for the great 
project and the help you always provided.

## Instructions <a name="instructions"></a>

There are no potential difficulties in running this file. When you run it for the first time, you can activate the two 
shifters at the beginning of the script to create three pickle files.


## Acknowledgments <a name="acknowledgments"></a>

I would like to thank the team from [Udacity's](https://www.udacity.com/) for the great support and the brilliant online 
course [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).