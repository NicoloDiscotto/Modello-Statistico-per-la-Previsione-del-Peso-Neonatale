# 👶 Statistical Model for Predicting Neonatal Birth Weight

> Inferential statistics project in R: multiple regression analysis to predict birth weight from clinical variables, with full model selection and assumption validation.

---

## 📌 Overview

Birth weight is one of the most important indicators of neonatal health. Accurately predicting it from maternal and clinical variables allows healthcare providers to identify at-risk pregnancies early and plan appropriate interventions.

This project builds and selects an **optimal multiple regression model** to predict neonatal birth weight from a simulated clinical dataset, following rigorous inferential statistics methodology: model comparison, statistical testing, and residual diagnostics.

📊 **Full interactive report on RPubs:** [rpubs.com/nicolo_discotto/1323226](http://rpubs.com/nicolo_discotto/1323226)

---

## 🎯 Objectives

- Build multiple regression models of increasing complexity
- Select the optimal model using formal statistical criteria
- Validate all regression assumptions through residual analysis
- Interpret coefficients in a clinical context

---

## 🏗️ Analysis Pipeline

```
Simulated Clinical Dataset
          │
          ▼
  Data Exploration & Cleaning
  (distributions, missing values, outliers)
          │
          ▼
  Candidate Model Building
  (simple → multiple regression)
          │
          ▼
  Model Comparison & Selection
  ├── ANOVA (nested model comparison)
  ├── BIC (Bayesian Information Criterion)
  └── VIF (Variance Inflation Factor — multicollinearity)
          │
          ▼
  Residual Diagnostics
  ├── Homoscedasticity (Breusch-Pagan test)
  ├── Normality (Shapiro-Wilk, Q-Q plot)
  └── Outlier detection (Cook's distance, leverage)
          │
          ▼
  Optimal Model + Interpretation
```

---

## 📋 Statistical Methods

| Method | Purpose |
|---|---|
| Multiple Linear Regression | Predict birth weight from clinical predictors |
| ANOVA | Compare nested models for significance |
| BIC | Penalized model selection (parsimony) |
| VIF | Detect multicollinearity among predictors |
| Breusch-Pagan test | Verify homoscedasticity of residuals |
| Shapiro-Wilk test | Verify normality of residuals |
| Cook's distance | Identify influential observations |

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| Language | R |
| Reporting | R Markdown (`.Rmd`) |
| Statistics | Base R (`lm`, `anova`, `BIC`, `vif`) |
| Visualization | `ggplot2`, `car`, `lmtest` |
| Publishing | RPubs |

---

## 📁 File Structure

```
Modello-Statistico-per-la-Previsione-del-Peso-Neonatale/
├── presentazione.Rmd     # Full analysis in R Markdown
└── README.md
```

---

## 📝 Notes

Developed as part of the **Master in Data Science @ ProfessionAI** (2025–2026) — Inferential Statistics module.  
This project demonstrates the full lifecycle of a regression analysis: from exploratory data analysis and model building, through formal statistical testing and selection, to assumption validation and clinical interpretation.

---

## 📫 Author

**Nicolò Discotto** · [LinkedIn](https://www.linkedin.com/in/nicolo-discotto/) · [GitHub](https://github.com/NicoloDiscotto) · [RPubs](https://rpubs.com/nicolo_discotto)
