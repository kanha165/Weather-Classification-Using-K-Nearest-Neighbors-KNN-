# 🌦 Weather Classification Using K-Nearest Neighbors (KNN)

This project is a **Machine Learning–based weather classification system** that predicts weather conditions using the **(KNN)** algorithm. The model is trained on **real-world meteorological data** to accurately classify different weather types such as **Sunny, Rainy, Cloudy, Humid, and Cold** based on atmospheric features.

---

## 📌 Project Objective
To predict the **type of weather** (Sunny, Rainy, Cloudy, etc.) using historical weather data such as:
- Temperature
- Humidity
- Wind Speed
- Precipitation
- Atmospheric Pressure
- UV Index
- Visibility

The main objective of this project is to:
- Build a **reliable weather prediction system**
- Use **historical weather data** to classify current conditions
- Demonstrate the working of the **KNN algorithm** in a real-world application
- Provide a **beginner-friendly Machine Learning project** for academic and practical use

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Pickle

---

## 📁 Project Structure
KNN classifier/
│
├── weather_data.csv
├── train_model.py
├── test_model.py
├── knn_weather_model.pkl
├── scaler.pkl
├── encoder.pkl
├── README.md


---

## 📊 Dataset Information
The dataset contains the following columns:

- Temperature
- Humidity
- Wind Speed
- Precipitation (%)
- Cloud Cover
- Atmospheric Pressure
- UV Index
- Season
- Visibility (km)
- Location
- Weather Type (Target)

Only **numeric columns** are used for training the KNN model.

---

## ⚙️ How to Run the Project

### 1️⃣ Install Required Libraries
```bash
pip install -r requirements.txt

2️⃣ Train the Model:  >>>run>>   python train_model.py


This will generate:

knn_weather_model.pkl

scaler.pkl

encoder.pkl



3️⃣ Test the Model (Live Prediction) >>run >>python test_model.py

✅ Algorithm Used

K-Nearest Neighbors (KNN)

Distance Metric: Euclidean Distance

Feature Scaling: StandardScaler

Label Encoding: LabelEncoder




🎯 Applications

Weather Forecasting Systems

Smart Agriculture

Disaster Management

Aviation Safety

Smart Cities




👨‍💻 Author

Kanha Patidar
B.Tech (CSIT)
Machine Learning Enthusiast



