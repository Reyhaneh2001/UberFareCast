# 🚕 UberFareCast: Predicting Uber Fares with Machine Learning and Visual Analytics

## 📌 Project Overview

This project explores historical Uber ride data to build a powerful fare prediction model. From in-depth exploratory data analysis (EDA) to geospatial mapping and advanced regression techniques, this project delivers both insight and performance.

**Key goals:**
- Clean and prepare Uber trip data
- Engineer meaningful time and geolocation features
- Visualize patterns and distributions in the dataset
- Train, evaluate, and compare ML models to predict fare amount
- Use real-world metrics and charts to present results clearly

---

## 📊 Dataset
- **Features**:
  - `pickup_datetime`
  - `pickup_longitude` & `pickup_latitude`
  - `dropoff_longitude` & `dropoff_latitude`
  - `passenger_count`
  - `fare_amount` (target)

---

## 🔍 Exploratory Data Analysis (EDA)

Extensive visualizations created using **Seaborn**, **Matplotlib**, and **Plotly**:

- 🗺️ Geospatial pickup & dropoff heatmaps  
- 📅 Fare vs time-of-day, day-of-week, month  
- 👥 Passenger count effects  
- 📏 Distance vs Fare scatter analysis  
- 📉 Outlier detection and cleaning  
- 📦 Feature distribution plots (before/after scaling)

---

## 🛠️ Feature Engineering

- Extracted temporal features: `hour`, `weekday`, `month`
- Calculated **geodesic distance (km)** between pickup and dropoff
- Handled outliers in coordinates, distance, and fare
- Scaled numeric features and encoded categorical ones

