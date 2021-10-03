# Challenge-14
The purpose of this challenge is to to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

## Baseline Trading Algorithm 

![baseline.png](https://github.com/BRichterman/Challenge-14/blob/main/Challenge-14/Images/baseline.png)

## New Machine Learning Classifier: Logistic Regression

![trading_aglo.png](https://github.com/BRichterman/Challenge-14/blob/main/Challenge-14/Images/trading_algo.png)

1. Updating the size of the dataset from 3 months to 6 months increased the distance between the actual and strategy returns. Adjusting down to 1 month decreased the distance between actual and strategy returns. 
2. I increased the short window from 4 to 50 and increased the long window from 100 to 150. This seemed to have a similar impact to increasing the size of the dataset from 3 to 6 months - it widened the difference between actual and strategy returns.
3. *Above depicts the "default" inputs and I believe that this is the best return as it encompasses a good amount of data without spreading the difference between actual and strategy returns too far.

## Summary
Both the baseline and logitic regression returns extremely similar results. I would recommend to continue adjsuting the dataset/window paratmeters as we move through time to ensure the best trading startegy is being represnted. 
