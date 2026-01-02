# Student Depression Prediction System

This project implements a multi-output deep learning model to predict both the
depression score and depression state (DPN_State) of students.

Data is collected at scale using Google Forms, allowing the system to handle
a large volume of real-world student responses. Form responses are stored in
Google Sheets, exported as a CSV file, and uploaded at the beginning of the
program for processing and prediction.

## Model Overview
- Multi-output neural network
- Regression: Depression Score
- Classification: Depression State (DPN_State)
- Shared hidden layers for efficient learning

##  Data Collection
- Data collected using Google Forms
- Responses stored automatically in Google Sheets
- CSV file uploaded at runtime for predictions

##  Files in this Repository
- `student depression prediction.ipynb` – Model training & prediction notebook

## Disclaimer
This project is for educational and research purposes only and is not intended
to be used as a medical diagnostic tool.
