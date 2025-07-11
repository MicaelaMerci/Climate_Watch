# Climate_Watch
# 🌍 Forecasting CO2 Emissions Using Environmental Data (SDG 13: Climate Action)

This project applies supervised machine learning to predict **CO2 Emissions** based on environmental indicators. It is part of the **PLP Academy Week 2 Assignment** under the theme: _"Machine Learning Meets the UN Sustainable Development Goals (SDGs)"_.

---

## 🎯 Objective

To build a machine learning model that predicts **CO2 emissions** using climate-related features such as temperature, sea level rise, precipitation, humidity, and wind speed. This aligns with **SDG 13: Climate Action**, helping stakeholders monitor and address climate change more effectively.

---

## 📂 Dataset

**Filename**: `DATA_ONE.csv`  
**Columns**:
- `Date`
- `Location`
- `Country`
- `Temperature`
- `CO2 Emissions` *(Target Variable)*
- `Sea Level Rise`
- `Precipitation`
- `Humidity`
- `Wind Speed`

---

## 🛠️ Tools & Technologies

- Python (Jupyter Notebook)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`
- Models Used:
  - Linear Regression
  - Random Forest Regressor

---

## 📈 Workflow

1. **Data Loading & Exploration**
2. **Preprocessing**
   - Dropping/encoding non-numeric features
   - Handling missing values
   - Feature scaling with `StandardScaler`
3. **Model Training**
   - Linear Regression
   - Random Forest Regressor
4. **Evaluation**
   - R² Score
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
5. **Visualization**
   - Feature importance
   - Correlation heatmap
   - Actual vs predicted scatter plots
6. **Model Saving**
   - Exported with `joblib`
7. **Ethical Reflection**
   - Discusses fairness, bias, and sustainability considerations

---

## 💾 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

