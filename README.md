# BigMart Sales Classification — Accurate Version

A complete, runnable machine-learning classification project based on the BigMart sales dataset.

## Objective
Convert `Item_Outlet_Sales` into a binary target:
- `0` = Low Sales
- `1` = High Sales

The threshold is calculated from the training set only.

## Models
- Logistic Regression
- Decision Tree
- Random Forest
- Extra Trees
- Gradient Boosting

## Preprocessing
- Missing-value imputation
- Categorical-value standardization
- Zero-visibility treatment
- One-hot encoding
- Standard scaling
- `New_Item_Type`
- `Outlet_Years`
- Removal of identifiers and original sales target from predictors

## Evaluation
Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, ROC Curves, and 5-fold Stratified Cross-Validation.

## Files
- `BigMart_Sales_Classification_Accurate.ipynb`
- `Train.csv`
- `classification_model_results.csv`
- `requirements.txt`

## Run
```bash
pip install -r requirements.txt
jupyter notebook BigMart_Sales_Classification_Accurate.ipynb
```
