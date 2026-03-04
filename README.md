📊 Sales Dashboard Project Description


This Excel-based Sales Dashboard is built using advanced formulas, data validation, and visual charts to analyze sales performance.

🔹 DETAILS Section (Formula-Based Automation)

The DETAILS section dynamically extracts customer and product information using advanced Excel formulas and validation techniques.

. Customer ID is selected using Data Validation to ensure controlled and accurate input.

. Customer Name is generated using UNIQUE and FILTER functions to remove duplicates and display valid customer names.

. Product ID is retrieved using VLOOKUP from the source dataset.

. Product Name is generated using INDEX + MATCH and XLOOKUP to ensure accurate product identification.

. Region is extracted using INDEX + XMATCH based on the selected customer and product.

. Customer Type is retrieved using VLOOKUP from the dataset.

. Payment Mode is dynamically fetched using lookup functions from sales records.

. Quantity is calculated using INDEX + XMATCH to return the correct quantity value.

. Sales Amount is displayed using XLOOKUP to return the exact sales value from the dataset.

This section ensures dynamic data extraction, accuracy, and automation without manual entry.

🔹 AMOUNTS Section (Calculation & Summary Formulas)

The AMOUNTS section focuses on financial calculations using aggregation and conditional formulas.

. Total Sales Amount is calculated using the SUM function to aggregate all sales values.

. Average Unit Price is calculated using the AVERAGE function to determine the average selling price per unit.

. Credit Card Sales Amount is calculated using SUMIFS based on the condition where Payment Mode = Credit Card.

. Debit Card Sales Amount is calculated using SUMIFS based on the condition where Payment Mode = Debit Card.

. Cash Sales Amount is calculated using SUMIFS based on the condition where Payment Mode = Cash.

. UPI Sales Amount is calculated using SUMIFS based on the condition where Payment Mode = UPI.

. Net Profit is calculated using formula-based logic using sales and cost values from the dataset.

These formulas provide a clear financial summary and allow conditional analysis of revenue by payment method.




📈 DATA VISUALIZATION (Charts)

The dashboard includes interactive charts created from formula-driven results:

1️⃣ Use of Payment Methods (Pie Chart)

Built using summarized Quantity data from SUMIFS.

Displays percentage distribution of Cash, Credit Card, Debit Card, and UPI usage.

2️⃣ Sales by Region (Line Chart)

Generated from Region-wise Sales Amount calculated using lookup and aggregation formulas.

Helps compare performance across East, North, South, and West regions.

3️⃣ Product-wise Sales (Column Chart)

Created using Product-wise Sales Amount extracted through lookup and summary formulas.

✅ Project Summary

This Sales Dashboard demonstrates strong command over Excel formulas such as SUM, AVERAGE, SUMIFS, UNIQUE, FILTER, VLOOKUP, INDEX-MATCH, XMATCH, and XLOOKUP to automate data extraction and calculations. 
By combining structured formulas with charts and data validation, the dashboard transforms raw sales data into a dynamic, interactive, and business-ready reporting tool.







