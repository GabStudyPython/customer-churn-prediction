# Customer Churn Prediction

## Overview
Machine learning classification model to predict which customers will leave (churn).

## Dataset
- **Source:** Kaggle Telco Customer Churn
- **Size:** 7,043 customers, 21 features
- **Target:** Churn (Yes/No)
- **Churn Rate:** 26.5%

## Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | 80.5% |
| Precision | 66.7% |
| Recall | 58.1% |
| F1-Score | 0.619 |
| AUC-ROC | 0.861 |

## Key Insights
1. **Tenure:** Customers who churn leave after ~18 months. Those who stay average ~38 months
2. **Monthly Charges:** Higher bills correlate with higher churn (churners pay $74 vs $61 for stayers)
3. **Internet Service:** Fiber optic customers churn at 2x the rate of other services

## Model Details
- **Best Model:** Random Forest Classifier
- **Features:** 20 engineered features from original data
- **Train/Test Split:** 80/20 stratified split

## Files
- `customer_churn_prediction.ipynb` - Complete analysis and model training
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` - Dataset from Kaggle

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Upload the CSV file to the same directory
3. Run all cells from top to bottom

## Technologies
- Python 3.8+
- Scikit-learn (Random Forest, Logistic Regression)
- Pandas (data manipulation)
- NumPy (numerical operations)
- Matplotlib & Seaborn (visualization)
