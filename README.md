# Algerian Forest Fires - Fire Weather Index (FWI) Prediction

This repository contains an end-to-end Machine Learning project focused on predicting the **Fire Weather Index (FWI)** of forest fires in Algeria using meteorological data. The dataset includes observations from two regions: Bejaia and Sidi Bel-Abbes.

---

## 📊 Dataset Overview
The dataset contains 243 instances with 14 attributes representing weather conditions and forest fire metrics:
* **Date:** Day, Month, Year
* **Weather Observations:** Temperature, Relative Humidity (`RH`), Wind Speed (`Ws`), Rain
* **FWI Components:** `FFMC`, `DMC`, `DC`, `ISI`, `BUI`, `FWI`
* **Target Variable:** `FWI` (Fire Weather Index) / Binary classification (`Classes`: fire / not fire)

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning & Preprocessing:** Scikit-Learn (`StandardScaler`, `LinearRegression`, `Lasso`, `LassoCV`)

---

## ⚙️ Project Workflow
1. **Data Cleaning & Preprocessing:**
   * Handling missing values and correcting formatting/typographical errors in column names and data types.
   * Encoding categorical target variables (`Classes`).
   * Combining regional datasets with proper region labeling.
2. **Exploratory Data Analysis (EDA):**
   * Analyzing feature correlations and distributions using statistical plots and heatmaps.
3. **Model Training & Evaluation:**
   * Splitting data into training and testing sets (80/20).
   * Feature scaling using `StandardScaler`.
   * Training and evaluating models including **Linear Regression**, **Lasso**, and **LassoCV**.

---

## 📈 Results & Performance
The regression models achieved high accuracy in predicting the Fire Weather Index (`FWI`):
* **Linear Regression:** $R^2 \approx 0.987$, MAE $\approx 0.49$
* **LassoCV:** $R^2 \approx 0.987$, MAE $\approx 0.41$

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/algerian-forest-fires-fwi-prediction.git](https://github.com/YOUR_USERNAME/algerian-forest-fires-fwi-prediction.git)
   cd algerian-forest-fires-fwi-prediction
