# 🧹 Data Cleaning — Online Retail Dataset

## Objective
Demonstrate professional-level data cleaning skills by taking a real-world messy dataset and systematically transforming it into a clean, analysis-ready dataset, with every decision documented.

## Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

## Tech Stack
- Python
- pandas, numpy
- Jupyter Notebook

## Key Steps
1. Data quality report (nulls, duplicates, dtype issues, value anomalies)
2. Missing data handling (row deletion for missing CustomerID, imputation for Description)
3. Duplicate row removal
4. Standardisation (Country names, CustomerID format, date format)
5. Outlier detection using the IQR method (capping extreme UnitPrice values)
6. Data type correction (InvoiceDate → datetime, CustomerID → string)
7. Before vs. after summary table
8. Export cleaned dataset to CSV

## Key Insights
- Significant portion of rows had missing CustomerID, requiring removal for customer-level analysis.
- Negative Quantity values represent legitimate returns, not errors — flagged rather than deleted.
- Outlier capping preserved valid bulk-order data instead of discarding it.

## How to Run
1. Download `Online Retail.xlsx` from the dataset link above.
2. Install dependencies: `pip install pandas numpy openpyxl`
3. Open `Task3_Data_Cleaning.ipynb` in Jupyter Notebook and run all cells.
4. Cleaned output is saved as `Online_Retail_Cleaned.csv`.

## Author
[Rehan Muzammal]
