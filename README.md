# 📊 Machine Learning Regression Models Project

This repository contains an interactive Jupyter Notebook (`AP22110011594.ipynb`) implementing and comparing multiple machine learning regression algorithms. The goal is to analyze performance across different models using metrics like **R², MSE, RMSE, and MAE**.

---

## ✨ Features
- Data preprocessing with NumPy and Pandas
- Exploratory data visualization using Matplotlib and Seaborn
- Implementation of multiple regression models:
  - Linear Regression
  - Lasso & Ridge Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - K-Nearest Neighbors Regressor
  - LightGBM Regressor
- Model evaluation with R², MSE, RMSE, MAE, ROC/AUC (for classification-like cases)
- Hyperparameter tuning via GridSearchCV

---

## 📂 Project Structure
```
AP22110011594.ipynb      # Main Jupyter Notebook
requirements.txt         # Dependencies
README.md                # Project documentation
data/                    # (Optional) Dataset files if provided separately
```

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ML-Regression-Comparison.git
   cd ML-Regression-Comparison
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook AP22110011594.ipynb
   ```

2. Run through the notebook cells:
   - Load dataset
   - Preprocess & visualize data
   - Train and evaluate models
   - Compare results across algorithms

3. Outputs include performance metrics and visual plots.

---

## 📊 Evaluation Metrics
- **R² (Coefficient of Determination)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **MAE (Mean Absolute Error)**
- **ROC & AUC** (for classification-style outputs)

---

## 🚀 Future Work
- Add more advanced models (XGBoost, CatBoost, Neural Networks)
- Implement cross-validation for more robust evaluation
- Deploy best model with a simple Flask/Django API or Streamlit app
