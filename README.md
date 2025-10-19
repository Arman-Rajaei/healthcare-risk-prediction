# 🩺 Multimodal Healthcare Risk Prediction

An end-to-end machine learning pipeline that integrates **clinical** and **physiological** features to predict patient risk and provide **explainable model insights**.

---

## 📂 Project Structure

- **`src/preprocessing.py`** — Data cleaning and feature engineering  
- **`src/modeling.py`** — Model training (Logistic Regression & Random Forest)  
- **`src/explainability.py`** — Model interpretation using SHAP  
- **`notebooks/risk_prediction_demo.ipynb`** — Interactive end-to-end workflow  
- **`reports/figures/`** — Saved visualizations (optional)

---

## 🧠 Data

Data files are **not included** in this repository for privacy reasons.  
To run the notebook, place your dataset in:


A **data dictionary** describing all features and units is available in:  
`docs/data_dictionary.md`

---

## ⚙️ Quickstart

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/healthcare-risk.git
cd healthcare-risk

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Lab / Notebook
jupyter lab
```
## 🧩 Requirements
See `requirements.txt` for dependencies (Python ≥ 3.8, scikit-learn, shap, matplotlib, seaborn, pandas, numpy).

---

## 🪪 License
MIT License — see [`LICENSE`](LICENSE) for details.
