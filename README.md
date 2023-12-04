# Data Analysis - Tasks 1 and 2

### TASK 1 – Data in CSV

On March 3rd, we observed a decline in the average revenue per session (calculated as Revenue / Sessions) on product pages in the Smartphones category. An analysis is needed to identify the cause of the problem. The attached data is in CSV format.

Using Excel, prepare a data analysis to answer the following questions:

- At what point did the problem arise?
- How can the data be segmented?
  
Describe the steps of your analysis in chronological order. Draw conclusions from the conducted analysis. If you have other insights not directly related to the task, include them as well.

### TASK 2 – Data in Excel

Using the Excel data (2. Sales) for transactions and products from H2 2022, demonstrate:

- Which sales channel performed the best?
- Which brand had the highest sales and in which channel?
- Which categories should be promoted and in which channel, based on sales from H2?
  
Prepare an Excel dashboard that addresses the above questions. Describe the steps of your analysis in chronological order.


### Data Sources

- **Task 1:** Data for analysis was provided in the file [Product Analysis in the Smartphones category.xlsx.](Analiza%20produktów%20w%20kategorii%20Smartfony.xlsx)
  
- **Task 2:** Data for the second task was made available in the file [Sales in H2 2022.xlsx.](Sprzedaż%20w%20II%20półroczu%202022.xlsx)

## Task 1

### 1. Loading Data from CSV File

The data was loaded from a CSV file into the appropriate data structure.

### 2. Decimal Separator Conversion

In the "revenues2" column, dots were replaced with commas to enable correct interpretation of decimal numbers.

### 3. Date Processing

For better data analysis, dates were split into three separate columns: day, month, and year. These variables were then transformed into a universal format for proper sorting.

### 4. Removing Unnecessary Spaces

The "traffic source" column applied the remove.extra.spaces (trim) function to eliminate excess spaces and create a new column with corrected data.

### 5. Creating a Pivot Table

Based on processed data, a pivot table was created, allowing data grouping according to selected categories and performing calculations.

### 6. Creating Calculated Fields

Using the pivot table, calculated fields such as average revenue per session or conversion were created.

### 7. Creating Tables and Charts for Analysis

Tables and charts were created to allow for a deeper analysis of the data.

### 8. Creating the "Analysis" Sheet

On the "Analysis" sheet, conclusions from the analysis of charts were described, and further actions based on the obtained data were proposed.

![image](https://github.com/pjowsianka/Excel-Analiza-Sprzeda-y/assets/130370888/b6a7599f-e017-4906-8acf-dd811735bab5)


## Task 2

### 1. Moving the "transactionid" Column

The "transactionid" column was moved to the left side of the first table to apply the VLOOKUP function.

### 2. Using the VLOOKUP Function

The VLOOKUP function was applied to the second table, and the results were moved to a new sheet named "Data Table."

### 3. Replacing Dots with Commas

In the "revenues" column, dots were replaced with commas using the Ctrl+H key combination, enabling the correct interpretation of numerical data by Excel.

### 4. Creating Pivot Tables and Charts

Pivot tables along with relevant charts were created, addressing the analysis questions.

### 5. Creating a Dashboard

A dashboard was created, combining all charts, allowing easy monitoring and analysis of data.

![image](https://github.com/pjowsianka/Excel-Analiza-Sprzeda-y/assets/130370888/ec505ff0-816f-4323-abf4-5e89880e63f5)
