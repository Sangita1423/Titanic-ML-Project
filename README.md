# Titanic-ML-Project

## Goal

It is your job to predict if a passenger survived the sinking of the Titanic or not.
For each in the test set, you must predict a 0 or 1 value for the variable.

## Metric

My score is the percentage of passengers you correctly predict. This is known as accuracy.

## Submission File Format
I should submit a csv file with exactly 418 entries plus a header row. My submission will show an error if you have extra columns (beyond PassengerId and Survived) or rows.

## The file should have exactly 2 columns:

PassengerId (sorted in any order)
Survived (contains your binary predictions: 1 for survived, 0 for deceased)
PassengerId,Survived
892,0       
893,1       
894,0
Etc.

The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. 

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.


## Plot the graph for gender and class of the survived peoples

![image](https://user-images.githubusercontent.com/88077075/165927847-3fba6918-61ca-4ee7-b15d-53547d1cfa84.png)

![image](https://user-images.githubusercontent.com/88077075/165927329-9925f841-51f1-4de7-9827-f3b64d443f2d.png)


finally get the accuracy in the form of 0 1nd 1 ant the score.

