
# Disease Prediction System

This repository contains a Disease Prediction System, a web application built using machine learning models. The system predicts the likelihood of various diseases based on user-provided medical data


## About
The Disease Prediction System utilizes machine learning models trained on medical data to predict the probability of different diseases. It incorporates models for predicting heart disease, diabetes, and Parkinson's disease. These models have been trained on relevant datasets to provide accurate predictions.
## Features

* Predicts Multiple Diseases: The system can predict heart disease, diabetes, and Parkinson's disease, covering a wide range of health conditions.
* User-Friendly Interface: The web application provides a simple and intuitive interface with input fields for entering medical data.
* Instant Predictions: Users receive immediate predictions upon submitting their medical data, facilitating quick decision-making.
## Usage
To use the Disease Prediction System:

1. Clone the Repository: Clone this repository to your local machine using Git.
2. Install Dependencies: Install the required Python packages using pip. Ensure you have Python installed on your system.
3. Run the Application: Execute the main script to launch the Streamlit application. This will start the web server and display the application in your default web browser.
4. Input Medical Data: Use the input fields provided in the web application to input relevant medical data for prediction.
5. Get Predictions: Click the appropriate button to trigger the prediction for the selected disease. The system will analyze the input data and provide an instant prediction.
## Installation

To install the necessary dependencies, follow these steps:

1. Install Python: If you haven't already, install Python on your system.
2. Install Dependencies: Use pip, the Python package manager, to install the required packages. These include:

* numpy: pip install numpy
* pandas: pip install pandas
* pickle: pip install pickle5 or pip install pickle-mixin
* streamlit: pip install streamlit
* streamlit_option_menu: pip install streamlit-option-menu

Code snippet for Set-up

1. import numpy as np
2. import pandas as pd
3. from sklearn.preprocessing import StandardScaler
4. from sklearn.model_selection import train_test_split
5. from sklearn import svm
6. from sklearn.metrics import accuracy_score
## How to Run
To run the application:

Execute Main Script: Run the main script using the streamlit run command.

Eg: streamlit run your_script.py

Replace your_script.py with the filename containing code in your system.

Eg: streamlit run "C:\Users\malti\Downloads\girl hackathon\Medical Assistant Web\Medical Assistant Model.py"
## Inputting Medical Data

Once the application is running, access it through your web browser.
Use the input fields provided in the web application to input relevant medical data for prediction from the CSV files present in the repository.
## Getting Prediction
Click the appropriate button to trigger the prediction for the selected disease. The system will analyze the input data and provide an instant prediction.
## Contributing 
Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the Repository: Fork this repository to your GitHub account.
2. Create a New Branch: Create a new branch for your feature or bug fix.
3. Make Changes: Implement your changes or additions to the codebase.
4. Commit Changes: Commit your changes with clear and descriptive commit messages.
5. Push Changes: Push your changes to your forked repository.
6. Open a Pull Request: Submit a pull request to merge your changes into the main repository.