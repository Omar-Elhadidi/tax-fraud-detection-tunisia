# 🧾 Tunisia Tax Fraud Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![LightGBM](https://img.shields.io/badge/Model-LightGBM-brightgreen)
![Competition](https://img.shields.io/badge/Zindi-6th%20Place%20Worldwide-gold)

> Detecting tax fraud in Tunisia using supervised machine learning on real Ministry of Finance data — achieving **6th place out of 286 teams** worldwide on the Zindi leaderboard.

---

## 🏆 Achievement

<img width="1919" height="807" alt="Screenshot 2026-05-21 041907" src="https://github.com/user-attachments/assets/976368d3-0e9f-48af-8c94-b3bb860d9022" />

Ranked **#6 globally out of 286 participants** in the [Tunisian Fraud Detection Challenge on Zindi](https://zindi.africa/competitions/tunisian-fraud-detection).

---

## 📌 Objective

- Improve tax fraud detection accuracy using ML
- Handle missing data and outliers effectively
- Create advanced engineered features for better performance
- Reach the lowest possible **Root Mean Squared Error (RMSE)**

---

## 🔗 Data Source

This project is based on the [Tunisian Fraud Detection Challenge on Zindi](https://zindi.africa/competitions/tunisian-fraud-detection)  
which provides the data and problem definition used here.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `tunisia_tax_fraud_model.ipynb` | Complete pipeline from loading data to model evaluation |
| `Report.pdf` | Final project summary and presentation |
| `Submission_Enhanced.csv` | Final prediction submission file |
| `README.md` | Project documentation |

---

## 🧪 Model & Techniques

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

| File | Description |
|------|-------------|
| `Train.csv` | 15,000 rows with features and a `target` column |
| `Test.csv` | 5,000 rows with features only |
| `submission.csv` | Sample format for submission |

---

## 🔍 Evaluation Metric

- **Root Mean Squared Error (RMSE)**
- Lower RMSE = better model performance

---

## ✅ Results

| Metric | Value |
|--------|-------|
| Baseline RMSE | 7.0856 |
| Final RMSE (OOF) | **5.377** |
| Improvement | ↓ ~24% |
| **Leaderboard Rank** | **🥇 6th / 286** |

---

## 📉 Visualizations

The notebook includes:
- Target distribution plots
- Missing value charts
- Feature importance plots
- Residual analysis
- Actual vs predicted comparison

---

## ⚙️ Tools & Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- LightGBM
- Category Encoders

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Omar-Elhadidi/tax-fraud-detection-tunisia.git
cd tax-fraud-detection-tunisia

# 2. Install dependencies
pip install lightgbm scikit-learn pandas numpy matplotlib seaborn category_encoders

# 3. Open the notebook
jupyter notebook tunisia_tax_fraud_model.ipynb
```

---

## 👨‍💻 Author

**Omar Elhadidi**  
[GitHub](https://github.com/Omar-Elhadidi) 
