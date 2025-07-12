# 🔌 Electricity Cost Prediction Using Linear Regression

This project applies **Linear Regression** to predict electricity costs based on given features in a structured dataset. It demonstrates how to train, evaluate, and visualize a regression model using Scikit-learn and Matplotlib.

---

## 📁 Dataset

- **Source**: `electricity_cost_dataset.csv`
- **Target Variable**: `electricity cost`
- **Features**: One or more numeric or categorical features that influence electricity cost (e.g., usage, region, time, etc.)

> **Note**: Ensure the dataset is located at `/content/electricity-cost-prediction-dataset/electricity_cost_dataset.csv` or modify the path accordingly.

---

## 📊 Objective

To build a model that can **predict electricity costs** based on relevant features using **Linear Regression**, and evaluate its performance using standard regression metrics and visualizations.

---

## 🛠️ Tools and Libraries Used

- Python 🐍
- pandas
- scikit-learn
- matplotlib
- seaborn

---

## 🚀 Steps Performed

### 1. Load and Preprocess Data
```python
df = pd.read_csv("electricity_cost_dataset.csv")
x = df.drop("electricity cost", axis=1)
y = df["electricity cost"]
