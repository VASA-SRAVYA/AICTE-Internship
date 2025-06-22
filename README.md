# 🌱 GHG Emissions Prediction Using Industry & Commodity Data (2010–2016)

This project focuses on modeling and predicting **Greenhouse Gas (GHG) emissions** from U.S. industries and commodities using official supply chain data (2010–2016).

---

## 📌 Objective

To build machine learning regression models that can accurately predict `GHG_Emissions_kgCO2e` based on descriptive and quality attributes such as substance, units, data reliability, temporal and geographical relevance, etc.

---

## 📂 Dataset Overview

**Key Features**:
- `Code`: Industry classification code
- `Industry_Name`: Name of the industry
- `Commodity`: Product/Service
- `GHG_Emissions_kgCO2e`: Emissions per unit (kg CO₂e)
- `Units`: Measurement units (e.g., kg/2018 USD)

---

## 🧹 Data Preprocessing

Performed preprocessing steps include:
- Handling missing values
- Unit normalization (if required)
- Encoding categorical variables
- Scaling numeric features
- Exploratory Data Analysis (EDA)

---

## 🤖 Model Building

### Models Used:
- 📈 Linear Regression
- 🌲 Random Forest Regressor

### Evaluation Metrics:
- ✅ **R² Score**
- ❌ **Mean Absolute Error (MAE)**
- ⚠️ **Root Mean Squared Error (RMSE)**

---

## 🚀 Workflow Steps

1. Import required libraries  
2. Load and explore the dataset  
3. Preprocess and encode data  
4. Train regression models  
5. Evaluate performance  
6. Tune hyperparameters  
7. Compare models and finalize the best one

---

## 🛠 Tools & Libraries

- Python 3.x  
- `pandas`, `numpy`  
- `scikit-learn`  
- `matplotlib`, `seaborn`

---



