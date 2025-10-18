
***

# Boston Housing Regression Tree Project

This project demonstrates how to build and evaluate a **Decision Tree Regressor** for predicting housing prices using the classic Boston Housing dataset.

## 📁 Project Overview
- **Goal:** Predict the median value of owner-occupied homes (MEDV) in Boston using various socio-economic and structural features found in the dataset.
- **Method:** Regression Tree (DecisionTreeRegressor from scikit-learn).
- **Dataset:** `Boston.csv` (contains 506 rows, 14 features like CRIM, ZN, INDUS, RM, etc.)

## 👩‍💻 Author
Sarah S V
B.Tech – Artificial Intelligence & Data Science
Rajalakshmi Institute of Technology, Chennai
📧 sarahsv.codes@gmail.com
LinkedIn: https://www.linkedin.com/in/sarahsv3107/

## 🛠️ Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- [Optional] seaborn

Install dependencies with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🚀 Usage
1. **Add Data File**: Place `Boston.csv` in the same folder as your notebook/script.
2. **Run Notebook**: Open `RegressionTrees.ipynb` in Jupyter or Colab and execute all cells.
3. **Main Steps**:
    - Data loading, inspection, and exploration
    - Feature/target extraction: Features (all columns except MEDV), Target (MEDV)
    - Data normalization (StandardScaler)
    - Train-test split (commonly 80:20 or 70:30)
    - Model training with DecisionTreeRegressor
    - Predictions and performance evaluation (Mean Squared Error, R² score)
    - Visualization of true vs predicted values

## 📊 Outputs
- Evaluation metrics, e.g.:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - R² Score
- Plots/Graphs:
    - Feature analysis
    - Prediction comparisons
    - (Optional) Regression tree visualization

## 📚 References
- [scikit-learn documentation](https://scikit-learn.org/)
- [Boston Housing Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/housing)
- [Matplotlib documentation](https://matplotlib.org/)
- [seaborn documentation](https://seaborn.pydata.org/)

***
