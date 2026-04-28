## Credit Risk Modeling (PD Estimation)
This folder contains the end‑to‑end workflow for building probability‑of‑default (PD) models using firm‑level financial data. The notebook covers:
- data preprocessing and train/test splitting
- scaling and handling class imbalance
- training Logistic Regression, Decision Tree, Random Forest, and XGBoost
- model evaluation using recall and ROC AUC
- selecting the final model
- extracting and comparing top‑5 features
- retraining on full data to generate PDs

The analysis identifies **XGBoost** as the best‑performing model, with **Logistic Regression** retained as an interpretable benchmark.

This project is designed to showcase practical skills in building end‑to‑end machine‑learning solutions for real‑world business problems. Credit risk modelling is a core application area in many industries—banking, fintech, insurance, and B2B lending—and estimating the probability of default is central to decision‑making in those environments. By developing a full modelling pipeline, comparing multiple algorithms, and incorporating interpretability techniques such as SHAP, the project demonstrates the ability to work with structured financial data, evaluate model performance, and extract actionable insights. It highlights competencies that are directly relevant to industry roles, including data preparation, model development, performance assessment, and communicating results in a way that supports risk‑driven business decisions.

### Folder Structure

Credit‑risk modeling/ <br>
└── Estimating expected PDs.ipynb <br>
└── README.md

### Workflow

Data → Preprocessing → Train/Test Split → Model Training → Evaluation → Top‑5 Features → Final Model → PD Estimation

**Main file:** `Estimating expected PDs.ipynb`
