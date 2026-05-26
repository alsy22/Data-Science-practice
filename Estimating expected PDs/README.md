## Credit Risk Modeling (PD Estimation)

This project implements an end‑to‑end machine‑learning pipeline for estimating the probability of default (PD) using firm‑level financial data. It demonstrates practical skills in data preparation, model development, evaluation, and interpretability — all core components of real‑world credit risk analytics.

### 🎯 Project Overview 
This notebook walks through the full workflow for building and comparing PD models:
- **Data preprocessing** and train/test splitting
- **Scaling** and handling **class imbalance**
- training Logistic Regression, Decision Tree, Random Forest, and XGBoost
- **Model evaluation** using recall and ROC-AUC
- **Feature importance** selection
- **Final model selection**
- Retraining on full data to generate **PD estimates**

The analysis identifies **XGBoost** as the best‑performing model, with **Logistic Regression** retained as an interpretable benchmark.

### 💼 Business Relevance
Estimating PD is a foundational task in:
- Banking
- Fintech
- Insurance
- B2B lending
- Credit analytics teams

Organizations rely on PD models to:
- Segment borrowers
- Price loans
- Allocate capital
- Monitor portfolio risk
- Support regulatory reporting

This project mirrors a real‑world credit‑risk workflow by:
- Building a reproducible modeling pipeline
- Comparing multiple algorithms
- Incorporating interpretability tools
- Producing actionable insights from structured financial data

It highlights competencies directly relevant to data science roles in financial services and risk analytics.

### Folder Structure

Credit‑risk modeling/ <br>
└── Estimating expected PDs.ipynb <br>
└── README.md

### Workflow

Data → Preprocessing → Train/Test Split → Model Training → Evaluation → Top‑5 Features → Final Model → PD Estimation

**Main file:** `Estimating expected PDs.ipynb`
