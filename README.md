# PREDICT SURVIVAL ON THE TITANIC
#### Powered by 𝑀𝑒𝑛𝑡𝑜𝑟𝑠ℎ𝑖𝑝 𝑃𝑟𝑜𝑔𝑟𝑎𝑚 𝐴𝑠𝑠𝑒𝑠𝑠𝑚𝑒𝑛𝑡

![image](https://github.com/Blaqdiana/Prediction_assessment/assets/109005502/17411ca0-a8f5-4fbc-bb27-6bc7aa535ccc)



## Description:
Your task is to predict survival on the Titanic using Python. The Titanic dataset includes features like age, sex, passenger class, and fare, among others. Use machine learning tools to analyze what sorts of people were more likely to survive the tragic event.

**Downloading the data:**

The dataset for the task is available in the folder named 'Datasets'. It consists of two main [FILES](https://drive.google.com/drive/folders/1xfkQnP7l85KdxhNHdPg5oHBZ3uUpyGYH):
- train.csv: Use this file for building your machine learning model.
- test.csv: This file will help you to test the performance of your model.

### Running this service:
Step 1: Import necessary libraries - You should start by importing the necessary libraries. Pandas is used for data manipulation, NumPy for numerical operations, and sklearn for machine learning tasks.

Step 2: Load the data - The training and testing data are loaded from CSV files into pandas DataFrames.

Step 3: Data exploration - This is a crucial step to understand the structure of the data.

Step 4: Data Preprocessing - Missing values in the datasets are replaced with their mean values, categorical variable(s) needed are encoded into numerical values. This is done for both datasets and he features to be used for training the model are selected.

Step 5: Split data into training and validation sets -The training data is split into a new training set and a validation set.

Step 6: Scale numerical features - The numerical features are scaled using StandardScaler.

Step 7: Train the model - A Random Forest Classifier is trained on the new training set.

Step 8: Evaluate the model Predictions, this is to be done on the validation set.

Step 9: Finally make predictions on the test set.

**NOTE:-** These predictions can be used for further analysis 
