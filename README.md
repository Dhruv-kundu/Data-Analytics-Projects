# Data Analysis Projects

A collection of exploratory data analysis (EDA) projects, each in its own folder with its notebook and a project-specific README.

## Projects

| Project | Description | Notebook |
|---|---|---|
| [Airbnb Hotel Booking Analysis](./airbnb-hotel-booking-analysis) | Cleans and explores Airbnb listings data; answers 9 research questions on pricing, neighborhoods, hosts, and reviews. | `Airbnb_Hotel_Booking_Analysis.ipynb` |
| [Employee Attrition Analysis](./attrition-analysis) | Investigates why employees leave an organization across gender, education, age, salary, tenure, and department. | `Attrition_Analysis_DA.ipynb` |
| [CarDekho Used Car Analysis](./cardekho-used-car-analysis) | Explores a used-car marketplace dataset — best-selling brands/models, pricing, mileage, and age trends. | `Project_CarDekho.ipynb` |
| [Crop Recommendation Analysis](./crop-recommendation-analysis) | EDA on soil nutrients, pH, temperature, and humidity across different recommended crops. | `Crop_recommendation.ipynb` |

## Repo Structure
```
data-analysis-projects/
├── README.md
├── airbnb-hotel-booking-analysis/
│   ├── README.md 
│   ├── Airbnb_Open_Data.csv
│   └── Airbnb_Hotel_Booking_Analysis.ipynb
├── attrition-analysis/
│   ├── README.md 
│   ├── Attrition_Analytics.csv
│   └── Attrition_Analysis_DA.ipynb
├── cardekho-used-car-analysis/
│   ├── README.md
│   ├── Cardekho_Dataset.csv
│   └── Project_CarDekho.ipynb
└── crop-recommendation-analysis/
    ├── README.md
    ├── Crop_recommendation.csv
    └── Crop_recommendation.ipynb
```

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Note on Data
Raw CSV files are not included in this repo (to keep it lightweight). Each project README lists the expected dataset filename — download it and place it in the corresponding project folder before running the notebook.

## How to Use
1. Clone/download this repo.
2. `cd` into the project folder you're interested in.
3. Add the dataset CSV listed in that project's README.
4. Open the `.ipynb` file in Jupyter Notebook, JupyterLab, or Google Colab and run all cells.
