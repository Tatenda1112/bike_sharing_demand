# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### NAME : TATENDA MUKONOWESHURO

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
The first time when I used the raw dataset without perfoming any data analysis or feature engineering the model did not perfomed as well as expected bescause it had a lot of error

### What was the top ranked model that performed?
My top score was achieved my the completing the second run with more features but no tuning og hyperparameters. The score was  0.48347

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
“I was able to determine that the temperature categories were normally distributed based on the data. I found that splitting the datetime into year, month, day and hour improved my model the most. The distribution of the data showed that all four seasons were present and that there were three categories of input for weather. Workday and holiday are binary fields and humidity and windspeed are left and right skewed respectively.”

### How much better did your model preform after adding additional features and why do you think that is?
Additional features can be good predictors to estimate the target value. In this case, I decided to separate the date because it helps the model analyze seasonality patterns in the data which can be useful for a regression model.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
The model performed better than the initial model but not as well as the improvement with just the features.

### If you were given more time with this dataset, where do you think you would spend more time?
Do a more extensive data analysis in order to get more information about this dataset

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.


![image](https://github.com/Tatenda1112/bike_sharing_demand/assets/102743794/cc08e816-fb2b-4c73-bd17-8dabbd269426)


### Create a line plot showing the top model score for the three (or more) training runs during the project.

![image](https://github.com/Tatenda1112/bike_sharing_demand/assets/102743794/ac339135-46e6-45f6-8c9c-02570aee85f6)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

![image](https://github.com/Tatenda1112/bike_sharing_demand/assets/102743794/4eab7808-1bc3-4c20-98cf-541197d0f205)


## Summary
In this project, I was able to apply all the concepts that were covered in this unit of the course. By using these skills, I was able to develop a   machine learning regression model using the Autogluon framework.
