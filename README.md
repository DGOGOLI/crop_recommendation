# 🌾 Crop Recommendation System

This project uses machine learning to recommend the most suitable crop to grow based on soil and climate conditions.

## 📄 Dataset

The dataset (from Kaggle) includes features like:

- Nitrogen (N), Phosphorus (P), Potassium (K)
- Temperature, Humidity
- pH, Rainfall
- Target crop label (e.g., rice, maize, cotton...)

## ⚙️ Model

A simple **Random Forest Classifier** is trained on the data. Other models were tested too, but RF gave solid results. Here's a simplified pipeline:

```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)
```

## 🚧 Work in Progrss

This is an early version — more improvements and a proper interface will be added later.