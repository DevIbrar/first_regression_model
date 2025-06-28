# first_regression_model
# First Regression Model – Energy Consumption Prediction

This project implements a simple linear regression model to predict energy consumption based on various building and environmental features. The dataset used is from a Kaggle competition focused on energy consumption.

---

## 📁 Dataset

- **Train Data:** `train_energy_data.csv`  
- **Test Data:** `test_energy_data.csv`  
- Source: [Kaggle Energy Consumption Dataset](https://www.kaggle.com/datasets/govindaramsriram/energy-consumption-dataset-linear-regression/code?datasetId=6435081&sortBy=dateRun&tab=profile&excludeNonAccessedDatasources=false)

---

## 🛠️ Features Used

- Building Type (mapped to numerical values)
- Building Size
- Temperature
- Humidity
- Day of Week (Weekday/Weekend)
- Hour of the Day

---

## 🧠 Model Used

- **Algorithm:** Linear Regression  
- **Library:** `scikit-learn`

---

## 📈 Evaluation Metrics

- **R² Score**
- **Mean Squared Error (MSE)**

---

## 🔄 Data Preprocessing

- Dropped missing values using `.dropna()`
- Encoded categorical values:
  - `"Residential"` → `1`, `"Commercial"` → `2`, `"Industrial"` → `3`
  - `"Weekday"` → `1`, `"Weekend"` → `0`

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/DevIbrar/first_regression_model.git
   cd first_regression_model
