# Predicting-Heart-Attack-Risk-Using-Sleep-Work-and-Health-Habits-in-Married-Adults

This project predicts heart attack occurrence in married adults based on modifiable health behaviors like sleep hours, work hours, and BMI. Support Vector Machines (SVM) with linear, RBF, and polynomial kernels were used to identify key predictors and compare model performance.

---
## Project Overview

Predicting heart attack risk based on daily health habits could unlock powerful early intervention strategies.

This project explores whether sleep hours, weekly work hours, and body mass index (BMI) can predict heart attack occurrence among married adults using Support Vector Machine (SVM) models.

---
## Methods

We trained three types of SVM models:
- Linear Kernel
- Radial Basis Function (RBF) Kernel
- Polynomial Kernel

Each model underwent hyperparameter tuning via GridSearchCV with cross-validation. Feature importance was assessed through permutation importance.

---
## Key Findings

- Health behaviors like sleep, work hours, and BMI meaningfully impact heart attack risk.
- Nonlinear models (RBF and polynomial) captured richer patterns than linear models.
- SVMs proved effective in both linear and nonlinear settings.

---
## Conclusion

Healthy habits matter: daily behaviors such as sleep, work, and weight management showed strong predictive power for heart attack risk.

SVM models, especially with nonlinear kernels, successfully modeled these complex relationships.

---
## Dataset Citation
Lynn A. Blewett, Julia A. Rivera Drew, Miriam L. King, Kari C.W. Williams, Daniel Backman, Annie Chen, and Stephanie Richards. IPUMS Health Surveys: National Health Interview Survey, Version 7.4 [dataset]. Minneapolis, MN: IPUMS, 2024. https://doi.org/10.18128/D070.V7.4. NHIS IPUMS Website

