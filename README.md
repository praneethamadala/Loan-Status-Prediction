# Loan-Status-Prediction
Predicting loan approval using R-based data visualization and machine learning techniques. A course project for ITS530 - Analyzing &amp; Visualizing Data at the University of the Cumberlands.

# 📊 Loan Status Prediction — ITS530 Project

This project is part of the **Analyzing & Visualizing Data (ITS530)** course at the University of the Cumberlands. Our objective was to develop a predictive model to determine whether a loan application should be approved or rejected based on various applicant features. The project involved data preprocessing, exploratory data analysis, model building, and data visualization using **R**.

---

## 📁 Repository Structure

```
Loan-Status-Prediction/
│
├── data/
│   └── loan_status_prediction.csv         # Raw dataset (Kaggle)
│
├── notebooks/
│   └── loan_prediction_analysis.Rmd       # R Markdown analysis
│   └── visualizations/                    # Charts and plots (EDA)
│
├── models/
│   └── logistic_regression_model.R        # Model code
│
├── report/
│   └── final_report.pdf                   # Project write-up (exported from Word)
│   └── screenshots/                       # All charts with explanations
│
├── README.md                              # Project summary and instructions
└── requirements.txt                       # R packages used (ggplot2, plotly, dplyr, etc.)
```

---

## 📌 Project Objectives

- Analyze loan application data to identify patterns affecting loan approvals.
- Use machine learning (Logistic Regression) for binary classification.
- Visualize correlations and outliers using scatter plots, box plots, bar charts, and heatmaps.
- Improve interpretability using high-level graphics in **R**.

---

## 📈 Technologies Used

- **Language:** R  
- **Libraries:** `ggplot2`, `plotly`, `dplyr`, `caret`, `readr`  
- **Data Source:** [Loan Status Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/loan-status-prediction-dataset)

---

## 📊 Visual Insights

Key graphs include:
- **Scatter Plots**: Applicant Income vs Loan Amount  
- **Bar Charts**: Loan Status by Gender and Education  
- **Box Plots**: Distribution of Loan Amount by Approval  
- **Heatmaps**: Feature correlation analysis

---

## 💡 Conclusion

Our Logistic Regression model achieved strong predictive performance and identified **credit history** as the most influential factor in loan approvals. The visualizations greatly improved stakeholder understanding and interpretation of trends.
