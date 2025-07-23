# 🧾 Tunisia Tax Fraud Detection Project

This project uses supervised machine learning techniques to detect potential tax fraud in Tunisia, using real-world data provided by the Ministry of Finance. The goal is to support local tax authorities by building a predictive model that can flag suspicious tax returns with high accuracy.

---

## 📌 Objective

- Improve tax fraud detection accuracy using ML
- Handle missing data and outliers effectively
- Create advanced engineered features for better performance
- Reach the lowest possible **Root Mean Squared Error (RMSE)**

---

## 📁 Project Structure

| File/Folder            | Description |
|------------------------|-------------|
| `tax_fraud_detection_pipeline.ipynb` | Complete pipeline from loading data to model evaluation |
| `Report.pdf`           | Final project summary and presentation |
| `submission_enhanced.csv` | Final prediction submission file |
| `requirements.txt`     | Python dependencies |
| `README.md`            | Project documentation |

---

## 🧪 Model and Techniques

- **Model**: [LightGBM](https://lightgbm.readthedocs.io/) (fast gradient boosting)
- **Validation**: 7-Fold Cross-Validation
- **Encoding**: CatBoostEncoder + Target Encoding
- **Feature Engineering**:
  - Ratio and log-ratio features
  - Categorical interactions
  - Missing value indicators
  - Aggregated statistics

---

## 📊 Dataset Overview

- `Train.csv`: 15,000 rows with features and a `target` column
- `Test.csv`: 5,000 rows with features only
- `submission.csv`: Sample format for submission

---

## 🔍 Evaluation Metric

- **Root Mean Squared Error (RMSE)**
- Lower RMSE = better model performance

---

## ✅ Results

| Metric               | Value     |
|----------------------|-----------|
| Baseline RMSE        | 7.0856    |
| Final RMSE (OOF)     | **5.377** |
| Improvement          | ↓ ~24%    |

---

## 📉 Visualization

The notebook includes:
- Target distribution plots
- Missing value charts
- Feature importance plots
- Residual analysis
- Actual vs predicted comparison

---

## ⚙️ Tools and Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- LightGBM
- Category Encoders

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your_username/tax-fraud-detection-tunisia.git
   cd tax-fraud-detection-tunisia
