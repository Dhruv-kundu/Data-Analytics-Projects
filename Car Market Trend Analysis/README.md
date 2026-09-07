# Data Analysis of Used Cars from CarDekho

Exploratory data analysis of a used-car marketplace dataset (CarDekho), exploring which brands and models sell best, how price relates to mileage/age/fuel type, and what drives resale value.

## Dataset
- **File:** `Cardekho_Dataset.csv` (not included — place it alongside the notebook)
- **Period covered:** 2019–20 listings (results reflect that market snapshot, not current prices)

## Tech Stack
- Python, Pandas, NumPy, Seaborn, Matplotlib

## Workflow
1. **Cleaning** — rename the unnamed index column to `Sr_No` and set it as the index; inspect head/tail/info
2. **Brand & Model Analysis** — highest-selling car brands and models, top 5 cars sold by unit count
3. **Fuel Type Analysis** — cars sold by fuel type, brand vs. fuel type comparison
4. **Seller Type** — distribution of Dealer / Individual / Trustmark Dealer listings
5. **Price Analysis** — selling price vs. actual cost vs. vehicle age; overview of mileage, selling price, and actual price
6. **Mileage Analysis** — brand vs. mileage (pie chart), max/min mileage cars, seating capacity comparison
7. **Age Analysis** — cars sold by vehicle age, cars ≤ 4 years old, cars listed for up to 29 years
8. **Budget Analysis** — filtering the market from ₹10K to ₹9L, and a full overview from ₹10K to ₹4Cr
9. **Correlations** — pair plot across all numeric variables

## Key Findings
- Maruti and Hyundai are the top-demand brands in the resale market, followed by Honda, Mahindra, and Toyota.
- The Hyundai i20 has the highest listing count in the market.
- Seller type split: Dealer (~61.9%), Individual (~37.0%), Trustmark Dealer (~1.1%).
- Selling price rises with engine power.
- Maruti and Hyundai stand out as the most trusted brands with good mileage and low maintenance; combined with resale value from Toyota, these three brands lead the used-car market, though Maruti and Hyundai are strongest on budget and mileage specifically.

## How to Run
1. Place `Cardekho_Dataset.csv` in the working directory.
2. Open `Project_CarDekho.ipynb` in Jupyter/Colab.
3. Run all cells top to bottom.
