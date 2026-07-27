# 🌱 ESG Score Prediction Using Machine Learning

> **Predicting Environmental, Social, and Governance (ESG) scores from financial and sustainability indicators using advanced Machine Learning models.**

---

## 📌 Project Overview

Environmental, Social, and Governance (ESG) performance has become a critical factor in investment decisions, corporate governance, and sustainability reporting. However, comprehensive ESG assessments often require extensive data collection, expert analysis, and periodic evaluations, making them expensive and time-consuming.

This project develops an end-to-end Machine Learning framework capable of predicting a company's ESG score using publicly available financial and environmental indicators. By leveraging historical company data, the model identifies the key business factors influencing ESG performance and provides reliable sustainability score predictions.

The project demonstrates how Artificial Intelligence can complement traditional ESG assessment methods by enabling faster, scalable, and data-driven sustainability evaluation.

---

## 🎯 Problem Statement

Organizations, investors, and financial institutions increasingly rely on ESG scores to assess long-term sustainability and business risk. Unfortunately,

* ESG ratings are not available for every company.
* Different rating agencies often produce inconsistent scores.
* Traditional ESG assessment is resource-intensive.
* Smaller organizations frequently lack formal ESG evaluations.

This project addresses these challenges by building a predictive Machine Learning model capable of estimating ESG scores from financial and sustainability metrics, enabling organizations to benchmark performance and investors to make more informed decisions.

---

## 📊 Dataset

The project utilizes a **panel dataset** containing company-level financial and sustainability information collected over multiple years.

**Dataset Highlights**

* 📅 Time Period: **2015 – 2025**
* 🏢 Companies: **1100**
* 📈 Total Observations: **11,000**
* 🎯 Target Variable: **ESG Score**
* 📋 Features: Financial, Environmental and Engineered Sustainability Indicators

Example variables include:

* Revenue
* Total Assets
* Profitability Metrics
* Leverage
* Liquidity
* Carbon Emissions
* Energy Consumption
* Water Usage
* Carbon Intensity
* Energy Intensity
* Water Intensity

---

# 🚀 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Development
        │
        ▼
Cross Validation
        │
        ▼
Model Evaluation
        │
        ▼
Best Model Selection
        │
        ▼
Feature Importance

```

The project follows a complete machine learning lifecycle beginning with raw data preparation and ending with business interpretation of model predictions.

---

# ⚙️ Feature Engineering

Several business-oriented features were engineered to improve model performance and better represent sustainability efficiency.

Key engineered variables include:

* Carbon Intensity
* Energy Intensity
* Water Intensity
* Log Revenue
* Log Total Assets

These variables normalize company size differences and allow more meaningful comparisons between organizations of varying scales.

---

# 🤖 Machine Learning Models

Three regression models were developed and compared.

| Model             | Purpose                                   |
| ----------------- | ----------------------------------------- |
| Linear Regression | Baseline model                            |
| Random Forest     | Captures complex non-linear relationships |
| XGBoost           | Optimized boosting algorithm              |

Each model was trained under identical conditions and evaluated using the same performance metrics.

---

# 📈 Model Performance

| Metric                 |       Value |
| ---------------------- | ----------: |
| Best Model             | **Linear Regression** |
| R² Score               |   **0.65** |
| RMSE                   |   **9.58** |
| MAE                    |   **7.75** |

---

# 🏆 Final Model

After comparing multiple regression algorithms, **Linear Regression** delivered the strongest predictive performance.

### Why Linear Regression?

* Highest predictive accuracy
* Lowest prediction error
* Excellent generalization capability
* Captured complex non-linear relationships
* Consistent performance during cross-validation
* 
---

# 🔍 Feature Importance

The model identified several variables that have the greatest influence on ESG performance.

### Top Predictive Features

1. **carbonemissions**
2. **energyconsumption**
3. **industry_manufacturing**
4. **industry_transportation**
5. **waterusage**

---

# 💡 Business Insights

The project provides several practical insights for organizations and investors.

✔ Companies with greater resource efficiency tend to achieve stronger ESG performance.

✔ Environmental intensity metrics are more informative than absolute resource consumption.

✔ Financial strength alone does not determine ESG success; efficient utilization of environmental resources is equally important.

✔ Machine Learning can provide reliable ESG estimates for companies lacking formal ESG ratings.

✔ Data-driven ESG prediction can support investment screening, sustainability benchmarking, and strategic decision-making.

---

# 📂 Repository Structure

```
ESG-Score-Prediction/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── ESG_Prediction.ipynb
│
├── requirements.txt
├── README.md
```

---

# 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* CatBoost
* Matplotlib
* Seaborn
* SHAP *(if implemented)*

---

# 🎯 Future Improvements

Future enhancements to the project include:

* Integration of real-time ESG reporting data.
* Inclusion of macroeconomic and industry-specific indicators.
* Expansion to global company datasets.
* Deployment as an interactive web application.
* Enhanced explainability using SHAP and other Explainable AI techniques.

---

# 👩‍💻 Author

**Sneha Vyas**

Ph.D. Economics | Data Analyst | Machine Learning Enthusiast

**Areas of Interest**

* Machine Learning
* ESG Analytics
* Business Analytics
* Predictive Modeling
* Sustainability Analytics
* Data Science
