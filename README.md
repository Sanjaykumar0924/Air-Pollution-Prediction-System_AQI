# 🌍 Air Pollution Prediction System

<p align="center">
  <img src="images/banner.png" alt="Air Pollution Prediction System" width="900"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/Scikit--Learn-Random%20Forest-orange">
  <img src="https://img.shields.io/badge/ML-Time%20Series-green">
  <img src="https://img.shields.io/badge/Dataset-50K+-success">
  <img src="https://img.shields.io/badge/Cities-4-red">
  <img src="https://img.shields.io/badge/License-MIT-blue">
</p>

---

# 📌 Overview

The **Air Pollution Prediction System** is an end-to-end **Machine Learning** application that predicts the **Air Quality Index (AQI)** for the **next 7 days** using historical air quality data. The project leverages **Random Forest Regression**, **time-series feature engineering**, and **interactive data visualization** to forecast pollution levels and generate health advisories.

The model is trained using **50,000+ historical air quality records** collected from **Kaggle**, covering four major Indian metropolitan cities:

- Chennai
- Bangalore
- Delhi
- Mumbai

The application helps users understand future pollution trends through graphical analysis, forecasting, and automated AQI-based health recommendations.

---

# 🚀 Features

✅ Predict AQI for the next **7 Days**

✅ Random Forest Regression

✅ Time-Series Feature Engineering

✅ 7 Lag Features

✅ Automatic Missing Value Handling

✅ Daily AQI Aggregation

✅ AQI Distribution Visualization

✅ Last 30 Days AQI Trend

✅ AQI Category Pie Chart

✅ Interactive Prediction Mode

✅ AQI Health Advisory Generator

✅ Multi-City Dataset Support

---

# 🏗 Project Architecture

```
                Kaggle Dataset
                      │
                      ▼
             Data Preprocessing
                      │
                      ▼
          Time-Series Feature Engineering
                      │
                      ▼
          Random Forest Regression Model
                      │
          ┌───────────┴────────────┐
          ▼                        ▼
   7-Day AQI Forecast      AQI Health Advisory
          │                        │
          └───────────┬────────────┘
                      ▼
             Interactive Visualizations
```

---

# 🛠 Technologies Used

| Category | Technologies |
|----------|--------------|
| Language | Python |
| ML | Random Forest Regressor |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Library | Scikit-learn |
| Model Storage | Joblib |
| Development | Google Colab |

---

# 📂 Dataset

**Source**

Kaggle

**Dataset Size**

- **50,000+ Records**

**Cities**

- Chennai
- Bangalore
- Delhi
- Mumbai

**Target Variable**

- Air Quality Index (AQI)

---

# ⚙ Machine Learning Workflow

### 1️⃣ Data Collection

Historical AQI dataset collected from Kaggle.

---

### 2️⃣ Data Cleaning

- Missing value removal
- Datetime conversion
- Daily AQI aggregation
- Linear interpolation

---

### 3️⃣ Feature Engineering

Created **7 lag features**

```
AQI Lag 1
AQI Lag 2
AQI Lag 3
AQI Lag 4
AQI Lag 5
AQI Lag 6
AQI Lag 7
```

Additional Features

- Day of Year
- Month
- Weekday

---

### 4️⃣ Train-Test Split

```
Training : 80%
Testing  : 20%
```

---

### 5️⃣ Model Training

Algorithm

```
Random Forest Regressor
```

Parameters

```
Number of Trees : 150

Random State : 42

Parallel Processing : Enabled
```

---

### 6️⃣ Prediction

The trained model predicts the AQI for the **next seven consecutive days** using historical pollution patterns.

---

# 📈 Visualizations

The system automatically generates

### AQI Distribution

```
Histogram + KDE
```

---

### Last 30 Days AQI Trend

```
Line Chart
```

---

### AQI Category Distribution

```
Pie Chart

Good

Moderate

Poor

Very Poor

Severe
```

---

### 7-Day Forecast

```
Predicted AQI Line Graph
```

---

# 🩺 AQI Health Advisory

| AQI | Status |
|------|--------|
| 0–50 | Good |
| 51–100 | Moderate |
| 101–200 | Poor |
| 201–300 | Very Poor |
| 300+ | Severe |

The application automatically generates precautionary messages for each AQI category.

---

# 📷 Project Outputs

## AQI Distribution

<img src="images/distribution.png">

---

## Last 30 Days Trend

<img src="images/trend.png">

---

## AQI Category Pie Chart

<img src="images/piechart.png">

---

## AQI Forecast

<img src="images/forecast.png">

---

# 📁 Project Structure

```
Air-Pollution-Prediction-System
│
├── app.py
├── README.md
├── requirements.txt
├── LICENSE
│
├── dataset
│     └── air_pollution.csv
│
├── model
│     └── random_forest_model.pkl
│
├── notebooks
│     └── Air_Pollution_Prediction.ipynb
│
└── images
      ├── banner.png
      ├── distribution.png
      ├── trend.png
      ├── piechart.png
      └── forecast.png
```

---

# ▶ Installation

Clone Repository

```bash
git clone https://github.com/Sanjaykumar0924/Air-Pollution-Prediction-System.git
```

Move into Project

```bash
cd Air-Pollution-Prediction-System
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run the Application

```bash
python app.py
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

Install

```bash
pip install -r requirements.txt
```

---

# 💻 How It Works

The program provides two operating modes.

### Mode 1

Predict AQI for the **next 7 days** automatically.

### Mode 2

Enter a custom AQI value to

- View health advice
- Predict tomorrow's AQI

---

# 📌 Future Enhancements

- Live AQI API Integration
- Weather Parameter Integration
- LSTM-Based Forecasting
- XGBoost Comparison
- Streamlit Web Deployment
- Docker Containerization
- Cloud Deployment (AWS/Azure)
- Mobile Application

---

# 👨‍💻 Author

**Sanjay Kumar H**

AI/ML Engineer | Computer Vision Engineer | Software Engineer

GitHub:
https://github.com/Sanjaykumar0924

LinkedIn:
https://linkedin.com/in/sanjay-kumar-h46

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork the repository

📢 Share your feedback

---

# 📜 License

This project is licensed under the **MIT License**.

---

## 💡 Project Highlights

- **Machine Learning-Based AQI Forecasting**
- **Random Forest Regression**
- **50,000+ Kaggle Records**
- **4 Major Indian Cities**
- **7-Day AQI Prediction**
- **Time-Series Feature Engineering**
- **Interactive Visualizations**
- **Health Advisory Generation**
- **Python • Scikit-learn • Pandas • NumPy**
