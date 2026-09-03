# Airbnb Hotel Booking Analysis

Exploratory data analysis of the Airbnb Open Data dataset — cleaning a messy, real-world listings dataset and answering nine business/research questions about pricing, neighborhoods, hosts, and reviews.

## Dataset
- **File:** `Airbnb_Open_Data.csv` (not included — place it in the same directory as the notebook, or update `DATA_PATH`)
- **Source:** Airbnb Open Data (NYC-style listings)

## Tech Stack
- Python, Pandas, NumPy, Matplotlib

## Workflow
1. **Setup** — install/import libraries
2. **Data Loading** — reads the CSV (path auto-detected, override via `DATA_PATH`)
3. **Initial Data Audit** — structure, missingness, duplicates, summary stats
4. **Data Cleaning**
   - Standardize column names to lowercase snake_case
   - Strip whitespace from text fields
   - Convert fields to numeric/datetime
   - Remove exact duplicates
   - Parse currency fields (price, service fee) into clean numeric columns
   - Mild outlier capping on price
5. **Exploratory Data Analysis** — distribution checks on key columns
6. **Research Questions** (each answered with tables + saved charts to `/exports`):
   - Q1: What property types exist in the dataset?
   - Q2: Which neighborhood group has the most listings?
   - Q3: Which neighborhood group has the highest average price?
   - Q4: Is there a relationship between construction year and price?
   - Q5: Who are the top 10 hosts by listing count?
   - Q6: Are hosts with verified identities more likely to get positive reviews?
   - Q7: Is price correlated with service fee?
   - Q8: How does average review rating vary by neighborhood group and room type?
   - Q9: Do hosts with more listings maintain higher year-round availability?
7. **Export Key Tables** — result tables saved as CSVs
8. **Appendix** — ad-hoc filtering helpers

## Outputs
Figures and result tables are written to an `exports/` folder created at runtime.

## How to Run
1. Place `Airbnb_Open_Data.csv` in the working directory (or update `DATA_PATH` in the notebook).
2. Open `Airbnb_Hotel_Booking_Analysis.ipynb` in Jupyter/Colab.
3. Run all cells top to bottom.
