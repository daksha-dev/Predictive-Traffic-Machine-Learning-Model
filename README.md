# 🚦 Predictive-Traffic-Machine-Learning-Model

This project is a research-oriented practice task focused on predicting traffic congestion levels using machine learning models. Two popular algorithms—**Random Forest Classification** and **Support Vector Regression (SVR)**—were implemented and compared for their effectiveness in modeling traffic patterns.

---

## 📊 Overview

The primary goal is to forecast traffic congestion based on temporal and environmental features. The dataset has been preprocessed with encoded values to make it suitable for model training and evaluation.

---

## 📁 Dataset Description

The dataset includes the following columns:

- **📅 Date**: Captures the date in the format `DD/MM/YYYY`.
- **🗓️ Day**: Specifies the day of the week (e.g., Monday, Tuesday) to help correlate traffic with weekdays.
- **🔢 Coded Day**: Numeric encoding of weekdays for easier model processing:
  - Monday: 1  
  - Tuesday: 2  
  - Wednesday: 3  
  - Thursday: 4  
  - Friday: 5  
  - Saturday: 6  
  - Sunday: 7  
- **🌍 Zone**: Identifies the geographical zone; associated with localized weather conditions (humidity, mist, visibility, precipitation).
- **🌡️ Temperature**: The recorded temperature for the respective zone and date; temperature is considered a factor influencing traffic flow.
- **🚗 Traffic**: The target variable—traffic volume—categorized on a 5-point scale:
  - 1 → Fewer than 5 cars  
  - 2 → 5–15 cars  
  - 3 → 15–30 cars  
  - 4 → 30–50 cars  
  - 5 → More than 50 cars  

---

## 🧠 Models & Results

| Model                         | Error (%) | Accuracy (%) |
|-------------------------------|-----------|---------------|
| Random Forest Classifier      | 13.42     | 86.58         |
| Support Vector Regression (SVR) | 12.16     | 87.84         |

Both models perform well, with SVR showing slightly better accuracy. The results validate the feasibility of using supervised learning techniques for traffic prediction based on day, weather, and temperature.

---

## 📚 References

https://github.com/atharva-hukkeri/Traffic-Prediction-using-Machine-Learning
