# Task 16: Hyperparameter Tuning - GridSearchCV

This repository demonstrates how to optimize an SVM model using **GridSearchCV** on the Breast Cancer dataset.

## Workflow:
1.  **Baseline**: Trained a default SVM model.
2.  **Grid Search**: Defined a parameter grid for `C`, `gamma`, and `kernel`.
3.  **Cross-Validation**: Used 5-Fold CV to validate each combination.
4.  **Result**: Improved model accuracy by identifying the optimal hyperparameters.

## Best Parameters Found:
* **C**: 10
* **Gamma**: 0.01
* **Kernel**: rbf

## Files:
* **Task_16_GridSearchCV.ipynb**: Code implementation.
* **Task_16_Report.pdf**: Comparison of Default vs Tuned models.
