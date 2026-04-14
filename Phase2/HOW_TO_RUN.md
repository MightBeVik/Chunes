# How To Run

## 1. Clone the repository

```bash
git clone https://github.com/MightBeVik/Chunes.git
cd Chunes
```

## 2. Create and activate virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 4. Add dataset locally

Place the MSD 10K subset folder in the project root so this path exists:

- `MillionSongSubset/`

Expected content format is nested `.h5` files (10,000 tracks).

## 5. Launch notebook

```bash
jupyter notebook
```

Open:

- `Phase2_Data_Preparation_MSD10K.ipynb`

Run cells from top to bottom.

## 6. Outputs

The notebook can export a cleaned CSV file:

- `phase2_cleaned_dataset.csv`

## Troubleshooting

- If `h5py` fails to import, reinstall dependencies in an active virtual environment.
- If no files are found, verify dataset path is exactly `MillionSongSubset/` in project root.
- If kernel errors occur, switch notebook kernel to the project `.venv` Python interpreter.
