# 🚗 Sensor Data Analysis & Outlier Detection (Python)

## 📌 Overview
This project focuses on processing and analyzing raw automotive sensor data generated from test bench systems. The raw data is highly unstructured, containing missing values, inconsistent formats, and noise.

The solution converts this raw data into a clean time-series dataset, applies statistical techniques to detect anomalies, and visualizes patterns to support engineering analysis.

> ⚠️ Note: This repository uses synthetic sample data for demonstration. The original data cannot be shared due to confidentiality.

---

## 🎯 Objective
- Convert raw `.txt` test data into structured datasets
- Clean and preprocess time-series sensor data
- Detect anomalies using statistical methods
- Visualize trends and outliers for analysis

---

## 🛠 Tools & Technologies
- Python (pandas, numpy)
- Matplotlib / Seaborn
- File handling (glob, os)
- Excel / CSV output
- Statistical methods (moving average, rolling window, standard deviation)

---

## ⚙️ Methodology

### 1️⃣ Automated Raw File Processing
- Read multiple `.txt` files from test bench output
- Parsed and merged them into a single dataset
- Standardized column names and timestamp formats

### 2️⃣ Data Cleaning & Preprocessing
- Handled missing and invalid sensor readings
- Converted text logs into numeric values
- Removed duplicate timestamps
- Synchronized data frequency for consistency

### 3️⃣ Time-Series Feature Engineering
Created derived features to analyze trends:
- Moving Average / Running Average
- Rolling Mean
- Rolling Standard Deviation
- Signal smoothing
- Helper columns for anomaly tracking

### 4️⃣ Outlier Detection
Applied statistical techniques:
- Rolling mean ± k * standard deviation
- Threshold-based anomaly detection
- Identified abnormal spikes in sensor values like speed and torque

### 5️⃣ Data Visualization
- Time-series line plots
- Highlighted outliers in red
- Trend comparison (raw vs smoothed signals)
- Helped engineers quickly identify abnormal patterns

---

## 📊 Sample Output
- Clean time-series dataset
- Graphs showing trends and anomalies
- Highlighted abnormal data points

---

## 🚧 Challenges Faced
- Handling unstructured raw files
- Missing and inconsistent sensor data
- Aligning timestamps across multiple files
- Noise in real-time sensor signals

---

## 📈 Impact
- Reduced manual data processing time from hours to minutes
- Improved identification of faulty sensor readings
- Enabled faster and more accurate engineering analysis
- Automated visualization improved decision-making

---

## 🚀 Future Improvements
- Implement machine learning-based anomaly detection
- Real-time data pipeline integration
- Dashboard integration for live monitoring
