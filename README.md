# Assignment 2 - DAVE3625

_We have decided to use the Ruter dataset for this assignment._

**Our task is to:**<br>
**1. Predict passenger data for Ruter Use the same data set given to you in assignment. Data file: Ruter_data.csv**
**2. Make a prediction algorithm which predicts the number of passengers on a specific date for a specific bus (pick any one).**
   - **Input should be date and output will be number of passengers.**
   - **Also show the prediction percentage score.**

**Regression algorithms** use **input data to predict a numerical value**. By fitting a mathematical model into the input data, we can then find a relationship / correlation between the input data and output data of the dataset. There are many types of regression algorithms and we will experiment with the dataset and find an algorithm which fits the dataset best.
<br>The reason we want to use **regression**, and more specifically **Linear Regression**, is because we want to be able to predict the amount of passengers on a bus on a given day so that we can plan ahead and deploy even more buses if needed, for example during rush hour or on holidays. This algorithm fits with the task because we use an input (the date) to predict our output (amount of passengers on a given date on a specific bus).
<br>In this case, we will use the date as our input and then try to find an algorithm and train it using the dataset to then find the output which will be the number of passengers on a specific bus on a specific date.
For this assignment, we will create a simple solution that fulfills the requirements.


# Findings
After training our model and predicting the passengers for a specific date and bus, we noticed that the **R2 score was quite low (~0.13)** and that the **MAE was around 4.089** which is quite high considering our sample size.
The prediction model is quite primitive and according to the R2 prediction score, very inaccurate.
