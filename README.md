
# CarSpec Analytics - Statistical Analysis of Automobile Features & Pricing

M.Sc. Data Science capstone project, Osmania University (2025-26).
Statistical and machine learning analysis of a 2,040-record, 57-variable automobile dataset to
identify which specifications drive price in the Indian automobile market.

## Highlights
- **EDA & Correlation** - Number of Airbags (r = 0.713) and Power/BHP (r = 0.702) are the strongest
  individual price predictors.
- **Hypothesis Testing** - One-way ANOVA + Tukey's HSD, Kruskal-Wallis, Chi-Square Test of
  Independence confirms significant price differences across segments (F = 1481.96, p < 0.000001).
- **Regression Modelling ** - Benchmarked Linear, Ridge, Lasso, Random Forest, XGBoost on R²/RMSE/MAE.
  Random Forest performed best (R² = 0.892, RMSE ≈ 19.25 lakhs).
- **Clustering & PCA** - K-Means and Hierarchical (Ward's linkage) clustering, validated via Elbow
  Method and Silhouette Score reveal 4 interpretable market segments.
- **Interpretability** - Random Forest feature importance + SHAP values.

## Tech Stack
Python · Pandas · NumPy · scikit-learn · XGBoost · SciPy · Matplotlib · Seaborn

## Repo Structure
\`\`\`
carspec-analytics/
├── notebooks/        # EDA, statistical tests, modeling, clustering
├── data/              # dataset
├── report/            # full project report (PDF/DOCX)
└── README.md
\`\`\`

## Author
H. Naveen — [LinkedIn](https://linkedin.com/in/hnaveen)
```
