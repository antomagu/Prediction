# Prediction
Analysis and prediction of monthly spending by category

# 💳 BBVA Spending Analysis and Prediction

A **Data Science and Predictive Analytics** project focused on credit card spending in Mexico, using BBVA's public dataset.

---

## 🎯 Objective

To analyze the evolution of monthly spending by category,
identify the most influential categories in total spending,
and generate 6-month spending projections.

---

## 📘 Dataset Description

The data was downloaded from BBVA Data.

The dataset **is already clean and structured**, so the analysis focuses on **exploration, correlation, predictive modeling, and visualization.**

Main variables:
- `Date`
- `Total` (total monthly spending)
- Spending categories (`Goods`, `Services`, `Food`, etc.)
- Change variables: `Year-over-year` and `Quarter-over-quarter`

---

## 🧠 Methodology

1. **Exploration and correlation analysis**

- Identification of the categories most closely related to total spending.

2. **Predictive modeling**

- Model: **Random Forest Regressor**

- Evaluation: MAE, RMSE, R²

- Additional variables: seasonality with `month_without` and `month_with`.

3. **Spending projection**

- Total spending projected for 6 months.

- Projection by category with average monthly growth.

4. **Monthly Segmentation (KMeans)**

- Grouping according to similar consumption patterns.

- Identification of monthly behavior types.

--

## 📊 Results

- **Model Accuracy (R²):** 0.99
- **Most Influential Categories:** Goods and Services
- **Projection:** Stable trend with slight natural variations.

- **Segmentation:** Three clusters representing different types of monthly consumption.

--

## 🧩 Files


`notebooks/Prediccion_Gasto_BBVA.ipynb` | Notebook with the complete analysis and modeling workflow |


## 🛠️ Libraries

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
