# SWYNEX Technologies — Task 2: Exploratory Data Analysis

## Objective
Explore the cleaned Titanic dataset, calculate summary statistics, visualize important patterns, and document at least five useful insights.

## Dataset
- File: `data/titanic_cleaned.csv`
- Source: The cleaned dataset produced for SWYNEX Task 1.
- Rows and columns: 891 rows × 12 columns (verify by running the notebook).

## Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## How to run on Windows
1. Extract this project folder.
2. Open Command Prompt inside the extracted `SWYNEX-Exploratory-Data-Analysis` folder.
3. Run `python -m pip install -r requirements.txt`
4. Run `jupyter notebook`
5. Open `notebook/SWYNEX_Task2_EDA.ipynb`.
6. Run the notebook cells from top to bottom.

## Analysis performed
- Dataset shape, column types, and descriptive statistics
- Missing-value and duplicate checks
- Survival distribution
- Survival by sex and passenger class
- Age and fare distributions
- Passenger class and embarkation-port patterns
- Charts saved to the `charts/` folder
- Five or more insights generated from the actual data

## Project structure
```text
SWYNEX-Exploratory-Data-Analysis/
├── README.md
├── requirements.txt
├── data/
│   └── titanic_cleaned.csv
├── notebook/
│   └── SWYNEX_Task2_EDA.ipynb
└── charts/
```

## Notes
This is an exploratory analysis, not a predictive machine-learning model. Interpretations are associations in this dataset and do not establish causation.
