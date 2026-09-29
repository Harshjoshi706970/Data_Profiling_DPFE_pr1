# Customer Churn Data Profiling

## Overview
This project explores customer data to understand customer churn and prepare the dataset for further analysis. It includes the customer dataset, a MySQL SQL dump, and a Jupyter Notebook for data profiling.

## Project Files
- `customer_churn_data.csv` – customer data in CSV format.
- `customer_churn_data.json` – customer data in JSON format.
- `cust_churn.sql` – MySQL table structure and sample records.
- `Data_Profile.ipynb` – notebook for data profiling.

## Dataset
The SQL table is named `customer_data`. Its fields include:
`CustomerID`, `Age`, `Gender`, `Income`, `Purchases`, `TotalSpent`, `Visits`, `SupportCalls`, `City`, `TenureMonths`, and `Churn`.

## Tools Used
- Python
- Jupyter Notebook
- Pandas
- MySQL
- ydata-profiling (for automated data profiling)

## How to Run
1. Clone or download this repository.
2. Open `Data_Profile.ipynb` in Jupyter Notebook or VS Code.
3. Install the required Python packages in the notebook environment:
   ```bash
   pip install pandas ydata-profiling
   ```
4. Load the CSV file into a Pandas DataFrame and run the notebook cells.
5. To use MySQL, import `cust_churn.sql` into your MySQL server.

## Note
The dataset contains some missing values and inconsistent capitalization in categorical values. Review and clean these before using the data for further analysis.
