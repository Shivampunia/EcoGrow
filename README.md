# EcoGrow
# 🌱 EcoGrow: AI-Powered Air Quality Prediction & Plant Recommendation System

(![WhatsApp Image 2025-06-25 at 11 55 06 PM](https://github.com/user-attachments/assets/f913843f-a9f6-4d18-8446-35928652611a)
) <!-- Replace with your app screenshot -->

---

## 📌 Overview

**EcoGrow** is a smart AI-driven system that tackles Delhi's pollution crisis by **predicting future air quality trends** and **recommending the best pollution-absorbing plants** for each region.

It uses **machine learning models**, **multi-source datasets**, and **time series forecasting** to guide eco-friendly actions like tree planting, tied to a **rewards-based web dashboard**.

---

## 🧠 How It Works

1. 🗺️ User selects or enters location (Delhi area)
2. 📊 Pollution data is fetched for that area (historical trends)
3. 🌾 Plant database filters species suitable to local **soil**, **climate**, and **pollution type**
4. 🔮 ML models predict future PM2.5 levels
5. 🌱 Output: **Future AQI trend + Recommended plants**
6. 🪙 Optional: Reward system via QR tracking and metro discounts (planned)

---

## 🎯 Key Features

- 📈 Forecast PM2.5 levels using ML & time series analysis
- 🌿 Suggest optimal plant species per location
- 🧠 AI pipeline combining multiple datasets
- 🌍 Dashboard UI to engage citizens & track eco-impact
- 📡 Future scope: Live IoT sensor integration

---

## 🧱 ML Models Overview

| Model      | Dataset Used             | Purpose                                 |
|------------|--------------------------|-----------------------------------------|
| **Model 1**| Delhi PM2.5 dataset (5 zones) | Time series prediction using SARIMA     |
| **Model 2**| Plant DB (pollution absorb %, soil type, size, care needs) | Plant matching by environmental data    |
| **Model 3**| Combined pipeline model   | AI fusion: Predict pollution + plant fit|

- 📁 All models are developed using **Jupyter Notebooks** (`notebooks/`)
- 🧪 Forecasting accuracy validated with RMSE
- 🔁 ML pipeline built with Scikit-learn + custom logic

---
🖥️ Website Dashboard
- 🌍 Built as a prototype front-end UI for public interaction

- 🔎 User enters Delhi location

- 🧾 Output: Predicted pollution levels + plant suggestions

- 💡 Dashboard provides education, eco-suggestions, and future impact visualization

🧠 Technologies Used

- Python, Pandas, NumPy, Matplotlib

- Scikit-learn, SARIMA, Time Series Forecasting

- Jupyter Notebooks

- HTML/CSS (for dashboard prototype)

- Google Maps API (optional future)
 
📈 Results & Impact

- ✅ Trained SARIMA model predicts PM2.5 trends with <15% error

- 🌿 Smart filtering logic matches plants to soil & climate

- 📊 Visualization of trends + recommendation card on dashboard

- 🔗 Ready for integration with IoT sensors (future)

📣 Acknowledgments

- Data sources: CPCB, Delhi Open Data, Kaggle plant databases

- Ideathon mentors and Smart Delhi challenge jury

- Python, Scikit-learn, and the open-source ML community 🙏




