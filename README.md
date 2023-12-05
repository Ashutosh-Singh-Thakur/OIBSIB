# Oasis Infobyte Data Science Virtual Internship

Welcome to the repository for my virtual internship tasks on Data Science with Oasis Infobyte! This repository showcases the work I have completed as part of the internship program, where the goal was to successfully accomplish at least three tasks.

## Table of Contents

- [About Oasis Infobyte](#about-oasis-infobyte)
- [Tasks](#tasks)
- [Task Details](#task-details)
- [How to Run](#how-to-run)
- [Results and Findings](#results-and-findings)
- [Acknowledgments](#acknowledgments)

## About Oasis Infobyte

[Oasis InfoByte](https://oasisinfobyte.com/), an MSME registered startup, excels in IT services, including website development, cloud computing, graphic and animation design, database management, and machine learning solutions. The virtual internship in Data Science provides hands-on experience and practical skills for aspiring data scientists.

## Tasks

To successfully complete the Oasis Infobyte Data Science Virtual Internship, participants are required to complete a minimum of three tasks. This repository contains my solutions and implementations for these tasks.

## Task Details

### Task 1: Iris Flower Classification

- **Objective:** Train a machine learning model to classify iris flowers into their respective species (setosa, versicolor, virginica) based on their measurements.
- **Implementation:** Utilize machine learning techniques to analyze and classify iris flower species.
- **Results:** [Link to Task 1 Code](TASK-1/Iiri-Flower-Classification.ipynb)

![Task 1 Screenshot](https://github.com/Ashutosh-Singh-Thakur/OIBSIB/assets/128626139/3d1463d0-77b6-494e-bdcf-6c0b38c6ca1d)

### Task 2: Unemployment Analysis with Python

- **Objective:** Analyze and explore unemployment rates, particularly during the Covid-19 period, using Python.
- **Implementation:** Use Python for data analysis and visualization to gain insights into unemployment trends.
- **Dataset:** [Download Unemployment Dataset](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
- **Results:** [Link to Task 2 Code](TASK-2/Unemployement-Analysis.ipynb)

![Task 2 Screenshot](https://github.com/Ashutosh-Singh-Thakur/OIBSIB/assets/128626139/6322754a-8b2b-45a5-b177-a8f209e08d6d)

### Task 3: Car Price Prediction with Machine Learning

- **Objective:** Train a machine learning model to predict car prices based on various factors such as brand goodwill, features, horsepower, and mileage.
- **Implementation:** Dive into machine learning techniques for car price prediction.
- **Dataset:** [Download Car Price Prediction Dataset](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)
- **Results:** [Link to Task 3 Code](TASK-3/Car-Price-Prediction.ipynb)

![Task 3 Screenshot](https://github.com/Ashutosh-Singh-Thakur/OIBSIB/assets/128626139/e7d0475c-2f14-4b0a-a6b7-068ebfe6a3ca)

## How to Run

To execute the code for tasks, you can leverage Google Colab for an interactive and collaborative environment. Simply click on the Colab icon at the top left of the `.ipynb` file in each task directory.

### Task 2 and Task 3 Datasets

For tasks 2 and 3, datasets need to be uploaded. You can use the following links to access the datasets directly on Google Colab without downloading them to your local machine:

- **Task 2 Dataset**: [Task2_data.csv](https://colab.research.google.com/github/Ashutosh-Singh-Thakur/OIBSIB/blob/main/TASK-2/Unemployement%20inI%20ndia.csv)
- **Task 3 Dataset**: [Task3_data.csv](https://colab.research.google.com/github/Ashutosh-Singh-Thakur/OIBSIB/blob/main/TASK-3/car%20data.csv)

Click on the links above, and it will open the respective dataset on Google Colab. You can then run the code with the provided dataset directly.

Please note that users will need a Google account to access and run the code on Google Colab.


## Results and Findings

### Task 1: Iris Flower Classification

The Iris Flower Classification task aimed to train a machine learning model to categorize iris flowers into their respective species. The model was trained using the Random Forest Classifier. Key findings include:

- **Model Accuracy:** The trained model achieved an accuracy of 100% on the test dataset.
- **Confusion Matrix:** The confusion matrix provides insights into the model's performance across different classes.

![Confusion Matrix](task1/results/task1_confusion_matrix.png)

### Task 2: Unemployment Analysis with Python

In the Unemployment Analysis task, we delved into exploring the unemployment rate, particularly during the Covid-19 period. Key findings include:

1. State with highest Unemployment: Andhra Pradesh
2. State with Lowest Unemployment: Chandigarh
3. Month with highest Unemployment: May
4. Month with lowest Unemployment: April
5. Graph Progress: Higher The labour participation Lower the unemployment rate

### Task 3: Car Price Prediction with Machine Learning

In the Car Price Prediction task, we trained two machine learning models—Linear Regression and Random Forest Regressor—to predict car prices based on various features. Here are the key performance metrics for each model:

#### Linear Regression

- **Mean Absolute Error:** 1.507058
- **Mean Squared Error:** 7.196046
- **R2 Score:** 0.778359

#### Random Forest Regressor

- **Mean Absolute Error:** 0.648656
- **Mean Squared Error:** 2.400151
- **R2 Score:** 0.926074

### Insights

- The Random Forest Regressor outperformed the Linear Regression model across all metrics, demonstrating its superior predictive capability.
- The low Mean Absolute Error and Mean Squared Error values for the Random Forest Regressor indicate accurate predictions and better model fit.
- The high R2 Score for both models suggests a good fit to the data, with the Random Forest Regressor achieving a slightly higher level of explained variance.

These results suggest that the Random Forest Regressor is a more suitable model for predicting car prices in this context. Further analysis and fine-tuning could lead to even more accurate predictions.


## Acknowledgments

I would like to express my gratitude to Oasis Infobyte for providing this valuable virtual internship opportunity and for the guidance and support throughout the program.
