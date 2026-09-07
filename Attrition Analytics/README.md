# Employee Attrition Analysis

Exploratory data analysis of an HR attrition dataset to understand why employees leave an organization, covering data cleaning, outlier handling, and visual analysis across gender, education, age, salary, tenure, and department.

## Dataset
- **File:** `Attrition_Analytics.csv` (not included — place it alongside the notebook)
- **Size:** 38 columns, 1,480 rows
- **Description:** Organizational HR data with factors that may influence employee attrition

## Tech Stack
- Python, Pandas, NumPy, Seaborn, Matplotlib

## Workflow
1. **Load & Inspect** — create the dataframe, review shape, dtypes, and summary statistics
2. **Missing Values** — null report, isolate affected rows, impute missing `YearsWithCurrManager` values with the column average
3. **Column Profiling** — full column list, dtypes, count of numerical vs. categorical columns, distribution histograms
4. **Outlier Handling**
   - Identify outliers in `Age`, `YearsAtCompany`, `MonthlyIncome`
   - Remove outliers from `YearsAtCompany` and `MonthlyIncome`
5. **Duplicates** — 10 duplicate rows identified and removed → final cleaned dataset `df_cleaned`
6. **Visualization & Insights**
   - Attrition by Gender (bar plot)
   - Attrition by Education (pie chart)
   - Attrition by Age Group (column chart)
   - Attrition by Salary Slab
   - Attrition by Years at Company
   - Attrition by Department (swarm plot)
   - Overall attrition count and percentage

## Key Findings
- Male employees left the organization noticeably more than female employees.
- Employees with a Life Sciences educational background showed the highest attrition.
- The 26–35 age group had the highest attrition; employees 55+ had the least.
- Employees earning under 5K had the highest attrition; those earning above 15K had the least.
- Most attrition came from employees with under 2.5 years of tenure; ~12-year tenure employees were the most stable.
- Research & Development had the highest departmental attrition; Human Resources had the least.
- Around 237 employees left the organization, an overall attrition rate of about 16%.

## How to Run
1. Place `Attrition_Analytics.csv` in the working directory.
2. Open `Attrition_Analysis_DA.ipynb` in Jupyter/Colab.
3. Run all cells top to bottom.
