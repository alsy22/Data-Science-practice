## Data Science Practice Notebooks (Python)

A collection of Jupyter notebooks created for self‑learning and hands‑on practice in data science, machine learning, and applied analytics. Each notebook explores a specific method, model, or dataset, with a focus on practical implementation and interpretation.

---

### 📂 Contents

#### 1. Estimating Expected Probability of Default
**Techniques used:** Logistic Regression, Decision Trees, Random Forest, XGBoost  
**Description:**  
Builds and compares multiple classification models to estimate the expected probability of default (PD). Includes model training, evaluation metrics and feature importance.

---

#### 2. K‑Means Clustering for Startup Characteristics
**Inspired by:** De Haas et al. (2022)  
**Features:** leverage, liquidity, tangibility, size (assets & employees)  
**Description:**  
Uses k‑means clustering to uncover natural groupings among startups based on financial and structural characteristics. Includes preprocessing, scaling, cluster evaluation, and visualization.

---

#### 3. Interactive Map Visualizations
**Tools:** Plotly  
**Description:**  
Creates interactive geographic visualizations using Plotly, demonstrating how to map spatial data and customize map layers, colors, and hover information.

---

#### 4. Tariff Announcement (April 2025) — Exploratory Data Analysis
**Description:**  
Performs simple data analysis around the initial announcement of tariffs in April 2025. Includes basic visualization.

---

#### 5. Retrieving Financial Market Data with yFinance
**Data retrieved:** individual stocks, stock indices, bond yields  
**Description:**  
Demonstrates how to retrieve financial market data using `yfinance`, visualize time series, and compute metrics such as:
- Cumulative Abnormal Returns (CAR) around the Silicon Valley Bank collapse  
- Event‑study regression related to the SVB collapse  

Includes event windows, abnormal return calculations, and regression modeling.

---

### 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**

#### Core Libraries
- pandas  
- NumPy  
- matplotlib  
- seaborn  

#### Machine Learning & Modeling
- scikit‑learn  
  - LogisticRegression  
  - DecisionTreeClassifier  
  - RandomForestClassifier / RandomForestRegressor  
  - KMeans  
  - preprocessing (StandardScaler, MinMaxScaler)  
  - model evaluation tools (ROC AUC, precision/recall, confusion matrix, etc.)
- XGBoost (XGBClassifier)  
- shap (model explainability)

#### Data & Visualization Tools
- Plotly (interactive maps)  
- yFinance (market data retrieval)

#### Statistical & Econometric Tools
- statsmodels  
- eventstudy (event‑study analysis)


---

### 🎯 Purpose
This repository documents my self‑learning journey in data science. Each notebook focuses on applying a specific method or concept to real datasets, emphasizing practical understanding.


