# 🌦️ Weather Prediction Model

A machine learning project that predicts weather conditions using classical ML algorithms, built and evaluated on 1,000+ real-world weather observations.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project explores and compares multiple machine learning models to predict weather outcomes based on historical weather and pollution data. The goal was to identify the most accurate and reliable model through systematic experimentation, feature engineering, and rigorous evaluation.

**Role:** Team Lead
**Dataset size:** 1,000+ weather observations

---

## 🚀 Key Highlights

- 🔍 Built and compared **three ML models**: Linear Regression, Logistic Regression, and Random Forest
- ⚙️ Applied **feature engineering** and **data normalization** to improve model performance
- 🏆 Achieved **91.5% accuracy** with an optimized Random Forest model
- 📊 Evaluated models using **R² scores** and **cross-validation** for robust performance assessment

---

## 🧠 Models Used

| Model | Purpose |
|---|---|
| Linear Regression | Baseline model for continuous weather variable prediction |
| Logistic Regression | Classification of weather categories |
| Random Forest | Final optimized model — best overall performance |

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn
- **Techniques:** Feature Engineering, Data Normalization, Cross-Validation

---

## 📂 Project Structure

```
Weather-Prediction/
│
├── WEATHER 11(2).ipynb              # Main notebook - model development & evaluation
├── weatherproject (1) (1).ipynb     # Supporting notebook - data exploration/experiments
├── weather_pollution_1000.csv       # Dataset (1,000+ weather observations)
├── .gitignore
└── README.md
```

---

## 📈 Methodology

1. **Data Preprocessing** — Cleaned and normalized raw weather and pollution data
2. **Feature Engineering** — Selected and transformed relevant features to boost model signal
3. **Model Training** — Trained Linear Regression, Logistic Regression, and Random Forest models
4. **Model Evaluation** — Compared models using R² scores and cross-validation
5. **Optimization** — Tuned the Random Forest model to achieve the best performance

---

## 📊 Results

| Metric | Result |
|---|---|
| Best Model | Random Forest |
| Accuracy | **91.5%** |
| Evaluation Methods | R² Score, Cross-Validation |

---

## ⚙️ Installation & Usage

```bash
# Clone the repository
git clone https://github.com/salmaahmed11/Weather-Prediction.git
cd Weather-Prediction

# (Recommended) create a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook "WEATHER  11(2).ipynb"
```

---

## 👩‍💻 Author

**Salma Ahmed** — Team Lead
[GitHub](https://github.com/salmaahmed11)

---

## 📄 License

This project is open source and available for educational and research purposes.
