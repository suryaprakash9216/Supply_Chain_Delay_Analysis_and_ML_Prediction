# 🚚 Supply Chain Delay Analysis and Machine Learning Prediction

## Overview

This project presents an end-to-end Python-based data analytics and machine learning workflow focused on analyzing supply chain delivery performance and predicting late delivery risks. The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and XGBoost to transform raw supply chain transaction data into meaningful operational insights and predictive models.

The project covers the complete analytics lifecycle, including data loading, preprocessing, exploratory data analysis (EDA), bottleneck detection, root cause analysis, feature engineering, machine learning modeling, and performance evaluation. The primary objective was to identify the major factors contributing to delayed deliveries and develop predictive models capable of forecasting late delivery risks.


# Dataset Information

The dataset contains supply chain transaction and delivery-related information collected from an e-commerce and logistics environment. It includes various operational, customer, product, and shipping-related attributes such as:

* Order details
* Shipping modes
* Delivery status
* Product categories
* Customer segments
* Regional information
* Order processing dates
* Profit and sales metrics
* Late delivery risk indicators

The dataset was processed and cleaned in Python before performing analysis and machine learning modeling.

> Note: The dataset was excluded from the repository due to GitHub file size limitations.


# Tools & Technologies Used

## Programming & Data Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Data Visualization

* Matplotlib
* Seaborn

## Machine Learning

* Scikit-learn
* XGBoost
* SMOTE

# Project Workflow

## 1. Data Loading

The dataset was imported into Jupyter Notebook using Pandas. Initial inspection was performed to understand the structure, columns, datatypes, and quality of the data.

## 2. Data Cleaning & Preprocessing

Several preprocessing techniques were applied to improve data quality and prepare the dataset for analysis:

* Handling missing values
* Removing redundant columns
* Converting date columns into datetime format
* Filtering canceled orders
* Creating new calculated features
* Feature engineering for machine learning

Additional features created include:

* Delay
* Order Processing Time
* Order Month
* Order Day
* Order Hour
* Delayed Order Indicators

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to identify supply chain delivery patterns and operational insights. The analysis included:

* Delay distribution analysis
* Profit impact analysis
* Delivery performance trends
* Shipping mode analysis
* Regional delay analysis
* Customer segment analysis
* Delay trends by:

  * Month
  * Day of Week
  * Hour of Day

Several visualizations were created using Matplotlib and Seaborn to support the analysis.

## 4. Bottleneck & Root Cause Analysis

Detailed bottleneck analysis was performed to identify the major operational factors contributing to late deliveries. The analysis included:

* Delay percentage by region
* Delay percentage by shipping mode
* Delay percentage by department
* Delay percentage by customer segment
* Top drivers of late deliveries
* Profit impact caused by delivery delays

The project also analyzed high-risk operational areas responsible for poor delivery performance.

## 5. Machine Learning Modeling

Machine learning models were developed to predict late delivery risks using supply chain operational features.

### Models Implemented

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### Feature Engineering Techniques

* Frequency Encoding
* Categorical Feature Transformation
* Feature Selection

### Data Balancing Technique

* SMOTE (Synthetic Minority Oversampling Technique)

### Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* Classification Report

The machine learning models successfully identified patterns associated with delayed deliveries and helped classify high-risk orders.

# Key Business Insights

* Certain shipping modes showed consistently higher delivery delays.
* Some regions contributed significantly to late delivery risks.
* Delayed deliveries negatively impacted operational profitability.
* Order timing patterns influenced delivery performance.
* Machine learning models were able to predict late delivery risks with strong performance.

# How to Run the Project

## Step 1: Clone the Repository

```bash
git clone <repository-link>
````

## Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

## Step 3: Open the Jupyter Notebook

Run the notebook file:

```text
Supply_Chain_Delay_Analysis_and_ML_Prediction.ipynb
```

## Step 4: Run the Notebook

Execute all cells sequentially to perform:

* Data preprocessing
* EDA
* Visualization
* Bottleneck analysis
* Machine learning modeling

# Project Files

| File Name                                             | Description                                            |
| ----------------------------------------------------- | ------------------------------------------------------ |
| `Supply_Chain_Delay_Analysis_and_ML_Prediction.ipynb` | Complete Python analysis and machine learning workflow |
| `README.md`                                           | Project documentation                                  |

# Conclusion

This project demonstrates practical data analytics and machine learning skills by combining Python-based data preprocessing, exploratory analysis, visualization, bottleneck detection, and predictive modeling to analyze supply chain delivery performance.

The project highlights the complete analytical workflow from raw operational data processing to predictive machine learning modeling and insight generation. It showcases the ability to transform supply chain transaction data into actionable business insights using modern data analytics and machine learning techniques.

# Author

## **Suryaprakash Reddy Muddireddy**

MSc Data Analytics
Technological University of the Shannon (TUS), Ireland

```
```
