# Stock Price Prediction using LSTM

## Overview

This project involves building a Long Short-Term Memory (LSTM) neural network model to predict stock prices. The dataset used for training and testing is historical stock price data for Amazon (AMZN) obtained from a CSV file.

## Project Structure

- **Data Preparation:**
  - Loaded stock price data into a Pandas DataFrame.
  - Selected relevant columns and created a subset for further processing.
  - Transformed the DataFrame to include a lookback window for LSTM training.

- **Data Preprocessing:**
  - Scaled the data using Min-Max scaling.
  - Prepared the dataset for training by creating input-output pairs for the LSTM model.

- **Modeling:**
  - Implemented an LSTM model using PyTorch.
  - Created a custom dataset class for handling time series data.
  - Utilized PyTorch DataLoader for efficient batching during training.

- **Training:**
  - Defined a training loop to train the LSTM model on the training dataset.
  - Validated the model on a separate test dataset.

- **Results:**
  - Plotted predicted vs. actual stock prices on both training and test datasets.
  - Analyzed model performance and visualized predictions.

## Project Usage

1. **Requirements:**
   - Python
   - PyTorch
   - Pandas
   - Numpy
   - Matplotlib
   - Scikit-learn

2. **Data:**
   - Replace the file path in the code with the path to your own stock price dataset.

3. **Training:**
   - Adjust hyperparameters such as learning rate, batch size, and model architecture if needed.
   - Run the training loop to train the LSTM model.

4. **Evaluation:**
   - Evaluate the model performance on the test dataset.
   - Visualize and analyze the predictions.

## Results

## Conclusion

This project demonstrates the use of LSTM networks for stock price prediction. It provides a template that can be extended to other financial time series forecasting tasks.

Feel free to reach out for any questions or collaborations.

## Author

[Keci Chilala]

Connect with me on [LinkedIn]((https://www.linkedin.com/in/keci-chilala/)https://www.linkedin.com/in/keci-chilala/).

--- 

