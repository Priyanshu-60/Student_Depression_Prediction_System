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
###  Google Form Link

The Google Form used to collect student responses for this project is available below:

**Google Form:**  
https://docs.google.com/forms/u/7/d/1nM4Qg53AnGpn8b6Vjtab6w9ZAJdURaS1VEGAqkTRoyk/edit?usp=drivesdk&ouid=116662275056715675044&chromeless=1

Responses submitted through this form are automatically stored in a connected
Google Sheet, exported as a CSV file, and uploaded at the beginning of execution
for model training and prediction.


##  Files in this Repository
- `student depression prediction.ipynb` – Model training & prediction notebook

## Disclaimer
This project is for educational and research purposes only and is not intended
to be used as a medical diagnostic tool.
