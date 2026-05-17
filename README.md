# predicting-grocery-sales

Sales forecasting for grocery items using machine learning, built during HackUPC.

## The Problem

- Grocery retailers need accurate sales forecasts to manage stock levels and reduce waste.
- Manual forecasting is slow and does not scale across a large product catalogue.
- Time-series prediction for perishable goods requires handling seasonality and irregular demand patterns.

## The Approach

**Inputs:** Historical grocery sales data in CSV format, stored in `data/`.

**Processing:** A Jupyter notebook (`forecasting.ipynb`) performs exploratory analysis and trains forecasting models. Python scripts in `src/` support data preparation. Reference materials are in `ref/`.

**Outputs:** Sales forecasts for grocery items.

## Value Delivered

- Demonstrates applied time-series forecasting on a real retail dataset.
- Covers the full pipeline from raw data to model evaluation.

## Scope & Status

- **Project type:** Hackathon / learning project
- **Current state:** Archived
- **Known limitations:**
  - Requires Python 3.6 specifically (older dependency constraints).
  - No production pipeline; inference is notebook-based only.
  - Model performance is not benchmarked against a baseline.

## Tech Stack

- **Language:** Python 3.6
- **Libraries:** Pandas, TensorFlow, Matplotlib, Seaborn, scikit-learn
- **Format:** Jupyter Notebook

## Who This Is For

Developers and data scientists reviewing the author's applied ML work in retail forecasting.

## Getting Started

```bash
conda create -n hackupc python=3.6 pandas tensorflow matplotlib seaborn scikit-learn ipykernel
conda activate hackupc
jupyter notebook forecasting.ipynb
```

## License

Not specified (LICENSE file present in root).
