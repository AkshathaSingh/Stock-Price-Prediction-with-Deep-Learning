## Stock Price Prediction using LSTM Recurrent Neural Networks
### Overview
In this project, we'll build a prediction model to predict the Adjusted Closing stock price of the Big 4 Tech companies, 
Google, Amazon, Facebook and Apple.

We'll be doing the following steps to complete our project:
- We'll first collect the data.
- Then preprocess the data so that it can be used to train our model.
- Split the data into training set(used to train the model) and test set(used to check the performance of the model).
- Build our Sequential LSTM RNN model using keras with TensorFlow backend.
- Fit the model to our data.
- Evaluate the performance of our model by testing it's performance on the test data.

### Data
- The data has been imported using the Tiingo API.
- The data of the stock prices for the last 2 years, i.e, from May 31st 2019 to May 28th 2021 has been taken.
