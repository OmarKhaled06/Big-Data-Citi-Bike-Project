# Citi Bike Big Data Analytics with PySpark

## Overview

This project analyzes more than **1.3 million Citi Bike NYC trip records** using **PySpark** and Python to extract operational and behavioral insights from large-scale real-world transportation data.

The project focuses on:

* Big data preprocessing and cleaning
* Scalable analytics using Spark
* Feature engineering
* Exploratory data analysis (EDA)
* Machine learning classification models
* Business insight generation

The dataset contains trip-level information such as:

* Trip duration
* Start and end stations
* Geographic coordinates
* Rider demographics
* Timestamps
* Bike IDs

---

## Objectives

The main goals of this project were to:

* Handle and clean messy large-scale real-world datasets
* Build scalable preprocessing workflows using PySpark
* Analyze rider and operational behavior patterns
* Engineer meaningful analytical features
* Train and evaluate machine learning models
* Translate raw trip data into actionable business insights

---

## Technologies Used

* Python
* PySpark
* PySpark MLlib
* Spark SQL
* Jupyter Notebook
* Matplotlib

---

## Dataset

* **Source:** Citi Bike NYC trip dataset
* **Size:** 1.3M+ records
* **File Size:** ~229 MB

---

## Data Cleaning & Preprocessing

The dataset required extensive preprocessing before analysis and modeling.

### Key cleaning steps included:

* Handling missing values
* Validating trip durations
* Removing invalid geographic coordinates
* Filtering unrealistic age values
* Handling sentinel values such as unknown genders (`Gender = 0`)
* Checking duplicate trip records
* Standardizing data formats
* Feature extraction and transformation

### Engineered Features

* Ride hour
* Weekday vs weekend usage
* Trip speed
* Rider age
* Trip distance
* Ride duration categories

---

## Exploratory Data Analysis

The analysis revealed several operational and behavioral patterns within the Citi Bike system.

### Key Insights

* Subscribers showed strong weekday commuting behavior during business hours
* Casual riders were significantly more active on weekends
* Certain stations experienced heavy congestion during peak hours
* Peak demand periods were concentrated around commuting windows
* Usage patterns varied significantly by rider demographic and trip timing

### Business Interpretation

These insights can support:

* Bike redistribution optimization
* Station capacity planning
* Demand forecasting
* Operational decision-making
* Rider behavior analysis

---

## Machine Learning

Three classification models were implemented using **PySpark MLlib**:

1. Logistic Regression
2. Decision Tree
3. Random Forest

### Objective

Predict rider gender based on trip behavior and engineered ride features.

### Evaluation Metrics

Models were evaluated using:

* Accuracy
* F1-score

### Results

| Model               | Accuracy                 | F1-Score |
| ------------------- | ------------------------ | -------- |
| Logistic Regression | Lower than Random Forest | Lower    |
| Decision Tree       | Moderate                 | Moderate |
| Random Forest       | ~74%                     | ~0.63    |

The Random Forest model achieved the best overall performance and handled the behavioral feature complexity more effectively than the other models.

---

## Project Structure

```bash
├── data/
├── notebooks/
├── outputs/
├── visualizations/
├── models/
└── README.md
```

---

## Skills Demonstrated

* Big Data Analytics
* PySpark
* Machine Learning
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Predictive Modeling
* Scalable Data Processing
* Business Intelligence
* Data Visualization

---

## Conclusion

This project provided hands-on experience in working with large-scale messy datasets and building scalable analytical workflows using Spark. It combined data engineering, analytics, and machine learning techniques to transform raw transportation data into meaningful operational and behavioral insights.
