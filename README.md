# Automobile Sales Statistics Dashboard

This project is a Dash-based interactive web application that visualizes automobile sales and related statistics over time. It includes customizable reports for yearly and recession period statistics, providing insights into trends in sales, expenditures, and other metrics.

## Features

- **Yearly Statistics**:
  - Analyze annual automobile sales trends.
  - Visualize total monthly sales and average sales by vehicle type.
  - Examine advertisement expenditure distribution by vehicle type.

- **Recession Period Statistics**:
  - Explore how automobile sales fluctuated during recession periods.
  - Visualize average vehicle sales by type, total advertising expenditure, and the effect of unemployment rates on sales.

- **Dynamic User Interaction**:
  - Dropdown menus to choose between different report types and select specific years for analysis.
  - Interactive visualizations powered by Plotly.

## Prerequisites

The following Python libraries are required to run the application:
- **dash**
- **dash-core-components**
- **dash-html-components**
- **dash-dependencies**
- **pandas**
- **plotly**

Install these packages using pip:
```bash
pip install dash pandas plotly
```


## Dataset Source

The dataset is publicly available and hosted on IBM's Developer Skills Network.

**Dataset URL**: [Historical Automobile Sales Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv)

## Key Columns in the Dataset

1. **Year**:  
   The year in which the sales data was recorded.

2. **Month**:  
   The month corresponding to the sales data.

3. **Automobile_Sales**:  
   The total number of automobiles sold in a given period.

4. **Vehicle_Type**:  
   The type of vehicle sold (e.g., sedan, SUV, truck).

5. **Advertising_Expenditure**:  
   The total expenditure on advertising during the given period.

6. **Recession**:  
   A binary flag (`1` for recession period, `0` otherwise) indicating whether the data corresponds to a time of economic recession.

7. **unemployment_rate**:  
   The unemployment rate for the given period, which can be used to analyze its effect on automobile sales.

## Usage

This dataset can be used for:
- Visualizing and analyzing automobile sales trends.
- Studying the impact of economic factors such as recessions and unemployment on sales.
- Evaluating the effectiveness of advertising expenditures.
- Comparing sales performance across different vehicle types.


## Application Layout

### Title
**Automobile Sales Statistics Dashboard**

### Dropdown Menus
1. **Select Statistics**:  
   Choose between:
   - Yearly Statistics
   - Recession Period Statistics

2. **Select Year**:  
   Available only when "Yearly Statistics" is selected.

### Visualizations
The application generates multiple dynamic charts based on the selected options. These visualizations provide valuable insights into automobile sales trends, advertising expenditures, and economic impacts.



## Visualization Details

### **Yearly Statistics**
1. **Yearly Automobile Sales**:  
   - Line chart showing yearly trends in automobile sales.

2. **Total Monthly Automobile Sales**:  
   - Line chart representing monthly sales trends over a year.

3. **Average Vehicles Sold by Vehicle Type**:  
   - Bar chart displaying the average number of vehicles sold by type for a selected year.

4. **Advertisement Expenditure by Vehicle Type**:  
   - Pie chart showcasing the distribution of advertising expenditure by vehicle type for a selected year.



### **Recession Period Statistics**
1. **Sales Fluctuation During Recessions**:  
   - Line chart highlighting the fluctuation in automobile sales during recession periods.

2. **Average Vehicles Sold by Vehicle Type**:  
   - Bar chart showing the average number of vehicles sold by type during recessions.

3. **Advertising Expenditure Distribution**:  
   - Pie chart illustrating the share of advertising expenditure by vehicle type during recessions.

4. **Effect of Unemployment on Sales**:  
   - Bar chart depicting the relationship between unemployment rates, vehicle types, and sales during recessions.



## How to Use
1. Select a report type from the **"Select Statistics"** dropdown menu.
2. For Yearly Statistics, choose a year from the **"Select Year"** dropdown menu.
3. View the dynamically generated charts and analyze the visualized data.












