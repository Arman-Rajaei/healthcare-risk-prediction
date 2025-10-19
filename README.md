# Multimodal Healthcare Risk Prediction

End-to-end pipeline that integrates clinical and physiological features to predict patient risk and provide model explanations.

## What’s inside
- Data preprocessing (`src/preprocessing.py`)
- Modeling (Logistic Regression & Random Forest) (`src/modeling.py`)
- Explainability with SHAP (`src/explainability.py`)
- Example notebook: `notebooks/risk_prediction_demo.ipynb`

## Data
Data files are **not included** in this repository due to privacy.  
To run the notebook, place your dataset at `data/healthcare_dataset.csv` and update the paths if needed.  
A **data dictionary** is provided in `docs/data_dictionary.md`.

## Quickstart
```bash
pip install -r requirements.txt
jupyter lab
