# Phone App Screen Time Analysis using Python

## Introduction

This project aims to analyze screen time data from mobile apps using Python. The dataset used contains information about the usage, notifications, and times each app was opened. The analysis provides insights into app usage patterns and the relationship between usage and notifications.

## Getting Started

To run this project, ensure you have Python installed on your machine, along with the following libraries:

- pandas
- matplotlib
- seaborn
- plotly
- numpy

You can install these libraries using pip:

```
pip install pandas matplotlib seaborn plotly numpy
```

After installing the required libraries, clone this repository to your local machine and run the provided Python script.

## Dataset

The dataset used in this project is located at [this path](https://statso.io/screen-time-analysis-case-study/). It contains the following columns:

1. `Date`: Date of the observation
2. `Usage`: Usage hours of the app
3. `Notifications`: Number of notifications from the app
4. `Times opened`: Number of times the app was opened
5. `App`: Name of the app

## Analysis

### 1. Overview of the Data

The `observe_data` function provides a summary of the dataset, including the number of null values, descriptive statistics, and data types.

### 2. Amount of Usage of the Apps

The `usage1` function visualizes the amount of usage of Instagram and WhatsApp over time.

### 3. Number of Notifications from the Apps

The `notifications` function displays the number of notifications received from Instagram and WhatsApp over time.

### 4. Number of Times Each App was Opened

The `app_open` function illustrates the number of times Instagram and WhatsApp were opened over time.

### 5. Relationship Between Usage and Notifications

The `usage_vs_notifications1` function presents the relationship between the number of notifications and the amount of usage, with a regression line indicating the trend.

## Conclusion

This project provides valuable insights into mobile app screen time, including usage patterns, notification frequency, and app open frequency. By analyzing this data, users can gain a better understanding of their app usage habits and make informed decisions about managing screen time.
