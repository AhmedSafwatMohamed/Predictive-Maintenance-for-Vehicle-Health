
# 🚗 Predictive Maintenance for Vehicle Health

This project aims to predict potential failures in vehicle components using machine learning techniques. By analyzing historical vehicle sensor data and service records, the model can identify patterns that indicate upcoming issues, allowing proactive maintenance.

---

## 📊 Project Overview

- **Objective:** Forecast vehicle failures before they happen to reduce downtime and improve reliability.
- **Tools Used:** Python (Scikit-learn, XGBoost), Power BI.
- **Data:** Historical vehicle sensor readings and maintenance logs.

---

## 📁 Repository Structure

```
├── Exploration.ipynb       # EDA and data visualization
├── Modeling.ipynb          # Feature engineering and model training
├── powerbi/                # Power BI dashboard and .pbix file
└── README.md               # Project documentation
```

---

## 🔍 Exploratory Analysis

- Examined key features from the dataset such as:
  - Error codes
  - Sensor readings
  - Component service history
- Identified trends and outliers in system behavior before failure events.

---

## 🧠 Modeling

Trained and evaluated the following classification models:

- **Random Forest**
- **XGBoost**

**Evaluation Metrics:**

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

These metrics were used to compare model performance and select the best predictor.

---

## 📈 Power BI Dashboard

The dashboard presents:

- Predicted failure probabilities
- Component-level risk scores
- Vehicle condition trends over time

This visualization helps maintenance teams quickly interpret model outputs and prioritize service actions.

---

## ✅ Conclusion

By integrating machine learning and visual analytics, this project supports predictive maintenance strategies—improving vehicle uptime and operational efficiency.

---

## 📬 Contact

Developed by **Ahmed Safwat Mohamed**  
For questions or suggestions, feel free to reach out via GitHub Issues.
