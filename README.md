# Happiness Score Prediction using Linear Regression
This project explores the relationship between various socio-economic indicators and global happiness scores using multiple linear regression. It involves thorough data cleaning, exploratory analysis, assumption testing, and model validation to ensure robust and interpretable results.

## Files Included
- `LR_Happiness_Project.ipynb`: Main notebook with data analysis, modeling, diagnostics, and conclusions.
- `Happiness_Cleaned.csv`: Cleaned dataset used for the analysis.
- `LR_Project_Report.pdf`: Final formatted project report summarizing methods and findings.

## Objectives
- Predict happiness scores using GDP per capita, social support, life expectancy, freedom, and corruption perception.
- Test regression assumptions (normality, homoscedasticity, linearity).
- Apply Extra Sum of Squares (ESS) for variable significance.
- Compare multiple models and select the best using Adjusted R² and residual diagnostics.

## Key Methods Used
- **Multiple Linear Regression (MLR)**: Built models to understand the impact of multiple predictors on happiness score.
- **Outlier Analysis**: Detected and removed extreme outliers based on boxplots and z-scores to reduce distortion in model estimates.
- **Variance Inflation Factor (VIF)**: Checked for multicollinearity among predictors and dropped variables with high VIF values.
- **Residual Analysis & Assumption Validation**: Validated linearity, homoscedasticity, and normality using residual plots and diagnostic tests.
- **Extra Sum of Squares (Type II ANOVA)**: Assessed the incremental value of each predictor when added to the model.
- **Train-Test Split**: Used a 70:30 split to evaluate model performance and avoid overfitting.

## Results Summary
- Final model achieved an Adjusted R² of **0.7539** on training data and **0.6049** on validation data.
- Model performance was found to be acceptable with no major violations of regression assumptions.

## Tools & Libraries
- Python (Jupyter Notebook)
- Pandas, NumPy
- Statsmodels, Matplotlib, Seaborn

## How to Run
1. Clone this repo  
2. Open the notebook in Jupyter  
3. Ensure `Happiness_Cleaned.csv` is in the same directory  
4. Run all cells for end-to-end execution  

## Contact
For any queries or collaboration ideas, feel free to reach out via [GitHub Issues](https://github.com/NithinRachakonda/Happiness_Scorecard/issues).
