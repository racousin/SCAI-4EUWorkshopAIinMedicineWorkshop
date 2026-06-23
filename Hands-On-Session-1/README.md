# Hands-On Session 1 — 2-Month Survival Prediction

Predict whether a critically ill patient is **`alive`** or **`dead`** at the 2-month
follow-up, from clinical data recorded at admission. Metric: **F1-macro**.

▶️ **Open the starter notebook in Colab:**
https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-1/survival_prediction.ipynb

The notebook loads the data, trains a baseline, writes `submission.csv` and submits
it. Paste your ml-arena.com API token (Profile page) in the setup cell.

## Files

- `survival_prediction.ipynb` — end-to-end starter (load → train → submit).
- `data/X_train.csv`, `data/y_train.csv` — training features and labels (`patient_id,outcome`).
- `data/X_test.csv` — test features (predict `outcome` for each `patient_id`).

Competition: https://ml-arena.com/viewcompetition/172
