# Hands-On Session 3 — Clinical Note Triage

Read a free-text **medical transcription** and predict which of **12 clinical
specialties** (`spec_01` … `spec_12`) it belongs to. Metric: **F1-macro**.

▶️ **Open the starter notebook in Colab:**
https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-3/clinical_note_triage.ipynb

The notebook downloads the data with the SDK, trains a baseline, writes
`submission.csv` and submits it. Paste your ml-arena.com API token (Profile page) in
the setup cell.

## Data

`client.download_dataset(174, "data/")` pulls the competition files:

- `train.csv` — training notes and labels (`id,transcription,label`).
- `test.csv` — test notes (predict a `label` for each `id`).

The baseline turns each note into TF-IDF features and fits a logistic regression; swap
in word embeddings or a fine-tuned transformer to climb the leaderboard.

Competition: https://ml-arena.com/viewcompetition/174
