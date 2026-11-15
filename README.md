# Decoded labs E-Commerce Data Cleaning & Validation

DecodeLabs Data Analytics Internship – Task 1.

This project cleans and checks an e-commerce orders dataset using Python and Pandas.

## What I Did

1. **Loaded the data** and checked rows, columns, and missing values
2. **Cleaned the data**: filled empty `CouponCode` with "NoCoupon", fixed `Date` format, and removed extra spaces from text
3. **Validated the data**: checked IDs (`OrderID`, `CustomerID`, `TrackingNumber`), number ranges, and that `TotalPrice = Quantity × UnitPrice`

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to Run

1. Install libraries: `pip install pandas numpy matplotlib seaborn jupyter`
2. Put the dataset CSV in the project folder
3. Open `data_analysis_decodelabs_project.ipynb` and run all cells
