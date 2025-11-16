📘 API Mini Project — Data Wrangling Notebook

This repository contains a Jupyter Notebook that demonstrates end-to-end API data retrieval, cleaning, transformation, and exploratory analysis using Python. The project focuses on fetching real-world weather data using an external API and applying data-wrangling techniques for further analysis.

🚀 Project Overview

The notebook api_data_wrangling.ipynb walks through the following steps:

API Request & Authentication

Sending HTTP GET requests

Handling JSON responses

Extracting relevant fields

Data Cleaning & Structuring

Normalizing nested JSON

Creating a pandas DataFrame

Handling missing values

Setting time indices and converting timestamps

Feature Engineering

Resampling time-based data

Aggregating hourly weather data

Creating new analytical variables (e.g., temperature differences, rainfall totals)

Exploratory Data Analysis (EDA)

Plotting trends using Matplotlib

Identifying patterns in rainfall and temperature

City-to-city comparisons (London vs Seattle)

📂 Repository Contents
API-Mini-Project-file/
│
├── api_data_wrangling.ipynb   # Main project notebook
├── README.md                  # Project documentation
└── (future files may include data, scripts, or visualizations)

🔧 Technologies Used

Python 3

pandas

NumPy

Matplotlib

Requests

Jupyter Notebook

🎯 Key Learning Outcomes

How to fetch and parse JSON data from APIs

How to clean, wrangle, and transform structured time-series data

How to generate insights from weather datasets

How to compare two geographic locations using aggregated statistics

How to visualize weather patterns effectively

▶️ Running the Notebook

To run locally:

git clone https://github.com/MIJUMBO/API-Mini-Project-file.git
cd API-Mini-Project-file
jupyter notebook api_data_wrangling.ipynb


Ensure the following are installed:

pip install pandas numpy matplotlib requests

📈 Sample Analysis Highlights

Weekly rainfall comparison between London and Seattle

Temperature and rainfall aggregation using resample()

Weather pattern discovery through trend visualization
