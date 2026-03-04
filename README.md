# Product Demand Forecasting with Machine Learning

End-to-end data analytics project analysing retail product sales and building predictive models to forecast demand across multiple product categories.

This project demonstrates how machine learning and statistical analysis can support inventory planning, pricing strategy, and revenue optimisation.

--- 

# Project Snapshot

## Objective
Develop predictive models to forecast product demand and identify key drivers of sales performance.

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Core Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Machine learning modelling
* Forecast evaluation
* Data visualisation

---

# Business Problem

Accurate demand forecasting is critical for retailers. Poor predictions lead to stock shortages, overstocking, and inefficient promotional strategies.

This project uses historical sales data to:

* Understand demand patterns
* Identify key sales drivers
* Build forecasting models
* Generate data-driven business insights

---

# Dataset Overview

The dataset contains retail performance information across multiple products and time periods, including:

* Product sales
* Store characteristics
* Promotional activity
* Temporal variables such as dates and seasonality

These variables allow analysis of both operational and behavioural drivers of demand.

---

# Analytical Workflow

## 1. Data Preparation

Initial preprocessing focused on ensuring data quality and usability.

Key steps included:

* Handling missing values
* Cleaning and standardising variables
* Data validation
* Feature construction

## 2. Exploratory Data Analysis

Exploratory analysis was used to uncover patterns and relationships in the dataset.

Key questions explored:

* How does demand change over time?
* Which products generate the most revenue?
* How do promotions influence sales?
* Are there seasonal demand patterns?

## 3. Feature Engineering

To improve predictive performance, several new variables were created:

* Lagged sales variables
* Rolling averages
* Promotion indicators
* Seasonal features

These features capture temporal patterns and behavioural signals in the data.

## 4. Predictive Modelling

Several machine learning models were developed and compared.

* Models tested:
* Linear Regression
* Random Forest
* Gradient Boosting

Evaluation metrics:

* RMSE
* MAE
* R²

---

# Results

The modelling process successfully captured demand patterns across product categories.

Key findings:

* Promotions significantly increase short-term demand
* Sales follow clear seasonal cycles
* Machine learning models outperform simple statistical baselines

---

# Business Insights

The analysis highlights several opportunities for retailers.

Promotion Optimisation
Promotional campaigns drive substantial sales increases.

Improved Inventory Planning
More accurate forecasts can reduce stockouts and excess inventory.

Product Strategy
Understanding demand drivers helps prioritise high-performing products.

---

# Repository Structure

```
product-demand-forecasting
│
├── dataset             # sample dataset used for analysis
├── notebooks           # analysis and modelling notebooks
├── report              # full academic report
```
