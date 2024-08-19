# Unveiling Insights: A Data-driven Analysis of Health Insurance Charges

## Project Overview
This project aims to analyze and predict health insurance charges using machine learning techniques, specifically Linear Regression and Support Vector Regression (SVR). The goal is to understand the factors influencing insurance costs and provide valuable insights for informed decision-making in the healthcare industry.

## Methodology

### Data Analysis
We explored correlations between various factors and insurance charges:
- Age (0.299): Moderate positive correlation
- Smoker status (0.787): Strong positive correlation
- BMI (0.198): Moderate positive correlation
- Number of children (0.068): Weak positive correlation
- Sex (0.057): Weak positive correlation
- Region (-0.006): Negligible correlation

### Predictive Modeling
1. **Linear Regression**: Used to establish relationships between independent variables and insurance charges. Particularly useful for uncovering linear associations.

2. **Support Vector Regression (SVR)**: Employed to capture both linear and nonlinear patterns in the data. Suitable for complex datasets with intricate relationships.

## Results

### Linear Regression:
- Mean Absolute Error (MAE): ~4187
- Root Mean Squared Error (RMSE): ~5800
- R-squared (R²) value: 0.78 (78% variance explained)

### Support Vector Regression (SVR):
- MAE: ~3826
- RMSE: ~8189
- R² value: 0.57 (57% variance explained)

### Hyperparameter Tuning:
Applied to Linear Regression, but no significant improvement in performance was observed.

## Key Findings
1. Linear Regression outperformed SVR in predicting health insurance charges.
2. Smoking status has the most substantial influence on insurance charges, followed by age and BMI.
3. Factors like sex, number of children, and region have weaker correlations with insurance costs.

## Model Suitability
Linear Regression suits the data well, demonstrating good predictive performance. In contrast, SVR is less suitable for this dataset, as indicated by its lower R-squared value.

## Conclusion
This study demonstrates the potential of data-driven insights in the insurance industry. Linear Regression proved to be more suitable for this dataset, explaining 78% of the variance in insurance charges. The analysis provides valuable information on the factors influencing insurance costs, which can inform decision-making processes in healthcare and insurance sectors.

## Future Work
- Explore more advanced machine learning techniques
- Incorporate additional relevant features if available
- Investigate the impact of interaction effects between variables

## Technologies Used
- Python
- Scikit-learn for machine learning models
- Pandas for data manipulation
- NumPy for numerical computations
- Matplotlib/Seaborn for data visualization

