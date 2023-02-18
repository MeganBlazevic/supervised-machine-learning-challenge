# supervised-machine-learning-challenge

The goal of this Module 19 challenge asked up to compate the Logistic Regression model and the Random Classifer modelules; to create the risk level for some loans.

## Programs Used
- Pandas
- SkiLearn (train-test-split, Logistic regression, random forest classifer)

## Data Retrieval
Import the lending_data csv file that was given to us.  We were asked to put that into a pandas data frame.

## Predict Performane
Predict our thoughts on what would perform better.

I beleive that the Logistic Regression will be a better model will be more accurate predictor then the Random Forest Classifer.  This data setcontains all numeric data, so that should work to the advantage of the Logistic Regression.  There are several different columns contining different features; which I believe is what the Random Forest Classifiers is better at.  But I don't feel that the number of features is enough to justify its used.  I also believe that the Logistic Regression model will aid in less overfitting in the end. 

## Split to test and training
Create our X values; and our Y value (Loan_Status).
Split the data into training and testing sets utilizing the train_test_split sklearn function.

## Create, Fit, and Model
Created a Logistic Regression model; that was fit and tested.
Created a Random Forest Classifer model; that was fit and tested.

## Outcomes
Which model performed better?  How accurate was my prediction?

I was incorrect.  The Random Forest Classifer model trained and tested at a higher rate; proving my prediction incorrect. Witha that being said, the testing data only varied by .000619.

## My Challenges
Once I got the flow, this module, was straight forward; as I had to just fit the numbers.  This modeling is easy, once you have your X and Y determined. 

My struggles are choosing the random state number; which I believe doesn't make much of a difference. Along with assigning the max-iter for the logistic regression and the n-estimator for the random forest classifer. I chose larger numbers for this as my data set contraing more than 77K rows of data. 
