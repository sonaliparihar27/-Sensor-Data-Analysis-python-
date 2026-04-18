# 🚗 Sensor Data Analysis & Outlier Detection (Python)

## 📌 Overview
This project focuses on processing and analyzing raw automotive sensor data generated from test bench systems. The data is unstructured and contains missing values, inconsistencies, and noise.

The goal was to convert this raw data into a clean time-series dataset and detect anomalies using statistical techniques.

---

## 🎯 Objective
- Convert raw .txt files into structured datasets
- Clean and preprocess sensor data
- Detect anomalies using statistical methods
- Visualize trends and outliers for analysis

---

## 🛠 Tools & Technologies
- Python (pandas, numpy)
- Matplotlib / Seaborn
- File handling (glob, os)
- Excel / CSV output

---

## ⚙️ Work Done

### 1. Data Processing
- Read multiple raw .txt files
- Merged into a single dataset
- Standardized timestamps and column names

### 2. Data Cleaning
- Handled missing values
- Removed duplicate timestamps
- Converted logs into numeric format

### 3. Feature Engineering
- Rolling Mean
- Moving Average
- Rolling Standard Deviation
- Signal smoothing

### 4. Outlier Detection
- Rolling mean ± k * standard deviation
- Threshold-based anomaly detection

### 5. Visualization
- Time-series plots
- Highlighted outliers
- Trend comparison (raw vs smoothed)

---

## 📈 Impact
- Reduced manual processing time from hours to minutes
- Improved detection of faulty sensor readings
- Enabled faster engineering analysis

