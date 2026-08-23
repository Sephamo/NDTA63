# NDTA 631 – Data Analysis and Visualisation

## Project Overview

This project performs data analysis and visualisation using two South African datasets obtained from World Bank Open Data.

The analysis focuses on South Africa's population and the female-to-male youth unemployment ratio over the period 1991–2023.

The project demonstrates data preparation, numerical analysis, data visualisation, database integration, and Python-based data analysis.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite

## Datasets

The project uses the following World Bank datasets:

- `WB_WDI_SP_POP_TOTL.csv`
- `WB_GS_SL_UEM_1524_FM_ZS.csv`

The datasets are filtered for South Africa (`ZAF`) and the analysis covers the period 1991–2023.

## Project Structure

```text
NDTA631-Data-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── WB_WDI_SP_POP_TOTL.csv
│   └── WB_GS_SL_UEM_1524_FM_ZS.csv
│
└── notebook/
    └── NDTA631_Data_Analysis.ipynb

``` 
## Requirements

This project requires:

Python 3
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn

The required Python packages are listed in requirements.txt.

## Environment Setup

It is recommended to use a Python virtual environment when running the project.

Create a virtual environment:

```bash
python -m venv .venv

Activate the virtual environment on Windows:

.venv\Scripts\activate

Install the required packages:

pip install -r requirements.txt

```
## Running the Project

Open Jupyter Notebook:

jupyter notebook

Open:

notebook/NDTA631_Data_Analysis.ipynb

Run the notebook cells from beginning to end.

The notebook performs the data preparation, numerical analysis, visualisation, database integration, and further analysis.

## Data Preparation

The project includes:

Loading the datasets
Inspecting the data
Filtering the data for South Africa
Filtering the analysis period
Checking for missing values
Checking for duplicate records
Cleaning and preparing the datasets
Combining the datasets

## Numerical Analysis

 NumPy and Pandas are used to perform numerical analysis, including:

Descriptive statistics
Mean and median calculations
Minimum and maximum values
Standard deviation
Population growth calculations
Percentage changes
Correlation analysis
NumPy array operations and reshaping

## Visualisation

The project includes visualisations such as:

Population trends
Female-to-male youth unemployment ratio trends
Scatter plots
Histograms
Box plots

The visualisations are used to identify trends, patterns, distributions, and relationships within the data.

## Database Integration

SQLite is used to create and query a local database.

The notebook demonstrates:

Creating a database
Creating a database table
Retrieving records using SQL
Filtering records
Updating records
Deleting records
Restoring records after testing
Loading database data into Pandas
Exporting database data to CSV

The database is generated when the notebook is executed.

## Limitations

The analysis is based on the selected World Bank datasets and the available data for the 1991–2023 period.

The analysis identifies relationships and patterns in the data but does not establish that one variable directly causes changes in another.

## Contributors

This project was completed as a group assignment for NDTA 631 – Data Analysis and Visualisation.

202330931
Sephamo Nick Phasha

202402065
Kopano Michael Matthews

202416227
Mbali Nomsa Ndlovu

202416544
Rpm Makhafola

202447571
Alison Omolemo Chounyane

202461953
Jayda Shaye Brooker

## Data Source

World Bank Open Data.

The original dataset information should be retained with the project for reference.