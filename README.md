# Mobile Price Prediction project overview

I tried to predict mobile price range (0-3). 

## Code and Resources Used
**Python Version:** `3.8.6`

**Packages:** `pandas, numpy, matplotlib, seaborn, sklearn`

**Pearson Correlation Github:** https://github.com/krishnaik06/Complete-Feature-Selection/blob/master/2-Feature%20Selection-%20Correlation.ipynb

## Data Cleaning
After loading the data I made the following changes:
* checked for any null values,
* ckecked if all of the features are of the correct type (numeric)

## EDA
I created a pie plot in order to clearly see that there are around 3/4 of phones supporting 3G in our train data. A box plot shows that the greater the price range 
the better the battery power.

## Model Building
I split the data into train and test subsets (to avoid overfitting) with a test size of 20%. I used 3 models: Linear Regression, Decison Tree and Random Forest to find out
that Linear Regression performed the best.

## Model performance
According to my analysis Ram and Battery Power are the two most important features.
