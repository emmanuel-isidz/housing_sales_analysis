# 🏠 UAE Real Estate Rental Market Analysis

## 📖 Project Overview

This project explores the UAE rental property market using over 73,000 real estate listings collected across major cities including Dubai, Abu Dhabi, Sharjah, Ajman, Fujairah, Ras Al Khaimah, Al Ain, and Umm Al Quwain.

The objective was to analyze rental pricing patterns, property performance, geographic trends, and market opportunities using Python-based data analytics techniques.

---

## 🎯 Business Problem

Real estate investors, property managers, and rental agencies need data-driven insights to understand:

* Which property types generate the highest rental income
* Which locations command premium rental prices
* How rental performance differs across cities
* Which property categories remain listed longer
* Emerging opportunities within the UAE rental market

This project aims to provide actionable insights that support investment and pricing decisions.

---

## 📊 Dataset Overview

| Metric            | Value  |
| ----------------- | ------ |
| Total Records     | 73,742 |
| Total Features    | 17     |
| Cities Covered    | 8      |
| Locations Covered | 441    |
| Property Types    | 9      |

### Features Included

* Property Address
* Rent
* Bedrooms
* Bathrooms
* Property Type
* Area (sq ft)
* Rent per sq ft
* Furnishing Status
* Listing Age
* Location
* City
* Geographic Coordinates

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning

### Missing Values

Identified missing geographic coordinates:

* Latitude: 719 missing values
* Longitude: 719 missing values

Missing values were handled before analysis.

### Feature Selection

Removed non-essential columns:

* Latitude
* Longitude
* Area_in_sqft
* Rent_per_sqft
* Posted_date
* Purpose

This allowed the analysis to focus on rental market behavior.

---

## 🔍 Analysis Performed

### Property Type Analysis

* Average Rent by Property Type
* Total Rental Revenue by Property Type
* Listing Duration by Property Type

### Location Analysis

* Revenue by Location
* Top Performing Rental Locations
* Rental Concentration Analysis

### City-Level Analysis

* Revenue Distribution Across Cities
* City Ranking by Rental Value

---

## 📈 Key Findings

### Highest Average Rent

| Property Type        | Average Rent |
| -------------------- | ------------ |
| Residential Building | AED 2.87M    |
| Residential Floor    | AED 1.41M    |
| Penthouse            | AED 481K     |

### Highest Revenue Generators

| Property Type | Total Rent |
| ------------- | ---------- |
| Apartment     | AED 6.20B  |
| Villa         | AED 3.66B  |
| Townhouse     | AED 655M   |

### Top Revenue Locations

1. Palm Jumeirah
2. Downtown Dubai
3. Dubai Marina
4. Al Reem Island
5. Dubai Creek Harbour

### Top Revenue Cities

| City      | Total Rent |
| --------- | ---------- |
| Dubai     | AED 7.31B  |
| Abu Dhabi | AED 2.69B  |
| Sharjah   | AED 456M   |

---

## 💡 Business Insights

* Apartments dominate the UAE rental market due to volume and affordability.
* Villas contribute significantly to overall rental revenue.
* Palm Jumeirah remains the most valuable rental location.
* Dubai accounts for the majority of rental activity.
* Premium property categories command substantially higher rental rates but contribute less overall volume.

---

## 🚀 Future Improvements

* Predictive rental pricing model
* Property recommendation engine
* Rental demand forecasting
* Geographic heatmaps
* Interactive Power BI dashboard

---

## 🧠 Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis (EDA)
* Trend Analysis
* Comparative Analysis
* Geographic Analysis

### Data Cleaning

* Missing Value Treatment
* Feature Engineering
* Data Validation

### Visualization

* Matplotlib
* Business Storytelling
* KPI Reporting

---

## 👨‍💻 Author

Emmanuel Isidahomhen

Aspiring Data Analyst | Marketing Analytics Enthusiast

Skills:
Python • SQL • Power BI • Excel • Data Visualization
