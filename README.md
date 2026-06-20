# NYC Motor Vehicle Collisions Analysis

A data wrangling project analyzing NYC motor vehicle collisions using data from the [NYC Open Data Portal](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4/about_data).

## Contents
- `NYC_Proj.ipynb` – Jupyter Notebook with full data wrangling analysis
- `requirements.txt` – Python dependencies

## Steps
1. Inspect the dataset (shape, columns, data types)
2. Handle missing values (drop/fill/Unknown strategy)
3. Correct data types (datetime64, Int64, category)
4. Clean and standardize text/categorical fields
5. Filter and group data (by borough, year, pivot tables, correlations)
6. Compute statistical summaries (means, top categories, derived stats)
7. Export raw and cleaned datasets to JSON and Parquet

## Setup
```bash
pip install -r requirements.txt
```

## How to Run
1. Download the dataset CSV from the link above
2. Place it in the project root folder
3. Open `NYC_Proj.ipynb` in Jupyter and run all cells

## Tech
- Python
- Pandas / NumPy
- Jupyter Notebook

## Reference
- [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4/about_data)
- [Pandas Docs](https://pandas.pydata.org/docs/index.html)