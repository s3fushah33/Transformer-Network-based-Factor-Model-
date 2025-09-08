# Advanced Investments Research

This repository contains a **commented Jupyter notebook**: `Advanced_Investements_Research_Commented.ipynb`,
which walks through data loading, cleaning, feature engineering, modeling, and visualization steps for an investment research workflow.

## Files
- `Advanced_Investements_Research_Commented.ipynb` — fully commented, GitHub-ready notebook.
- `Advanced_Investements_Research.ipynb` — original notebook (as provided).
- `requirements.txt` — Python dependencies (heuristically derived from imports).

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then open the notebook in Jupyter or VS Code and run cells in order.

## Notes
- If loading from Google Drive links, ensure sharing is set to *Anyone with the link can view* or place the CSV locally.
- Prefer deterministic operations and seed setting for reproducibility.
- Save artifacts (CSV/plots) to a `outputs/` folder for easier comparison between runs.
