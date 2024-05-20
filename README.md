## Introduction
The goal of this project is to build a machine learning model that predicts flight prices based on various features such as date of journey, source, destination, airline, and more. AWS SageMaker is used for data processing, model training, and deployment.
## Project Workflow
Data Collection: Import flight price data.
Data Cleaning: Handle missing values, duplicate records, and convert data types.
Exploratory Data Analysis (EDA): Visualize and understand the data.
Feature Engineering: Create new features and transform existing ones.
Model Training: Train an XGBoost model using AWS SageMaker.
Evaluation: Evaluate the model's performance.
Deployment: Deploy the model for inference.
## Data
The dataset used in this project contains information about flight bookings, including:

Airline
Date of Journey
Source and Destination
Route
Duration
Total Stops
Additional Info
Price
## Exploratory Data Analysis (EDA)
EDA was performed to understand the data distribution and relationships between features. Key steps included:

## Visualizing the distribution of flight prices.
Analyzing the impact of features like airline, source, destination, and stops on prices.
Checking for correlations between features.
## Feature Engineering
Feature engineering involved:

Extracting day, month, and year from the Date of Journey.
Calculating total duration in minutes.
Converting categorical variables into numerical representations using techniques like one-hot encoding.
## Model Training & Deployment
The XGBoost model was chosen for its efficiency and accuracy in regression tasks. Steps for training the model:
Data Preparation: Split the data into training and validation sets.
Upload Data to S3: Store the training data in an S3 bucket.

Creating a web application from scratch and deploying over cloud using Streamlit.

## Evaluation
Model performance was evaluated using metrics such as RMSE (Root Mean Squared Error). The trained model was tested on a separate validation dataset to ensure its accuracy and robustness.

## website link- https://flpriceprediction-uk75k75qztxts5zrfx6cab.streamlit.app/

