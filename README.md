# AQI Weather Analysis and Prediction

## 📌 Overview
This project analyzes how weather factors such as temperature, humidity, and wind speed affect Air Quality Index (AQI). A simple machine learning model is built to predict AQI based on these variables.

---

## 🎯 Objective
The goal of this project is to understand the relationship between environmental factors and air quality, and to develop a basic predictive model for AQI.

---

## 📊 Dataset
- Daily weather data (March dataset)
- Features:
  - Temperature (°F)
  - Humidity (%)
  - Wind Speed (mph)
  - AQI

---

## 📈 Analysis Performed
- Correlation analysis between variables
- Scatter plot visualizations:
  - Temperature vs AQI
  - Humidity vs AQI
  - Wind Speed vs AQI
- Combined multi-variable analysis

---

## 🤖 Model
- Linear Regression model
- Inputs: Temperature, Humidity, Wind Speed
- Output: AQI

---

## 📉 Results
- Mean Absolute Error (MAE): ~11
- Model performs better for moderate AQI values
- Less accurate for extreme values

---

## ⚠️ Limitations
- Small dataset (only ~28 days)
- Weak correlations between variables
- Missing external factors (pollutants, traffic, etc.)

---

## 📄 Report
Detailed report is available here:  
👉 [View Detailed Report](./final-report-aqi.pdf)

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Conclusion
AQI is influenced by multiple environmental factors rather than a single dominant variable. The model provides a basic understanding, but more data and features are needed for better accuracy.
