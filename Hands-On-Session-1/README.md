# Hands-On Session 1 — 2-Month Survival Prediction

Predict whether a critically ill patient is **`alive`** or **`dead`** at the 2-month
follow-up, from clinical data recorded at admission. Metric: **accuracy**.

▶️ **Open the starter notebook in Colab:**
https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-1/survival_prediction.ipynb

The notebook loads the data, trains a baseline, writes `submission.csv` and submits
it. Paste your ml-arena.com API token (Profile page) in the setup cell.

## Learn the method first

New to the data-preparation workflow? Work through the standalone example notebook before
the competition — it covers imputation, outlier handling, encoding, scaling, and a Random
Forest on a separate (Breast Cancer) dataset:

▶️ https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-1/data_preparation_example.ipynb

## Files

- `data_preparation_example.ipynb` — worked example of the full data-prep + Random Forest
  workflow (self-contained, uses `breast_cancer_noisy.csv`).
- `breast_cancer_noisy.csv` — dataset for the worked example.
- `survival_prediction.ipynb` — competition starter (load → train → submit).
- `data/X_train.csv`, `data/y_train.csv` — training features and labels (`patient_id,outcome`).
- `data/X_test.csv` — test features (predict `outcome` for each `patient_id`).

Competition: https://ml-arena.com/viewcompetition/172
