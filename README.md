

# Project Title: Earthquake Severity Prediction

## Overview
This project develops a predictive model for earthquake severity using SVM, Linear Regression, and Random Forest, analyzing a dataset of 782 entries with 19 features. The approach includes comprehensive data cleaning, exploratory data analysis (EDA), and data preprocessing. The objective is to compare the effectiveness of these machine learning models in accurately forecasting earthquake impacts. This work is vital for enhancing earthquake response strategies and mitigating risks. Additionally, the project explores the correlation between various seismic indicators and the actual severity, aiming to contribute valuable insights to seismology and disaster risk management.

## Models Implemented
- **Model 1:** Linear regression 
- **Model 2:** SVM
- **Model 3:** Random Forest

## Dataset Used
Dataset used for the prediction is in the data folder and name of dataset is "earthquake_data.csv"

## Results 
- **Linear Regression:** R^2: 0.17, MSE: 0.12
- **SVM:** R^2: -0.11, MSE: 0.15,
- **Random Forest:** MSE:  0.03693351719745237,  R^2:  0.7324789111372308

## Getting Started

1. Clone the repository using command : git clone [repository URL]
2. Open the Anaconda
3. Launch the jupyter notebook
4. Navigate to the cloned folder
5. Open the "Machine Learning Project_SP24.ipynb" file
6. Run the file using "Restart and Run all"
7. You will get the results of all chunks

## Using your own data for prediction

1. In the code go to the "Predict for new data" chunk
2. Then add your values for "cdi	mmi	alert	tsunami	sig	net	nst	dmin	gap	magType	depth	latitude	longitude" these columns/features . This is now your new_data
3. After running the cell for your data you will get the predicted "Magnitude" which is the target variable
4. According to magnitude you will get notify on the earthquake severity

