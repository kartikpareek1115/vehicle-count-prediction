# vehicle-count-prediction
ML project to predict vehicle count from timestamp features

# Final Vehicle Count Prediction using Machine Learning

This project uses timestamp features to **predict the number of vehicles** passing a traffic sensor. It demonstrates a complete machine learning pipeline including data preprocessing, feature extraction, model training, evaluation, and visualization.

---

## Files Included

| File Name                          | Description                                  |
|-----------------------------------|----------------------------------------------|
| `Final_Vehicle_Count_Prediction.ipynb` | Jupyter Notebook with complete ML pipeline |
| `vehicles.csv`                    | Sample dataset with hourly vehicle counts   |

---

## Problem Statement

Predict the number of vehicles on the road based on **DateTime-derived features** like:
- Hour of the day
- Weekday
- Day of month
- Month
- Year
- Day of year
- Week of year

---

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Random Forest, Linear Regression, Metrics)
- Jupyter Notebook

---

## Steps Performed
1. **Data Cleaning & Feature Engineering**
2. **Datetime Feature Extraction**
3. **Exploratory Data Analysis (EDA)**
4. **Model Training**
   - Linear Regression
   - Random Forest Regressor
5. **Model Evaluation**
   - MAE, MSE, R² Score
6. **Feature Importance**
7. **Prediction on New Input**

---

## Sample Prediction

```python
Input: [hour=11, weekday=6, day=1, month=11, year=2015, dayofyear=305, weekofyear=44]
Output: Predicted vehicle count ≈ 25
