# 🚀 Space Mission Data Analysis

This project focuses on analyzing historical space mission data using Python. The dataset contains information about rocket launches, organizations, mission status, locations, and costs. The goal is to clean the dataset and extract meaningful insights through data analysis and visualization.

---

## 📊 Project Overview

- Dataset contains **4324 space mission records**
- Cleaned dataset reduced to **964 valid records**
- Performed:
  - Data Cleaning
  - Data Transformation
  - Exploratory Data Analysis (EDA)
  - Data Visualization

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas 📊
- Plotly 📈

---

## 📂 Dataset Features

- Organisation
- Location
- Date
- Rocket Details
- Rocket Status
- Mission Status (Success/Failure)
- Price (Mission Cost)

---

## 🧹 Data Cleaning Steps

- Removed unnecessary columns (`Unnamed`)
- Handled missing values using `dropna()`
- Converted:
  - Date → datetime format
  - Price → numeric format
- Extracted:
  - Country from Location
  - Year & Month from Date

---

## 📈 Key Analysis Performed

### 1. 💰 Total Spending by Organisation
- Calculated total spending of each space organization
- Visualized using **Treemap**

### 2. 🌍 Launches by Country
- Extracted country from location
- Mapped launch distribution using **Choropleth Map**

### 3. 🚀 Mission Success Analysis
- Compared success vs failure rates
- Visualized using **Sunburst Chart**

### 4. 📅 Launch Trends Over Time
- Launches per year by organization
- Monthly launch trends

---

## 📊 Visualizations

- Treemap → Organization Spending
- Choropleth Map → Country Launch Distribution
- Sunburst Chart → Mission Status
- Line Chart → Launches per Year
- Bar Chart → Monthly Launch Trends

---
