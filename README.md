# Uber Trip Analysis Dashboard

<p align="center">

![Power BI](https://img.shields.io/badge/POWER%20BI-1F1F1F?style=for-the-badge&logo=powerbi&logoColor=white)
![Dashboard](https://img.shields.io/badge/DASHBOARD-1F1F1F?style=for-the-badge)
![Python](https://img.shields.io/badge/PYTHON-1F1F1F?style=for-the-badge&logo=python&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-1F1F1F?style=for-the-badge)
![Pandas](https://img.shields.io/badge/PANDAS-1F1F1F?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analysis](https://img.shields.io/badge/DATA%20ANALYSIS-1F1F1F?style=for-the-badge)
![Plotly](https://img.shields.io/badge/PLOTLY-1F1F1F?style=for-the-badge&logo=plotly&logoColor=white)
![Interactive Charts](https://img.shields.io/badge/INTERACTIVE%20CHARTS-1F1F1F?style=for-the-badge)
![MIT License](https://img.shields.io/badge/LICENSE-MIT-1F1F1F?style=for-the-badge)

</p>

---

## Overview

This project presents an end-to-end business intelligence solution for analyzing Uber trip data using **Python**, **Exploratory Data Analysis (EDA)**, and **Microsoft Power BI**.

The objective is to transform raw transportation data into actionable business insights through data preprocessing, feature engineering, statistical analysis, interactive visualizations, and dashboard development.

The project combines Python-based analytics with an interactive Power BI dashboard to provide insights into booking trends, revenue, customer preferences, vehicle performance, payment behavior, and location-based demand.

---

## Dashboard Preview

> Replace the image below with your dashboard screenshot.

<p align="center">
<img src="Images/Dashboard.png" width="100%">
</p>

---

## Project Objectives

- Understand the structure and quality of the dataset
- Perform data cleaning and preprocessing
- Engineer meaningful analytical features
- Analyze booking trends and ride patterns
- Explore fare, distance, and trip duration distributions
- Identify high-demand pickup and drop-off locations
- Study payment preferences and vehicle performance
- Build an interactive Power BI dashboard
- Generate business insights and recommendations

---

## Dataset

### Uber Trip Details

The primary dataset contains detailed ride information including:

- Trip ID
- Pickup Time
- Drop Off Time
- Passenger Count
- Trip Distance
- Pickup Location ID
- Drop-off Location ID
- Fare Amount
- Surge Fee
- Vehicle Type
- Payment Type

**Records:** 103,728

**Features:** 11

---

### Location Table

Maps numerical location IDs to corresponding location names and cities.

**Records:** 265

**Features:** 3

---

## Exploratory Data Analysis

The EDA notebook includes:

- Data Quality Assessment
- Missing Value Analysis
- Duplicate Detection
- Feature Engineering
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Time Series Analysis
- Location-Based Analysis
- Statistical Summary
- Business Insights
- Recommendations

---

## Power BI Dashboard Features

- Executive KPI Cards
- Dynamic Date & City Filters
- Drill-Through Navigation
- Interactive Visualizations
- Booking Trend Analysis
- Revenue Analysis
- Vehicle Performance Analysis
- Payment Method Analysis
- Pickup & Drop-off Location Analysis
- Time-Based Analysis
- Dynamic DAX Measures

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Business Intelligence | Microsoft Power BI |
| Data Modeling | DAX |
| Data Source | Excel |

---

## Repository Structure

```text
uber-trip-analysis-dashboard/
│
├── Data/
│   ├── Uber Trip Details.xlsx
│   └── Location Table.xlsx
│
├── Notebook/
│   └── Uber_Trip_Analysis_EDA.ipynb
│
├── PowerBI/
│   └── Uber Trip Analysis.pbix
│
├── Images/
│   ├── Dashboard.png
│   ├── Overview.png
│   ├── Time Analysis.png
│   └── Details.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Key Business Insights

- Identified the most preferred vehicle category.
- Analyzed booking distribution across payment methods.
- Evaluated revenue contribution by vehicle type.
- Identified peak booking hours and daily demand patterns.
- Analyzed trip distance and fare relationships.
- Studied surge pricing behavior.
- Identified the busiest pickup and drop-off locations.
- Compared weekday and weekend ride patterns.

---

## Future Improvements

- Demand Forecasting using Machine Learning
- Revenue Prediction Models
- Driver Allocation Optimization
- Customer Segmentation
- Interactive Streamlit Dashboard
- Real-Time Data Integration

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/gaathapatel07/uber-trip-analysis-dashboard.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open

- `Notebook/Uber_Trip_Analysis_EDA.ipynb` for the Python analysis.
- `PowerBI/Uber Trip Analysis.pbix` using Microsoft Power BI Desktop.

---

## Author

**Gaatha Patel**

GitHub: https://github.com/gaathapatel07

LinkedIn: *Add your LinkedIn profile*

---

## License

This project is licensed under the MIT License.
