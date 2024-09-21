# Coffee Sales Dashboard Project

## Overview
This project demonstrates an end-to-end Excel analysis using a **Coffee Sales Dataset**. The project walks through gathering, transforming, and visualizing data using **Pivot Tables**, **Pivot Charts**, and **Slicers** in Excel. The final output is an interactive **Coffee Sales Dashboard**, featuring various visual elements such as line charts, bar charts, and interactive slicers.

## Project Goals
- **Data Transformation**: Clean and structure the dataset by filling in missing information using Excel functions such as **XLOOKUP** and **INDEX-MATCH** to gather customer and product data efficiently.
- **Sales Analysis**: Provide insights into sales trends over time, including breakdowns by coffee type, country, and customer. The goal is to identify top-performing coffee types, key customers, and sales hotspots geographically.
- **Interactive Data Exploration**: Enable stakeholders to dynamically filter the data using **Slicers** and **Timelines** for different coffee roast types, package sizes, and loyalty card status.
- **Visualization of Key Metrics**: Build clear and informative visualizations using **Pivot Tables** and **Pivot Charts** to represent sales trends, customer behavior, and regional sales performance.

## Raw Data Overview
Below are screenshots of the **Raw Data File**, which represents the unprocessed coffee sales data. This data is in its original state, and several key issues need to be addressed before it can be used for meaningful analysis:

1. **Missing Data**: Several columns, such as customer information (names, emails, countries) and product details (coffee type, roast type, and price), are incomplete or missing entirely.
2. **Unstructured Information**: The dataset lacks consistency in formatting, such as missing labels for coffee types and roast levels, which need to be corrected to ensure accuracy.
3. **No Calculations**: The data does not include derived metrics like total sales or profit, which will be necessary for analysis.

The raw data will undergo cleaning and transformation steps, including filling in missing data using **lookup functions**, structuring the data using **formulas**, and calculating key metrics like total sales. These transformations will be reflected in the processed data file, which is used to build the dashboard.

*Screenshots of the raw data are shown below.*
![image](https://github.com/user-attachments/assets/abbc9c09-af6e-4f02-9e50-86aacbdc9a65)

## Steps Taken
The following steps outline the process of transforming raw data into an interactive dashboard, leveraging Excel's powerful functions and features:

1. **XLOOKUP**: Used the `XLOOKUP` formula to populate missing fields such as "Customer Name," "Email," and "Country" by referencing the Customer ID in a separate customer data table.
2. **IF Formula**: Applied the `IF` function to handle missing values. If a cell contained no value, the formula ensured it displayed as blank rather than "0."
3. **INDEX-MATCH**: Used the `INDEX-MATCH` formula to dynamically retrieve product data such as coffee type, roast type, and unit price from the product data table.
4. **Absolute and Relative Cell References**: Implemented absolute (`$D$1`), mixed (`$D1`, `D$1`), and relative references to ensure formulas referenced the correct cells when dragged across rows or columns.
5. **Nested IF Functions**: Utilized multiple `IF` functions in a single formula to return more complex outputs based on multiple conditions (e.g., displaying full coffee type names from abbreviations).
6. **Date Formatting**: Reformatted the "Order Date" column to a custom format for better clarity, displaying the day, month (in abbreviated text), and year.
7. **Number Formatting**: Applied custom number formatting for columns such as "Size" (displayed in kilograms) and "Unit Price" to show currency values in U.S. Dollars.
8. **Duplicate Check**: Performed a check for duplicate records using Excel’s built-in **Remove Duplicates** feature to ensure data integrity.
9. **Converting Range to Table**: Converted the data range into an Excel Table for easier data management, including automatic updating of references in Pivot Tables.
10. **Pivot Tables and Pivot Charts**: Created dynamic Pivot Tables and associated Pivot Charts to analyze and visualize the data.
11. **Insert Timeline and Formatting**: Added a timeline to the dashboard to filter data by date ranges and customized its design for a cohesive look.
12. **Creating Slicers**: Inserted three slicers for **Roast Type**, **Size**, and **Loyalty Card Status** to enable users to filter and explore the data interactively.
13. **Sales by Country**: Developed a bar chart to show coffee sales performance across countries (U.S., Ireland, and the UK).
14. **Top 5 Customers**: Built a bar chart to highlight the top 5 customers based on total sales.
15. **Dashboard Creation**: Integrated all pivot charts, slicers, and timelines into a single cohesive dashboard, adjusting design elements to ensure an intuitive and interactive user experience.

## Key Features of the Dashboard:
1. **Total Sales Over Time**: A dynamic line chart that shows the total sales split by coffee type over time.
2. **Sales by Country**: A bar chart that breaks down coffee sales in different countries.
3. **Top 5 Customers**: A bar chart displaying the top 5 customers based on sales volume.
4. **Interactive Filters**:
   - **Timeline Filter**: Allows users to select specific date ranges.
   - **Slicers for Roast Type, Coffee Size, and Loyalty Cards**: These filters allow dynamic exploration of the data.

![image](https://github.com/user-attachments/assets/b78513e9-1b3e-45c1-879b-0748b972ab27)

## How to Use This Project:
1. There are two Excel files available in the repository:
   - **Raw Data File**: This file contains the original, unprocessed data. It has not been cleaned or transformed, and includes missing values and unstructured information, which will require further manipulation for analysis.
   - **Processed Data File**: This file contains the data after all necessary transformations have been applied, including data cleaning, lookups, and calculations. It is ready for use in the analysis and includes all formulas, pivot tables, and visualizations built into the dashboard.
2. Open the processed Excel file in Excel.
3. Explore the various pivot charts and slicers to interact with the data.
4. Use the timeline to filter sales by specific date ranges and the slicers to filter data based on roast type, coffee size, and customer loyalty card status.

## Contact Information
Feel free to reach out if you have any questions or would like to discuss the insights from this dashboard:
- **Email:** syahrein01@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/syahrein/)
