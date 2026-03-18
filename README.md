# 🚑 Cardiac Arrest Prediction in ICU Patients

## 📌 Overview
This project builds an end-to-end machine learning system to predict cardiac arrest risk in ICU patients using the MIMIC-IV dataset. The goal is early detection to improve clinical decision-making and patient outcomes.

---

## 🧠 Features
- 40+ clinical features (vitals, labs, demographics)
- Models Used:
  - Random Forest (Primary)
  - Logistic Regression (Baseline)
- Optimized for high recall in critical healthcare scenarios

---

## 📊 Model Performance

### Random Forest
- Accuracy: 1.00
- Precision: 1.00
- Recall: 1.00
- F1-Score: 1.00
- ROC-AUC: 1.00

### Logistic Regression
- Accuracy: 0.99
- Precision: 0.99
- Recall: 0.99
- F1-Score: 0.99

---

## 📈 Key Insights
- Mean Arterial Pressure (MAP) is the most important feature
- Heart rate contributes significantly to predictions
- Strong class separability observed in ROC curve and confusion matrix

---

## 📊 Visualizations
- Confusion Matrix
- ROC Curve
- Feature Importance Plot
- Correlation Heatmap
- Boxplots of vital signs

---

## 🌐 Web Application
- Flask-based UI for real-time prediction
- Input patient data → Get instant risk prediction
- Automated PDF report generation

---

## 🚀 How to Run

```bash
git clone https://github.com/Sahildas2003/Prediction-Of-Cardiac-Arrest.git
cd Prediction-Of-Cardiac-Arrest
pip install -r requirements.txt
python CardiacApp/app.py

## ⚠️ Note
This model uses proxy labels based on clinical thresholds, which may lead to near-perfect performance. Real-world performance may vary due to noisy and incomplete clinical data.
