
# Coffee Shop Sales Analysis - README

## 1. Overview
This Excel workbook contains data related to coffee shop sales, analyzing transactions, sales, and customer footfall over different locations and times. The workbook consists of three primary sheets:
- **Transactions Sheet**: Contains raw transaction data.
- **Pivot Sheet**: Summarizes data using pivot tables.
- **Dashboard Sheet**: Visualizes key insights and allows for interactive data analysis.

---

## 2. Sheets Description

### 2.1 Transactions Sheet
- **Sheet Name**: `Transactions`
- Contains detailed raw data, including:
  - `Transaction Date`, `Transaction Time`
  - `Store Location`, `Product Type`, `Product Category`
  - `Unit Price`, `Total Bill`
  - Additional metadata such as `Size`, `Month Name`, `Day Name`, etc.
  
  This data is used as the basis for the pivot tables and the dashboard.

### 2.2 Pivot Sheet
- **Sheet Name**: `Pivot`
- Provides summarized data in the form of pivot tables, showcasing:
  - Total sales and transactions by different days of the week.
  - Breakdown of total sales by product categories and product types.
  - Sales trends across months and locations.
  
  These pivot tables provide insight into sales patterns across various dimensions, such as time, product types, and locations.

### 2.3 Dashboard Sheet
- **Sheet Name**: `Dashboard`
- This sheet provides a visual representation of key insights from the data.

### Key Visuals on the Dashboard:
   - **Average Order Per Person**: Displays the average number of orders per customer.
   - **Total Sales**: Displays the total sales amount in dollars ($698,812.33).
   - **Total Footfall**: Shows the total number of customer transactions (149,116).
   - **Average Bill Per Person**: Displays the average bill value per customer ($4.69).

### Interactive Filters:
   - **Month Filter**: You can filter the data by selecting a specific month, and all charts will adjust accordingly.
   - **Day Filter**: Similarly, selecting a particular day will dynamically change the visuals to reflect data for that specific day.
   
   These filters provide flexibility to explore the data for specific time periods, making the dashboard interactive and user-friendly.

### Charts and Visuals:
   - **Line Chart**: Shows the quantity of orders throughout different hours of the day.
   - **Bar Charts**: Footfall across various locations (`Astoria`, `Hell's Kitchen`, `Lower Manhattan`), and top-selling products based on total sales.
   - **Pie Chart**: Percentage distribution of categories (e.g., `Bakery`, `Coffee`, `Tea`, etc.) based on sales.

---

