# Lung-Nodule-XAI-FYP
# A Faithfulness-Evaluated Comparison of Post-hoc and Concept-Based Explainable Deep Learning for Lung Nodule Malignancy Classification on Low-Dose CT (FYP)

This project focuses on building a leakage-free 3D nodule-level pipeline to compare post-hoc explanations (Grad-CAM, Grad-CAM++) and concept-based explanations for lung nodule malignancy classification on low-dose computed tomography (LDCT) scans.

## Datasets

* **Dataset 1:** LIDC-IDRI (The Cancer Imaging Archive - TCIA) — 1,018 CT cases featuring radiologist-annotated contours, malignancy ratings, and morphological attributes.
* **Dataset 2:** LUNA25 (Zenodo) — Screening-trial malignancy labels and nodule-block archives for cross-dataset evaluation and benchmarking[cite: 1].

## Setup Instructions

1. **Clone repository:** `git clone https://github.com/zuhairgit/Lung-Nodule-XAI-FYP.git`
2. **Install requirements:** `pip install -r requirements.txt`
3. **Run preprocessing script:** `python src/preprocess.py`
