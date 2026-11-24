# 🌍 Air Quality Analytics & AQI Prediction

An end-to-end Machine Learning project that analyzes air quality data, explores pollution patterns, and predicts the Air Quality Index (AQI) using pollutant measurements.

<p align="center">

  **Transforming Air Quality Data into Meaningful Insights**

</p>

## 🌐 Live Demo

Experience the interactive AQI Prediction Dashboard:

[🚀 Launch Air Quality Analytics App](https://chauhannikil494-star-air-quality-analytics-app-gl4o6q.streamlit.app/)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on air quality data and builds machine learning models to predict AQI.

Two regression algorithms are evaluated:

- Linear Regression
- Random Forest Regression

Random Forest Regression was selected as the final model because it achieved better performance on the test dataset.

The trained model is integrated with a Streamlit web application where users can enter pollutant measurements and receive AQI predictions, AQI categories, and health recommendations.

## 🚀 Features

- Exploratory Data Analysis (EDA)
- City-wise AQI analysis
- Monthly and yearly AQI trends
- Seasonal AQI analysis
- Pollutant correlation analysis
- AQI distribution analysis
- AQI category analysis
- Linear Regression model
- Random Forest Regression model
- Model performance comparison
- Feature importance analysis
- Residual analysis
- AQI prediction using new pollutant values
- Interactive Streamlit dashboard
- AQI category classification
- Health recommendations
- Live Streamlit deployment

## 🧪 Pollutants Used

The machine learning model uses 12 pollutant features:

| No. | Pollutant |
|---:|---|
| 1 | PM2.5 |
| 2 | PM10 |
| 3 | NO |
| 4 | NO2 |
| 5 | NOx |
| 6 | NH3 |
| 7 | CO |
| 8 | SO2 |
| 9 | O3 |
| 10 | Benzene |
| 11 | Toluene |
| 12 | Xylene |

## 🤖 Machine Learning Models

Two regression algorithms were implemented and evaluated.

### 1. Linear Regression

A baseline regression model used to predict AQI from pollutant measurements.

### 2. Random Forest Regression

An ensemble learning algorithm selected as the final prediction model because of its better evaluation results.

## 📊 Model Performance

The following metrics were obtained during model evaluation:

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 31.17 | 59.45 | 0.807 |
| Random Forest Regression | 20.83 | 40.84 | 0.909 |

### Best Performing Model

**Random Forest Regression**

- Lower Mean Absolute Error (MAE)
- Lower Root Mean Squared Error (RMSE)
- Higher R² Score

The Random Forest model achieved an R² score of **0.909** on the test dataset.

## 🔍 Important Features

According to the Random Forest model, the most important features were:

1. PM2.5
2. CO
3. NO
4. PM10
5. O3

Feature importance represents the model's contribution from each feature and should not be interpreted as direct causation.

## 🖥️ Streamlit Dashboard

The interactive dashboard allows users to:

1. Enter pollutant measurements.
2. Predict AQI using the trained Random Forest model.
3. View the predicted AQI.
4. View the AQI category.
5. Get health recommendations.
6. View an AQI level indicator.
7. Review entered pollutant values.

## 🔄 Project Workflow

```text
Air Quality Dataset
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Selection
        ↓
Missing Value Handling
        ↓
Train-Test Split
        ↓
Linear Regression
        ↓
Random Forest Regression
        ↓
Model Evaluation
        ↓
Final Model Selection
        ↓
Model Saving
        ↓
Streamlit Dashboard
        ↓
AQI Prediction
```

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Saving | Joblib |
| Web Application | Streamlit |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/TheDataForgeX/air-quality-analytics.git
```

### 2. Navigate to Project Directory

```bash
cd air-quality-analytics
```

### 3. Create Virtual Environment (Optional)

```bash
python -m venv .venv
```

### 4. Activate Virtual Environment

**Windows:**

```powershell
.venv\Scripts\activate
```

### 5. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Run Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📁 Project Structure

```text
air-quality-analytics/
│
├── Air_Quality_Analytics.ipynb
├── Project_Interview_Questions.ipynb
├── app.py
├── app_backup.py
├── city_day.csv
├── random_forest_aqi_model.pkl
├── requirements.txt
├── README.md
├── .gitignore
└── .gitattributes
```

## 🎯 Project Objectives

- Analyze air pollution patterns across different cities.
- Understand the relationship between pollutants and AQI.
- Apply
