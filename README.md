# 📘 API Mini Project — Data Wrangling Notebook

Welcome to the **API Mini Project**!  
This repository contains a Jupyter Notebook focused on **retrieving**, **cleaning**, and **analyzing** weather data using the Open-Meteo API. The project demonstrates practical data wrangling techniques commonly used in analytics and data science workflows.

---

## 🧾 Project Overview

This mini project explores key steps in API-based data analysis:

- Connecting to a public weather API  
- Extracting hourly and daily variables  
- Cleaning and transforming JSON responses  
- Resampling and aggregating time-series data  
- Creating comparative insights between geographic locations  

The primary objective is to compare **weekly rainfall patterns** between **London** and **Seattle** over a one-year period.

---

## 📂 Repository Contents

├── api_data_wrangling.ipynb # Main analysis notebook
└── README.md # Project documentation

---

## 🔍 What the Notebook Covers

### ✔ 1. API Data Retrieval  
The notebook fetches weather data from the **Open-Meteo Archive API**, focusing on hourly rainfall variables.

### ✔ 2. Data Wrangling  
Includes:
- JSON normalization  
- Datetime parsing and indexing  
- Resampling (hourly → weekly)  
- Handling missing values and outliers  

### ✔ 3. Feature Engineering  
A new column, **Rain Difference**, is created to compare rainfall between London and Seattle on a weekly basis.

### ✔ 4. Exploratory Analysis  
- Total rainfall comparison  
- Weekly rainfall patterns  
- Identification of dominant rain periods  
- Summary statistics  

---

## 🌦 Key Findings

- **Seattle had more rainfall than London overall.**
- Weekly breakdown:
  - **Seattle:** 31 wetter weeks  
  - **London:** 21 wetter weeks  
  - **Equal rainfall:** 1 week  
- Seattle shows strong rainfall in winter and late autumn.
- London’s rain is more evenly distributed but less intense.
- Both cities experience a dry summer with minimal rainfall differences.

---

## 📊 Visualizations  
The notebook includes:
- Bar charts of weekly rainfall  
- Comparative line plots  
- Rainfall difference trends  

---

## 🚀 Getting Started

To run the notebook locally:

1. Clone the repository  
   ```bash
   git clone https://github.com/MIJUMBO/API-Mini-Project-file.git
