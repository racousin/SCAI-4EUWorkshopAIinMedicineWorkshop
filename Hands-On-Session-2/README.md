# Hands-On Session 2 — Blood Cell Classification

Classify microscopy images of **blood cells** into one of **8 cell types**, from
28×28 RGB images. Metric: **F1-macro**.

▶️ **Open the starter notebook in Colab:**
https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-2/blood_cell_classification.ipynb

The notebook downloads the data with the SDK, trains a baseline, writes
`submission.csv` and submits it. Paste your ml-arena.com API token (Profile page) in
the setup cell.

## Data

`client.download_dataset(173, "data/")` pulls the competition files:

- `train_images.npz` — training images: `image_id`, `images` (N×28×28×3 `uint8`).
- `y_train.csv` — training labels (`image_id,label`).
- `test_images.npz` — test images (predict a `label` for each `image_id`).

The baseline flattens the pixels and fits a random forest; swap in a small CNN
(or transfer learning) to climb the leaderboard.

Competition: https://ml-arena.com/viewcompetition/173
