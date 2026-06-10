# Predicting-Restaurant-Tips-using-Predictive-Analytics-on-Excel
Use excel to predict restaurant tips.

The dataset in file Restaurant tips dataset.xlsx contains tips data for different customers. The following are the features in the dataset:

- sex: sex of customer
- smoker: indicates if customer is a smoker or not
- day: day of the restaurant visit
- time: indicates whether they ate lunch or dinner
- size: number of members dining
- total bill: bill amount in USD
- tip: tip amount in USD

#### Tools required: Microsoft Excel, Data Analysis Add-in.

## The following project tasks have been completed in Excel:

### 1. Find out if there are any missing values and clean the data:
  There are no missing values in the dataset.
### 2. Find the features that are independent and dependent:
  Dependent: total bill, tip\
  Independent: sex, smoker, day, time, size
### 3. Identify which predictive problem is needed:
  Regression
### 4. Encode the categorical variables to numeric values using IF conditions:
  When looking at the strength between the variables (sex, smoker, day, time, size, & total) and the tip amount, there is no significant correlation besides the size and total bill. This is due to more people dining, therefore more food is ordered, meaning there is a larger total bill, which leads to a larger tip.\
  When looking at the strength between the variables and the tip percentage, however, there is no significant correlation between any of them.
### 5. Build an appropriate model with the dataset:
  For each of the variables, I made a pivot table comparing each item of the variable and calculating both the average tip amount and average tip percentage.\
  Everyone seems to always tip around 14-16% of the total bill.\
  There is, however, and exception for people who dined alone, where the average tip for a solo diner is 21.73%. That is usually because they do not purchase a lot of food and tip about a dollar, which is a big proportion to the bill.
### 6. Calculate the predicted and actual tips values:
  I added 3 columns to the dataset.\
  One predicts the average by percent in which I take the total bill and multiply the average tip percentage of each variable.\
  The next column predicts the average by amount. Here I do the same calculations as the first column, but use the amount instead of percent.\
  Lastly, I calculate the averages of both percentage and amount.
  \
  I created a line chart that compares all columns mentioned above with the actual tips.\
  In the chart, you can see that the least accurate to the actual would be the predicted average by amount. The predicted average by percent seems to follow the actual trend closer, however, the average of both seems to be the best fit.
### 7. Calculate the RMSE(Root Mean Square Error) of the model. RMSE is root of mean of square errors.
the smallest root mean square error is the average of both the tip amounts and tip %.\
this rsme data reflects the line chart well. The least accurate is predicted average by amount, followed by predicted average by percent, and the most accurate is the average of both. 

