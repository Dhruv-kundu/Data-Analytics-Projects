# Crop Recommendation — Exploratory Data Analysis

Exploratory analysis of a crop recommendation dataset, examining soil nutrients (N, P, K), pH, temperature, and humidity to understand what conditions suit different crops.

## Dataset
- **File:** `Crop_recommendation.csv` (not included — place it alongside the notebook)
- **Features:** N, P, K (soil nutrients), temperature, humidity, ph, rainfall, and a crop `label`

## Tech Stack
- Python, Pandas, NumPy, Seaborn, Matplotlib

## Workflow
1. **Load & Inspect** — head, tail, shape, info, describe, dtypes, null check
2. **Distribution Analysis** — histograms for all numerical features
3. **Outlier Detection** — boxplots for temperature, humidity, pH, N, K, and P
4. **Outlier Treatment** — IQR-based capping applied to the `P` (phosphorus) column
5. **Relationship Analysis**
   - Scatter plot of humidity vs. temperature, colored by crop label
   - Violin plot of soil pH distribution by crop type

## How to Run
1. Place `Crop_recommendation.csv` in the working directory.
2. Open `Crop_recommendation.ipynb` in Jupyter/Colab.
3. Run all cells top to bottom.

## Notes
This notebook is analysis-only (EDA); it does not yet include a predictive model for crop recommendation.
