# Automotive Data Analysis: 11k+ Car Dataset

This repository contains a comprehensive Exploratory Data Analysis (EDA) and data cleaning project performed on a dataset of over 11,000 vehicle records. The goal of this project was to handle a "messy" real-world dataset and uncover trends in automotive pricing and specifications.

## 📊 Project Overview
The analysis covers 16 different features including MSRP, Engine HP, Fuel Type, and Popularity across 48 unique car brands.

### Key Tasks Performed:
* **Data Cleaning:** Standardized column naming conventions (lowercase and underscores) and handled significant missing values in the `market_category`, `engine_hp`, and `engine_cylinders` columns.
* **Duplicate Removal:** Identified and removed duplicate entries to ensure statistical accuracy.
* **Statistical Profiling:** Analyzed the distribution of car prices (MSRP) and performance metrics.
* **Visualization:** Used **Matplotlib** and **Seaborn** to create:
    * Histograms of price distributions.
    * Correlation heatmaps to see how features like HP and Cylinders affect price.
    * Scatter plots to analyze popularity vs. cost.
    * Boxplots for luxury brand price comparisons.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 📂 File Structure
* `car_dataset.ipynb`: The main Jupyter Notebook containing the cleaning logic and visualizations.
* `Data collection Cleaning Visualization and Analysis.pptx`: Presentation explaining role of data cleaning and visualizing in data science.

---
