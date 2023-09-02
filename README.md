# Prediction-of-Product-Sales

Author: 
Eric

Stakeholder requirement:
- The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.


## Data Dictionary
![image](https://github.com/FoxEW/Prediction-of-Product-Sales/assets/138833063/733b3ca0-fe20-425b-b80b-55086a427558)



## Exploratory data analysis was performed - by using data visualisations.
(Some examples below)



![image](https://github.com/FoxEW/Prediction-of-Product-Sales/assets/138833063/a4f70301-0559-4675-8f63-695a5739f524)

Countplot that indicates the number of Item Types that are available per Outlet Type - indicating that Fruit & Veg is the highest in the Supermarket Type 1 grouping


![image](https://github.com/FoxEW/Prediction-of-Product-Sales/assets/138833063/e2aa4123-d408-4ad4-a6d1-21b805302c1d)

Heatmap:  This indicates that there is a positive correlation between Item Outlet Sales and Item MRP.



## Model Metrics:

### Regression Model

![image](https://github.com/FoxEW/Prediction-of-Product-Sales/assets/138833063/609acfe4-7215-4a21-9cd3-98c937cf81c8)


### Random Forest

![image](https://github.com/FoxEW/Prediction-of-Product-Sales/assets/138833063/b4fbe216-f51d-4411-b939-7e12982f9727)



## Model: Evaluation and Recommendations:

You need to determine which model to implement.

Overall, which model do you recommend?
(justify your recommendation)

- Based on the metrics obtained - the Random Forest Model is recommended.

The following measures were obtained in the model:

- Root Mean Squared Error (RMSE) = 1,100.21

- R-squared (R^2) = 0.56

In a Markdown cell:
Interpret your model's performance based on R-squared - in a way that your non-technical stakeholder can understand.

- The model achieves a rating of 56% for indicating how independent variables influence the dependent variable.
- This metric indicates how well the model fits the data.

Select another regression metric (RMSE/MAE/MSE) to express the performance of your model to your stakeholder.
Include why you selected this metric to explain to your stakeholder.
- The Root Mean Squared Error (RMSE) metric can be used to measure the performance of the model and indicates the average errors between the predicted and actual values in the model.

Compare the training vs. test scores and answer the question: to what extent is this model overfit/underfit?
- To evaluate whether the model is overfitting or underfitting, we compare the performance on the training and test datasets:
- For R^2 the model achieves a higher result on TRAINING data vs. TEST data.
- For RMSE a lower TRAINING result is achieved vs. TEST data.
- R^2: Training = 0.94 vs. Test = 0.56
- RMSE: Training = 428.56 vs. Test = 1,100.21


The above metric differences of TRAINING vs. TEST data - is an indication that there is certain extend of OVERFITTING in the model.
