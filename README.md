# 📊 Data Leverager

🎥 **[Watch the Complete Video Explanation Here](YOUR_GOOGLE_DRIVE_LINK_HERE)** ## 

* **Dynamic Folder Extraction:** Automated the extraction and combination of multiple monthly Excel files (`Sales_Jan`, `Sales_Feb`, `Sales_Mar`, etc.). When a new file (e.g., `Sales_Apr`) is added to the folder, the data updates automatically upon refresh.
* **Web Scraping:** Successfully loaded and transformed live HTML tables from Wikipedia (List of countries by GDP).
* **Data Merging & Joins:** Integrated Sales transaction data with Employee Master Data using a Left Outer Join on `EmployeeID`.
* **Data Cleaning & Formatting:** Handled null values, removed duplicates, and applied Text Tools (UPPER, TRIM, CLEAN, Split by Delimiter, Replace Values).
* **Custom & Conditional Columns:** Created calculated columns (e.g., `Profit = Revenue - Cost`) and conditional columns to categorize sales into 'High', 'Medium', and 'Low' tiers.
* **Date & Time Intelligence:** Extracted Year, Month, Day, and Quarter from date fields without relying on Power BI's default Auto Date/Time feature.
* **Grouping & Aggregation:** Grouped data by 'Region' to calculate Total Sales, Average Order Value, and Transaction Count.
* **Parameterization:** Implemented a dynamic `FolderPath` parameter, allowing the data source directory to be changed globally without breaking the queries.

## 💻 Tools Used
* **Power BI Desktop**
* **Power Query Editor** (M Formula Language)
* **Microsoft Excel** (Raw Data Sources)

## 🚀 How to Use
1. Download the `DataLeverager.pbix` file.
2. Open it in Power BI Desktop.
3. Go to **Transform Data** -> **Edit Parameters** and update the `FolderPath` to your local machine's directory where the source files are stored.
4. Click **Refresh** to see the data load dynamically!
