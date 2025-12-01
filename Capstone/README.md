# Data Science Capstone Project

## Project Overview

Welcome to my Capstone Project repository. This project serves as the final assessment for the **IBM Data Science Professional Certificate**. 

The primary objective of this project was to apply the skills and methodologies acquired throughout the data science curriculum to a real-world scenario. In this analysis, I aim to predict **whether the SpaceX Falcon 9 first stage will land successfully** using historical data.

This repository documents the entire end-to-end data science pipeline, from raw data collection to the deployment of machine learning models and interactive dashboards.

## Project Components & Methodology

This repository is structured to reflect the standard data science workflow. It includes the following key stages:

* **Data Collection via API:** Extraction of historical data using GET requests to the REST API.
* **Web Scraping:** Collection of auxiliary data (such as launch records) by scraping HTML tables from Wikipedia using **BeautifulSoup**.
* **Data Wrangling:** Pre-processing the dataset to handle missing values, format dates, and standardize data types using **Pandas**.
* **Exploratory Data Analysis (EDA):** Conducting SQL queries and statistical analysis to understand data distribution and relationships.
* **EDA with Visualization:** Creating static charts (bar charts, scatter plots, confusion matrices) using **Matplotlib** and **Seaborn** to visualize success rates and trends.
* **Interactive Visual Analytics with Folium:** utilizing geospatial analysis to map launch sites and visualize the success/failure of launches based on geographical location.
* **Interactive Dashboard with Plotly Dash:** Development of a user-friendly, interactive dashboard that allows users to filter data by launch site and payload mass to view success metrics in real-time.
* **Machine Learning Prediction:** Building, training, and evaluating various classification models (Logistic Regression, SVM, Decision Tree, and KNN) to predict the outcome of the landing. Hyperparameters were tuned using GridSearchCV to achieve the best accuracy.

## Technologies Used
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn, Folium, Plotly Dash
* **Machine Learning:** Scikit-Learn
* **Web Scraping:** BeautifulSoup, Requests
