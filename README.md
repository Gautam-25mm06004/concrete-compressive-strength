# Concrete Compressive Strength Prediction

Regression of concrete compressive strength from mix design and age, from a first baseline notebook to a fuller study comparing linear, tree-based and boosted models.

## Contents

| File | What it does |
|---|---|
| `notebooks/concrete_strength_study.ipynb` | Concrete Compressive Strength |
| `notebooks/concrete_strength_baseline.ipynb` | Concrete Compressive Strength Prediction |

Notebooks are saved with the outputs of their last run, so results and figures can be read on GitHub without running anything.

## Data

UCI "Concrete Compressive Strength" dataset (the study notebook fetches it with `ucimlrepo`).

## How to run

The notebooks were developed on Google Colab. Upload a notebook to Colab (File → Upload notebook) and run the cells in order; the first cells install anything missing. To run locally in VS Code instead: `python -m venv .venv`, activate it, `pip install -r requirements.txt jupyter`, then open the notebook and pick the `.venv` kernel. Cells that mount Google Drive (`google.colab`) can be skipped locally if the data files are placed next to the notebook.

Python packages used: `catboost`, `ipython`, `joblib`, `lightgbm`, `matplotlib`, `numpy`, `pandas`, `scikit-learn`, `scipy`, `seaborn`, `ucimlrepo`, `xgboost` (see `requirements.txt`).

## License

MIT, see `LICENSE`.
