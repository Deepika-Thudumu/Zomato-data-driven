# Zomato Food Delivery Data Analysis

This project explores and analyzes customer and restaurant partner data from Zomato’s food delivery business. Using **Jupyter Notebook**, the project focuses on performing Exploratory Data Analysis (EDA), uncovering key insights, and visualizing trends related to food delivery services on the platform.

## Problem Statement

Zomato has an average of 17.5 million monthly transacting customers for its food delivery business. The average monthly active restaurant partners on the platform have also increased by 8.7% year-on-year, from 208,000 to 226,000. The goal of this project is to analyze the customer dataset, perform exploratory data analysis, and visualize the data to extract meaningful insights about customer behavior, transaction patterns, and restaurant growth.

## Features

- **Data Cleaning and Preprocessing**.
- **Exploratory Data Analysis (EDA)** with descriptive statistics and data visualization.
- **Visualizations** using libraries such as `matplotlib`, `seaborn`, `plotly`, etc.
- **Key Metrics**: Analyze transaction frequency, restaurant partner growth, and customer behavior.
- **Interactive Charts** created in Jupyter for a better understanding of the data.

## Tools and Technologies Used

- **Jupyter Notebook**: Interactive Python notebook for data analysis.
- **Python**: The programming language used for data manipulation and analysis.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For static data visualizations.
- **Plotly**: For interactive data visualizations.
- **NumPy**: For numerical operations and transformations.


## Dataset

The dataset contains various features such as:

- name
- online_order
- book_table
- rate	
- votes
- approx_cost(for two people)
- listed_in(type)


> **Note**: The dataset used in this project is anonymized and is provided for analysis purposes.

## Project Structure

- `Zomato_EDA_Analysis.ipynb`: Main Jupyter notebook for data analysis and visualizations.
- `data/`: Folder containing the dataset (e.g., CSV or other file formats).

## Key Steps in the Analysis

1. **Data Cleaning**:
   - Handle missing values.
   - Remove duplicates.
   - Convert data types where necessary.
   - Address any inconsistencies in the data.

2. **Exploratory Data Analysis (EDA)**:
   - Perform descriptive statistics (mean, median, mode, etc.) for transaction amounts and other features.
   - Investigate customer activity patterns over time (monthly/weekly trends).
   - Analyze the growth of restaurant partners on the platform.

3. **Data Visualizations**:
   - **Transaction Trends**: Visualize customer transaction behavior over time (e.g., monthly active users, transaction amounts).
   - **Restaurant Growth**: Plot restaurant growth (new vs. active restaurants).
   - **Correlation Heatmap**: Analyze correlations between variables such as customer demographics and transaction amounts.
   - **Customer Behavior**: Distribution of transaction amounts across different restaurant categories.

4. **Key Insights**:
   - Growth of the platform in terms of customer base and restaurant partners.
   - Patterns in transaction behavior over time (seasonal trends, peak periods).
   - Insights into which restaurant categories or locations are performing best.
