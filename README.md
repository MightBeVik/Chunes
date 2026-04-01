# Chunes - Project Phase 2 (MSD 10K)

This repository contains the Phase 2 data preparation work for the Million Song Dataset (MSD) 10K subset.

## What is included

- `Phase2_Data_Preparation_MSD10K.ipynb`: Main Jupyter notebook for CRISP-DM data preparation.
- `requirements.txt`: Python dependencies.
- `HOW_TO_RUN.md`: Step-by-step setup and execution guide.

## Phase 2 tasks covered

- Data extraction from MSD HDF5 files
- Data structuring and wrangling
- Missing value handling
- Class imbalance handling (oversampling)
- Feature engineering (encoding + scaling)
- EDA and visualizations
- Pearson correlation heatmap and interpretation
- Train-test split
- K-fold cross-validation

## Dataset note

The full `MillionSongSubset` folder is large (multi-GB). It is not committed in this repository by default.

Use one of these options:

1. Download MSD 10K subset locally and place it at:
   - `MillionSongSubset/`
2. Track data with Git LFS or upload as a release asset (recommended for very large data).

## Repository structure

- `Phase2_Data_Preparation_MSD10K.ipynb`
- `requirements.txt`
- `HOW_TO_RUN.md`
- `.gitignore`
- `MillionSongSubset/` (local only, ignored by git)

## Team

- Vik Dayal
- Nathaniel Ola Ogunleye
- Osele Adeoye
- Huynh Hai Trieu Le
