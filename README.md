# SCAI · 4EU+ Workshop — AI in Medicine

Hands-on materials for the AI in Medicine workshop. Each session pairs a **worked
example** (learn the method) with a **competition starter** (apply it on
[ml-arena.com](https://ml-arena.com)). Click any **Open in Colab** badge below to run a
notebook in the browser — no local setup required.

> For notebooks that benchmark or train on a GPU, enable it first in Colab:
> **Runtime → Change runtime type → Hardware accelerator → GPU**.

## Schedule (3 days)

Each session pairs a **worked example** (learn the method) with a **competition starter**
(apply it). The warm-up is pre-work to run before Day 1.

| Day | Session | Modality | You'll learn | Competition |
| --- | --- | --- | --- | --- |
| Warm-up *(before Day 1)* | PyTorch, optimization & GPUs | — | tensors, gradient descent, CPU vs GPU | — |
| **Day 1** | Survival Prediction | tabular | data prep → Random Forest / boosting | [172](https://ml-arena.com/viewcompetition/172) |
| **Day 2** | Blood Cell Classification | images | CNNs & transfer learning | [173](https://ml-arena.com/viewcompetition/173) |
| **Day 3** | Clinical Note Triage | text | embeddings & transfer learning | [174](https://ml-arena.com/viewcompetition/174) |

## Warm-up — PyTorch, optimization & GPUs

Get comfortable with tensors, gradient descent, and CPU-vs-GPU performance before the
sessions begin.

| Notebook | Open in Colab |
| --- | --- |
| Optimization & training (gradient descent → MLP, CPU vs GPU) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-warmup/optimization_warmup.ipynb) |
| CPU vs GPU benchmark (matrix multiply + BERT forward pass) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-warmup/cpu_gpu_benchmark.ipynb) |

## Session 1 — 2-Month Survival Prediction (tabular)

Predict whether a critically ill patient is `alive` or `dead` at 2 months from
admission data. Metric: **accuracy**.
[Competition 172](https://ml-arena.com/viewcompetition/172) · [Session README](Hands-On-Session-1/README.md)

| Notebook | Open in Colab |
| --- | --- |
| Data preparation — worked example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-1/data_preparation_example.ipynb) |
| Survival prediction — competition starter | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-1/survival_prediction.ipynb) |

## Session 2 — Blood Cell Classification (images)

Classify 28×28 RGB microscopy images into 8 cell types. Metric: **F1-macro**.
[Competition 173](https://ml-arena.com/viewcompetition/173) · [Session README](Hands-On-Session-2/README.md)

| Notebook | Open in Colab |
| --- | --- |
| Image classification — worked example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-2/image_classification_example.ipynb) |
| Blood cell classification — competition starter | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-2/blood_cell_classification.ipynb) |

## Session 3 — Clinical Note Triage (text)

Classify a free-text medical transcription into 1 of 12 clinical specialties.
Metric: **F1-macro**.
[Competition 174](https://ml-arena.com/viewcompetition/174) · [Session README](Hands-On-Session-3/README.md)

| Notebook | Open in Colab |
| --- | --- |
| Text embeddings & transfer learning — worked example | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-3/text_embeddings_example.ipynb) |
| Clinical note triage — competition starter | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/racousin/SCAI-4EUWorkshopAIinMedicineWorkshop/blob/main/Hands-On-Session-3/clinical_note_triage.ipynb) |

---

To submit, paste your [ml-arena.com](https://ml-arena.com) API token (from your Profile
page) into the setup cell of each competition starter notebook.
