# Thailand Temperature Forecasting

## 📌 Project Overview
This project analyzes and predicts the average temperature in Thailand. Using NASA data from 2022 to 2025, I identified trends and seasonal patterns to build a model that predicts temperatures for the next 12 months.

## 📊 Summary of Findings

### 1. Model Selection & Performance
* **Baseline vs. Tuned Model**: After testing, the **Baseline Prophet Model** performed better than the Tuned Model (which was optimized using Optuna).
* **Accuracy**: The Baseline Model has a lower **MAPE** (Mean Absolute Percentage Error). It is more stable and accurate for real-world use.

### 2. Seasonality & Trends (2026 Forecast)
* **Yearly Pattern**: This is the most important factor. It causes temperatures to change by about ±4°C throughout the year.
* **Peak & Low**: Temperatures **peak in May** and are at their **lowest in December and January**.
* **Main Trend**: The forecast for 2026 shows a slight **"downward trend."** The average temperature is expected to drop from about 27.0°C to 25.5°C.
* **Weekly Pattern**: Temperatures tend to be **higher on Thursdays and Fridays** compared to other days of the week.

### 3. Data Characteristics
* **Distribution**: The temperature data follows a **Normal Distribution** (Skewness: -0.01).
* **Preprocessing**: Since the data is already normal, I did not need to perform any extra normalization before building the model.

## 🛠️ Tech Stack
* **Language**: Python
* **Key Libraries**: 
    * **Forecasting**: Facebook Prophet
    * **Optimization**: Optuna
    * **Data Analysis**: Pandas, NumPy
    * **Visualization**: Matplotlib, Seaborn
    * **Metrics**: Scikit-learn (MAPE)

## 📂 Data Source
The dataset is **Thailand Weather 2022 - 2025** from NASA, available on [Kaggle](https://www.kaggle.com/datasets/sakdaphoda/thai-weather-2022-2025/data?select=Thailand_Weather_NASA_2022_2025.csv).

<img width="584" height="453" alt="image" src="https://github.com/user-attachments/assets/a5166b25-2189-4687-bb15-9740556d0a8f" />

<img width="1389" height="1190" alt="image" src="https://github.com/user-attachments/assets/065434fd-b4eb-4d4d-b2ab-9842bb3038e1" />

<img width="886" height="890" alt="image" src="https://github.com/user-attachments/assets/6d00f12f-69f1-49d6-a31e-dc4270044beb" />
